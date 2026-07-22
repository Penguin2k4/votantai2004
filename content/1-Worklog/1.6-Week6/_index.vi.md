---
title: "Worklog Tuần 6"
date: 2026-06-08
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:
- **Nghiên cứu & Phát triển AI/ML:** Triển khai (deploy) mô hình AI thông qua Ngrok ra internet. Mục tiêu nhằm tạo môi trường Public trơn tru để tiến hành kiểm thử (test) thực tế và đánh giá toàn diện các tính năng của mô hình.
- **Thực hành AWS chuyên môn:** 
  - Hoàn tất dứt điểm toàn bộ các bài thực hành (Lab) còn lại của Module 4.
  - Tìm hiểu Module 5 về bảo mật: KMS, IAM, Cognito và File share.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **Tìm hiểu Module 5 (Cơ bản)**: <br>&emsp;+ Module 05-01: Mô hình chia sẻ trách nhiệm (Share Responsibility Model) <br>&emsp;+ Module 05-02: Quản lý truy cập và định danh (Amazon Identity and Access Management - IAM) <br>&emsp;+ Module 05-03: Amazon Cognito | 08/06/2026 | 08/06/2026 | [Module 05-01](https://www.youtube.com/watch?v=tsobAlSg19g&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=150)<br>[Module 05-02](https://www.youtube.com/watch?v=N_vlJGAqZxo&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=151)<br>[Module 05-03](https://www.youtube.com/watch?v=pZ2fgEFK3Vs&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=152) |
| 3 | - **Thực hành Lab 18**: <br>&emsp;+ Kích hoạt Security Hub <br>&emsp;+ Đánh giá điểm theo bộ tiêu chí <br>&emsp;+ Dọn dẹp tài nguyên <br>- **Thực hành Lab 22**: <br>&emsp;+ Tạo VPC, Security Group, EC2 & Tag <br>&emsp;+ Cấu hình Incoming Web-hooks Slack <br>&emsp;+ Tạo Role và Lambda Function (Start/Stop EC2) <br>&emsp;+ Kiểm tra kết quả & Dọn dẹp tài nguyên | 09/06/2026 | 09/06/2026 | [Lab 18](https://000018.awsstudygroup.com/3-connecttordgw/)<br>[Video Lab 22](https://www.youtube.com/watch?v=YnLo4MgOXyA&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=158) |
| 4 | - **Phát triển AI/ML (Deploy):** <br>&emsp;+ Cài đặt và cấu hình Ngrok trên máy local. <br>&emsp;+ Triển khai mô hình AI qua đường hầm mạng (tunnel) của Ngrok để tạo public URL. | 10/06/2026 | 10/06/2026 |  |
| 5 | - **Làm việc nhóm & Kiểm thử:** + Tiến hành gọi API và test giao diện mô hình thông qua đường dẫn public của Ngrok. | 11/06/2026 | 11/06/2026 | |
| 6 | -- **Thực hành Lab 27**: <br>&emsp;+ Tạo EC2 và quản lý Tag trong AWS <br>&emsp;+ Lọc tài nguyên và sử dụng Tag qua CLI <br>&emsp;+ Tạo Resource Group <br>&emsp;+ Dọn dẹp tài nguyên |12/06/2026  | 12/06/2026| [Lab 27](https://000027.awsstudygroup.com/vi/) |  |

### Kết quả đạt được tuần 6:
  * Bước đầu làm chủ kiến thức nền tảng của Module 5 về bảo mật: Hiểu rõ Mô hình chia sẻ trách nhiệm (Shared Responsibility Model), nắm bắt cách hoạt động của IAM, Cognito trong việc quản lý định danh/phân quyền, và hiểu cơ chế mã hóa bảo vệ dữ liệu của KMS cũng như File share.
  * Hoàn thành xuất sắc **Lab 18**: Nắm vững cách kích hoạt và sử dụng AWS Security Hub để đánh giá, chấm điểm bảo mật cho hệ thống dựa trên các bộ tiêu chí chuẩn.
  * Ứng dụng thành công tự động hóa qua **Lab 22**: Thực hiện tích hợp AWS Lambda với EC2 để tự động Start/Stop máy chủ, đồng thời thiết lập thành công luồng thông báo (Incoming Web-hooks) báo cáo trạng thái trực tiếp về kênh Slack.

  * Triển khai (deploy) thành công mô hình AI lên internet thông qua công cụ Ngrok.
  * Quá trình kiểm thử (test) thực tế diễn ra thuận lợi thông qua Public URL, bước đầu xác nhận các tính năng của mô hình phản hồi tốt, xử lý dữ liệu chính xác khi nhận request từ môi trường bên ngoài.