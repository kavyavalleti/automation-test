Prepared by: **Kavya Sree Valleti**

---

## 📋 Overview

This repository contains both **manual and automation testing deliverables** for the OrangeHRM web application as part of the QA Intern Assignment 2025.

- Website under test: [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/)
- Tools: `Python`, `Selenium`, `Pytest`, `POM Design Pattern`

---

## 📌 Project Contents

### ✅ Manual Testing (Excel Sheets in `manual-testing/`)
- Login Functionality Test Cases
- Employee Management (Add, View, Edit, Delete) Test Cases
- Bug Report (3 UI/UX issues identified)

### 🤖 Automation Testing
- **Automated Workflow**:
  - Login with valid credentials
  - Navigate to PIM
  - Add 4 employees
  - Verify names in Employee List
  - Logout

### 📁 Folder Structure

```
pages/       - POM classes for Login, Dashboard, PIM
tests/       - Automation test script
manual-testing/ - Test cases + bug report (Excel)
assets/      - Screenshots or Loom link (optional)
```

---

## 🚀 How to Run the Automation Script

1. Install Python and dependencies:
   ```bash
   pip install selenium pytest
   ```

2. Run the test:
   ```bash
   pytest tests/test_orangehrm_workflow.py
   ```

3. Update `ChromeDriver` if needed

---

---

## 📌 Author

**Kavya Sree Valleti**  
📅 Submission: QA Intern Assignment 2025
