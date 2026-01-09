# 🧪 Selenium Automation Test Case — Professional QA Tester Demo Project

## 👀 Overview:

A **production-oriented Selenium automation framework** built with **Python**, **Pytest**, and **Page Object Model (POM)** architecture. Complete UI automation suite built to validate the **Onsite Experiment / Inspector Popup Component** integrated into an e-commerce product page. 

📌 The goal is to ensure:
  - Correct popup visibility behavior.
  - Accurate mapping between campaign data and Inspector panel details.
  - Responsive layout functionality across multiple viewports.
  - Early detection of UI regressions or rendering issues.
  - Realistic QA automation demo, clean architecture, and scalable test design.

This automation suite reflects real product behavior and identifies genuine defects without bypassing or manipulating test outcomes. The repository demonstrates how modern QA engineers structure **UI test automation**, manage **test data**, generate **reports**, and prepare projects for **CI/CD pipelines**.

---

## 👨‍💻 Engineering & QA Intent:

This work is intentionally structured to demonstrate:
  - Clean and scalable **Page Object Model (POM)** architecture.  
  - Data-driven testing using **JSON**.
  - Realistic UI waiting strategies (explicit waits).  
  - Responsible **logging, screenshot capturing, and reporting**.  
  - Production-grade practices required in modern QA Automation roles. 

During test execution, the suite successfully detected **multiple UI defects**, including:
  - Popup failing to render despite Inspector state changing. 
  - Duplicate DOM nodes for the popup container.  
  - Responsive view failures. 
  - Inconsistent visibility logic between pages.  

---

## 📂 Project Structure:

```
kul_tunc_selenium_test_case/
│
├── config/
│   ├── __init__.py
│   ├── settings.py
│   ├── env.py
│   └── privacy.py
│
├── tests/
│   ├── __init__.py
│   ├── test_popup.py
│   ├── test_inspectorVdetails.py
│   ├── test_responsiveness.py
│   └── conftest.py
│
├── pages/
│   ├── __init__.py
│   ├── page_products.py
│   ├── page_home.py
│   ├── inspector.py
│   ├── page_login.py
│   └── page_base.py
│
├── utilities/
│   ├── __init__.py
│   ├── driver_factory.py
│   ├── helpers.py
│   ├── waiter.py
│   └── logger.py
│
├── data/
│   └── test_data.json
│
├── screenshots/
├── reports/
├── venv/
├── logs/
├── Dockerfile
├── requirements.txt
└── pytest.ini
```
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-WebDriver-green?logo=selenium&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-Automation-orange?logo=pytest&logoColor=white)
![Testing](https://img.shields.io/badge/Testing-UI%20Automation-informational)
![Allure](https://img.shields.io/badge/Allure-Report-yellowgreen?logo=allure)
![Stability](https://img.shields.io/badge/Stability-Explicit%20Waits-brightgreen)
![Docker](https://img.shields.io/badge/Dockerized-Test%20Runner-blue?logo=docker)
![QA Engineer](https://img.shields.io/badge/Role-QA%20Automation%20Engineer-purple)
![Architecture](https://img.shields.io/badge/Design-Page%20Object%20Model-blueviolet)
![CI Ready](https://img.shields.io/badge/CI/CD-GitHub%20Actions-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## ⚙️ Tech Stack:

| Technology | Purpose |
|----------|--------|
| **Python 3.10+** | Core language |
| **Selenium** | Browser automation |
| **Pytest** | Test runner |
| **JSON** | Test data |
| **ChromeDriver** | Browser driver |
| **GitHub** | Version control |

---

## 🌐 Setup & Execution:

### Clone the repository
```
git clone https://github.com/tnctungkl/full_selenium_testCase.git
[clone on my GitHub repository (only use for education&learning)]
```

### Create virtual environment
```
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### Install dependencies
```
pip install -r requirements.txt
```

### Run with Allure
```
pytest --alluredir=allure-results
allure serve allure-results
```

### Run tests
```
pytest -v
```

---

## 📊 Reports & Test Results:

| Test | Result |
|------|--------|
| Home Page – Popup Hidden | PASS |
| Product Page – Popup Visible | FAIL (UI Defect) |
| Inspector Details | FAIL (UI Defect) |
| Responsiveness Test | FAIL (UI Defect) |

  -> Test outputs are generated locally, Reports directory is intentionally gitignored

Designed for easy integration with:
  - Allure
  - CI pipelines
  - HTML / XML reporting

---

## 🧠 Essential Key Features:

- Page Object Model (POM)
- JSON-driven test data
- Reusable components and selectors
- Explicit waits & stability-focused design
- Popup visibility & behavior validation
- Responsive UI testing (multiple viewports)
- Dynamic content handling
- Timeout & edge-case awareness
- Automatic failure screenshots
- Allure reporting integration
- Configurable environment settings
- WebDriver factory abstraction
- Explicit wait abstraction layer
- Clean code, documented, scalable
- Selenium WebDriver
- Python
- Pytest
   
---

## 🧩 Edge Cases Considered:

 - Dynamic DOM loading delays
 - Responsive layout changes
 - Element visibility vs presence
 - Timeout handling for unstable UI states
 - GitHub Actions
 - Dockerized test execution
 - Headless browser support
 - Scheduled regression tests

---

## 🔒 Security Notes {⚠️Important Notes}:
If you plan to be inspired this project in the future, don't forget these things;
 - No credentials are hardcoded, credentials come only from .env.
 - URLs and environments are configurable.
 - Anonymize before sharing publicly.
 - Reports & runtime artifacts are excluded from version control.
 - Project is safe for public GitHub repositories.

---

## 📜 Conclusion:

- Solid automation engineering foundations  
- Realistic approach to defect identification  
- Professional coding practices  
- Strong awareness of test architecture  
- Ability to communicate defects clearly

---

## 📨 Contact:

GitHub: github.com/tnctungkl  
LinkedIn: linkedin.com/in/tnckl1n

---

## 👑 Author:  
                **Tunç KUL**  
            **Computer Engineer** 
