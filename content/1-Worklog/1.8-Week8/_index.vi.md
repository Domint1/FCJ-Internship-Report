---
title: "Worklog Tuần 8"
date: "2025-12-08"
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---



### Mục tiêu của Tuần 8:

* Deploy frontend của dự án thật bằng AWS Amplify Hosting.
* Hiểu quy trình Amplify: kết nối Git → build → deploy tự động.
* Cấu hình các biến môi trường (API URL, Region...).
* Kiểm tra hoạt động frontend → API Gateway → Lambda → DynamoDB.
* Chuẩn bị cho việc tích hợp xác thực (Cognito) ở các tuần sau.

---

### Công việc thực hiện trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Rà soát mã nguồn frontend và xác nhận chạy được local <br> - Build ở chế độ production để kiểm tra lỗi | 27/10/2025 | 27/10/2025 | Project Source |
| 3 | - Tìm hiểu workflow Amplify Hosting: <br>&emsp; + Build tự động <br>&emsp; + Deploy tự động <br>&emsp; + Preview builds theo branch | 28/10/2025 | 28/10/2025 | 
| 4 | - Kết nối GitHub repo với Amplify (khuyến nghị) <br> HOẶC <br> - Upload bản build thủ công (cho static site) <br> - Amplify tự tạo amplify.yml | 29/10/2025 | 29/10/2025 | 
| 5 | - Cấu hình môi trường dự án: <br>&emsp; + API Gateway URL <br>&emsp; + AWS Region <br>&emsp; + Token hoặc các biến cần thiết <br> - Trigger build & deploy | 30/10/2025 | 30/10/2025 |
| 6 | - Test toàn hệ thống: <br>&emsp; + Frontend → API Gateway → Lambda → DynamoDB <br>&emsp; + Kiểm tra CORS <br>&emsp; + Kiểm tra HTTPS & cache static files <br> - Ghi lại lỗi và fix nếu có | 31/10/2025 | 31/10/2025 | AWS Docs |

---

### Kết quả đạt được trong Tuần 8:

* Deploy thành công frontend dự án lên AWS Amplify Hosting.
* Hiểu quy trình build và deploy tự động thông qua GitHub.
* Cấu hình đầy đủ environment variables cho ứng dụng.
* Kiểm tra thành công luồng end-to-end: **Frontend → API → Lambda → DynamoDB**.
* Chuẩn bị nền tảng để tuần 9 tích hợp xác thực bằng Cognito.

---


