# Automated-Testcase Generator

## Project Overview
This project automates the generation of software test cases from a given set of requirements. It parses requirement statements, classifies them as **Functional**, **UI**, or **Other** tests, and generates detailed test steps with expected results. The output is exported as an Excel file ready for use in software testing and CI/CD pipelines.

---

## Problem Statement
Manual test case generation is a time-consuming and error-prone process in software development. Test engineers spend hours interpreting requirements and writing test cases, which can lead to delays, inconsistent coverage, and reduced software quality. Automating this process improves efficiency, ensures consistency, and prepares the organization for scalable testing.

---

## Proposed Solution
This project uses a **rule-based Python script** to:
- Parse software requirements from a text file.
- Classify each requirement into **Functional**, **UI**, or **Other** test types.
- Generate **detailed, actionable test steps** for each requirement.
- Export all test cases into an **Excel file** (`enhanced_test_cases.xlsx`) for easy reference.

Future enhancements could include integration with **Selenium** or **ML-based predictive testing** for fully automated testing in real-world projects.

---

## Features
- Parses requirements from a `.txt` file or directly defined in code.
- Generates unique **Test Case IDs**.
- Classifies test type automatically based on keywords.
- Provides **detailed test steps** for each requirement.
- Exports results to an **Excel file** for practical use.
- Easy to extend for Selenium or AI-based automation.

---

## Tools and Libraries
- **Python 3.x**
- **Pandas** – for data manipulation
- **OpenPyXL** – for Excel file export
- **Google Colab** – optional, for online execution without installation

---

## How to Use
1. **Upload your requirements** file (`requirements.txt`) or define them directly in the Python script.
2. **Run the Python script** (`enhanced_test_case_generator.ipynb`) in Google Colab or a local Python environment.
3. **Download the generated Excel file** `enhanced_test_cases.xlsx`.
4. Review the test cases for your software project.

---

## Sample Output
| ID     | Requirement                                      | Test Type       | Test Steps                                        | Expected Result                    |
|--------|-------------------------------------------------|----------------|-------------------------------------------------|----------------------------------|
| TC_001 | The system should allow the user to register...| Functional Test | 1. Navigate to relevant page. 2. Perform action: the system should allow the user to register with email and password. 3. Verify expected result. | Requirement is fulfilled correctly |
| TC_002 | Users must be able to log in using credentials | Functional Test | 1. Navigate to relevant page. 2. Perform action: users must be able to log in using their credentials. 3. Verify expected result. | Requirement is fulfilled correctly |

---

## Future Enhancements
- Integrate with **Selenium** for automated execution of test steps.
- Use **machine learning** for advanced test case prediction and prioritization.
- Add **priority and severity classification** for each test case.

---

## Author
**Baruri Ashrith Sharma**  
- Email: ashrithbaruri@gmail.com  
- Location: Karlskrona, Sweden  
- GitHub: [Your GitHub Profile Link]

---

