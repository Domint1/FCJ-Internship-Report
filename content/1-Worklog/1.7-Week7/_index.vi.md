---
title: "Worklog Tuần 7"
date: "2025-12-08"
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---



### Mục tiêu tuần 7:

* Học sâu hơn về S3: bucket, object, permission.
* Hiểu cơ chế S3 static website hosting.
* Học CloudFront cơ bản để phân phối nội dung toàn cầu.
* Thực hành host website HTML đơn giản trên S3.
* Kết nối S3 → CloudFront để tối ưu tốc độ và bảo mật.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Tìm hiểu khái niệm S3: bucket, object key, region <br> - Học permissions: Block Public Access, Bucket Policy (mức cơ bản) | 20/10/2025 | 20/10/2025 | AWS S3 Docs |
| 3 | - Bật S3 static website hosting <br> - Upload file index.html, error.html <br> - Test website qua endpoint S3 | 21/10/2025 | 21/10/2025 | AWS S3 Docs |
| 4 | - Tìm hiểu CloudFront: distribution, origin, cache (TTL) <br> - Hiểu vai trò CDN giúp giảm latency | 22/10/2025 | 22/10/2025 | AWS CloudFront Docs |
| 5 | - Tạo CloudFront distribution dùng S3 làm origin <br> - Cấu hình behavior mặc định (GET, HEAD) <br> - Test domain CloudFront | 23/10/2025 | 23/10/2025 | AWS CloudFront Docs |
| 6 | - So sánh tốc độ giữa endpoint S3 và CloudFront <br> - Thực hiện cache invalidation đơn giản <br> - Kiểm tra tốc độ tải trang | 24/10/2025 | 24/10/2025 | AWS Docs |



### Kết quả đạt được tuần 7:

* Hiểu AWS là gì và nắm được các nhóm dịch vụ cơ bản: 
  * Compute
  * Storage
  * Networking 
  * Database
  * ...

* Đã tạo và cấu hình AWS Free Tier account thành công.

* Làm quen với AWS Management Console và biết cách tìm, truy cập, sử dụng dịch vụ từ giao diện web.

* Cài đặt và cấu hình AWS CLI trên máy tính bao gồm:
  * Access Key
  * Secret Key
  * Region mặc định
  * ...

* Sử dụng AWS CLI để thực hiện các thao tác cơ bản như:

  * Kiểm tra thông tin tài khoản & cấu hình
  * Lấy danh sách region
  * Xem dịch vụ EC2
  * Tạo và quản lý key pair
  * Kiểm tra thông tin dịch vụ đang chạy
  * ...

* Có khả năng kết nối giữa giao diện web và CLI để quản lý tài nguyên AWS song song.
* ...


