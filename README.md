# SocialEcho

SocialEcho is a full-stack social networking platform built using the MERN stack (MongoDB, Express.js, React.js, and Node.js).

The platform provides user authentication, profile management, posts, comments, likes, following/unfollowing, communities, reporting, content moderation, context-based authentication, and role-based access for administrators and moderators.

The project also includes an automated content moderation system using NLP services and a Flask-based machine learning classifier.

---

## 🚀 Live Demo

### Frontend

https://socialecho-2.onrender.com

### Backend

https://socialecho-1-v8ef.onrender.com

### Backend Health Check

https://socialecho-1-v8ef.onrender.com/server-status

---

## 📌 Project Overview

SocialEcho is a social networking web application developed using the MERN stack.

The application allows users to:

- Create accounts
- Login securely
- Create and manage profiles
- Create posts
- Like posts
- Comment on posts
- Follow and unfollow users
- Join communities
- Report inappropriate content
- Manage their devices
- Interact with other users

The application also provides separate roles for:

- Admin
- Moderator
- General User

The Admin and Moderator systems allow authorized users to manage communities, review reported content, monitor users, and perform moderation-related tasks.

---

# ✨ Features

## 👤 User Features

- User Registration
- User Login
- JWT Authentication
- User Profile Creation
- Profile Management
- Create Posts
- Edit Posts
- Delete Posts
- Like Posts
- Comment on Posts
- Like Comments
- Follow Users
- Unfollow Users
- Community Interaction
- Report Posts
- Device Management
- Context-Based Authentication

---

## 🔐 Authentication & Authorization

SocialEcho uses JWT-based authentication and Passport.js for authentication and authorization.

The application supports role-based access control.

### User Roles

| Role | Description |
|------|-------------|
| Admin | Manages the overall system, moderators, communities, users, and moderation settings |
| Moderator | Manages assigned communities and reviews reported content |
| General User | Creates posts, comments, likes, follows users, and interacts with communities |

---

# 👨‍💼 Admin Dashboard

The application contains a dedicated Admin Dashboard.

The Admin can:

- Manage moderators
- Manage communities
- Monitor user activity
- Review reported content
- Manage platform settings
- Manage moderation services
- Enable or disable API services
- Switch between moderation services

### Admin Route

```text
/admin
