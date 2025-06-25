# AWS Cloud Resume Challenge 🌥️

This repository contains my version of the Cloud Resume Challenge where I used a range of tools and AWS services to build and deploy a personal CV website.

Check out my site here: https://hasanscloudcv.click

## ✅ What’s Done

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

- **Infrastructure as Code (IaC)**  
  All backend resources are defined in a SAM template and deployed using the AWS SAM CLI.

- **Source Control**  
  Both front end and back end have separate GitHub repos, with version control in place.

- **CI/CD Pipeline**  
  Set up with GitHub Actions:
  - **Backend**: Automatically runs integration tests and deploys via SAM if they pass  
    > ⚠️ Note: I tried setting up unit tests for the Lambda function but ran into a lot of issues with mocking DynamoDB properly. After spending a lot of time trying to fix it, I decided to comment them out so the CI pipeline could run smoothly. The integration test still works and checks the live API.
  - **Frontend**: Frontend repo is connected and working.

- **Blog Post**  
  A short write-up explaining what I learned and how I built the project is coming soon.

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
  - SAM (Infrastructure as Code)  
- **CI/CD:** GitHub Actions  
- **Version Control:** Git & GitHub

---

Thanks for checking out my first project on GitHub!
