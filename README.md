# 🏊 LIS Swimming Championship 2026 — Management Portal

> A browser-based event management system designed to manage an inter-branch swimming championship from athlete registration to results, certificates, payments and reporting.

## 📌 Overview

The **LIS Swimming Championship Management Portal** is a lightweight, browser-based application developed to simplify the management of a swimming championship.

The system brings multiple event-management activities into a single application, including athlete registration, call-room management, referee timing, marks calculation, live leaderboards, payments, reporting and certificate generation.

The application is designed to operate without a backend or database and can run directly in a modern web browser.

---

## 🚀 Key Features

### 👥 Role-Based Access

The system provides different access levels for different users:

- **Admin** - Full system access
- **Staff** - Operational access
- **Branch** - Access limited to an individual branch

### 📊 Dashboard

- Live event statistics
- Branch score overview
- Activity feed
- Automatic data refresh

### 🏊 Event Management

- Athlete registration
- Athlete search and filtering
- Event configuration
- Call-room management
- Swimmer, lane and heat assignments

### ⏱️ Referee Timing

- Record swim times by lane
- Manage event results
- Support marks and placing calculations

### 🏆 Results & Leaderboards

- Automatic marks calculation
- Event placings
- Branch standings
- Real-time championship leaderboard

### 💳 Payments & Reports

- Registration payment tracking
- Athlete reports
- Event reports
- Exportable information

### 📜 Certificate Management

- Certificate generation
- Drag-and-drop certificate designer
- Custom certificate backgrounds
- PDF export using jsPDF

### 📧 Email

- Compose result and confirmation emails
- Gmail integration for sending emails

### 📱 Responsive Interface

- Mobile-friendly interface
- Responsive layouts
- Dedicated mobile navigation

---

## 🛠️ Technology Stack

### Frontend

- HTML5
- CSS3
- JavaScript

### Libraries & Services

- [Chart.js](https://www.chartjs.org/) — Dashboard charts
- [jsPDF](https://github.com/parallax/jsPDF) — PDF generation
- Google Fonts — Barlow Condensed & DM Sans
- Browser `localStorage` — Local application data persistence

### Development Tools

- Git
- GitHub
- Visual Studio Code
- Modern Web Browser

---

## 🏗️ Application Architecture

The application follows a lightweight client-side architecture.

```text
User
  │
  ▼
Web Browser
  │
  ├── Authentication
  │
  ├── Dashboard
  │
  ├── Athlete Management
  │
  ├── Event Management
  │
  ├── Call Room
  │
  ├── Referee Timing
  │
  ├── Marks Calculation
  │
  ├── Leaderboard
  │
  ├── Payments
  │
  ├── Reports
  │
  └── Certificate Designer
          │
          ▼
     Browser localStorage
