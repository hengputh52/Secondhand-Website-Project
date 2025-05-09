﻿# Secondhand-Website-Project
# 📖 **Secondhand Website Project Documentation**  

## **Table of Contents**  
1. [Project Overview](#project-overview)  
2. [Tech Stack](#tech-stack)  
3. [Installation Guide](#installation-guide)  
4. [Project Structure](#project-structure)  
5. [Features](#features)  
6. [Routing & Navigation](#routing--navigation)  
7. [Components](#components)  
8. [How to Contribute](#how-to-contribute)  
9. [Future Enhancements](#future-enhancements)  
10. [License](#license)  

---

## **1. Project Overview**  
The **Secondhand Website Project** is a platform where users can **buy, sell, and exchange** secondhand books. Users can **sign up**, **browse book lists**, view **detailed book descriptions**, and manage their **profiles**.  

---

## **2. Tech Stack**  
- **Frontend:** React.js, React Router  
- **Styling:** CSS3  
- **State Management:** useState, useEffect  
- **Icons & Images:** FontAwesome, Local Assets  
- **Hosting:** GitHub Pages (Optional)  

---

## **3. Installation Guide**  
### **Prerequisites**  
- Install **Node.js** and **npm/yarn**  
- Install **Git**  

### **Clone Repository**  
```sh
git clone https://github.com/hengputh52/Secondhand-Website-Project.git
cd Secondhand-Website-Project
```

### **Install Dependencies**  
```sh
npm install
```
or  
```sh
yarn install
```

### **Run the Project**  
```sh
npm start
```
or  
```sh
yarn start
```
🔹 Open `http://localhost:3000/` in your browser.

---

## **4. Project Structure**  
```
Secondhand-Website-Project/
│── src/
│   ├── assets/               # Images & Icons
│   ├── components/           # Reusable Components
│   │   ├── BookList.jsx
│   │   ├── BookDetail.jsx
│   │   ├── Nav.jsx
│   │   ├── Footer.jsx
│   │   ├── SignUp.jsx
│   │   ├── Profile.jsx
│   ├── styles/               # CSS Styles
│   │   ├── Nav.css
│   │   ├── BookList.css
│   │   ├── BookDetail.css
│   │   ├── Profile.css
│   ├── pages/                # Page Components
│   │   ├── HomePage.jsx
│   │   ├── ProfilePage.jsx
│   │   ├── SignUpPage.jsx
│   ├── App.jsx               # Main Component
│   ├── index.js              # React Entry File
│── public/                    # Static Files
│── package.json               # Dependencies
│── README.md                  # Documentation
```

---

## **5. Features**  
✅ **User Authentication** (Sign Up via Google, Facebook, Apple)  
✅ **Browse Books** (List & Detail View)  
✅ **Sell Books** (Upload & Manage Listings)  
✅ **Profile Management** (Edit User Info)  
✅ **Responsive UI** (Mobile-Friendly)  

---

## **6. Routing & Navigation**  
| **Route**            | **Component**        | **Description**             |
|----------------------|---------------------|-----------------------------|
| `/`                 | `HomePage.jsx`       | Displays book categories & best picks  |
| `/signup`           | `SignUpPage.jsx`     | User authentication page    |
| `/book/:id`         | `BookDetail.jsx`     | Displays book details       |
| `/profile`          | `ProfilePage.jsx`    | User profile management     |
| `/genres/:type`     | `GenrePage.jsx`      | Lists books by genre        |
| `/sell`             | `SellBook.jsx`       | Upload book for sale        |

---

## **7. Components**  
### 📌 **`Nav.jsx`**  
- **Contains:** Navigation bar  
- **Links:** Home, Genres, Profile, Sell  
- **Handles:** User authentication state  

### 📌 **`BookList.jsx`**  
- **Displays:** List of books  
- **Uses:** `BookCard` for each book  
- **Navigation:** Clicking a book navigates to `/book/:id`  

### 📌 **`BookDetail.jsx`**  
- **Displays:** Single book details  
- **Includes:** Title, Image, Description, Price  

### 📌 **`Profile.jsx`**  
- **Displays:** User info  
- **Allows:** Editing user details  

### 📌 **`SignUp.jsx`**  
- **Sign-up Methods:** Google, Facebook, Apple  

---

## **8. How to Contribute**  
### **1️⃣ Fork the Repository**  
Click the **Fork** button on GitHub.  

### **2️⃣ Clone Your Fork**  
```sh
git clone https://github.com/your-username/Secondhand-Website-Project.git
cd Secondhand-Website-Project
```

### **3️⃣ Create a New Branch**  
```sh
git checkout -b feature-name
```

### **4️⃣ Make Changes & Commit**  
```sh
git add .
git commit -m "Added new feature"
```

### **5️⃣ Push Changes**  
```sh
git push origin feature-name
```

### **6️⃣ Open a Pull Request**  
Go to **your repository** on GitHub → Click **Pull Request** → Compare & Submit  

---

## **9. Future Enhancements**  
🚀 **Search Functionality** – Search books by title or author  
🚀 **Wishlist Feature** – Save books to buy later  
🚀 **Payment Integration** – Secure online transactions  
🚀 **Chat System** – Buyers & Sellers can communicate  

---

## **10. License**  
📜 This project is licensed under the **MIT License**.  

---
💡 **Need Help?** Feel free to open an **issue** in the repository or contact the maintainers! 🚀🔥
