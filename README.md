# 🐳 Docker Guide

A complete visual and command-based guide to essential **Docker** operations — from running containers to cleaning up 
system space.  
Perfect for beginners who want a practical reference for everyday Docker tasks.

---

## 🌐 Live Demo 

### 🚀 Live site: https://someshdiwan.github.io/Docker-Guide/

---

## 📘 Overview

This guide helps developers quickly recall Docker commands for:
- **Operations** – start, stop, rebuild, and manage containers
- **Monitoring** – check logs, health, and dashboards
- **Cleanup** – safely remove images, volumes, and cache
- **Best Practices** – optimize builds and maintain clean environments

The interface is minimal, responsive, and interactive — built using plain **HTML**, **CSS**, and **JavaScript**.

---

## 📂 Structure

```
Docker-Guide/
├── index.html    # Main page with all sections
├── styles.css    # Styling for layout and design
├── app.js        # Tab switching logic
├── LICENSE       # MIT license
└── README.md     # Project overview
```

---

## 🧹 Docker Cleanup Command Reference

| 🧭 Action                   | 🧰 Command                        |
|-----------------------------|------------------------------------|
| Stop containers             | `docker compose down`              |
| Remove build cache          | `docker builder prune -af`         |
| Remove unused images        | `docker image prune -a -f`         |
| Clean containers/networks   | `docker container prune -f`        |
| Delete unused volumes       | `docker volume prune -f`           |
| Full cleanup (everything)   | `docker system prune -af`          |

💡 **Tip:** Run `docker system df` before and after cleanup to see reclaimed space.

---

📖 License

This project is licensed under the MIT License — free to use, modify, and share.

---

Created by Somesh Diwan, Clean, interactive, and beginner-friendly Docker documentation.

---
