# Samuel Omokhafe Dania | QA Engineer
**Manual & Automation Testing | API Validation | Cypress & JavaScript**

[LinkedIn](https://linkedin.com/in/samueldania) | [GitHub](https://github.com/nwaniba) | [Email](mailto:daniaomokhafe1@gmail.com)

---

## 🚀 Professional Summary
Detail-oriented Software Tester with experience validating enterprise-grade web applications, including **Dry Dock Management** and **Inspection Systems**. I specialize in identifying critical edge cases and ensuring system stability through modern E2E frameworks like **Cypress**.

---

## 🛠 Technical Stack
| Category | Tools & Technologies |
| :--- | :--- |
| **Automation** | Cypress, JavaScript, Mocha/Chai |
| **API Testing** | Postman, REST API Validation |
| **Manual QA** | Test Case Design, Regression Testing, SDLC/STLC |
| **Tools** | Jira, GitHub, SQL (Basic) |

---

## 📂 Featured QA Projects

### 🚢 Dry Dock Job Management System
*Functional & Regression Testing of maritime maintenance workflows.*
* **Scope:** Validated job scheduling, project grouping, and real-time status updates.
* **[View Test Cases](./docs/Test_Cases.md)**

### 🔍 Inspection Module Testing
*Validation of high-stakes data entry and UI integrity.*
* **Key Finding:** Identified a character limit bypass in the Observation Field (Severity: Medium).
* **[View Bug Report](./docs/Sample_Bug_Report.md)**

---

## 💻 Automation Snippet (Cypress)
```javascript
describe('Login Flow', () => {
  it('successfully logs in with valid credentials', () => {
    cy.visit('/login');
    cy.get('#user-email').type('tester@example.com');
    cy.get('#user-password').type('password123');
    cy.get('#login-button').click();
    cy.url().should('include', '/dashboard');
  });
});
