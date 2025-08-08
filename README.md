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
