## AWS Project - Stocks Party

[GitHub Repository](https://github.com/StocksParty/stocks-party)



A serverless application that allows users to set custom stock price alerts and receive real-time notifications via email or SMS when their target price is reached.

---

## 📜 **Table of Contents**
- [Project Purpose](#project-purpose)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## 💡 **Project Purpose**
The Real-Time Stock Price Alert System was designed to automate stock monitoring for users who actively trade or invest. The application:
- Saves users time by eliminating the need to constantly track stock prices manually.
- Ensures users never miss key market opportunities by providing instant alerts.

---

## 🚀 **Features**
- Fetch live stock prices from an external API twice daily.
- Allow users to configure:
  - Stock ticker symbols
  - Target price thresholds
  - Notification preferences (email/SMS)
- Send real-time notifications when stock prices match user-defined targets.
- Serverless architecture for high scalability and cost efficiency.
- Monitoring and logging for debugging and usage analytics.

---

## 🛠️ **Technologies Used**

### Backend:
- **Programming Language:** Java
- **Cloud Services:**
  - AWS Lambda (Serverless Compute)
  - DynamoDB (NoSQL Database)
  - AWS SES (Email Notifications)
  - AWS SNS (SMS Notifications)
  - CloudWatch (Monitoring & Logs)

### Deployment Tools:
- AWS Management Console
- AWS CLI
- GitHub Actions (CI/CD pipeline for automated deployments)

---

## 🏗️ **Architecture**

The system follows a serverless architecture:
1. **Stock Price Fetching:**  
   - Lambda function triggered by CloudWatch every 12 hours.
   - Fetches stock prices using an external API.

2. **Database Management:**  
   - DynamoDB stores user configurations, including stock tickers, target prices, and notification preferences.

3. **Notification Service:**  
   - Lambda function sends alerts to users via SES (email) or SNS (SMS) when conditions are met.


# 🧠 Competencies Achieved

## Building Scalable, Cloud-Native Systems
A significant aspect of this project was designing a scalable, cost-effective system using cloud platforms. The serverless architecture leveraged AWS Lambda for compute, DynamoDB with auto-scaling for data storage, and CloudWatch for real-time monitoring. This ensured the application could efficiently handle increased user activity without impacting performance or incurring unnecessary costs. These design decisions demonstrated expertise in creating robust and scalable systems.

---

## Problem-Solving with Real-World Impact
The project addressed a common challenge for users: tracking stock prices in real time. By integrating external APIs, AWS notification services, and an efficient database structure, the application streamlined this process and provided timely alerts. This demonstrated the ability to understand user needs, design a tailored solution, and implement it effectively.

---

## Leveraging Serverless Technology for Innovation
The project showcased innovative use of serverless technology to deliver a highly reliable and cost-efficient solution. Using AWS services such as Lambda, SES, SNS, and CloudWatch not only minimized operational overhead but also ensured flexibility and scalability. This demonstrated a strong grasp of modern cloud-based development practices.

---
