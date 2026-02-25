🚀 Selenium Data-Driven Login Automation Framework

A robust Data-Driven Test Automation Framework built using Selenium WebDriver, Pytest, Allure Reporting, and OpenPyXL.

This framework automates login validation for the SauceDemo website by executing multiple test cases dynamically from an Excel file.

🔗 Test Website: https://www.saucedemo.com

📌 Overview

This project demonstrates:

✅ Data-driven testing using Excel (.xlsx)

✅ Pytest parameterization

✅ Selenium WebDriver automation

✅ Allure report integration

✅ Scalable test structure using fixtures

It is designed for learning and demonstrating automation framework concepts suitable for entry-level QA and SDET roles.

🏗 Project Architecture
project-root/
│
├── test_login.py
├── test_data.xlsx
├── allure-results/
├── README.md
⚙️ Tech Stack
Technology	Purpose
Python	Programming Language
Selenium	Browser Automation
Pytest	Test Execution Framework
Allure	Test Reporting
OpenPyXL	Excel Data Handling
✨ Features

Parameterized login test cases

Excel-based test data management

Automatic browser setup & teardown using fixtures

Assertion validation for login success

Allure-compatible test result generation

Easy to extend into Page Object Model (POM)

🛠 Installation Guide
1️⃣ Clone Repository
git clone <your-repo-link>
cd project-folder
2️⃣ Create Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux
3️⃣ Install Dependencies
pip install -r requirements.txt

If requirements.txt is not available:

pip install selenium pytest allure-pytest openpyxl
4️⃣ Install Allure CLI

Download from:
https://docs.qameta.io/allure/

Verify installation:

allure --version
▶️ Test Execution
Run Tests
pytest -v
Run with Allure Reporting
pytest --alluredir=allure-results
allure serve allure-results
📊 Test Flow

Excel file is loaded

Test data is extracted row by row

Pytest parameterizes test cases

Browser launches

Login performed

Assertion validates login success

Browser closes

Report generated

📷 Sample Output

You can add:

Screenshot of browser execution

Screenshot of Allure dashboard

GIF demo of test run

Example:

docs/
   ├── execution.png
   ├── allure_report.png
🧪 Example Test Logic

The test verifies successful login by asserting:

assert "inventory" in driver.current_url
🔒 Requirements

Python 3.8+

Google Chrome browser

Selenium 4+

Allure installed and added to PATH

🚧 Roadmap

Planned Enhancements:

🔹 Implement Page Object Model (POM)

🔹 Add Screenshot Capture on Failure

🔹 Integrate Logging

🔹 Add Cross-Browser Testing

🔹 CI/CD integration (GitHub Actions)

🔹 Docker execution support

🤝 Contributing

Contributions are welcome.

Steps:

Fork the repository

Create a new branch

Make changes

Run tests

Submit Pull Request

Run tests before committing:

pytest -v
👨‍💻 Author

Pranav S

GitHub: https://github.com/SPRANAV0

LinkedIn: https://www.linkedin.com/in/pranav-s-a34668296/

📜 License

This project is licensed under the MIT License.

📌 Project Status

🟢 Active – Learning & Enhancement Phase
