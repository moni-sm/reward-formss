# 🏆 Rewards & Recognition System (Confidential)

> **⚠️ Confidential Internal Project**  
> This repository is for documentation purposes only. Source code is private and not publicly accessible.

---

## 🚀 Deployed Applications

| 🎯 **Client (Employee Nomination Form)** | Used by employees to nominate peers for recognition. 
| 🔐 **Admin Dashboard** | Allows internal admins to review, manage, and track nominations. 

## 🛠️ Tech Stack

### 🔹 Frontend (Client & Admin)
- React.js (Vite)
- Axios
- React Router DOM
- State Management via useState/useEffect

### 🔹 Backend
- Node.js
- Express.js
- `xlsx` for Excel file parsing
- `csv-writer` for storing nominations
- File system-based storage (JSON)

### 🔹 Deployment
- Vercel (for Client and Admin)
- Render hosting for Express server

---

## 📋 Features

### ✅ Client (Employee Portal)
- Dynamic form to submit nominations
- Auto-fill employee and nominator details from internal data (Excel)
- Monthly / Quarterly / Yearly nomination support
- Nomination reason entry with category tracking
- Submission stored securely on the server

### ✅ Admin Dashboard
- Displays top nominees by category
- Monthly / Quarterly / Yearly category breakdown
- Nominee name click reveals detailed nomination data
- Clean UI with collapsible sidebar and responsive design
- Dropdown filters for year, quarter, and month
- Data sourced from JSON or CSV files

---

## 📎 Notes

- This project is under internal usage and is not meant for public or external sharing.
- All data access and manipulation is secure and restricted to internal tools.
- Authentication and database (MongoDB) integration are planned for a future release.

---

## 📌 Disclaimer

This README is for informational purposes only. No source code is included.  
© 2025 All rights reserved.
