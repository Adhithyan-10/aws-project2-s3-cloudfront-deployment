# 🏗️ Architecture Diagram

## 📌 Overview
This project demonstrates static website hosting using **Amazon S3** and **Amazon CloudFront** with secure HTTPS delivery and optimized performance.

---

## 🖼️ Architecture Diagram

![Architecture Diagram](./architecture-diagrammm.png)

---

## ⚙️ Architecture Components

### 👤 User
End users access the website via a browser using HTTPS.

### 🌐 Amazon CloudFront
- Acts as a Content Delivery Network (CDN)
- Provides **edge caching** for low latency
- Delivers content over HTTPS

### 🔐 AWS Certificate Manager (ACM)
- Provides SSL/TLS certificates
- Enables secure HTTPS communication

### 🪣 Amazon S3
- Static website hosting enabled
- Stores HTML, CSS, and JavaScript files
- Configured with index and error documents

### 🛡️ Bucket Policy
- Blocks public access
- Allows access only through CloudFront (OAC)
- Prevents direct access to S3

---

## 🔄 Request Flow

1. User sends HTTPS request
2. CloudFront checks cache:
   - If **cache hit** → serves from edge
   - If **cache miss** → fetches from S3
3. S3 returns static content
4. CloudFront delivers content securely to user

---

## 🚀 Key Highlights

- Serverless architecture (No EC2)
- Global content delivery
- Secure HTTPS communication
- Cost-efficient (Free Tier eligible)
- Scalable and low maintenance
