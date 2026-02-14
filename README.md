# FUTURE_CS_03 – API Security Risk Analysis Report

---

##  Project Objective

This project focuses on analyzing and evaluating the security posture of a public REST API.

The assessment includes authentication checks, data exposure analysis, authorization testing, and risk classification.

Target API:
https://jsonplaceholder.typicode.com

---

##  Assessment Process

1. Reviewed API documentation
2. Tested endpoints using Postman
3. Inspected HTTP requests & responses
4. Analyzed headers
5. Identified security risks
6. Classified risk severity
7. Suggested remediation steps

---

## 🛠 Tools Used

- Postman
- Browser Developer Tools
- Public REST API (JSONPlaceholder)
- Manual API Testing

---

##  Key Risks Identified

1. Open / Unauthenticated Endpoints
2. Excessive Data Exposure
3. No Authentication Tokens Required
4. No Rate Limiting
5. Lack of Authorization Controls

---

## ⚖ Risk Severity Classification

| Risk | Severity |
|------|----------|
| Open Endpoints | High |
| Excessive Data Exposure | Medium |
| Missing Rate Limiting | High |
| Authorization Issues | High |

---

## 🛡 Remediation Recommendations

- Implement OAuth2 / JWT Authentication
- Apply Role-Based Access Control (RBAC)
- Enable Rate Limiting
- Restrict Sensitive Data Fields
- Validate Input Parameters

Business Impact

This project demonstrates the ability to:
- Identify insecure API configurations
- Detect improper access control
- Analyze backend data exposure risks
- Recommend industry-standard security practices

---

## Author

Rishikesh Borse  
Aspiring Cybersecurity Analyst  
Focused on SOC & Blue Team Operations
