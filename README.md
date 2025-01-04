# 🚀 **LinkStack**

LinkStack is a full-stack Linktree clone designed for users who want a personalized and customizable way to organize and display their links in a centralized location. Built with the robust MERN stack (MongoDB, Express.js, React.js, Node.js), this tool allows seamless integration of personal or professional links into one easily accessible platform.

### **Key Features:**
- **Customizable Link Management:** Effortlessly create, edit, and reorder links.
- **Drag-and-Drop Functionality:** Easily organize links with visual drag-and-drop interaction.
- **User Authentication:** Secure token-based sessions for user data protection.
- **Responsive Design:** Optimized for all screen sizes for a seamless user experience across devices.

Designed to demonstrate cutting-edge development techniques, LinkStack showcases proficiency in **React.js**, **Tailwind CSS**, and **Node.js**. The robust backend leverages **MongoDB** for scalable data management and ensures reliable performance. Adherence to secure coding practices guarantees the platform’s security and scalability.

🔗 **Live Demo:** [LinkStack](https://linknest.onrender.com/)

---

## 🛠️ **Features**

- **Personalized Link Management:** Add, edit, and reorder links quickly.
- **Drag-and-Drop Interface:** Visualize and organize links with ease.
- **Token-Based Authentication:** Secure access with JWT token authentication.
- **Mobile-Responsive:** Optimized for seamless experiences on any device.

---

## 💻 **Tech Stack**

### **Frontend**
- ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
- ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

Additional Libraries: **React Beautiful DND**, **React Toastify**, **daisyUI**, **SweetAlert2**

### **Backend**
- ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
- ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
- ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

### **Testing**
- ![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
- ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)

### **Deployment**
- ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)

---

## 🚧 **Getting Started**

### **Prerequisites**
| Requirement | Version |
|-------------|---------|
| [Node.js](https://nodejs.org) | `^18.17.0` |
| npm (comes with Node.js) | `^9.7.1` |

### **Installation**

1. **Initialize the project:**
    ```bash
    mkdir LinkNest
    cd LinkNest
    git init
    ```

2. **Clone the repository:**
    ```bash
    git pull https://github.com/pushpakrai/LinkStack
    ```

3. **Install backend dependencies:**
    ```bash
    cd backend
    npm install
    ```

4. **Create a `.env` file in the backend directory:**
    ```env
    MONGODB_URI= <Connection to production MongoDB database>
    TEST_MONGODB_URI= <Connection to test MongoDB database>
    PORT= <Port for running development server>
    ACCESS_TOKEN_SECRET= <Secret string for access token>
    REFRESH_TOKEN_SECRET= <Secret string for refresh token>
    ```

5. **Install frontend dependencies:**
    ```bash
    cd ../frontend
    npm install
    ```

### **Running the Application**
1. **Start the backend server:**
    ```bash
    cd backend
    npm run dev
    ```

2. **Start the frontend client:**
    ```bash
    cd ../frontend
    npm run dev
    ```

3. Open the app in your browser at:
    ```
    http://localhost:3000
    ```

---

## 📜 **License**

This project is licensed under the [MIT License](LICENSE).

---

## 📝 **Disclaimer**

This project is inspired by **Linktree** but developed independently as a personal project. It is not affiliated with or endorsed by Linktree.

---

This streamlined version provides clarity and highlights key elements of the project in a professional format. Let me know if you'd like any further enhancements!
