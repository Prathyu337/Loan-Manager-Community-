# Loan Manager (Community)

This project is a full-stack web application that allows users to submit loan applications and view dynamic statistics on a dashboard. It is built with:

- **Backend**: Node.js, Express.js, PostgreSQL
- **Frontend**: React.js

## 📦 Features

- Submit loan applications through a form.
- Store application data in a PostgreSQL database.
- Display real-time statistics on the dashboard:
  - Total applications
  - Average loan amount
  - Success rate (based on approved applications)

## 🛠 Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js + Express.js
- **Database**: PostgreSQL

## 🗂 Project Structure

loan-manager/
├── backend/
│ ├── config/ # Database configuration
│ ├── controllers/ # (Optional) Controller logic
│ ├── models/ # DB query functions
│ ├── routes/ # Express routes
│ └── app.js # Entry point for backend server
├── frontend/
│ └── src/
│ ├── components/ # React components
│ ├── App.js
│ └── index.js
└── README.md


---

## 🚀 Getting Started

### 📋 Prerequisites

- Node.js installed
- PostgreSQL installed and running

### 🧑‍💻 Backend Setup

1. Go to the backend directory:

   ```bash
   cd backend
Install dependencies:
npm install
