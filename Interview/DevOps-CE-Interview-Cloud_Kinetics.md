## 1. **Cơ bản về Cloud Computing**: 

"Bạn có thể giải thích sự khác biệt giữa IaaS, PaaS, và SaaS không, và đưa ra ví dụ cho mỗi loại?"
- IaaS (Infrastructure as a Service) cung cấp cơ sở hạ tầng máy chủ, lưu trữ, và mạng ảo. 
- PaaS (Platform as a Service) cung cấp môi trường phát triển và triển khai ứng dụng. 
- SaaS (Software as a Service) là việc sử dụng phần mềm qua đám mây.

-	Ví dụ: AWS EC2 (IaaS), Heroku (PaaS), và Google Workspace (SaaS).

## 2. **Kinh nghiệm với các nhà cung cấp dịch vụ đám mây**: 

"Bạn đã từng làm việc với các nhà cung cấp dịch vụ đám mây nào (ví dụ: AWS, Azure, Google Cloud)? Hãy kể về một dự án bạn đã thực hiện sử dụng dịch vụ đám mây."
Làm việc chủ yếu với AWS, triển khai một hệ thống quản lý nội dung dựa trên các dịch vụ như EC2, S3, và RDS.
-	Ví dụ: Triển khai WordPress trên EC2, lưu trữ media trên S3 và database trên RDS (Relational Database Service).

## 3. **Kiến thức về Containers và Orchestration**: 

"Kinh nghiệm sử dụng Docker và Kubernetes? Hãy mô tả cách  triển khai và quản lý containers trong một môi trường sản xuất."

- Tôi đã sử dụng Docker để containerize các ứng dụng và Kubernetes để quản lý và tự động mở rộng containers.
-	Ví dụ: Triển khai một ứng dụng microservice trên Kubernetes, sử dụng Docker images cho mỗi microservice.
Khi sử dụng Kubernetes, tôi chịu trách nhiệm cấu hình và quản lý các pods (đơn vị cơ bản của Kubernetes chứa một hoặc nhiều containers), services (để phơi bày các ứng dụng ra bên ngoài hoặc nội bộ), và deployments (để quản lý việc triển khai và cập nhật ứng dụng).

Quản lý containers trong môi trường sản xuất với Kubernetes bao gồm việc theo dõi trạng thái của các containers, tự động mở rộng hoặc thu nhỏ số lượng containers dựa trên nhu cầu, và tự động phục hồi từ các sự cố. Tôi cũng sử dụng Helm charts để quản lý các deployments phức tạp một cách dễ dàng và Kubernetes Ingress để quản lý truy cập ngoại vi vào các services trong cluster.

## 4. **Hiểu biết về Infrastructure as Code (IaC)**: 

"Bạn đã sử dụng công cụ IaC nào (ví dụ: Terraform, AWS CloudFormation)? Hãy chia sẻ về kinh nghiệm của bạn trong việc quản lý và triển khai cơ sở hạ tầng như code."

Tôi đã sử dụng Terraform để tạo và quản lý cơ sở hạ tầng như code, cho phép tái sử dụng và tự động hóa đáng kể.
-	Ví dụ: Sử dụng Terraform để tạo một VPC, các Subnets, và EC2 Instances trong AWS.

## 13. CNI