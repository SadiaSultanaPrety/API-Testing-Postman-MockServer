# 🚀 Mock API Testing (Postman & Newman)

This repository demonstrates **API Testing** using Postman. I have implemented a complete testing workflow, from setting up a **Mock Server** to generating automated reports with **Newman**.

---

## 🎯 Project Scope
The project involves testing a set of REST APIs by simulating a real-world environment. It focuses on validating data integrity between the API responses and a local database setup.

### Key Highlights:
- **Mock Server Integration:** Simulated backend responses for consistent testing.
- **Assertions:** JavaScript tests for every request.
- **Environment Management:** Managed complex data using `QA Env` variables.
- **Automated Execution:** Integrated with **Newman** for CLI-based test runs.

---

## 🧪 Assertions & Validations
I have implemented assertions to ensure API reliability:

- ✅ **Functional Validation:** Checking if status codes match (`200 OK`, `201 Created`).
- ✅ **Data Integrity:** Comparing API response values with local database records.
- ✅ **Schema Validation:** Verifying that the JSON structure and data types are correct.
- ✅ **Performance Benchmarking:** Asserting that response times are within acceptable limits.

---

## 🛠️ Tech Stack & Tools
<p align="left">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Newman-EF5B25?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" />
</p>

---

## 📂 Repository Structure

| File / Folder Name | Description |
| :--- | :--- |
| 📁 [API-Testing-Postman-MockServer](./API-Testing-Postman-MockServer) | **Main Project Folder** containing all test artifacts. |
| 📄 [API Collection](./API-Testing-Postman-MockServer/MockAPITesting.postman_collection.json) | Main collection with requests and JavaScript assertions. |
| 📄 [Environment File](./API-Testing-Postman-MockServer/QA%20Env.postman_environment.json) | QA environment variables for dynamic testing. |
| 📁 [Newman Reports](./API-Testing-Postman-MockServer/newman) | Automated HTML execution reports. |
| 📁 [DB Screenshots](./API-Testing-Postman-MockServer/DB_Screenshots) | Database schema and data validation evidence. |
   
---

### 🗄️ Database Validation Evidence
I used a local database to verify that API responses accurately reflect the backend data. You can find the database schema and verification screenshots in the [DB_Screenshots](./DB_Screenshots) folder.
