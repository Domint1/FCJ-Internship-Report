---
title: "Worklog Tuần 4"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---



### Mục tiêu tuần 4:

* Học sâu hơn về IAM: Users, Groups, Policies, Roles.
* Hiểu IAM kiểm soát truy cập vào AWS như thế nào.
* Học Lambda cơ bản: chức năng, cách hoạt động, khi nào nên dùng.
* Tìm hiểu giới thiệu về API Gateway.
* Xây nền tảng để kết nối các dịch vụ trong các tuần tới.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Học IAM Users & Groups <br> - Phân biệt Access Key và Password <br> - Tìm hiểu best practice bảo mật IAM | 29/09/2025 | 29/09/2025 | AWS IAM Docs |
| 3 | - Học cấu trúc IAM Policy (JSON): Effect, Action, Resource <br> - Tạo 1 policy đơn giản (chỉ read-only) | 30/09/2025 | 30/09/2025 | AWS IAM Docs |
| 4 | - Tìm hiểu IAM Role & Trust Policy <br> - Hiểu vì sao Lambda/EC2 dùng Role thay vì Access Key | 01/10/2025 | 01/10/2025 | AWS IAM Docs |
| 5 | - Học Lambda cơ bản: <br>&emsp; + Handler <br>&emsp; + Môi trường thực thi <br>&emsp; + Memory & Timeout <br> - Tạo Lambda “Hello World” | 02/10/2025 | 02/10/2025 | AWS Lambda Docs |
| 6 | - Tìm hiểu API Gateway cơ bản: <br>&emsp; + Endpoint <br>&emsp; + Method (GET/POST) <br>&emsp; + Tích hợp Lambda đơn giản | 03/10/2025 | 03/10/2025 | AWS API Gateway Docs |


### Kết quả đạt được tuần 4:

* Hiểu rõ các thành phần của IAM (User, Group, Policy, Role).
* Biết cách đọc và viết policy IAM ở mức cơ bản.
* Biết lý do IAM Role quan trọng đối với Lambda và EC2.
* Tạo được hàm Lambda đơn giản và test thành công.
* Hiểu nền tảng của API Gateway và cách tích hợp với Lambda.
* Xây dựng kiến thức serverless cơ bản cho những tuần tiếp theo.
