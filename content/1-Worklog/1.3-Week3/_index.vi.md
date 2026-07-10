---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Thực hành thiết lập công cụ quản lý chi tiêu AWS Budgets để giám sát chi phí dịch vụ đám mây một cách chặt chẽ.
* Nắm vững các bước phân quyền thực tế trong hệ thống với AWS IAM thông qua việc quản trị Users, Groups, Roles và cấu hình Switch Role.
* Nghiên cứu hạ tầng vật lý và mô hình vận hành của AWS Data Center cùng các bài lab bổ trợ.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Nghiên cứu chi tiết về dịch vụ AWS Budgets và cách thức thiết lập ngân sách <br> - Thực hành tạo lập ngân sách kiểm soát chi phí (Cost Budget) và cấu hình ngưỡng cảnh báo tự động qua email khi chi phí vượt hạn mức | 04/05/2026 | 04/05/2026 | <https://000007.awsstudygroup.com/> |
| 3 | - Thực hành quản lý truy cập cơ bản bằng dịch vụ AWS IAM <br> - Khởi tạo các IAM Users, IAM Groups và gán chính sách phân quyền (Policies) phù hợp để quản trị người dùng | 05/05/2026 | 05/05/2026 | <https://000002.awsstudygroup.com/> |
| 4 | - Nghiên cứu sâu hơn và thực hiện bài lab nâng cao về IAM Roles <br> - Tiến hành thực hành cơ chế chuyển đổi vai trò (Switch Role) từ tài khoản thường sang vai trò Admin quản trị | 06/05/2026 | 06/05/2026 | <https://000002.awsstudygroup.com/> |
| 5 | - Học tập kiến thức tổng quan về trung tâm dữ liệu vật lý AWS Data Center <br> - Nghiên cứu cách thiết kế độ sẵn sàng cao, hệ thống dự phòng nguồn điện, tản nhiệt và các tiêu chuẩn bảo mật vật lý nghiêm ngặt | 07/05/2026 | 07/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | - Thực hiện các bài lab trực quan hóa và mô phỏng cấu trúc hạ tầng vật lý toàn cầu của AWS <br> - Tổng kết kiến thức đã học trong tuần, đánh giá hoạt động phân quyền IAM và kiểm tra trạng thái ngân sách AWS Budgets | 08/05/2026 | 08/05/2026 | <https://000007.awsstudygroup.com/> |


### Kết quả đạt được tuần 3:

* **Kiểm soát tốt ngân sách đám mây:**
  * Cấu hình thành công các cảnh báo tài chính trong AWS Budgets với các ngưỡng chi tiêu dự báo (forecasted cost) và chi tiêu thực tế (actual cost).
  * Hiểu rõ cơ chế tự động gửi thông báo qua email khi tài khoản có xu hướng vượt ngưỡng chi phí đã lập lịch trước.

* **Làm chủ kỹ năng cấu hình AWS IAM thực tế:**
  * Biết cách tạo lập, quản lý và phân nhóm người dùng (IAM Users & Groups) một cách bài bản.
  * Tự tay xây dựng chính sách (IAM Policies) và vai trò (IAM Roles) phục vụ việc ủy thác quyền truy cập tạm thời.
  * Thực hành thành thạo tính năng Switch Role từ tài khoản vận hành Operator User sang Admin Role, tuân thủ nguyên tắc không sử dụng Root Account cho các hoạt động thường ngày.
  * Thực hành và áp dụng thành công Nguyên tắc đặc quyền tối thiểu (Least Privilege).

* **Hiểu sâu về hạ tầng vật lý của AWS (AWS Data Center):**
  * Nắm được cách thức AWS thiết kế các trung tâm dữ liệu nhằm đảm bảo tính dự phòng cao (High Availability) và khả năng chống chịu lỗi (Fault Tolerance).
  * Hoàn thành các bài lab mô phỏng và sơ đồ trực quan hóa hạ tầng mạng lưới vật lý của AWS.
