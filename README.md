# Technology Risk Management Web App (RCM-based)

This is a full-stack web application for managing technology risks using a Risk and Control Matrix (RCM) approach.

## 📦 Structure

- `client/`: React + TailwindCSS frontend
- `api/`: Express + SQLite backend

## 🚀 Quick Start

### Backend (Render / localhost)

```bash
cd api
npm install
node server.js
```

### Frontend (Vercel / localhost)

```bash
cd client
npm install
npm run dev
```

> Make sure backend runs on port 5000.

## 📊 Features

- Risk table with filters
- Dynamic heatmap visualization
- In-memory SQLite data

## 🌐 Deployment

- Deploy `client/` to [Vercel](https://vercel.com)
- Deploy `api/` to [Render](https://render.com)

## 🛠 Tech Stack

- React, TailwindCSS, Vite
- Express.js, SQLite
