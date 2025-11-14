# College Marksheet Management System 🚀

An advanced, secure, and efficient web application designed for educational institutions to manage student academic records. This full-stack project features a modern React frontend and a robust Node.js backend, focusing on a smart, automated workflow for teachers to reduce errors and save time.

---
## ## Key Features ✨

* **Secure Teacher Authentication**: Implements JWT (JSON Web Tokens) with a secure `httpOnly` refresh token in a cookie to persist user sessions and protect against XSS attacks.
* **Student Information System (SIS)**: Full CRUD (Create, Read, Update, Delete) functionality for student records.
* **Intelligent Result Management**:
    * A "smart" workflow that automatically determines the correct academic year and semester for result entry based on the student's admission details.
    * Dynamic subject population based on the student's year, department, and a special grouping logic for the first year.
    * Handles complex evaluation schemes (ISE, MSE, ESE).
* **Dynamic Data Model**: The system is built around a "single source of truth" model where a student's current academic year is calculated dynamically, eliminating the need for manual annual updates.
* **Role-Based Authorization**: A security layer that prevents teachers from accessing or modifying records of students from other departments.
* **Analytics Dashboard**: Provides a comprehensive overview of key statistics, including pass percentages, department-wise performance, and recent activities.
* **Efficient & Modern Frontend**:
    * Built with React and TypeScript.
    * Utilizes lazy loading for faster initial page loads.
    * Features an optimized routing structure that prevents unnecessary re-rendering of layout components.

---
## ## Tech Stack ⚙️

### **Frontend**
* **React.js**: For building the user interface.
* **TypeScript**: For static typing and improved developer experience.
* **Vite**: Next-generation frontend tooling for a fast development experience.
* **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
* **React Router**: For client-side routing.
* **Fetch API**: For making requests to the backend.

### **Backend**
* **Node.js**: JavaScript runtime for the server.
* **Express.js**: A minimal and flexible Node.js web application framework.
* **MongoDB**: NoSQL database for storing application data.
* **Mongoose**: An Object Data Modeling (ODM) library for MongoDB and Node.js.
* **JSON Web Token (JWT)**: For handling secure authentication.
* **Bcrypt.js**: For hashing user passwords.

---
