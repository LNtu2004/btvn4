# bai tap 4: (sql server)
yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó

Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)
  

deadline: 15/4/2025
#                    BÀI LÀM
I Tạo database mới có tên là : TKB / ( Thời khóa biểu )
![image](https://github.com/user-attachments/assets/a2390ca6-1633-4279-ad17-86140fa9a9fc)
II tạo bảng 
làm như những gì đã được học
![image](https://github.com/user-attachments/assets/b4ae63ad-7f88-4619-87ef-05f918086b70)
2.1 giáo viên 
![image](https://github.com/user-attachments/assets/660c9d86-635f-4d88-9c02-d30918da2e8f)
2.2 Môn học 
![image](https://github.com/user-attachments/assets/4a9b9223-109d-4e6a-962e-67cac09582b5)
2.3 lớp học
![image](https://github.com/user-attachments/assets/e56733ab-d7b7-4c37-95b1-ea4f9d96aefe)
2.4 thời khóa biểu
![image](https://github.com/user-attachments/assets/e3092f53-fbb8-47d8-8fe3-d898d5d23243)
III nhập thông tin cho các bảng 
3.1 Giáo viên 
![image](https://github.com/user-attachments/assets/449c1e10-151d-468b-b1d1-3090001c0b39)
3.2 lớp học
![image](https://github.com/user-attachments/assets/46ebb08c-7700-4a7c-a213-606f0db04d80)
3.3 môn học
![image](https://github.com/user-attachments/assets/720af5f7-b8e0-44d3-adee-468ed3af4c6d)
3.4 thời khóa biểu
![image](https://github.com/user-attachments/assets/13db5d97-5f40-465a-9611-bd30d935346a)
IV bảng diagram
![image](https://github.com/user-attachments/assets/51d23fe3-dc3b-4aa8-bf16-228401b96dd8)

