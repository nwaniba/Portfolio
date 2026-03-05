# Samuel Omokhafe Dania | QA Engineer
**Manual & Automation Testing | API Validation | Cypress & JavaScript**

[LinkedIn](https://linkedin.com/in/samueldania) | [GitHub](https://github.com/nwaniba) | [Email](mailto:daniaomokhafe1@gmail.com)

---

## 🚀 Professional Summary
Result-oriented Software Tester with experience validating enterprise-grade web applications. I specialize in identifying critical edge cases and ensuring system stability through modern testing strategies, including manual testing and automated regression suites using **Cypress**.

---

## 🛠 Technical Stack
| Category | Tools & Technologies |
| :--- | :--- |
| **Automation** | Cypress, JavaScript/TypeScript, Selenium |
| **API Testing** | Postman, REST API Validation |
| **Manual QA** | Test Case Design, Regression Testing, Exploratory Testing |
| **Management** | Jira, GitHub, Agile/Scrum, SQL (Basic) |

---

## 📂 Featured QA Projects

### 🚢 Dry Dock Job Management System
*Functional & Regression Testing of maritime maintenance workflows.*
* **Scope:** Validated job scheduling, project grouping, and real-time status updates.
* **[View Test Cases](./docs/DryDock_TestCases.md)**

### 🔍 Inspection Module Testing
*Validation of high-stakes data entry and UI integrity.*
* **Key Bug Found:** Identified character limit bypass (Severity: Medium).
* **[View Bug Report](./docs/Sample_Bug_Report.md)**

### 🔌 API Testing (Postman)
*End-to-end validation of authentication and error handling.*
* **[View Postman Collection](./docs/API_Testing.json)**

---

## 💻 Automation Snippet (Cypress)
*Modern, clean, and readable automation logic.*

```javascript
describe('User Login Flow', () => {
  it('should successfully log in with valid credentials', () => {
    cy.visit('/login');
    cy.get('#username').type('test_user');
    cy.get('#password').type('securePassword123');
    cy.get('#login-btn').click();
    
    // Assert dashboard load
    cy.url().should('include', '/dashboard');
    cy.get('.welcome-message').should('be.visible');
  });
});
