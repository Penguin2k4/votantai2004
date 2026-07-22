---
title: "Worklog Tuần 7"
date: 2026-06-15
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:
- **Phát triển & Tối ưu AI:** Khắc phục lỗi chụp màn hình (screenshot) khi kiểm tra bằng URL. Tích hợp thêm các tính năng trích xuất thông tin tên miền (Domain Info) như: Phát hiện địa chỉ IP, tuổi đời website (domain age), vị trí địa lý và thông tin nhà đăng ký (registrar). 
- **Tinh chỉnh mô hình:** Tiến hành tinh chỉnh (Fine-tune) lại mô hình AI để nâng cao độ chính xác và tối ưu hóa khả năng nhận diện Phishing.
- **Thực hành AWS:** Tiếp tục nghiên cứu và hoàn thành các nội dung trong Module 5.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **Sửa lỗi hệ thống (Bug Fixing):**<br>&emsp;+ Rà soát mã nguồn xử lý đầu vào URL.<br>&emsp;+ Khắc phục triệt để lỗi không chụp được ảnh màn hình (screenshot) của trang web khi quét. | 15/06/2026 | 15/06/2026 | |
| 3 | - **Tích hợp Domain Info (Phần 1):**<br>&emsp;+ Tìm hiểu và tích hợp các API/Thư viện (như Whois).<br>&emsp;+ Viết script trích xuất thông tin: Địa chỉ IP, Vị trí địa lý (Location) và Nhà đăng ký (Registrar). | 16/06/2026 | 16/06/2026 | |
| 4 | - **Tích hợp Domain Info (Phần 2):**<br>&emsp;+ Trích xuất tính năng Tuổi đời website (Domain Age).<br>&emsp;+ Ghép nối toàn bộ dữ liệu tên miền vào Pipeline dữ liệu chung để làm đầu vào cho mô hình phân tích. | 17/06/2026 | 17/06/2026 | |
| 5 | - **Tinh chỉnh mô hình (Fine-tuning):**<br>&emsp;+ Bổ sung các đặc trưng (features) mới lấy từ Domain Info vào tập dữ liệu huấn luyện.<br>-  **Thực hành Lab 28**: <br>&emsp;+ Tạo IAM User, Policy và Role <br>&emsp;+ Thực hiện Switch Roles <br>&emsp;+ Truy cập EC2 console, tạo EC2 và chỉnh sửa Tag <br>&emsp;+ Kiểm tra chính sách (Policy Check) <br>&emsp;+ Dọn dẹp tài nguyên . | 18/06/2026 | 18/06/2026 | [Lab28](https://000028.awsstudygroup.com/vi/)|
| 6 | - **Thực hành Lab 30**: <br>&emsp;+ Tạo Restriction Policy <br>&emsp;+ Tạo IAM Limited User <br>&emsp;+ Kiểm tra giới hạn quyền IAM User <br>&emsp;+ Dọn dẹp tài nguyên <br>- **Thực hành Lab 33**: <br>&emsp;+ Tạo IAM (Policy, Role, Group, User) <br>&emsp;+ Tạo khóa KMS, S3 Bucket & Upload data <br>&emsp;+ Cấu hình CloudTrail để ghi log <br>&emsp;+ Sử dụng Athena để truy xuất dữ liệu <br>&emsp;+ Test & chia sẻ dữ liệu mã hóa trên S3| 19/06/2026 | 19/06/2026 | [Lab30](https://000030.awsstudygroup.com/vi/3-createpolicy/)<br>[Lab 33](https://000033.awsstudygroup.com/vi/3-createpolicy/) |

### Kết quả đạt được tuần 7:


* Xử lý triệt để lỗi (bug) không chụp được ảnh màn hình từ URL, đảm bảo luồng dữ liệu đầu vào hoạt động trơn tru, ổn định cho quá trình phân tích.
* Tích hợp thành công module trích xuất thông tin tên miền (Domain Info). Hệ thống đã tự động thu thập được các đặc trưng quan trọng làm cơ sở đánh giá bao gồm: Địa chỉ IP, tuổi đời website (Domain Age), vị trí địa lý và thông tin nhà cung cấp (Registrar).
* Hoàn thành bước tinh chỉnh (Fine-tune) mô hình AI bằng cách bổ sung bộ đặc trưng Domain Info vào tập dữ liệu huấn luyện. Nhờ sự kết hợp phân tích đa chiều (Hình ảnh, URL và Thông tin tên miền), mô hình đã cho ra kết quả dự đoán chính xác hơn và giảm thiểu đáng kể tỷ lệ nhận diện sai (False Positive).
* Nắm vững các thao tác quản lý phân quyền từ cơ bản đến nâng cao. Thực hiện thành thạo việc tạo User/Role/Policy, chuyển đổi vai trò (Switch Roles), cũng như áp dụng các chính sách hạn chế (Restriction Policy) và kiểm thử giới hạn quyền của IAM User. 
* Triển khai thành công luồng bảo mật và giám sát toàn diện: Sử dụng KMS để mã hóa dữ liệu trên S3 Bucket, cấu hình CloudTrail để ghi log mọi hoạt động, và ứng dụng Amazon Athena để truy xuất/phân tích dữ liệu log một cách hiệu quả.
* Luôn đảm bảo tuân thủ nguyên tắc dọn dẹp tài nguyên (Clean up resources) sau mỗi bài Lab để tối ưu hóa chi phí cho hệ thống.