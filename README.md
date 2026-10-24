# Gold-Loan-Manager (GoldFlow)

A full-stack Gold Loan Management & Ledger System designed to streamline gold loan origination, user management, loan approval workflows, repayments, renewal requests, and administrative operations.

---

## 🌟 Features

- **User Management & KYC**: User registration, KYC verification, profile tracking, and role-based access.
- **Loan Management**: Creation, tracking, interest calculation, tenure management, and overdue checking.
- **Transactions & Ledger**: Payment tracking, transaction receipts, and full audit logs.
- **Admin Dashboard**: System metrics, pending user/loan approvals, loan renewal approvals, and financial analytics.
- **Real-time Notifications**: Alerts for due dates, transaction status, and administrative updates.
- **Modern UI**: Intuitive and responsive interface built with React, Vite, and Tailwind CSS.

---

## 🏗️ Architecture

```
Gold-Loan-Manager/
├── backend/            # Express.js & MongoDB API
│   ├── src/
│   │   ├── config/     # Database & app configuration
│   │   ├── controllers/# Route controllers
│   │   ├── middleware/ # Auth & error handling
│   │   ├── models/     # Mongoose models
│   │   ├── routes/     # API routes
│   │   └── utils/      # Utility helpers
│   ├── package.json
│   └── README.md
├── frontend/           # Vite, React, TypeScript & Tailwind CSS
│   ├── src/
│   │   ├── components/ # UI components (shadcn/ui)
│   │   ├── pages/      # Application views
│   │   ├── hooks/      # Custom React hooks
│   │   └── lib/        # Helper functions & state
│   ├── package.json
│   └── README.md
└── README.md
```

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Language**: TypeScript
- **Styling**: Tailwind CSS & shadcn/ui
- **Icons**: Lucide React

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT & bcryptjs
- **Security**: Helmet, CORS, Rate Limiting

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or later recommended)
- [MongoDB](https://www.mongodb.com/) (running locally or MongoDB Atlas)
- npm or bun

### 1. Clone the Repository
```bash
git clone https://github.com/KS-Adharshini/Gold-Loan-Manager.git
cd Gold-Loan-Manager
```

### 2. Backend Setup
```bash
cd backend
npm install
cp env.example .env
# Configure your MongoDB URI and JWT secrets in .env
npm run dev
```

### 3. Frontend Setup
```bash
cd ../frontend
npm install
npm run dev
```

---

## 📄 License
This project is licensed under the MIT License.
