---
title: "Worklog Tuần 8"
date: 2026-06-22
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:
- **Phát triển sản phẩm:** Tập trung lập trình và hoàn thành dứt điểm các chức năng (features) đang được giao trong dự án.
- **Đảm bảo chất lượng (QA/QC):** Lên kịch bản và chuẩn bị chi tiết bộ Test Case cho sản phẩm để sẵn sàng cho giai đoạn kiểm thử toàn diện.


### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **Thực hành Lab 44**: <br>&emsp;+ Tạo IAM Group, Users & kiểm tra quyền. <br>&emsp;+ Tạo Admin Role & cấu hình Switch role. <br>&emsp;+ Giới hạn Switch role theo IP và thời gian. <br>&emsp;+ Dọn dẹp tài nguyên. | 22/06/2026 | 22/06/2026 | [Lab 44](https://000044.awsstudygroup.com/vi/) |
| 3 | - **Chuẩn bị Kiểm thử (Testing):** <br>&emsp;+ Phân tích yêu cầu hệ thống để xác định các luồng kiểm thử (test flow). <br>&emsp;+ Bắt đầu soạn thảo các kịch bản kiểm thử (Test Case) cho sản phẩm (bao gồm cả trường hợp đúng và sai). | 23/06/2026 | 23/06/2026 | |
| 4 | - **Thực hành Lab 48**: <br>&emsp;+ Tạo EC2 Instance và S3 bucket <br>&emsp;+ Tạo và sử dụng IAM user cùng Access Key <br>&emsp;+ Tạo và cấu hình IAM role <br>&emsp;+ Dọn dẹp tài nguyên | 24/06/2026 | 24/06/2026 | [Lab48](https://000048.awsstudygroup.com/vi/)|
| 5 | - **Hoàn thiện Test Case:** <br>&emsp;+ Rà soát và hoàn thành bộ Test Case tổng thể, đảm bảo bao phủ các luồng nghiệp vụ. <br>&emsp;+ Tiến hành chạy thử (execute) Test Case trên các chức năng vừa phát triển. | 25/06/2026 | 25/06/2026 | |
| 6 | - **Review & Xử lý lỗi (Fix Bug):** <br>&emsp;+ Review chéo kết quả test với team để phát hiện các vấn đề tiềm ẩn. <br>&emsp;+ Tiến hành fix các lỗi phát hiện được: Cập nhật lại logic đăng ký, tối ưu tính năng upload (cho phép click chọn file thay vì chỉ bắt buộc kéo thả). | 26/06/2026 | 26/06/2026 | |

### Kết quả đạt được tuần 8:

* **Về mảng Điện toán đám mây (AWS):**
  * Hoàn thành xuất sắc Lab 44, nắm vững các kỹ năng quản trị IAM nâng cao. Biết cách thiết lập Admin Role, cấu hình Switch Role linh hoạt và áp dụng các chính sách bảo mật chặt chẽ (giới hạn quyền truy cập theo địa chỉ IP và khoảng thời gian nhất định).

* **Về mảng Phát triển & Đảm bảo chất lượng dự án:**
  * Xây dựng thành công bộ Test Case chi tiết và bao quát, giúp hệ thống hóa lại các luồng tính năng của sản phẩm.
  * Hoàn thành fix dứt điểm các lỗi (bug) phát sinh trong quá trình test: Logic luồng đăng ký đã hoạt động mượt mà, tính năng upload file được cải thiện trải nghiệm người dùng (UX) và hỗ trợ đa dạng định dạng tệp hơn, sẵn sàng cho các bước triển khai tiếp theo.

