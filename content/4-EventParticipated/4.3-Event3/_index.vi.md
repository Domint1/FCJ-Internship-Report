---
title: "Event 3"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 4.3. </b> "
---

# Báo cáo thu hoạch : AWS Cloud Mastery Series #2 – DevOps trên AWS  

### Mục tiêu sự kiện  

- Giới thiệu cho khách mời cách áp dụng các nguyên tắc DevOps một cách hiệu quả trên nền tảng AWS.  
- Trang bị cho khách mời nền tảng vững chắc về Infrastructure-as-Code (IaC), pipeline CI/CD, nền tảng container và chiến lược giám sát trên hệ sinh thái AWS.  
- Trình diễn các workflow DevOps thực tế sử dụng những dịch vụ như AWS CodeCommit, CodeBuild, CodeDeploy, CodePipeline, CloudFormation/CDK và các dịch vụ container (ECS/EKS/App Runner).  
- Cung cấp một lộ trình học tập DevOps từ đầu đến cuối cho developer và engineer muốn xây dựng và vận hành ứng dụng cloud-native trên AWS.  

### Diễn giả  

- **Văn Hoàng Kha** – AWS Community Builder  
- **Huỳnh Hoàng Long** – Cloud Engineer Trainee, First Cloud AI Journey  
- **Nguyễn Thịnh** – Cloud Engineer Trainee, First Cloud AI Journey  
- **Hoàng Quý** – Cloud Engineer Trainee, First Cloud AI Journey  

### Điểm nổi bật chính  

- Phiên buổi sáng giới thiệu về văn hoá DevOps, các nguyên lý cốt lõi và tác động kinh doanh khi áp dụng DevOps trên AWS, nhấn mạnh vào tốc độ, độ tin cậy và sự cộng tác.  
- Phân tích từng bước cách một pipeline CI/CD trên AWS hoạt động, từ source code trong CodeCommit đến build tự động bằng CodeBuild và triển khai bằng CodeDeploy do CodePipeline điều phối.  
- Phần Infrastructure-as-Code trình bày cả AWS CloudFormation và AWS CDK, gồm cách mô hình hoá hạ tầng thành template tái sử dụng, phát hiện “drift” cấu hình và quản lý nhiều môi trường một cách nhất quán.  
- Phần container hoá giải thích các khái niệm cơ bản về Docker, registry lưu trữ image với Amazon ECR, và các lựa chọn triển khai bằng Amazon ECS, Amazon EKS và AWS App Runner, minh hoạ qua kịch bản ứng dụng microservices.  
- Phần giám sát & khả năng quan sát (monitoring & observability) minh hoạ cách thu thập và phân tích metrics, logs và traces sử dụng Amazon CloudWatch và AWS X-Ray, kèm hướng dẫn thiết lập cảnh báo (alerts), dashboard và quy trình trực/on-call.  
- Các phiên buổi chiều tập trung vào best practice DevOps: lựa chọn chiến lược triển khai (blue/green, canary, feature flags), tích hợp kiểm thử tự động vào pipeline, xử lý sự cố (incident) và học hỏi từ các case study triển khai DevOps thực tế.  

### Bài học rút ra  

- Làm DevOps hiệu quả trên AWS được dẫn dắt bởi văn hoá và các chỉ số đo lường (như tần suất triển khai, thời gian đưa thay đổi lên production, MTTR), chứ không chỉ là chọn “đúng tool”.  
- Kết hợp pipeline CI/CD với IaC (CloudFormation/CDK) giúp đội ngũ tiêu chuẩn hoá việc triển khai, giảm lỗi thủ công và mở rộng hệ thống một cách tự tin.  
- Sử dụng containers và các dịch vụ container của AWS (ECS/EKS/App Runner) giúp đơn giản hoá việc chạy microservices, từ đó xây dựng hệ thống có khả năng mở rộng và tách rời (loosely coupled).  
- Thực hành monitoring và observability tốt — bao phủ metrics, logs và distributed tracing — là yếu tố then chốt để đảm bảo sức khoẻ hệ thống và phản ứng nhanh khi xảy ra sự cố.  
- Sự “xuất sắc” trong DevOps đến từ việc duy trì các best practice một cách liên tục: kiểm thử tự động, chiến lược triển khai hợp lý, review sau sự cố (postmortem) và cải tiến không ngừng.  

### Trải nghiệm sự kiện  

- Sự kiện mang lại một hành trình mạch lạc từ các khái niệm DevOps nền tảng đến triển khai thực tế trên AWS, giúp khách mời nhìn rõ cách mọi mảnh ghép kết nối với nhau.  
- Sự cân bằng giữa phần lý thuyết (văn hoá, metrics, nguyên lý DevOps) và phần demo thực hành (pipeline, IaC, containers) giúp nội dung dễ tiếp thu và có thể áp dụng ngay.  
- Các demo trực tiếp và case study về microservices giúp biến các khái niệm trừu tượng thành workflow cụ thể mà khách mời có thể điều chỉnh cho dự án của riêng mình.  
- Việc nhấn mạnh vào monitoring, observability và xử lý sự cố cho thấy vận hành ứng dụng trong môi trường production không chỉ dừng ở việc viết code, mà còn đòi hỏi khả năng quan sát hệ thống, kỷ luật vận hành và các quy trình được thiết kế tốt.