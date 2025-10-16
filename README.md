# PersonalFinTracker
# Personal Finance Tracker for Students (Desktop App)

### A simple and intuitive desktop app to help students manage their finances — track expenses, set budgets, and monitor savings goals.


## Overview
The **Personal Finance Tracker for Students** is a desktop application designed to help students develop better money management habits.  
It allows users to:
- Track daily expenses
- Set and monitor monthly budgets
- Define and progress towards savings goals

This project is developed as part of a university course project by **Group 4**, using **React (with Electron)** for the frontend, **Node.js** for the backend, and **MySQL** as the database.



## Team Members (Group 4)

| Name | Student ID | Email |
|------|-------------|--------|
| **Devyan Jethwa** | 183428 | devyan.jethwa@strathmore.edu |
| **Ian Kiprotich** | 192026 | ian.kiprotich@strathmore.edu |
| **Stacy Mwangi** | 160077 | njoki.mwangi@strathmore.edu |
| **Brian Memusi** | 189718 | brian.memusi@strathmore.edu |
| **Amani Abigael** | 188947 | abigael.wanjiku@strathmore.edu |
| **Victor Mwakisagu** | 189944 | victor.mwakisagu@strathmore.edu |
| **Paulette Mbaika** | 190016 | paulette.mbaika@strathmore.edu |
| **Eric Ghati** | 191652 | eric.chacha@strathmore.edu |



## Features 

### Functional Features
- **User Authentication**
  - Register & login with phone number + password
  - OTP-based login for enhanced security
  - Password recovery via SMS
  - Auto-logout after 30 min of inactivity

- **Dashboard**
  - Monthly expense summary
  - Remaining budget overview
  - Savings progress tracker
  - Quick buttons for key actions
  - Color-coded indicators (green = on track, red = overspending)

- **Expense Logging**
  - Manual entry (amount, date, category, notes)
  - Predefined categories (tuition, food, transport, books, other)
  - View expense history with filters
  - Validation: No negative/future amounts

- **Budget Setting & Visualization**
  - Set monthly budgets per category
  - Alerts at 80% and 100% usage
  - Pie charts and line graphs for analysis
  - Option to adjust mid-month

- **Savings Goals**
  - Create and track goals (amount, deadline, purpose)
  - Progress bars with milestone notifications
  - Manual savings contributions

### Non-Functional Features
- **Security**: HTTPS, bcrypt password hashing, JWT session management  
- **Performance**: Dashboard loads in <2s; offline cache support  
- **Usability**: Simple interface, onboarding tutorial, undo option for 5 minutes  
- **Scalability**: Handles 500–1000 users initially  
- **Reliability**: 99.9% uptime (excluding maintenance), daily DB backups  



