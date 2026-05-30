# SafePay — Student Digital Wallet System

**SafePay** is a secure, intuitive student digital wallet system designed to help students track payments, manage daily/monthly spending, and monitor transactions seamlessly. Built using a modern frontend stack paired with a lightweight backend database configuration, SafePay offers robust financial tracking tailored for student lifestyles.

---

## 🚀 Key Features

* **Secure Payment Tracking:** Monitor income, transfers, and expenses in real-time.
* **Smart Spending Management:** Enforce customizable **daily and monthly spending limits** to encourage budgeting.
* **Transaction Monitoring:** Maintain a detailed, searchable log of all financial activities.
* **PIN Verification:** Secure account actions and sensitive operations with mandatory PIN confirmations.
* **Dual Deployment Environments:** Supports localized development scripts as well as static web deployment configurations.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+), [Vite](https://vite.dev/) (Build tool)
* **Backend & Automation:** Node.js, Express (Production server hosting), Batch scripting (`.bat`)
* **Database:** SQL-based transaction ledger management

---

## 📂 Project Structure

```text
SafePay/
├── .github/workflows/      # Automated GitHub Actions deployment pipeline
├── database/               # SQL schema definitions and database logic
│   └── (Contains budget limits, PIN enforcement features)
├── src/                    # Main application source code (JS, CSS, Assets)
├── index.html              # Core application entry point
├── server.js               # Node.js production static server configuration
├── vite.config.js          # Vite relative base path asset compilation
├── Start_SafePay.bat       # Local development launch script
└── Start_SafePay_Production.bat # Production environment test script
```

---

## 💻 Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Local Development

To run the wallet system locally with automated asset updates:

1. Double-click **`Start_SafePay.bat`** (or execute it via your terminal).
2. Open the provided local URL (typically `http://localhost:5173`) in your browser.

### Production Build & Preview

To run the application inside a simulated static hosting production server:

1. Double-click **`Start_SafePay_Production.bat`**.
2. This triggers `server.js` to serve compiled production files.

---

## 🛡️ Security & Limits Implementation

SafePay isn't just a basic ledger; it enforces structural rules to simulate a genuine banking ecosystem:

* **Budget Guardrails:** Validates transaction amounts against pre-set daily and monthly thresholds prior to processing.
* **State Verification:** Incorporates a rigorous `verify-pin` step to prevent unauthorized transaction execution.

---

## 👤 Developer Profile

* **Author:** bhanuatla521-svg
* **GitHub:** [@bhanuatla521-svg](https://github.com/bhanuatla521-svg)
* **Project Link:** [SafePay Repository](https://bhanuatla521-svg.github.io/SafePay/)

---

## 📄 License

This project is open-source and available for educational and student-budgeting tracking purposes.
