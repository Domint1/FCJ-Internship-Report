---
title: "Worklog Tuần 5"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---



### Mục tiêu tuần 5:

* Củng cố kiến thức về AWS Lambda thông qua các bài thực hành.
* Tìm hiểu cách Lambda tương tác với các dịch vụ AWS khác.
* Hiểu cơ bản về DynamoDB – cơ sở dữ liệu NoSQL của AWS.
* Học cách thực hiện thao tác đọc/ghi đơn giản với DynamoDB.
* Tìm hiểu CloudWatch Logs để xem log chạy của Lambda.


### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Ôn lại cấu trúc Lambda: handler, event object, kết quả trả về <br> - Hiểu sơ lược khác biệt giữa synchronous vs asynchronous invocation | 06/10/2025 | 06/10/2025 | AWS Lambda Docs |
| 3 | - Học DynamoDB cơ bản: Table, Partition Key (PK), Sort Key (SK) <br> - Hiểu sự khác nhau giữa NoSQL và database quan hệ | 07/10/2025 | 07/10/2025 | AWS DynamoDB Docs |
| 4 | - Tạo 1 bảng DynamoDB (PK đơn giản) <br> - Thêm item thủ công trong bảng qua Console <br> - Thử Query & Scan trên Console | 08/10/2025 | 08/10/2025 | AWS DynamoDB Docs |
| 5 | - Viết Lambda để đọc dữ liệu từ DynamoDB (GetItem) <br> - Học quyền IAM cần thiết: `dynamodb:GetItem` | 09/10/2025 | 09/10/2025 | AWS Lambda + DynamoDB Docs |
| 6 | - Viết Lambda để ghi dữ liệu vào DynamoDB (PutItem) <br> - Kiểm tra log bằng CloudWatch Logs | 10/10/2025 | 10/10/2025 | AWS CloudWatch Docs |



### Kết quả đạt được tuần 5:

* Hiểu rõ hơn cách Lambda nhận input và trả output dưới dạng JSON.
* Nắm được kiến thức cơ bản của DynamoDB và cách lưu trữ dữ liệu key-value.
* Tạo bảng DynamoDB thành công và thử Query/Scan.
* Viết Lambda đơn giản để đọc và ghi dữ liệu DynamoDB.
* Hiểu vai trò của IAM permissions khi Lambda truy cập DynamoDB.
* Biết sử dụng CloudWatch Logs để xem log và debug lỗi của Lambda.

