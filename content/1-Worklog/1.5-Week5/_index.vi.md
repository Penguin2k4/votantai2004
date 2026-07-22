---
title: "Worklog Tuần 5"
date: 2026-06-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

- **Nghiên cứu & Phát triển AI/ML:** Tối ưu và kiểm thử (test) thực tế mô hình nhận diện Phishing URL, đảm bảo tỷ lệ phát hiện chính xác (Detection Rate) ở mức cao. Bắt đầu nghiên cứu và xây dựng tiếp mô hình phát hiện Phishing Email.
- **Thực hành AWS chuyên môn:** Hoàn tất dứt điểm bài tập Module 3 và tiến hành thực hành các kiến thức của Module 4.
- **Phối hợp nhóm (Teamwork):**  đồng bộ định hướng dự án cùng team.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **Hoàn Thành Lab 57:** <br>&emsp;+ Sao chép đối tượng đa khu vực (Multi-Region) <br>&emsp;+ Dọn dẹp tài nguyên <br>- **Tìm hiểu Module 04:** <br>&emsp;+ Tạo và cấu hình Amazon S3 (Access, CORS, Static Website) <br>&emsp;+ Tìm hiểu Snow Family, Storage Gateway & AWS Backup | 01/06/2026 | 01/06/2026 | [Module 04-02](https://www.youtube.com/watch?v=_yunukwcAwc&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=104)<br>[Module 04-03](https://www.youtube.com/watch?v=mPBjB6Ltl_Q&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=105)<br>[Module 04-04](https://www.youtube.com/watch?v=YXn8Q_Hpsu4&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=106) |
| 3 | - **Thực hành Lab 14 (VM Import/Export):** <br>&emsp;+ Cài đặt VMWare Workstation <br>&emsp;+ Xuất và tải máy ảo từ On-premises lên AWS <br>&emsp;+ Nhập máy ảo (Import VM) vào AWS <br>&emsp;+ Triển khai EC2 Instance từ AMI <br>&emsp;+ Cấu hình S3 bucket ACL <br>&emsp;+ Xuất máy ảo từ Instance (Export VM) <br>&emsp;+ Dọn dẹp tài nguyên trên AWS Cloud | 02/06/2026 | 02/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Nghiên cứu AI/ML:** <br>&emsp;+ Đưa mô hình phát hiện Phishing URL vào test thực tế. <br>&emsp;+ Đánh giá các URL để đảm bảo tỷ lệ phát hiện ở mức tốt trên 75%. | 03/06/2026 | 03/06/2026 | |
| 5 | - **Thực hành Lab 25**: <br>&emsp;+ Tạo hệ thống file SSD Multi-AZ <br>&emsp;+ Tạo hệ thống file HDD Multi-AZ <br>&emsp;+ Tạo các file shares mới <br>&emsp;+ Kiểm tra hiệu suất <br>&emsp;+ Giám sát hiệu suất <br>&emsp;+ Bật data deduplication <br>&emsp;+ Bật shadow copies<br>&emsp;+ Dọn dẹp tài nguyên | 04/06/2026 | 05/06/2026 | [Lab 25](https://000025.awsstudygroup.com/1-introduce/) |

### Kết quả đạt được tuần 5:


  * Nắm vững kiến thức Module 4 về các giải pháp lưu trữ trên AWS: Hiểu rõ cơ chế hoạt động của Amazon S3 (Access, CORS, Static Website) cũng như các dịch vụ mở rộng như Snow Family, Storage Gateway.
  * Hoàn thành xuất sắc Lab 14: Làm chủ quy trình luân chuyển, xuất/nhập máy ảo (VM Import/Export) giữa môi trường On-premises (VMWare) và AWS Cloud, bao gồm cả việc triển khai EC2 từ AMI và cấu hình quyền truy cập S3 ACL.
  * Hoàn thành Lab 25: Triển khai thành công hệ thống file Multi-AZ (cả SSD và HDD) mang tính dự phòng cao. Thực hiện thành thạo các thao tác tối ưu hóa hệ thống như giám sát hiệu năng, bật tính năng chống trùng lặp dữ liệu (data deduplication) và khôi phục bản sao ẩn (shadow copies). Đảm bảo tuân thủ nguyên tắc dọn dẹp tài nguyên (Clean up) sau khi thực hành.


  * Đưa mô hình Phishing URL vào môi trường kiểm thử thực tế và tiến hành đánh giá tập dữ liệu mới. Kết quả mô hình hoạt động ổn định, đáp ứng và vượt mục tiêu đề ra với tỷ lệ phát hiện chính xác (Detection Rate) đạt trên 75%.
