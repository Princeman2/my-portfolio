# Automated Portfolio Website on AWS | Cloud & DevOps Project

**Modern, fully automated static website deployed on AWS with CI/CD pipeline**

![Live Portfolio](screenshots/1-live-website.png)

---

## 📋 Project Summary

Built and automated a professional portfolio website on **AWS Free Tier** to demonstrate core **Cloud Engineering** and **DevOps** competencies. The solution features Infrastructure configuration, secure access management, and fully automated deployments.

**Live Demo**: [https://dxxxxxxxxxxxx.cloudfront.net](https://dncirrmczawoc.cloudfront.net/)  
**Status**: Production-ready | Fully Automated

---

## 🎯 Key Achievements

- Designed and deployed a responsive, professional website using **AWS S3 + CloudFront**
- Implemented **end-to-end CI/CD pipeline** that deploys changes in under 60 seconds
- Applied **least privilege security principles** using custom IAM policies
- Achieved **zero-downtime deployments** with automatic CloudFront cache invalidation
- Maintained **$0 monthly cost** through careful Free Tier usage

---

## 🛠️ Technologies & Tools

| Category              | Technologies                                      |
|-----------------------|---------------------------------------------------|
| **Cloud Platform**    | AWS S3, CloudFront, IAM                           |
| **CI/CD**             | GitHub Actions                                    |
| **IaC & Automation**  | AWS CLI, S3 Sync                                  |
| **Frontend**          | HTML5, Tailwind CSS, Responsive Design            |
| **Security**          | Least Privilege IAM Policy, Origin Access Control |
| **Version Control**   | Git, GitHub                                       |

---

## 📸 Project Highlights

### 1. Live Professional Portfolio
![Live Website](screenshots/1-live-website.png)

### 2. S3 Static Website Hosting
![S3 Bucket Configuration](screenshots/2-s3-bucket.png)

### 3. CloudFront Global CDN
![CloudFront Distribution](screenshots/3-cloudfront.png)

### 4. Automated CI/CD Pipeline
![GitHub Actions Workflow](screenshots/4-github-actions.png)

### 5. IAM User & Permissions
![IAM User Permissions](screenshots/5-iam-policy.png)

### 6. Least Privilege Policy (JSON)
![Custom IAM Policy](screenshots/6-iam-policy-json.png)

---

## 🧩 Architecture & Implementation

### Step-by-Step Highlights

1. **Infrastructure Provisioning**
   - Created S3 bucket with Static Website Hosting
   - Configured CloudFront distribution for global delivery and HTTPS

2. **Security Implementation**
   - Designed a custom IAM policy following **least privilege** principle
   - Secured S3 access via proper bucket policies

3. **CI/CD Pipeline**
   - Built GitHub Actions workflow for automatic deployment
   - Integrated secure credential management using GitHub Secrets

---

## 💡 What I Learned & Demonstrated

- **Cloud Services**: Deep understanding of S3 static hosting and CloudFront CDN
- **DevOps Practices**: End-to-end automation and CI/CD principles
- **Security Best Practices**: Least privilege access and secure credential handling
- **Troubleshooting**: IAM permission issues and CloudFront caching behaviour
- **Documentation**: Clear technical communication for future team collaboration

---

## 🚀 Future Enhancements (Roadmap)

- Custom domain with AWS Route 53
- Infrastructure as Code using **Terraform**
- Serverless contact form using AWS Lambda + DynamoDB
- Monitoring with CloudWatch
- Multi-environment deployment (dev/prod)

---

## 📂 Project Structure
