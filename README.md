# FinSync: Your All-in-One Financial Management Platform

**FinSync** is a modern, user-centric financial management system designed to simplify personal and business finance. Built with Agile methodologies, FinSync offers secure authentication, multi-currency dashboards, transaction tracking, tax/credit/loan management, and customizable reporting. With 74 user stories across 18 functional areas, FinSync empowers users to track income, manage loans, and generate insights—all in one intuitive platform.

---

## 🚀 Features

### 🔐 Secure Authentication
- **User Registration**: Validate email, password, phone, and ensure users are 18+ (Stories 1.1–1.4).
- **Email Verification**: 6-digit OTPs with 10-minute expiration (Stories 2.1–2.4).
- **Login System**: Hashed passwords and unverified user redirection (Stories 3.1–3.4).

### 👤 Profile Management
- **Personal Information**: View/edit name, date of birth, gender, and masked CNIC (Stories 4.1–4.4).
- **Contact & Address**: Update email, phone, country, city, and zip code with validation (Stories 5.1–6.4).
- **Financial Details**: Manage occupation and income (Stories 7.1–7.4).
- **Account Info**: Track account status, last login, and membership start date (Stories 8.1–8.4).

### 🎨 Personalized UI/UX
- **Theme Switching**: Light/dark/multiple modes with session persistence (Stories 9.1–9.2).
- **Interactive Dashboard**: Income, expenses, net flow, top categories, recent transactions in multiple currencies (Stories 10.1–10.5).

### 💰 Core Financial Operations
- **Account Management**: Add, view, refresh, and select accounts (Stories 12.1–12.4).
- **Transactions**: List, filter, search, and share details with category/date sorting (Stories 13.1–14.3).
- **General Operations**: Deposit, send, or request money with transaction history (Stories 11.1–11.4).

### 📈 Advanced Modules
- **Tax Management**: Track obligations, estimate taxes, pay, and monitor deductions (Stories 15.1–15.4).
- **Credit Management**: View credit scores, reports, tips, and utilization (Stories 16.1–16.4).
- **Loan Management**: Apply, review, pay, and project loan payoffs (Stories 17.1–17.4).
- **Reporting**: Custom/scheduled/exportable reports (PDF/CSV) inspired by Power BI (Stories 18.1–18.5).

---

## 🌟 Key Highlights

- **Multi-Currency Support**: Manage finances across currencies.
- **Regulatory Compliance**: Secure and tax-ready.
- **Real-Time Analytics**: Data-driven financial insights.

---

## 🛠 Tech Stack

- **Frontend**: WPF for responsive UI.
- **Backend**: Secure RESTful APIs for authentication, transactions, and reporting.
- **Database**: Relational schema for users, accounts, and financial data.
- **Security**: Hashed passwords, OTPs, SMTP email services.
- **DevOps**: CI/CD, automated testing, Git version control.
- **Tools**: Trello, burndown charts, Power BI-inspired reporting.

---

## 📅 Project Development

- **Duration**: 79 days
- **Methodology**: Scrum (4 iterations)
- **Workflow**:
  - Agile sprints prioritized 74 user stories
  - Features validated via UX workshops
  - Automated and boundary testing ensured reliability

---

## 📦 Installation

### Prerequisites
- .NET Framework (for WPF)
- SQL Server or compatible database
- Git
- SMTP service (e.g., Gmail, SendGrid)

### Steps

```bash
# Clone the Repository
git clone https://github.com/your-username/finsync.git
cd finsync

# Set Up Database
# Run SQL scripts in /database
# Update appsettings.json with connection strings

# Configure SMTP
# Add credentials in backend config

# Build and Run
dotnet build
dotnet run
```

- **Access**: Open via browser (http://localhost:5000) or WPF executable.

---

## 🧭 Usage

### Register
- Enter email, password, phone.
- Verify with 6-digit OTP.

### Log In
- Use username/email and password.

### Explore
- Customize themes.
- Monitor dashboards, manage accounts/transactions, and use tax/credit/loan features.

### Reports
- Generate/export custom or scheduled reports.

> See `/docs` for detailed guides.

---

## 🏗 Architecture

- **Frontend**: WPF-based responsive UI.
- **Backend**: RESTful APIs for core functionality.
- **Database**: Relational storage for users, accounts, and transactions.
- **Security**: Hashed passwords, OTPs, data masking.
- **Diagrams**: Activity, use case, class, and sequence diagrams in `/diagrams`.

---

## 📊 Project Insights

### Lessons Learned
- **Agile**: Sprints and reviews ensured alignment.
- **Communication**: Standups and Trello kept sync.
- **UX Design**: Early validation improved usability.
- **Security**: Early focus saved effort.
- **Testing**: Caught edge cases early.

### Metrics
- **Timeline**: 79 days, 4 iterations.
- **User Stories**: 74 completed.
- **KPIs**:
  - Registration: <2 min
  - Dashboard load: <1 sec
  - Transactions: 1000+/hr

---

## 🤝 Contributing

```bash
# Fork
git fork https://github.com/your-username/finsync.git

# Branch
git checkout -b feature/your-feature

# Commit
git commit -m "Add your feature"

# Push & PR
git push origin feature/your-feature
```

- **Guidelines**:
  - Follow `/docs/CONTRIBUTING.md`
  - Include tests and update docs

---

## 📄 License

MIT License

---

## 📬 Contact

**Email**: [azibnaeem17official@gmail.com](mailto:azibnaeem17official@gmail.com)

---

## 🙏 Acknowledgments

- **Tools**: Trello, WPF, SQL Server, Git.
- **Inspiration**: Mint, QuickBooks.

---

**FinSync — Simplify finances, amplify your future!**
