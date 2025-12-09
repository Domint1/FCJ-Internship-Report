---
title: "Worklog Tuần 11"
date: "2025-12-08"
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---



### Mục tiêu tuần 11:

* Học bảo mật web cơ bản cho ứng dụng cloud.
* Hiểu AWS WAF và cách bảo vệ website/API.
* Làm quen với các kiểu tấn công phổ biến (SQLi, XSS, bot xấu).
* Tạo WebACL đơn giản và gắn vào CloudFront hoặc API Gateway.
* Bật các Rule Group có sẵn của AWS để bảo vệ nhanh.

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | ---------------- | ------------------- |
| 2 | - Tìm hiểu các khái niệm bảo mật web cơ bản: <br>&emsp; + Tấn công WAF có thể chặn <br>&emsp; + Layer 7 vs Layer 4 <br>&emsp; + OWASP Top 10 (phiên bản đơn giản) | 17/11/2025 | 17/11/2025 | AWS Security Docs |
| 3 | - Học thành phần AWS WAF: WebACL, Rules, Rule Groups <br> - Hiểu Allow / Block / Count | 18/11/2025 | 18/11/2025 | AWS WAF Docs |
| 4 | - Tạo WebACL trong console <br> - Gắn WebACL vào CloudFront hoặc API Gateway <br> - Bật AWS Managed Rules (CommonRuleSet) | 19/11/2025 | 19/11/2025 | AWS WAF Managed Rules |
| 5 | - Tạo Rules đơn giản: <br>&emsp; + Chặn IP xấu <br>&emsp; + Chặn đường dẫn nguy hiểm (/wp-admin, /xmlrpc.php) <br>&emsp; + Rule theo rate (đếm số request) | 20/11/2025 | 20/11/2025 | AWS WAF Docs |
| 6 | - Test WAF: gửi request hợp lệ và request chứa ký tự SQL <br> - Xem log WAF và Dashboard để kiểm tra rule hoạt động | 21/11/2025 | 21/11/2025 | AWS WAF Logging |



### Kết quả đạt được tuần 11:

* Hiểu vai trò của AWS WAF trong việc bảo vệ ứng dụng khỏi tấn công Layer 7.
* Nắm cấu trúc WebACL, Rules và Rule Groups.
* Tạo WebACL và gắn vào CloudFront/API Gateway thành công.
* Bật Managed Rule Groups để bảo vệ khỏi các lỗ hổng phổ biến.
* Tạo một số Rule đơn giản để chặn IP/đường dẫn không hợp lệ.
* Test được WAF và xem log để xác minh hoạt động.
