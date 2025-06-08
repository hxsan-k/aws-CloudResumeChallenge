# AWS Cloud Resume Challenge 🌥️

This repository contains my version of the Cloud Resume Challenge where I used a range of tools and AWS services to build and deploy a personal CV website.

Check out my site here: https://hasanscloudcv.click

## ✅ What’s Done So Far

- **Static HTML Resume**  
  Hosted on Amazon S3 as a static website.

- **HTTPS Enabled**  
  Set up with Amazon CloudFront for secure access.

- **Custom Domain**  
  Managed via Route 53 for a clean, professional URL.

- **Visitor Counter**  
  Built with:
  - JavaScript on the front end
  - API Gateway & Lambda to connect to the back end
  - DynamoDB to store and update the visit count

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (AWS Lambda)  
- **Cloud Services:**  
  - S3 (static website hosting)  
  - CloudFront (HTTPS + caching)  
  - Route 53 (DNS + domain management)  
  - DynamoDB (NoSQL database)  
  - API Gateway (REST API)  
  - Lambda (serverless functions)  
- **Version Control:** Git & GitHub

## 🚧 In Progress

- **Infrastructure as Code (IaC):**  
  Automating AWS resource setup using [SAM or Terraform] (to be decided)

- **CI/CD Pipeline:**  
  Setting up GitHub Actions for automatic deployment of:
  - Frontend (to S3 + CloudFront cache invalidation)  
  - Backend (to AWS Lambda via SAM)

> More updates will be added as I continue building (or if I remember to update this:)). Thanks for checking it out!
