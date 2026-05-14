# naga-conveyor-app
# 🏭 Naga Conveyor Monitoring System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-19-blue.svg)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-8-purple.svg)](https://vitejs.dev/)
[![Capacitor](https://img.shields.io/badge/Capacitor-8-blue.svg)](https://capacitorjs.com/)

A high-visibility, Industrial 4.0 monitoring dashboard designed for real-time tracking of multiple conveyor lines. This application provides a premium, technical aesthetic optimized for factory floors and mobile devices.

## 🚀 Key Features

- **Live Status Tracking:** Real-time monitoring of 4 independent conveyor lines via MQTT integration.
- **Industrial 4.0 UI:** Technical grid backgrounds, glass-morphism panels, and high-visibility status indicators.
- **Multi-Platform:**
  - 🌐 **Web:** Fully responsive PWA (Progressive Web App).
  - 📱 **Mobile:** Native-like experience via Capacitor.
  - 💻 **Desktop:** Electron integration for workstation monitoring.
- **Smart Reporting:** Automated PDF generation for performance metrics and conveyor health reports.
- **Dynamic Alerts:** Visual indicators for emergency stops, motor failures, and connectivity issues.

## 🛠 Tech Stack

- **Core:** React 19 + Vite
- **Styling:** CSS3 (Technical UI Design System)
- **Animations:** Framer Motion
- **Database/Hosting:** Firebase
- **Communication:** MQTT (via `mqtt.js`)
- **Report Generation:** jsPDF + autoTable

## 📂 Project Structure

```text
src/
├── components/   # Reusable UI components
├── context/      # App State Management
├── pages/        # Dashboard, Status, and Detail views
├── assets/       # Icons and Industrial assets
└── firebaseConfig.js
```

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/naga-conveyor-app.git
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run in development mode:**
   ```bash
   npm run dev
   ```

4. **Build for production:**
   ```bash
   npm run build
   ```

## 👷 Author
**Ravindhar** - *Lead Developer*

---
*Developed for industrial efficiency and real-time monitoring.*

