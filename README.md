

---

# 🚀 Python API Automation Framework

### Hybrid Custom API Automation Framework (Enterprise Ready)

A scalable, modular, and reusable **Hybrid API Automation Framework** built using **Python + PyTest**, designed for real-world enterprise automation projects.

---
## 📸 Framework Architecture

![API Automation Framework Structure](https://github.com/user-attachments/assets/3c7d5fe5-207a-42e7-84fe-f4d53354d987)

---

## 🏗️ Project Folder Structure

```
api_automation_framework/
│
├── tests/                          # Test Cases
│   ├── crud/
│   │   ├── test_create_booking.py
│   │   ├── test_update_booking.py
│   │   └── test_delete_booking.py
│
├── api/                            # API Layer
│   ├── api_client.py               # Reusable API request methods
│   ├── routes.py                   # All API endpoints
│
├── utils/                          # Utility Classes
│   ├── config.py
│   ├── logger.py
│   ├── data_reader.py              # CSV / Excel / JSON reader
│
├── test_data/                      # Test Data Files
│   ├── booking.json
│   ├── booking.csv
│   └── booking.xlsx
│
├── schemas/                        # JSON Schema Validation
│   └── booking_schema.json
│
├── reports/                        # Generated Reports
│
├── conftest.py                     # PyTest Fixtures
├── requirements.txt
└── README.md
```

---

## 🛠️ Tech Stack

* **Python 3.12**
* **PyTest** – Testing Framework
* **Requests** – API Handling
* **Allure Report** – Advanced Reporting
* **PyTest HTML** – HTML Reporting
* **Faker** – Dynamic Test Data
* **jsonschema** – API Schema Validation
* **pytest-xdist** – Parallel Execution
* **Test Data Support** – CSV, Excel, JSON

---

## 📦 Installation Guide

### 1️⃣ Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 2️⃣ Install Required Packages

```bash
pip install requests pytest pytest-html faker allure-pytest jsonschema pytest-xdist
```

OR create `requirements.txt` and run:

```bash
pip install -r requirements.txt
```

---

## ▶️ Test Execution Commands

---

### ✅ Run Basic Test

```bash
pytest tests/crud/test_create_booking.py -s
```

---

### 📊 Run Test with Allure Report

```bash
pytest tests/crud/test_create_booking.py --alluredir=allure_results -s
```

Generate Allure Report:

```bash
allure serve allure_results
```

---

### 🧾 Run Test with HTML Report

```bash
pytest tests/crud/test_create_booking.py --html=report.html -s
```

---

### 📊🧾 Run with Both Allure + HTML Report

```bash
pytest tests/crud/test_create_booking.py --alluredir=allure_results --html=report.html -s
```

---

### ⚡ Run Tests in Parallel

```bash
pytest -n 4
```

Example with Reports + Parallel Execution:

```bash
pytest tests/ --alluredir=allure_results --html=report.html -n 4 -s
```

---

## 🔎 Framework Features

✔ Hybrid Architecture (Modular + Data Driven)
✔ Reusable API Client
✔ Centralized Route Management
✔ Schema Validation using jsonschema
✔ Data-Driven Testing (CSV / Excel / JSON)
✔ Parallel Execution using pytest-xdist
✔ Allure Advanced Reporting
✔ PyTest HTML Reporting
✔ Logging Support
✔ Scalable & Maintainable Structure

---

## 🧪 Advanced Capabilities

* Dynamic Test Data Generation using Faker
* JSON Schema Validation for response verification
* Centralized configuration management
* Easy integration with CI/CD tools
* Supports large-scale API regression suites

---

## 🎯 Why Hybrid Framework?

Because it combines:

* Modular API design
* Data-driven testing approach
* Schema validation
* Reporting integration
* Parallel execution

Making it **enterprise-grade and production-ready**.

---

## 🎤 2-Minute Interview Explanation

> I developed a Hybrid API Automation Framework using Python and PyTest.
> The framework follows a modular architecture with reusable API client methods and centralized route management.
> It supports data-driven testing using CSV, Excel, and JSON files.
> For validation, it includes JSON schema validation and assertion handling.
> It supports parallel execution using pytest-xdist and provides reporting through Allure and PyTest HTML.
> The framework is scalable, maintainable, and suitable for enterprise-level API automation projects.

---

If you want next level improvement, I can:

* Add sample `api_client.py` code
* Add `conftest.py` example
* Add logging implementation
* Add CI/CD (GitHub Actions / Jenkins pipeline)
* Convert this into Product-Based Company level framework

Tell me the level you want next 🚀
