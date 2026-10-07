# 📱 TP Headless Strapi + Next.js + Docker

## 📌 Description

This project implements a decoupled Headless Architecture for a phone accessories showcase.

The backend is developed with Strapi and exposes product data through a REST API. The frontend is developed with Next.js and consumes the API to display the products.

The two services are containerized and orchestrated using Docker Compose.

## 🏗️ Architecture

```text
User / Browser
      |
      v
Next.js (Frontend)
Port 3000
      |
      | REST API
      v
Strapi (Backend)
Port 1337
      |
      v
SQLite Database
