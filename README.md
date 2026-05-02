# Gregory Olsen Photo Studio - QA Testing Project

## 1. Project Overview
This repository showcases a comprehensive functional and GUI testing suite conducted for the **Gregory Olsen Photo Studio** web application. The project serves as a professional demonstration of end-to-end quality assurance, focusing on defect identification, rigorous documentation and technical system validation.

**Target Website:** [http://80.249.129.99:58363/](http://80.249.129.99:58363/)

---

## 2. Testing Scope & Methodology
The testing process followed a structured lifecycle, utilizing professional industry tools to simulate real-world QA environments.

*   **Functional Testing:** Validated core session booking flows, payment gateway integration and the accuracy of complex pricing logic across multiple service tiers.
*   **GUI Testing:** Assessed visual layout, typography, and responsiveness across Google Chrome and mobile viewports.
*   **Defect Tracking:** Managed the full bug lifecycle using **JIRA**, from initial discovery to technical reporting.

---

## 3. Repository Structure
The following artifacts are included in this repository to provide evidence of the testing process:

*   **`Requirements.pdf`**: The technical and functional specifications that served as the basis for all test.
*   **`Acceptance Sheet.xlsx`**: Log of test execution including build information and environment configuration.
*   **`GregOlsen.PhotoStudio (JIRA Bug Tickets).pdf`**: Comprehensive reports of all logged defects, including steps to reproduce and severity levels.
*   **`Test-Survey.xlsx`**: Contains the core testing plan and the final results specific to the Lifestyle Gallery module.


---

## 4. Key Bug Highlights
During the testing phase, several critical and major issues were identified and documented:

| Bug ID | Description | Severity |
| :--- | :--- | :--- |
| **QATC-981002** | Payment redirect fails with a 404 error during checkout. | Critical |
| **QATC-980981** | Incorrect price calculation when adding extra subjects to a session. | Major |
| **QATC-981047** | Navigation buttons incorrectly display in Russian language. | GUI/Minor |

---

## 5. Tools Used
*   **Project Management:** JIRA
*   **Documentation:** Microsoft Excel
*   **Environment:** Windows 11 pro, Google Chrome
