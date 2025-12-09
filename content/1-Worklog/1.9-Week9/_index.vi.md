---
title: "Worklog Tuần 9"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---



### Mục tiêu tuần 9:

* Học các khái niệm xác thực cơ bản (authentication).
* Phân biệt authentication và authorization.
* Xem lại IAM roles/policies dành cho ứng dụng.
* Học các khái niệm đơn giản về Cognito (User Pool, App Client).
* Thử nghiệm login cơ bản qua Hosted UI của Cognito.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Học các khái niệm xác thực: <br>&emsp; + Authentication là gì? <br>&emsp; + Authorization là gì? <br>&emsp; + Vì sao hệ thống cần quản lý danh tính? | 03/11/2025 | 03/11/2025 | AWS Security Docs |
| 3 | - Ôn lại IAM dành cho application: Roles, Permissions <br> - Hiểu ứng dụng nhận quyền truy cập AWS như thế nào | 04/11/2025 | 04/11/2025 | AWS IAM Docs |
| 4 | - Học cơ bản về Cognito: <br>&emsp; + User Pool <br>&emsp; + App Client <br>&emsp; + Hosted UI | 05/11/2025 | 05/11/2025 | AWS Cognito Docs |
| 5 | - Tạo Cognito User Pool <br> - Cấu hình password policy <br> - Tạo user test trong User Pool | 06/11/2025 | 06/11/2025 | AWS Cognito Docs |
| 6 | - Bật Hosted UI <br> - Test login, signup, reset password <br> - Quan sát ID token và access token | 07/11/2025 | 07/11/2025 | AWS Cognito Docs |


### Kết quả đạt được tuần 9:
* Hiểu rõ sự khác nhau giữa authentication và authorization.
* Nắm vai trò của IAM trong môi trường ứng dụng.
* Tìm hiểu các thành phần cơ bản của Cognito.
* Tạo User Pool thành công và thiết lập các cấu hình cơ bản.
* Thử login, signup qua Hosted UI và quan sát token trả về.
* Có nền tảng để kết hợp xác thực trong hệ thống serverless sau này.


