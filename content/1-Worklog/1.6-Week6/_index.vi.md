---
title: "Worklog Tuần 6"
date: "2025-12-08"
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---



### Mục tiêu tuần 6:

* Học sâu hơn về API Gateway theo mô hình REST API.
* Hiểu cách API Gateway xử lý Resource, Method và Response.
* Thực hành kết nối API Gateway → Lambda → DynamoDB.
* Học cách xử lý input, mapping, và trả về status code cơ bản.
* Test API bằng trình duyệt, Postman hoặc curl.


### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Tìm hiểu cấu trúc API Gateway: Resource, Method, Stage <br> - Phân biệt hành vi của GET và POST | 13/10/2025 | 13/10/2025 | AWS API Gateway Docs |
| 3 | - Tạo API đơn giản với endpoint `/test` <br> - Kết nối API Gateway → Lambda dùng “Lambda Proxy Integration” | 14/10/2025 | 14/10/2025 | AWS API Gateway Docs |
| 4 | - Học cách API Gateway gửi event vào Lambda <br> - Tìm hiểu mapping cơ bản: statusCode, headers, body | 15/10/2025 | 15/10/2025 | AWS Lambda Docs |
| 5 | - Kết nối API → Lambda → DynamoDB <br> - Dùng GET để lấy dữ liệu DynamoDB <br> - Trả kết quả dưới dạng JSON | 16/10/2025 | 16/10/2025 | AWS API + DynamoDB Docs |
| 6 | - Dùng POST để ghi dữ liệu vào DynamoDB qua Lambda <br> - Test API bằng Postman/browse/curl <br> - Xem log API/Lambda bằng CloudWatch | 17/10/2025 | 17/10/2025 | AWS CloudWatch Docs |



### Kết quả đạt được tuần 6:


* Hiểu rõ cấu trúc REST API của API Gateway.
* Tạo API với nhiều Resource và Method khác nhau.
* Hiểu cơ chế Proxy Integration và cách event truyền xuống Lambda.
* Xây dựng thành công luồng API → Lambda → DynamoDB.
* Biết sử dụng GET/POST để đọc và ghi dữ liệu thông qua API.
* Thành thạo việc test API bằng nhiều công cụ khác nhau.
* Biết xem log CloudWatch để kiểm tra lỗi và theo dõi hoạt động API.
