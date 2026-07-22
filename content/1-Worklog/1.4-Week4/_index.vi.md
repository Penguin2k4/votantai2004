---
title: "Worklog Tuần 4"
date: 2026-05-25
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

- **Nghiên cứu & Huấn luyện mô hình (AI/ML):** Thử nghiệm kết hợp các thuật toán Học máy (Random Forest, XGBoost) và Học sâu (CNN). Đặt mục tiêu tối ưu hóa mô hình để đạt độ chính xác (Accuracy) trên 83% với Dataset 1, đồng thời mở rộng kiểm thử trên các tập dữ liệu khác để đánh giá tính khái quát.
- **Thực hành AWS chuyên môn:** Hoàn thành toàn bộ các bài tập thực hành thuộc Module 3.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu về AWS Backup cho hệ thống <br> - **Thực Hành Lab 13**:<br>&emsp;+ Tạo backup plan <br>&emsp;+ Kiểm tra hoạt động <br>&emsp;+ Dọn dẹp tài nguyên <br> - **Thực hành Lab 24**: <br>&emsp;+ Tạo S3 Bucket <br>&emsp;+ Tạo EC2 cho Storage Gateway <br>&emsp;+ Tạo Storage Gateway <br>&emsp;+ Tạo File Shares | 25/05/2026 | 25/05/2026 | [Lab13](https://000013.awsstudygroup.com/vi/5-testrestore/) <br>[Lab24](https://000024.awsstudygroup.com/vi/5-testrestore/) |
| 3 | - Thử mô hình học sâu như Random Forest, XGBoost, CNN đạt được kết quả lần lượt là 93%, 95%, 92% cho dataset phishing url 1.<br>- Thử nghiệm dataset 2 (hơn 500k url) đạt được 94% cho XGBoost. | 26/05/2026 | 27/05/2026 | |
| 5 | **Thực hành Lab 57**: <br>&emsp;+ Tạo S3 bucket <br>&emsp;+ Tải dữ liệu lên <br>&emsp;+ Bật tính năng trang web tĩnh <br>&emsp;+ Cấu hình chặn truy cập công khai <br>&emsp;+ Cấu hình đối tượng công khai <br>&emsp;+ Kiểm tra trang web <br>&emsp;+ Chặn toàn bộ truy cập công khai <br>&emsp;+ Cấu hình Amazon CloudFront <br>&emsp;+ Kiểm tra Amazon CloudFront <br>&emsp;+ Quản lý phiên bản Bucket (Bucket Versioning) <br>&emsp;+ Di chuyển đối tượng | 28/05/2026 | 28/05/2026 | [Lab57](https://000057.awsstudygroup.com/vi/10-s3ccr/) |
| 6 | - **Triển khai và test thử model:** <br>&emsp; + Triển khai UI đơn giản <br>&emsp; + Test bằng 3 url ngẫu nhiên (đạt 33% tỷ lệ đúng) <br>&emsp;  | 29/05/2026 | 29/05/2026 |> |

### Kết quả đạt được tuần 4:

* **Dự án nhóm:**
  * Vượt xa mục tiêu ban đầu (83%), huấn luyện thành công các mô hình phát hiện Phishing URL với độ chính xác rất cao trên Dataset 1: XGBoost (95%), Random Forest (93%), và CNN (92%).
  * Chứng minh được tính khái quát và khả năng chịu tải của mô hình khi test trên Dataset 2 quy mô lớn (hơn 500.000 URLs), mô hình XGBoost vẫn duy trì độ chính xác ấn tượng ở mức 94%.
  * Bước đầu hoàn thành việc triển khai UI cơ bản để tích hợp mô hình và thực hiện kiểm thử thực tế (cần tối ưu thêm để cải thiện tỷ lệ nhận diện ngẫu nhiên).

* **Kiến thức AWS:**
  * Hoàn thành Module 3 với kiến thức chuyên sâu về lưu trữ và sao lưu.
  * **Lab 13 & 24:** Cấu hình thành công AWS Backup (tạo plan, test restore) và thiết lập Storage Gateway để tạo luồng lưu trữ file mượt mà giữa hệ thống và S3.
  * **Lab 57:** Làm chủ dịch vụ lưu trữ Amazon S3 và mạng phân phối nội dung CloudFront (CDN). Đã thực hành chi tiết việc thiết lập Static Website, quản lý phân quyền truy cập (Public Access Block), bật tính năng Versioning bảo vệ dữ liệu và cấu hình CDN để tăng tốc độ tải trang.
  * Thực hiện thành thạo thao tác quản lý ổ đĩa lưu trữ block-level thông qua việc gắn thành công EBS volume.