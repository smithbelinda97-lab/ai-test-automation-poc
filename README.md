# 🤖 AI Test Automation Proof of Concept (PoC)

### Evaluating AI-Assisted Automation Using Selenium, Python and Prompt Engineering
![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AI](https://img.shields.io/badge/AI-Test_Automation-blueviolet?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt-Engineering-success?style=for-the-badge)
![Selenium](https://img.shields.io/badge/Selenium-Automation-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-Evaluated-orange?style=for-the-badge)
## Objective

This project demonstrates a Proof of Concept (PoC) for AI-assisted test automation using:

- AI-generated manual test cases
- JSON-based locator mapping
- Selenium with Python
- Reusable helper framework
- Screenshot capture
- Word execution reporting

The goal is to reduce repetitive automation scripting effort and improve maintainability using reusable automation assets.

---

# Framework Architecture

ai-test-automation-poc
│
├── drivers/
│   └── chromedriver.exe
│
├── helpers/
│   ├── locator_helper.py
│   ├── screenshot_helper.py
│   └── report_helper.py
│
├── locators/
│   └── locators.json
│
├── tests/
│   └── test_login_logout.py
│
├── test_cases/
│   └── SauceDemo_Login_Logout_TestCase.xlsx
│
├── screenshots/
│
├── reports/
│
├── requirements.txt
│
└── README.md

---

# Technologies Used

* Python
* Selenium WebDriver
* PyTest
* python-docx
* JSON locator mapping

---
## Evaluation Methodology

The generated automation assets were evaluated using the following criteria:

- Code correctness
- Framework compatibility
- Reusability
- Maintainability
- Prompt quality
- Manual effort required

---

# AI-Assisted Development Workflow in This PoC

## AI-assisted activities:

* Manual test case generation
* Selenium Python script generation
* Reusable automation framework generation
* Locator abstraction design

## Human-assisted activities:

* Initial locator identification
* Framework setup
* Execution validation

---

# Features

* Reusable locator mapping
* Helper-based automation framework
* Screenshot capture after key actions
* Word execution report generation
* Structured framework design
* AI-friendly automation architecture

---

# Sample Flow Automated

SauceDemo Login and Logout Flow:

1. Launch application
2. Enter username
3. Enter password
4. Click login
5. Validate successful login
6. Open menu
7. Click logout
8. Validate logout

---

# Results

| Area | Result |
|-------|--------|
| Test Case Generation | Successful |
| Selenium Script Generation | Successful |
| JSON Locator Mapping | Successful |
| Screenshot Capture | Successful |
| Word Reporting | Successful |
| Manual Validation Required | Yes |

---

# Installation

## Clone Repository

```bash
git clone https://github.com/smithbelinda97-lab/ai-test-automation-poc.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Execution

Navigate to the tests folder:

```bash
cd tests
```

Run the automation script:

```bash
python test_login_logout.py
```

---

# Execution Output

After successful execution:

## Screenshots

Saved inside:

```text
screenshots/
```

## Word Execution Report

Saved inside:

```text
reports/
```

---

# Future Enhancements

* Dynamic test case execution
* AI-based locator generation
* Self-healing locators
* HTML reporting
* CI/CD integration
* PyTest framework integration
* Multi-browser execution

---

# Challenges

- AI occasionally generated incorrect locator strategies.
- Generated scripts required refinement for framework integration.
- Prompt specificity significantly influenced output quality.
- Manual validation remained essential before execution.

---

# Limitations

- AI cannot fully replace human validation.
- Generated scripts may require framework customization.
- Locator maintenance still depends on application changes.
- Complex business workflows require tester expertise.

---


# Disclaimer

This project uses SauceDemo as a public demo application for learning and demonstration purposes only.

No confidential or proprietary application data is included.

---

# Author

Belinda Smith
