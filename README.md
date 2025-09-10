# 🌐 Serverless Web Application – Beast Mode Fitness  

## 📖 Project Overview  
Ye project ek *serverless web application* hai jo *AWS Services* ke through bana hai.  
Iska main aim hai users ka *registration data securely store karna DynamoDB (NoSQL database)* me.  
Frontend ko host kiya gaya hai *Amazon S3* par, taaki world-wide accessible ho.  

Ye application *scalable, cost-efficient aur easy-to-manage* hai, aur ek fitness platform provide karta hai jaha users apni journey start ya continue kar sakte hain – chahe beginner ho ya pro athlete.  

---

## 🛠 AWS Services Utilized  
- *Amazon S3* → Static website hosting (HTML, CSS, JS)  
- *AWS DynamoDB* → NoSQL DB for storing registration data  
- *AWS Lambda* → Backend logic (Python runtime)  
- *Amazon API Gateway* → RESTful API jo frontend aur backend ko connect karti hai  
- *IAM Role* → Secure access control Lambda aur DynamoDB ke beech  

---

## 💻 Web Technologies  
- *Frontend* → HTML, CSS, JavaScript  
- *Backend* → Python (AWS Lambda)  
- *IDE* → Visual Studio Code  

---

## ⚙ Implementation Workflow  

1. *Frontend Development*  
   - HTML, CSS, JS use karke website design banayi.  
   - User Registration form add kiya (name, email, fitness goals etc).  

2. *Database Configuration*  
   - DynamoDB me table create kiya with Partition Key.  

3. *IAM Role Setup*  
   - Custom IAM Role banayi jisse Lambda ko DynamoDB access securely mil sake.  

4. *AWS Lambda Function*  
   - Python me Lambda function likha jo POST request handle kare.  
   - Logic: User data DynamoDB me insert karna.  

5. *API Gateway Integration*  
   - API Gateway me REST API create kiya.  
   - POST method banakar Lambda function link kiya.  
   - CORS enable kiya aur API deploy karke endpoint URL generate kiya.  

6. *Frontend–Backend Integration*  
   - Registration form ke JavaScript code me API Gateway ka endpoint paste kiya.  

7. *S3 Hosting*  
   - Ek S3 bucket banayi aur usme website files upload ki.  
   - Public access configure kiya for global availability.  

8. *Testing & Validation*  
   - Website S3 public URL se access ki.  
   - Dummy data submit karke DynamoDB me verify kiya.  

---

## ✅ Key Outcomes  
- Pure serverless architecture bina server manage kiye.  
- Frontend (S3) + Backend (API Gateway + Lambda + DynamoDB) successful integration.  
- Real-time user data registration and storage.  
- Fitness community ke liye ek scalable cloud-native foundation ready.  

---

## 🎥 Demo Video  
👉 [Watch Project Demo](https://drive.google.com/file/d/17KxVS0SWKl0QKlvUWcv7fpqketOHxE0Z/view?usp=drivesdk)  

---
