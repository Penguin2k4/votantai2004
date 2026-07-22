---
title: "Worklog Tuần 3"
date: 2026-05-18
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---



### Mục tiêu tuần 3:

- Nắm vững kiến thức nền tảng và thực hành cấu hình mạng trên AWS với Amazon VPC (Virtual Private Cloud), hiểu rõ cách vận hành của các thành phần mạng (Subnet, Gateway, Security Group).
- Nghiên cứu tài liệu khoa học chuyên sâu về phát hiện URL lừa đảo  và áp dụng thực hành xây dựng mô hình Deep Learning cơ bản.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu về VPC: <br>&emsp; + Khái niệm <br>&emsp; + VPC security group <br>&emsp; + Network Access Control List <br>&emsp; + VPC flow logs ...              | 18/05/2026   | 18/05/2026      |[Module02-01](https://www.youtube.com/watch?v=O9Ac_vGHquM&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=25)<br>[Module02-02](https://www.youtube.com/watch?v=BPuD1l2hEQ4&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=26)
| 3   | - Nghỉ ngày hôm nay                                | 19/05/2026   | 19/05/2026     | |
| 4   |  - Lên văn phòng học tập <br> - **Thực Hành:**<br>&emsp; - Tạo VPC với subnet, internet gateway, route table, security group, EC2 server, NAT gateway, và môi trường VPN <br> - Kết nối Lai & DNS              |20/5/2026|20/5/2026        | [Lab03](https://000003.awsstudygroup.com/vi/)|
| 5   | **Nghiên cứu tài liệu khoa học (URL Phishing):** <br>&emsp;+ Tìm kiếm và chọn lọc các bài báo khoa học (research papers) liên quan đến kỹ thuật phát hiện URL lừa đảo (Phishing Detection). <br>&emsp; <br>&emsp;+ Tổng hợp các kiến thức và các đặc trưng họ đã dùng.                  | 21/05/2026   | 21/05/2026      |  |
| 6   | - Viết model cnn 1 lớp test độ chính xác trên dataset phishing url đạt 83% <br>&emsp;                                                                                          | 15/08/2025   | 15/08/2025      |  |


### Kết quả đạt được tuần 3:
* **Kiến thức AWS:**
  * Nắm vững các khái niệm cốt lõi của dịch vụ mạng Amazon VPC (Security Group, NACL, VPC Flow Logs).
  * Việc tự tay triển khai và thiết lập một hệ thống mạng VPC hoàn chỉnh trên AWS, bao gồm cấu hình routing (Route Table, Internet/NAT Gateway), bảo mật (Security Group) và thiết lập môi trường mạng lai kết nối VPN & DNS.

* **Về mảng Trí tuệ nhân tạo (AI/ML):**
  * Nâng cao kỹ năng nghiên cứu khoa học: Đọc hiểu, tổng hợp và rút trích thành công các đặc trưng  quan trọng từ các bài nghiên cứu về Phishing URL.
  * Ứng dụng thành công lý thuyết vào thực hành: Tự tay lập trình và xây dựng mô hình Deep Learning . Mô hình đã được kiểm thử trên tập dữ liệu Phishing URL và đạt được độ chính xác rất khả quan ở mức 83%, tạo tiền đề tốt để tối ưu hóa trong các tuần tiếp theo.

* **Về quá trình làm việc:**
  * Việc lên văn phòng giúp tăng cường tương tác trực tiếp, trao đổi kiến thức các vướng mắc trong quá trình làm Lab AWS.