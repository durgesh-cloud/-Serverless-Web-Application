# 🌐 Beast Mode Fitness – Serverless Web Application  

## 📖 Project Overview  
Beast Mode Fitness is a *serverless web application* built with *AWS Services*.  
The application allows users to register online, and their details are securely stored in *DynamoDB (NoSQL database)*.  
The *frontend is hosted on Amazon S3*, making it globally accessible.  

This project provides a *scalable, cost-efficient, and easy-to-manage solution* for delivering a fitness platform where users can start or continue their journey – whether beginners or pro athletes.  

---

## 🛠 AWS Services Used  
- *Amazon S3* → Static website hosting (HTML, CSS, JS)  
- *AWS DynamoDB* → NoSQL database for user registration data  
- *AWS Lambda* → Backend logic (Python runtime)  
- *Amazon API Gateway* → RESTful API connecting frontend & backend  
- *IAM Role* → Secure access control between Lambda and DynamoDB  

---

## 💻 Technologies  
- *Frontend* → HTML, CSS, JavaScript  
- *Backend* → Python (AWS Lambda)  
- *IDE* → Visual Studio Code  

---

## ⚙ Implementation Workflow  

1. *Frontend Development*  
   - Built using HTML, CSS, JS.  
   - Includes user registration form (name, email, fitness goals).  

2. *Database Setup*  
   - DynamoDB table created with Partition Key.  

3. *IAM Role*  
   - Custom IAM Role created to allow Lambda access to DynamoDB.  

4. *Lambda Function*  
   - Python Lambda handles POST requests.  
   - Inserts user data into DynamoDB.  

5. *API Gateway*  
   - REST API created in API Gateway.  
   - POST method integrated with Lambda.  
   - CORS enabled and endpoint deployed.  

6. *Frontend–Backend Integration*  
   - API Gateway endpoint added to frontend JS code.  

7. *S3 Hosting*  
   - Website files uploaded to S3 bucket.  
   - Public access enabled for global reach.  

8. *Testing & Validation*  
   - Website tested using S3 public URL.  
   - Submitted dummy data verified in DynamoDB.  

---

## ✅ Key Outcomes  
- 100% serverless architecture (no server management).  
- Frontend (S3) + Backend (API Gateway + Lambda + DynamoDB) integration.  
- Real-time user data registration & storage.  
- Scalable and cloud-native foundation for fitness platforms.  

---

## 🎥 Demo Video  
👉 [Watch Project Demo](https://drive.google.com/file/d/17KxVS0SWKl0QKlvUWcv7fpqketOHxE0Z/view?usp=drivesdk)  

---
