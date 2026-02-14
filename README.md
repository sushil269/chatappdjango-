# Social Real-time Chat & Networking Engine
A Django-powered communication platform featuring a complete social ecosystem, including user authentication, friend management, and real-time messaging.

## 📌 Project Overview
This project was engineered to explore the complexities of relational user data and real-time interaction. Beyond simple messaging, it implements a full "Social Graph" where users can manage their digital connections and communicate securely.

## 🚀 Technical Features

### 1. Social Relationship Management (Friendship Logic)
Implemented a robust "Friend Request" system that handles complex states:
* **Asynchronous Requests:** Users can send, receive, and track pending friend requests.
* **Relationship Control:** Functionality to accept or delete friend requests and manage active friend lists.
* **Data Integrity:** Ensured that chat rooms are only accessible to verified connections.

### 2. Full-Stack User Ecosystem
* **Authentication:** Secure registration and login protocols using Django's Auth system.
* **Dynamic Profiles:** User-specific dashboards to manage connections and conversational history.

### 3. Real-time Communication Interface
* **Interactive Chat:** Optimized frontend for sending and receiving messages instantly.
* **State Management:** Logic to handle message replies and real-time UI updates without page reloads.

## 🛠 Tech Stack
* **Backend:** Python, Django (Models, Views, and Auth)
* **Database:** MySQL / SQLite (Relational mapping for Friendships)
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
* **Tools:** Git, GitHub, VS Code, Postman
