# 🔐 Web Application Security Testing


![Security](https://img.shields.io/badge/Cybersecurity-Vulnerability%20Assessment-red?style=for-the-badge)
![OWASP](https://img.shields.io/badge/OWASP-Top%2010-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)
![Tools](https://img.shields.io/badge/Tools-OWASP%20ZAP%20%7C%20Burp%20Suite-blue?style=for-the-badge)

---

## 📌 Project Overview

This project demonstrates a **Web Application Vulnerability Assessment** performed on intentionally vulnerable web applications.

The objective is to simulate a **real-world penetration testing engagement**, where security flaws are discovered, analyzed, and documented using ethical hacking tools.

The assessment follows industry standards such as the **OWASP Top 10 Web Application Security Risks**.

Through this project, multiple vulnerabilities were identified and analyzed, along with their potential impact and recommended remediation steps.

---

## 🎯 Objectives

✔ Perform vulnerability scanning on a web application
✔ Identify common security weaknesses
✔ Map vulnerabilities to **OWASP Top 10** categories
✔ Analyze impact and risk levels
✔ Document findings in a **professional security report**

---

## 🛠 Tools Used

| Tool                                | Purpose                          |
| ----------------------------------- | -------------------------------- |
| 🔍 **OWASP ZAP**                    | Automated vulnerability scanning |
| 🛠 **Burp Suite Community Edition** | Manual testing and interception  |
| 🧪 **DVWA / OWASP Juice Shop**      | Vulnerable testing applications  |
| 💻 **Kali Linux (Optional)**        | Security testing environment     |
| 📄 **MS Word / Google Docs**        | Security report creation         |

---

## 🧪 Vulnerabilities Tested

This assessment focuses on security issues listed in the **OWASP Top 10**.

| Vulnerability                     | Severity  | OWASP Category                      |
| --------------------------------- | --------- | ----------------------------------- |
| SQL Injection                     | 🔴 High   | A03: Injection                      |
| Cross-Site Scripting (XSS)        | 🟠 Medium | A07: Identification & Auth Failures |
| Cross-Site Request Forgery (CSRF) | 🟠 Medium | A08: Software Integrity Failures    |
| Security Misconfiguration         | 🟡 Low    | A05: Security Misconfiguration      |

Reference:
OWASP Top 10 → https://owasp.org/www-project-top-ten/

---

## 🔎 Testing Methodology

The security testing process followed a structured workflow.

### 1️⃣ Reconnaissance

Exploring the application to understand pages, inputs, and request flows.

### 2️⃣ Automated Scanning

Running vulnerability scanners such as **OWASP ZAP** to detect potential weaknesses.

### 3️⃣ Manual Testing

Using **Burp Suite** to intercept requests and manually test attack vectors.

### 4️⃣ Vulnerability Validation

Confirming identified issues to eliminate false positives.

### 5️⃣ Documentation

Recording each vulnerability with:

• Screenshots
• Attack steps
• Severity rating
• OWASP mapping
• Remediation guidance

---

## 📂 Repository Structure

```
web-vulnerability-assessment
│
├── screenshots
│
├── reports
│   └── security-assessment-report.pdf
│
├── scan-results
│   └── zap-report.html
│
└── README.md
```

---

## 📊 Deliverables

📄 **Security Assessment Report (PDF)**
Includes detailed vulnerability analysis and remediation steps.

📊 **Scanner Logs**
OWASP ZAP scan reports and tool outputs.

📸 **Screenshots**
Proof-of-concept exploitation and vulnerability evidence.

---

## 🧠 Skills Demonstrated

🔓 Web Application Security Testing
🛡 Vulnerability Assessment
⚔ Ethical Hacking Techniques
📊 Risk Analysis and Threat Modeling
📄 Security Documentation & Reporting

---

## 📚 Learning Outcome

This project provided practical exposure to how **attackers identify vulnerabilities in web applications** and how security professionals analyze and mitigate those risks.

It also helped develop skills in **security analysis, penetration testing methodology, and professional security reporting**.

---

## ⚠️ Disclaimer

This project was conducted **only on intentionally vulnerable applications in a controlled environment**.

No real systems or unauthorized targets were tested.

---

## 📖 References

OWASP Top 10
https://owasp.org/www-project-top-ten/

OWASP Juice Shop
https://owasp.org/www-project-juice-shop/

DVWA
https://github.com/digininja/DVWA

Burp Suite Documentation
https://portswigger.net/burp/documentation

OWASP ZAP Documentation
https://www.zaproxy.org/docs/

---

## 👨‍💻 Author

**Benny Hinn**

Cybersecurity Enthusiast | Engineering Student
Interested in Ethical Hacking, Web Security, and Threat Analysis.
