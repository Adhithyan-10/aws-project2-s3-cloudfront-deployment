<h1 align="center">🌐 Project 2 — Static Website Hosting using Amazon S3 & CloudFront</h1>

<p align="center">
  <b>Serverless • CDN Accelerated • HTTPS Secured • Free-Tier Optimized</b>
</p>

---

## 🎯 Objective

Deploy a **static website** using **Amazon S3** for hosting and **Amazon CloudFront** for global CDN delivery with **HTTPS**, without using EC2 or any backend server — ensuring **zero maintenance** and **free-tier cost efficiency**.

---

## 🧩 Problem Statement

| Requirement | Explanation |
|------------|-------------|
| Host a static website | Use S3 static site hosting |
| Public Access | Apply S3 bucket policy for public read |
| Improve Global Performance | Use CloudFront CDN |
| Enable Security | Redirect HTTP → HTTPS |
| Ensure Cost Efficiency | Avoid EC2 compute charges |

---

## 🏗️ Architecture Diagram

```mermaid
flowchart LR
    A[👤 User Browser] --> B[🌍 CloudFront CDN (HTTPS + Caching)]
    B --> C[🪣 Amazon S3 Bucket (Static Website Files)]
# aws-project2-s3-cloudfront-deployment

## ☁️ AWS Services Used
---------------------------------

| Service | Icon | Purpose | Why Used |
|--------|:----:|---------|---------|
| **Amazon S3** | 🪣 | Stores and hosts static website files | Cost-efficient, serverless web hosting |
| **Amazon CloudFront** | 🌍 | Delivers content globally with caching | Ensures fast load speeds + low latency |
| **AWS Certificate Manager (ACM)** | 🔐 | Provides free SSL certificates | To enable **HTTPS** securely at no extra cost |
| **IAM (Identity and Access Management)** | 🔑 | Controls S3 bucket access permissions | Ensures correct public read access |
| **S3 Bucket Policy** | 📜 | Grants public object access | Allows users to access website files over the internet |


📂 Project Folder Structure
-------------------------------------
aws-project2-s3-cloudfront-deployment/
│
├─ site/
│   ├─ index.html
│   └─ style.css
│
└─ docs/
    ├─ project2_problem_statement.pdf
    ├─ project2_overview.pdf
    └─ project2_final_report_v8.pdf

🌍 Live Website URL:
  https://d345486x3djd94.cloudfront.net
Website loads globally with HTTPS and CDN caching enabled ✅

🎥 Project Demo Video
--------------------------
Click to Watch 👉
https://drive.google.com/file/d/1-IxHhJpkYO3g4SYbmF_WneD4RCHDNWsm/view?usp=drive_link


💡 Key Learnings
----------------------------
S3 works as a web hosting service for static content.
CloudFront improves global speed using edge caching.
ACM enables HTTPS at zero cost.
Avoiding EC2 means no compute cost and no server maintenance.


💼 Resume Bullet Points:
Deployed a static web application using Amazon S3 and CloudFront, enabling secure, globally distributed access under AWS Free Tier.
Configured S3 bucket policies, static website hosting, and CloudFront CDN for caching and HTTPS enforcement.
Achieved cost-effective and serverless deployment by eliminating EC2 compute requirements.

🗣️ Viva / Interview Response
------------------------------------
“I hosted the website on S3 because it contains only static files and doesn't need a server.
CloudFront provides global caching and enables HTTPS for secure delivery.
This architecture is scalable, cost-efficient, and commonly used in industry deployments.”


<p align="center"> ✅ <b>Project Successfully Completed</b> Next → <b>Project 3 (Backend + EC2 + RDS + IAM Roles)</b> 🔥 </p> ```


---
<h2 align="center">👨‍💻 Author</h2>

<p align="center"><b>Adhithyan Sivaraman T</b></p>

<p align="center">
📧 <a href="mailto:adhithyansivaraman@gmail.com">adhithyansivaraman@gmail.com</a><br>
🔗 <a href="https://www.linkedin.com/in/adhithyan-sivaraman-t-399b5b362">LinkedIn Profile</a><br>
💻 <a href="https://github.com/Adhithyan-10">GitHub Profile</a><br>
</p>

<p align="center">Feel free to connect for collaboration or discussions 🤝</p>
