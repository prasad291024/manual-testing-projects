# PHPtravels Manual Testing Suite

## Table of Contents
1. [Project Title](#project-title)  
2. [Description](#description)  
3. [Repository Structure](#repository-structure)  
4. [Test Artifacts](#test-artifacts)  
   - [Test Plan](#test-plan)  
   - [Test Cases & Bug Report](#test-cases--bug-report)  
5. [Test Scope](#test-scope)  
6. [Test Environment](#test-environment)  
7. [How to Use](#how-to-use)  
8. [Contributing](#contributing)  
9. [Contact & Support](#contact--support)  

---

## Project Title
**PHPtravels Manual Testing Suite**

---

## Description
PHPTRAVELS provides a comprehensive, user-friendly platform for online travel businesses—covering hotel bookings, flight reservations, and custom web services. With over four years of industry experience, PHPtravels is renowned for reliable, scalable solutions and exceptional 24/5 support, ensuring customer satisfaction and lasting partnerships.

---

## Repository Structure
```
/
├─ docs/
│  ├─ PHPtravels_Test_Plan.docx
│  └─ PHPtravels_Test_Cases_And_Bug_Report.xlsx
└─ README.md
```
- **docs/PHPtravels_Test_Plan.docx**: High-level strategy, objectives, resources, and schedule for testing.  
- **docs/PHPtravels_Test_Cases_And_Bug_Report.xlsx**:  
  - **Sheet “Test Cases”**: Detailed test scenarios, steps, expected vs. actual results.  
  - **Sheet “Bug Report”**: Logged defects with severity, steps to reproduce, status.  

---

## Test Artifacts

### Test Plan
The Test Plan outlines the scope, objectives, approach, and resources for validating PHPtravels before launch. It covers test deliverables, entry/exit criteria, risk assessment, and schedule.

### Test Cases & Bug Report
All manual test cases are documented in the Excel workbook, with clear steps for executing each test and recording outcomes. The accompanying Bug Report sheet captures any defects found during execution, following standard QA templates for consistency.

---

## Test Scope
The following key features are covered by this suite:
- **Customer Login**  
- **Customer Profile Management**  
- **Flight Booking Process**  
- **Customer Logout**

These functionalities represent the core user journeys and will be verified across supported browsers and devices.

---

## Test Environment
- **Application URL**: https://phptravels.net/login  
- **Credentials**:  
  - Email: `user@phptravels.com`  
  - Password: `demouser`  
- **Tools Used**: Microsoft Word (for Test Plan), Microsoft Excel (for Test Cases & Bug Report), JIRA for defect tracking, and Confluence for collaboration.

---

## How to Use
1. **Clone or download** this repository to your local machine.  
2. **Open** the `docs/PHPtravels_Test_Plan.docx` in Word to review the test strategy.  
3. **Launch** the `docs/PHPtravels_Test_Cases_And_Bug_Report.xlsx` in Excel and execute each test case under the “Test Cases” sheet.  
4. **Log defects** directly in the “Bug Report” sheet or in your organization’s issue tracker.  
5. **Update** this README or your test artifacts as needed—keeping documentation up-to-date is essential for effective collaboration.

---

## Contributing
Contributions, enhancements, or feedback are welcome! Please:
1. Fork this repository.  
2. Create a new branch (`git checkout -b feature/YourFeatureName`).  
3. Commit your changes (`git commit -m 'Add some feature'`).  
4. Push to the branch (`git push origin feature/YourFeatureName`).  
5. Open a Pull Request detailing your improvements.

---

Thank you for reviewing the PHPtravels Manual Testing Suite! Feel free to open issues or pull requests for any clarifications or enhancements.
