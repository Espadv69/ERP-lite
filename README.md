# ERP Lite App

A lightweight ERP-style web application with basic login and inventory management. Built entirely in **React**, this project simulates core business operations (like user roles and stock control) without a backend server — making it fast and easy to deploy on platforms like **Netlify**.

> 🧑‍💼 Built as a personal project to practice concepts from SCM, ERP, and business process automation.

## 🚀 Live Demo

_(Coming soon, after deployment to Netlify)_

## 🛠️ Tech Stack

- **Frontend only:** React
- **Styling:** CSS
- **State management:** React Context + useState
- **Data storage:** localStorage (simulating database)

## ✨ Features

- Basic login system
  - Static list of allowed usernames
  - One shared password (`erp2025`)
- Role detection: tutor vs employee
- Inventory management
  - Add, edit, delete items
  - View current stock in table/list
- Responsive UI

## 🗂️ Folder Structure

erp-lite-app/
├── public/
├── src/
│ ├── components/
│ ├── context/
│ ├── pages/
│ ├── App.jsx
│ └── main.jsx
├── README.md
└── package.json

## 🧪 Static Users (for login)

| Username | Role     | Password |
|----------|----------|----------|
| scm00    | tutor    | erp2025  |
| scm01    | employee | erp2025  |
| scm02    | employee | erp2025  |

## 🧾 How to Run Locally

```bash
git clone https://github.com/Espadv69/ERP-lite.git
cd ERP-lite
npm install
npm run dev
```

## 📚 License

This project is licensed under the **[MIT License](https://opensource.org/license/mit)**.

---

Made with ❤️ by Espadv69