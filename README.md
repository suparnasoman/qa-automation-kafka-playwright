# qa-automation-kafka-playwright
End-to-end Quality Engineering project integrating API testing, UI testing, Kafka messaging, and CI/CD in Azure DevOps

## 📌 Overview
This is an **end-to-end Quality Engineering showcase project** built using the [RealWorld Example App](https://github.com/gothinkster/realworld) as the application under test.  
The goal of this project is to demonstrate my expertise in:

- **Backend API testing** (Postman / Playwright API)
- **UI automation** with Playwright + TypeScript
- **SQL & advanced data validation** using PostgreSQL
- **Message queue validation** with Apache Kafka *(planned)*
- **CI/CD pipelines** in Azure DevOps
- **Containerized deployments** with Docker & Kubernetes *(planned)*
- **ETL testing**

This project is designed to mimic a real-world enterprise QA workflow — from local environment setup to automated regression execution in CI/CD.

---

## 🛠 Tech Stack
| Layer               | Technology |
|---------------------|------------|
| **Backend**         | Node.js, Express |
| **Database**        | PostgreSQL (Docker) |
| **UI Automation**   | Playwright + TypeScript |
| **API Testing**     | Playwright API Testing, Postman |
| **CI/CD**           | Azure DevOps Pipelines *(upcoming)* |
| **Messaging Queue** | Apache Kafka *(upcoming)* |
| **Containerization**| Docker, Kubernetes *(upcoming)* |

---

## 🚀 Features
- Automated **API test suite** for CRUD operations
- Automated **UI tests** for core workflows
- Database query validation for backend consistency
- Ready for Kafka consumer/producer validation
- Modular test architecture for scalability

---

## 📂 Project Structure

end-to-end-quality-engineering-project/
│
├── backend/ # Node.js RealWorld backend
├── qa-tests/ # Playwright + TypeScript automation
│ ├── tests/ # Test cases
│ ├── fixtures/ # Test data
│ ├── utils/ # Helpers, DB connections, Kafka client
│
└── README.md


---

## 🏗 Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/realworld-quality-engineering-project.git
cd realworld-quality-engineering-project
---

### 2️⃣ Start PostgreSQL in Docker
```bash
Copy
Edit
docker run --name postgres-realworld \
  -e POSTGRES_USER=realworld \
  -e POSTGRES_PASSWORD=realworld \
  -e POSTGRES_DB=realworld \
  -p 5432:5432 -d postgres:14

### 3️⃣ Run Backend
```bash
Copy
Edit
cd backend
npm install
npm start

**
### 4️⃣ Run Tests**
```bash
Copy
Edit
cd qa-tests
npm install
npx playwright test

📅 Roadmap

Integrate Kafka producer/consumer and validate message flow

 Deploy backend & DB on Kubernetes

 Add ETL pipeline validation

 Configure CI/CD in Azure DevOps

 Performance testing with k6

📜 License

MIT License — feel free to fork and adapt.

yaml
Copy
Edit

---
