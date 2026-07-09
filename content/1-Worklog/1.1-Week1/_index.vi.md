---
title: "Worklog Tuần 1"
date: 2026-04-20
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---



### Mục tiêu tuần 1:

* Tham dự sự kiện khởi động dự án (Kickoff AWS).
* Giao lưu, kết nối với đội ngũ First Cloud AI Journey (FCAJ), đồng thời tiếp thu và tuân thủ các quy định, nội quy làm việc của đơn vị thực tập.
* Nghiên cứu cơ chế kiểm soát và quản lý quyền truy cập thông qua dịch vụ AWS IAM.
* Thực hành xây dựng mô hình phân quyền cơ bản với IAM Users, Groups, Roles và thử nghiệm tính năng chuyển đổi vai trò.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Gặp gỡ các thành viên trong dự án FCAJ <br> - Học tập nội quy và quy chế hoạt động của đơn vị thực tập <br> - Tham dự sự kiện AWS Kickoff khởi động kỳ thực tập <br> - Tìm hiểu tổng quan về hạ tầng cloud AWS và các nhóm dịch vụ cốt lõi (Compute, Storage, Network, Database) | 20/04/2026 | 20/04/2026 |  |
| 3 | - Thiết lập tài khoản AWS Free Tier phục vụ cho quá trình thực hành <br> - Thực hiện chuỗi thử thách giới thiệu để nhận hỗ trợ 100$ AWS Credit <br> - Thiết lập cơ chế xác thực đa yếu tố (MFA) để bảo vệ tài khoản gốc <br> - Cấu hình công cụ quản lý ngân sách AWS Budgets | 21/04/2026 | 21/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Nghiên cứu cơ chế hoạt động của IAM Users và IAM Groups <br> - Khởi tạo Admin Group cùng tài khoản Admin User quản trị hệ thống <br> - Gán quyền hạn `AdministratorAccess` cho Admin Group <br> - Thực hành đăng nhập và thao tác bằng tài khoản Admin User mới | 22/04/2026 | 22/04/2026 | <https://000002.awsstudygroup.com/> |
| 5 | - Nghiên cứu vai trò và ứng dụng của IAM Roles trong thực tế <br> - Tạo lập các phân quyền vai trò chuyên biệt (AdminRole, S3Role) <br> - Khởi tạo Operator User và gán chính sách cấu hình quyền ủy thác vai trò | 23/04/2026 | 23/04/2026 | <https://000002.awsstudygroup.com/> |
| 6 | - Thực hành kỹ thuật Switch Role (Chuyển đổi vai trò) từ Operator sang Admin để xử lý công việc <br> - Kiểm tra và xác thực giới hạn truy xuất dịch vụ S3 thông qua quyền hạn của S3Role <br> - Thực hành thiết lập quyền hạn theo nguyên tắc tối thiểu cần thiết | 24/04/2026 | 24/04/2026 | <https://000002.awsstudygroup.com/> |


### Kết quả đạt được tuần 1:

* **Hội nhập môi trường làm việc:**
  * Tham gia đầy đủ buổi khai mạc Kickoff, làm quen với tập thể First Cloud AI Journey (FCAJ).
  * Hiểu rõ và tuân thủ các quy tắc ứng xử, quy định nội bộ và quy trình thực tập tại cơ quan.

* **Kiến thức nền tảng về hạ tầng AWS:**
  * Có cái nhìn tổng quan về điện toán đám mây AWS và phân biệt rõ các nhóm dịch vụ cốt lõi:
    * **Compute (Tính toán):** Nắm rõ chức năng của EC2, Lambda,.
    * **Storage (Lưu trữ):** Hiểu các giải pháp S3.
    * **Networking (Mạng lưới):** Cách thức hoạt động cơ bản của VPC, Route53, CloudFront.
    * **Database (Cơ sở dữ liệu):** Làm quen với RDS, DynamoDB.
    * **Security & Identity (An ninh & Định danh):** Nắm bắt vai trò của IAM, KMS.

* **Quản trị tài khoản cá nhân & Kiểm soát chi phí:**
  * Thiết lập thành công môi trường thực hành AWS Free Tier.
  * Tích lũy được $100 AWS Credit nhờ hoàn thành các thử thách hướng dẫn ban đầu.
  * Tăng cường an toàn thông tin bằng cách cấu hình bảo mật đa lớp (MFA) cho tài khoản Root.
  * Chủ động cài đặt hạn mức và cảnh báo tự động thông qua dịch vụ AWS Budgets để phòng tránh phát sinh chi phí ngoài ý muốn.

* **Làm chủ dịch vụ quản lý định danh AWS IAM:**
  * Phân biệt rõ ràng mục đích sử dụng của IAM User (cung cấp thông tin xác thực cố định) và IAM Role (cấp quyền truy cập tạm thời có thời hạn).
  * Định cấu hình thành công nhóm quyền Admin (Admin Group) sử dụng chính sách `AdministratorAccess` và chỉ định người dùng tương ứng.
  * Thiết kế và triển khai các Roles chuyên biệt: `AdminRole` (quản trị toàn diện) và `S3Role` (chỉ truy xuất bộ lưu trữ S3).
  * Xây dựng cơ chế ủy quyền bằng cách tạo Operator User cùng chính sách chuyển đổi vai trò (Assume Role policy).
  * Kiểm nghiệm thực tế quy trình Switch Role thành công, chuyển đổi linh hoạt từ tài khoản thường sang vai trò Admin.
  * Thiết lập thói quen thao tác an toàn bằng cách đăng nhập và làm việc thông qua IAM User thay vì dùng tài khoản Root.

* **Ứng dụng các quy chuẩn bảo mật IAM tốt nhất:**
  * Quán triệt nguyên tắc phân quyền tối thiểu (Least Privilege), chỉ cấp đúng những gì cần thiết cho công việc.
  * Khuyến khích sử dụng IAM Roles khi phân quyền tạm thời để hạn chế lộ lọt Access Keys/Secret Keys dài hạn.
  * Thiết lập yêu cầu bắt buộc kích hoạt MFA cho các tài khoản có quyền hạn cao.
  * Sử dụng công cụ AWS CloudTrail để ghi vết lịch sử hoạt động và giám sát hành vi truy cập hệ thống.
  * Hạn chế tối đa việc sử dụng tài khoản Root cho công việc vận hành thường nhật.
