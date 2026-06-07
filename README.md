# Cloud Computing Project Roadmap

Personal project roadmap documenting my journey learning AWS cloud infrastructure, security, automation, and production-style cloud architecture. Most infrastructure is written in Terraform and deployed on AWS using cost-conscious lab environments that are destroyed after testing.

---

## Projects

| #  | Project                    | Repo                                                                                                                                       | Status      |
| -- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ----------- |
| 1  | AWS Account Hardening      | [resil-project-01-aws-hardening](https://github.com/TGLEE4/resil-project-01-aws-hardening)                                                 | ✅ Complete |
| 2  | S3 Static Website          | [resil-project-02-s3-website](https://github.com/TGLEE4/resil-project-02-s3-website)                                                       | ✅ Complete |
| 3  | EC2 Web Server             | [resil-project-03-ec2-webserver](https://github.com/TGLEE4/resil-project-03-ec2-webserver)                                                 | ✅ Complete |
| 3b | EC2 Security Hardening     | [resil-project-03b-ec2-security-hardening](https://github.com/TGLEE4/resil-project-03b-ec2-security-hardening)                             | ✅ Complete |
| 4  | CloudFront + HTTPS         | [resil-project-04-cloudfront](https://github.com/TGLEE4/resil-project-04-cloudfront)                                                       | ✅ Complete |
| 5  | Route 53 Custom Domain     | [resil-project-05-route53](https://github.com/TGLEE4/resil-project-05-route53)                                                             | ✅ Complete |
| 6  | Lambda Serverless Function | [resil-project-06-lambda](https://github.com/TGLEE4/resil-project-06-lambda)                                                               | ✅ Complete |
| 7  | API Gateway + Lambda       | [resil-project-07-api-gateway-lambda](https://github.com/TGLEE4/resil-project-07-api-gateway-lambda)                                       | ✅ Complete |
| 8  | Docker                     | [resil-project-08-docker](https://github.com/TGLEE4/resil-project-08-docker)                                                               | ✅ Complete |
| 9  | Kubernetes + EKS           | coming soon                                                                                                                                | 🔲 Upcoming |
| 10 | CI/CD + GitHub Actions     | [tenglee-portfolio CI/CD docs](https://github.com/TGLEE4/tenglee-portfolio/blob/main/docs/ci-cd-github-actions.md)                         | ✅ Complete |
| 11 | Prometheus + Grafana       | coming soon                                                                                                                                | 🔲 Upcoming |

---

## Tools & Environment

| Tool          | Version / Use                                  |
| ------------- | ---------------------------------------------- |
| OS            | Ubuntu 24.04.4 LTS through WSL2                |
| VS Code       | Code editor opened from WSL using `code .`     |
| Terraform     | v1.15.3                                        |
| AWS CLI       | 2.34.48                                        |
| Git           | 2.43.0                                         |
| GitHub CLI    | 2.45.0                                         |
| Docker Engine | Used to build Docker images and run containers |
| Python        | 3.12 runtime used inside the Docker container  |
| curl          | Used to test local and cloud HTTP endpoints    |

---

## Skills Demonstrated

* AWS account security hardening
* IAM users, permissions, and least-privilege access
* S3 static website hosting
* EC2 provisioning and Linux web server configuration
* Production-style EC2 security hardening
* Custom VPC design with public and private subnets
* Private EC2 deployment with no public IP address
* No-SSH architecture using AWS Systems Manager Session Manager design
* Application Load Balancer configuration
* Security group chaining between ALB and EC2
* NAT Gateway for private subnet outbound internet access
* CloudFront CDN with HTTPS enforcement
* Origin Access Control (OAC)
* Route 53 DNS management and custom domain routing
* ACM SSL/TLS certificate validation
* HTTP to HTTPS redirection
* Lambda serverless function deployment
* API Gateway HTTP API integration with Lambda
* Docker image builds and container lifecycle basics
* Local container testing with port mapping
* Infrastructure as Code (Terraform)
* Terraform deploy, validate, plan, apply, and destroy workflow
* Infrastructure cost-control through immediate resource cleanup
* Security and cost tradeoff documentation
* Git and GitHub version control
* Technical documentation and project README writing
