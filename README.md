# ☁️ Zara’s Cloud Portfolio

Welcome to my AWS-based cloud and software engineering portfolio!  
This site showcases hands-on projects I've built while transitioning from a biomedical science background into tech — focusing on real-world solutions across health tech, fintech, and cloud cost visibility.

Hosted on **Amazon S3**, this portfolio includes both low-code and code-based cloud projects using core AWS services.

---

## 🌟 Featured Projects

### 🔐 Secure Health API Gateway
Simulates exposing an internal health service via a secure API using:
- **AWS Lambda (Python)** for mock test result lookup
- **API Gateway (REST)** to expose and control the endpoint
- **API Keys + Usage Plan** for secured, rate-limited access
- **Tested** using `curl` for both authorized and unauthorized scenarios

📎 [Live API Endpoint (key required)](https://7j836ikqz0.execute-api.eu-west-2.amazonaws.com/check-test-result?patient_id=12345)

---

### 🖼️ Auto-Tag Image Uploads with Lambda
Auto-tags uploaded images in S3 with metadata (file type, size, etc.) using:
- **S3 triggers**
- **Python Lambda**
- **Boto3 SDK**
- A serverless, scalable automation example

---

### 🏥 NHS Contact Tracing Data Query
Analyzed real contact tracing data using:
- **Amazon S3** for data storage
- **Amazon Athena** for serverless SQL queries
- **CSV tagging & metadata** for discoverability

---

### 💱 Currency Exchange Tracker (FinTech)
Tracked USD → GBP rates over 30 days using:
- **Daily snapshots stored in S3**
- **Athena queries** to show trends
- Focus on low-code AWS analytics

---

### 📊 Cloud Cost Tracker
Analyzed simulated AWS billing reports with:
- S3 upload of cost CSVs
- Athena SQL queries to summarize by service & date
- FinOps-style accountability

---

## 🧠 Tech Stack

- **Hosting:** Amazon S3 (Static Website)
- **Cloud Services:** Lambda, API Gateway, S3, Athena, IAM
- **Languages:** Python, HTML/CSS, SQL
- **Tools:** Boto3, VS Code, Terminal, GitHub

---

## 🚀 Live Portfolio Site

[Visit the live site →](https://YOUR-S3-WEBSITE-ENDPOINT-HERE)

---

## 🙋‍♀️ About Me

I'm Zara — a Biomedical Sciences grad turned AWS Cloud Engineer. I’m passionate about building secure, efficient, and practical solutions in both the health and financial space.

This portfolio is built and deployed independently to showcase my growth, learning, and proof of work.

---

## 📫 Connect with Me

- LinkedIn: [linkedin.com/in/your-link](https://linkedin.com)
- GitHub: [github.com/yourusername](https://github.com/yourusername)
