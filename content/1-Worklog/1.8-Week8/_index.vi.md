---
title: "Worklog Tuần 8"
date: "2025-12-08"
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---



### Mục tiêu tuần 8:

* Build và export website Hugo hoàn chỉnh.
* Học cách chuẩn bị output từ Hugo để deploy.
* Triển khai website Hugo tĩnh lên S3.
* Kết nối S3 → CloudFront để chạy website production.
* Kiểm tra lại website về tốc độ và khả năng truy cập.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Rà soát cấu trúc Hugo: layouts, themes, content <br> - Dọn dẹp nội dung, đảm bảo đầy đủ trang để deploy | 27/10/2025 | 27/10/2025 | Hugo Docs |
| 3 | - Chạy lệnh `hugo` để build website <br> - Kiểm tra folder `/public` (HTML, CSS, JS) | 28/10/2025 | 28/10/2025 | Hugo Docs |
| 4 | - Upload folder `/public` lên S3 bucket <br> - Bật static website hosting (nếu chưa bật) <br> - Truy cập thử qua endpoint S3 | 29/10/2025 | 29/10/2025 | AWS S3 Docs |
| 5 | - Cập nhật CloudFront distribution trỏ đến S3 <br> - Deploy thay đổi và test website qua domain CloudFront | 30/10/2025 | 30/10/2025 | AWS CloudFront Docs |
| 6 | - Kiểm tra website: <br>&emsp; + Tốc độ tải trang <br>&emsp; + Trang lỗi <br>&emsp; + Tất cả worklogs hiển thị đúng <br> - Thực hiện cache invalidation | 31/10/2025 | 31/10/2025 | AWS CloudFront Docs |



### Kết quả đạt được tuần 8:

* Build thành công website Hugo bằng thư mục `/public`.
* Kiểm tra và xác nhận toàn bộ trang được build đầy đủ.
* Upload website lên S3 và chạy được qua static hosting.
* Kết nối S3 và CloudFront để website chạy nhanh và ổn định trên toàn cầu.
* Test website qua CloudFront và đảm bảo mọi trang đều hiển thị đúng.
* Thực hiện cache invalidation để cập nhật nội dung tức thì.


