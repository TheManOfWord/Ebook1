# íº€ Serverless Lead Capture System on AWS

## í³– Overview
This project demonstrates a fully serverless web application built on AWS that captures user inquiries from a static website and processes them using cloud-native services.

---

## í¿—ï¸ Architecture

User â†’ S3 (Static Website) â†’ API Gateway â†’ Lambda â†’ 
â†’ DynamoDB (store data)
â†’ SES (send email)

---

## âš™ï¸ Services Used

- Amazon S3 (Static Hosting)
- Amazon CloudFront (CDN)
- AWS Lambda (Backend Logic)
- Amazon API Gateway (REST API)
- Amazon DynamoDB (Database)
- Amazon SES (Email Service)
- IAM (Security)
- CloudWatch (Monitoring)

---

## í´¥ Features

- Fully serverless architecture
- Scalable and cost-efficient
- Contact form integration
- Email notifications via SES
- Data persistence using DynamoDB
- CORS-enabled API

---

## í·ª How It Works

1. User submits form on website
2. API Gateway receives request
3. Lambda processes data
4. Data stored in DynamoDB
5. Email sent via SES

---

## í³‚ Project Structure

.
â”œâ”€â”€ website/
â”œâ”€â”€ lambda/
â”œâ”€â”€ docs/
â””â”€â”€ README.md

## í·  Learning Outcomes

- Built end-to-end serverless architecture
- Integrated multiple AWS services
- Implemented event-driven design
- Hands-on with IAM roles and policies

---

## í±¨â€í²» Author 
Hassan Javed Lodhi

