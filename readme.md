# 🚀 WhatsApp Backend Clone

A  real-time backend system inspired by WhatsApp, built using Django, DRF, Channels, and Redis.

This project demonstrates production-level backend engineering concepts including WebSockets, JWT authentication, real-time messaging, and scalable architecture.
---

## 🎥 Demo

    https://github.com/user-attachments/assets/your-video-id

> 📌 If video doesn’t play, download `vid.mp4` from the repo.

---

## 🧠 Overview

This project is a **real-time messaging backend** supporting one-to-one chat with:

- ⚡ Instant messaging via WebSockets  
- ✍️ Typing indicators  
- 🟢 Online / Offline presence  
- 🖼️ Image sharing  
- 🔐 Secure JWT authentication  

Built with a focus on **scalability and production-ready backend architecture**.

---

## 🛠️ Tech Stack

| Category                | Technology                          |
|------------------------|-----------------------------------|
| Backend Framework      | Django                            |
| API Layer              | Django REST Framework (DRF)       |
| Real-Time Communication| Django Channels, WebSockets       |
| Message Broker / Cache | Redis                             |
| Database               | PostgreSQL                        |
| Authentication         | Custom JWT-based system           |

---

## ✨ Features

### 💬 Real-Time Chat
- One-to-one messaging
- Instant delivery using WebSockets
- Message persistence

### 📡 Live System Features
- Typing indicators
- Online / Offline user tracking
- Redis-powered pub/sub system

### 🔐 Authentication System
- Custom JWT authentication
- Login & Registration
- Change password
- Password reset via email
- Email verification

### 👤 User Features
- Profile creation & update
- User search
- Friend invitations / connections

### 📦 REST APIs
- Built with DRF
- Clean and modular endpoints for:
  - Authentication
  - Messaging
  - User interactions

---

## ⚙️ Architecture

- Async backend using **Django Channels**
- Redis for real-time event handling
- Separation of:
  - REST APIs (HTTP)
  - WebSockets (real-time layer)

---
