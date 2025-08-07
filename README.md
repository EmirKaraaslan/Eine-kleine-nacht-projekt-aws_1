

# ⚡️ The Power of Math (AWS Serverless Project)

This project is a simple **math calculator** that takes two inputs from the frontend and calculates the power of a number (base^exponent), using AWS services in a fully **serverless architecture**.

---

## 🧠 Features

- Static frontend hosted on **AWS Amplify**
- REST API powered by **API Gateway**
- Logic handled in **AWS Lambda** (Python)
- Data written into **DynamoDB**
- **IAM roles** for secure access
- Fully automated **CI/CD** with Amplify

---

## 🔧 Architecture Diagram

![diagram](diagram.png)

## 🖥️ Final Working UI

![final_web](final_web.png)

---



---

## ⚙️ AWS Lambda

Lambda function is written in **Python** and uses `math.pow` for calculation and writes to DynamoDB.

![aws_lambda](aws_lambda.png)

**Lambda Test Success**:
![aws_lambda_2_test](aws_lambda_2_test.png)

---

## 🧩 API Gateway Integration

![aws_apigateway](aws_apigateway.png)

Includes proper **CORS** setup and integration with Lambda.

---

## 🚀 AWS Amplify Hosting

![aws_amplify](aws_amplify.png)
![aws_amplify_2](aws_amplify_2.png)

The frontend is deployed and versioned using Amplify with support for multiple environments (e.g. `staging`, `test2`).

---

## 🔐 IAM Permissions

![aws_IAM](aws_IAM.png)

Lambda function uses an IAM role with permission to write to DynamoDB.

---

## 📦 Tech Stack

- Frontend: HTML + JS
- Backend: Python (AWS Lambda)
- Database: DynamoDB
- Infrastructure: API Gateway, IAM, Amplify

---

## 🧪 How to Run

1. Clone the repo
2. Deploy frontend with Amplify or locally with `Live Server`
3. Make sure your Lambda + API Gateway are deployed
4. Try the app!

---

## 📷 Screenshots

All screenshots above are taken from live deployments on AWS.

