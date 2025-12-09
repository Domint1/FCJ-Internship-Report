---
title: "Worklog Tuần 7"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---



### Mục tiêu tuần 7:

* Hiểu cách AWS Amplify Hosting(CloudFront + S3).
* Học quy trình build → deploy → host của Amplify dành cho frontend.
* Chuẩn bị mã nguồn frontend của dự án để deploy lên Amplify.
* Tìm hiểu cấu hình build, environment variables, và preview builds.
* Đảm bảo frontend đã sẵn sàng kết nối với API ở các tuần tiếp theo.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Tìm hiểu Amplify Hosting là gì và cách hoạt động (CloudFront + S3 bên trong) <br> - Hiểu các tính năng chính: CI/CD, SSL tự động, domain, preview | 20/10/2025 | 20/10/2025 | AWS Amplify Docs |
| 3 | - Rà soát cấu trúc project frontend <br> - Chạy project local để đảm bảo không bị lỗi <br> - Xác định build command và thư mục output | 21/10/2025 | 21/10/2025 | Project Source Code |
| 4 | - Tìm hiểu các cách deploy của Amplify: <br>&emsp; + Kết nối GitHub repo <br>&emsp; + Upload build folder thủ công cho site tĩnh <br> - Kiểm tra Amplify hỗ trợ framework bạn đang dùng | 22/10/2025 | 22/10/2025 | Amplify Console |
| 5 | - Chuẩn bị project chạy trên Amplify: <br>&emsp; + Kiểm tra build scripts (npm build/yarn build) <br>&emsp; + Xóa dependency không dùng <br>&emsp; + Chuẩn bị file .env.example | 23/10/2025 | 23/10/2025 | Project Docs |
| 6 | - Build project local ở chế độ production <br> - Kiểm tra folder build (HTML, JS, CSS) <br> - Ghi lại các bước build để dùng cho Week 8 | 24/10/2025 | 24/10/2025 | Project Source |



### Kết quả đạt được tuần 7:

* Hiểu Amplify Hosting.
* Chuẩn bị đầy đủ project frontend để deploy lên Amplify.
* Biết cách Amplify tự động build và deploy thông qua CI/CD.
* Xác nhận frontend chạy tốt ở local và đã sẵn sàng cho môi trường production.
* Tạo tài liệu build để hỗ trợ triển khai tuần sau.

---

