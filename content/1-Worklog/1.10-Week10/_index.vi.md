---
title: "Worklog Tuần 10"
date: "`r Sys.Date()`"
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---



### Mục tiêu tuần 10:

* Học CloudWatch cơ bản để giám sát ứng dụng AWS.
* Hiểu CloudWatch Logs và cách Lambda/API Gateway gửi log.
* Học CloudWatch Metrics (CPU, lỗi, latency…).
* Tạo cảnh báo đơn giản (CloudWatch Alarm).
* Hiểu vai trò giám sát trong serverless.


### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Học khái niệm CloudWatch: Logs, Metrics, Alarms <br> - Hiểu cách CloudWatch thu thập dữ liệu | 10/11/2025 | 10/11/2025 | AWS CloudWatch Docs |
| 3 | - Xem CloudWatch Logs: <br>&emsp; + Log nhóm của Lambda <br>&emsp; + Log stream <br>&emsp; + Tìm lỗi | 11/11/2025 | 11/11/2025 | CloudWatch Logs Docs |
| 4 | - Học các Metrics quan trọng: <br>&emsp; + Invocation count <br>&emsp; + Errors <br>&emsp; + Duration (Lambda) <br>&emsp; + Latency (API Gateway) | 12/11/2025 | 12/11/2025 | AWS Metrics Docs |
| 5 | - Tạo CloudWatch Alarms: <br>&emsp; + Alarm khi Lambda lỗi > 0 <br>&emsp; + Alarm khi API Gateway có nhiều 5XX | 13/11/2025 | 13/11/2025 | AWS Alarm Docs |
| 6 | - Kiểm tra alarm bằng cách tạo lỗi test <br> - Xem thông báo qua SNS (email) <br> - Xác nhận hệ thống monitor đã hoạt động | 14/11/2025 | 14/11/2025 | AWS SNS Docs |


### Kết quả đạt được tuần 10:

* Hiểu cách CloudWatch thu thập logs và metrics từ các dịch vụ AWS.
* Xem được log Lambda và API Gateway trong Log Groups.
* Hiểu các metrics quan trọng để theo dõi hiệu năng.
* Tạo cảnh báo CloudWatch Alarm đơn giản.
* Học cách SNS gửi thông báo khi alarm kích hoạt.
* Xây nền tảng giám sát phục vụ việc debug và đảm bảo vận hành.
