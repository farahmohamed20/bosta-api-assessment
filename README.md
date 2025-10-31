# Bosta API Assessment 🚀

**Author:** Farah Mohamed  
**Role:** Software Quality Engineer  
**Task:** Senior QA Engineer Assessment – API Automation & Security Testing  

---

## 📘 Overview

This project contains Postman collections and automation setup for testing Bosta APIs as part of Task IV of the Senior QA Assessment.

The goal is to validate:
- Functional and negative behavior of API endpoints  
- Authentication and authorization (401, 403)  
- Input validation and security checks (SQLi, XSS, etc.)  
- API performance (response time tests)  
- CI/CD integration using GitHub Actions and Newman  

---

## 🧩 Contents

| File/Folder | Description |
|--------------|-------------|
| **Bosta Api Task/** | Contains Postman collections and environment files |
| `bosta-apis-security.postman_collection.json` | Collection covering login, pickup, bank info, forget password, and tracking APIs |
| `Bosta-Stg.postman_environment.json` | Postman environment for staging setup |
| `.github/workflows/api-ci.yml` | GitHub Actions workflow for automated API testing |
| `README.md` | Project documentation |

---

## ⚙️ How to Run Tests Locally

### 1️⃣ Install [Newman](https://www.npmjs.com/package/newman)
```bash
npm install -g newman
