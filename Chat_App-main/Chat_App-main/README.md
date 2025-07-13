# Chat Application MERN-Stack Web Application

## Project Overview

_A real-time **Chat application** built using the MERN stack (MongoDB, Express, React, Node.js) and styled with Tailwind CSS. It supports user authentication, group chats, and instant messaging with real-time updates via Socket.IO. The application is fully responsive and provides smooth communication with features like notifications and state management using Redux._

## Technologies & Packages Used

- **MongoDB**: NoSQL database for flexible and scalable data storage.
- **Express.js**: Web application framework for Node.js, providing robust features for web and mobile applications.
- **Node.js**: JavaScript runtime for server-side development.
- **React.js**: A JavaScript library for building reusable UI components and efficient single-page application views.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Socket.IO**: Enables real-time, bidirectional and event-based communication.
- **JWT (JSON Web Tokens)**: Securely transmits information between parties as a JSON object.
- **Redux**: A Predictable State Container for JavaScript Apps.
- **React-Toastify**: A JavaScript library for providing toast notifications in React.

## Key Features

- **User Authentication:** SignIn, SignUp, and Logout functionality.
- **Real-time Chat:** Users can send and receive messages in real-time.
- **Group Chat:** Create and participate in group chats.
- **Message Notifications:** Get notified of new messages with sound and visual alerts.
- **State Management:** Manage application state efficiently using Redux.
- **Responsive Design:** Tailwind CSS for a responsive and modern user interface.
<!-- -   **User Status:** Display online/offline status of users. -->

## How to Install

Follow these steps to set up and run the project locally:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Vipul1407/Messaging-Site-Using-MERN
    cd Messaging-App-using-MERN-
    ```

2. **Install Dependencies:**
    Frontend Folder :

    ```bash
    cd frontend
    npm install
    ```

    Backend Folder :

    ```bash
    cd backend
    npm install
    ```

3. **Set Up Environment Variables:**

    Configure the following environment variables by creating a .env file in the root of Forntend and Backend Folder:

    Frontend Folder :

    ```bash
    VITE_BACKEND_URL=http://localhost:9000
    ```

    Backend Folder :

    ```bash
    FRONTEND_URL=http://localhost:5173
    MONGODB_URI=mongodb://127.0.0.1:27017/Messaging-App-using-MERN-
    PORT=9000
    JWT_SECRET=secret-kvndkvdlkajkhkJkBiu6JJNjkbhkvnskcmhLJ5dKbkjsamnv
    ```

    Replace the values with your specific configurations.

4. **Run the Application:**

    Frontend Folder :

    ```bash
    npm run dev
    ```

    Backend Folder :

    ```bash
    npm run dev
    ```

5. **Open in Your Browser:**

Open `http://localhost:5173` in your web browser.

## Project Structure

    ├── frontend
    │   ├── public
    │   ├── src
    │   │   ├── assets
    │   │   ├── components
    │   │   ├── pages
    │   │   ├── redux
    │   │   ├── socket
    │   │   ├── utils
    │   │   ├── App.jsx
    │   │   ├── main.jsx
    │   │   └── index.css
    │   ├── index.html
    │   ├── tailwind.config.js
    │   ├── .env
    │   └── package.json
    ├── backend
    │   ├── config
    │   ├── controllers
    │   ├── middlewares
    │   ├── models
    │   ├── routes
    │   ├── server.js
    │   ├── .env
    │   └── package.json
    └── README.md

## Images

**Profile**
![Macbook-Air-localhost](https://github.com/user-attachments/assets/7ea906d8-10a9-4e79-a3aa-46f45dd328bb)

**Group Create**
![Macbook-Air-localhost (5)](https://github.com/user-attachments/assets/49cff226-f372-4668-8095-8f741265edc3)

**Chat & Group Overview**
![Macbook-Air-localhost (2)](https://github.com/user-attachments/assets/1c367efe-4059-432c-8e6c-86ccb41bf712)

**Chat & Group Members**
![Macbook-Air-localhost (3)](https://github.com/user-attachments/assets/58764949-ac05-4c6b-ae6d-34c1d3232f64)

**Chat & Group Setting**
![Macbook-Air-localhost (4)](https://github.com/user-attachments/assets/33001244-8e21-46ff-b047-14bcac81829d)

**Add User in Group (Admin Access)**
![Macbook-Air-localhost (1)](https://github.com/user-attachments/assets/3dbf0fdb-4754-4d77-af5e-81fbf7a681d5)

**Remove User in Group (Admin Access)**
![Macbook-Air-localhost (6)](https://github.com/user-attachments/assets/526d6786-8813-4997-922c-bc3bfba2ee8b)

**User Search & Chat**
![Macbook-Air-localhost (7)](https://github.com/user-attachments/assets/b187e389-0fac-4c50-ba9c-aee1f9f55d66)

**Notification Box**
![Macbook-Air-localhost (8)](https://github.com/user-attachments/assets/376bdfd8-7ffa-435b-b506-0a7405d5137c)

**Notification Alert**
![Screenshot 2024-07-22 231334](https://github.com/user-attachments/assets/fbaa92af-ee49-48b7-8442-cd8f8cc4d3bc)

**Shimmer**
![image](https://github.com/user-attachments/assets/45b6665a-9e2d-4a61-b092-7cb7a0b775be)

---
