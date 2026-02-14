# Nexus Analytics | Enterprise-Grade Dashboard UI 🚀

[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-black?style=for-the-badge&logo=vercel)](https://nexus-analytics-dash.vercel.app/)
[![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)

**Nexus Analytics** is a high-performance, responsive analytics dashboard built to showcase modern frontend engineering principles. It features real-time state management, seamless routing, and a mobile-first design approach.

---

## 🌟 Key Features

* **Real-time Interactivity:** Implemented dynamic counters using React `useState` and `useEffect` to simulate live data streaming.
* **MERN-Ready Architecture:** Configured with a Node.js/Express backend bridge (`server.js`) to handle server-side routing and static file serving.
* **Responsive UI:** Fully optimized for all screen sizes (Mobile, Tablet, Desktop) using Tailwind CSS.
* **Production Optimized:** Deployed via Vercel with custom `vercel.json` configurations to ensure zero-downtime and proper asset rendering.

---

## 🚀 Technical Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React.js (v18), Babel (Standalone) |
| **Styling** | Tailwind CSS (Utility-first framework) |
| **Backend** | Node.js, Express.js (Server-side Bridge) |
| **Deployment** | Vercel (Edge Functions & Static Hosting) |
| **Icons** | FontAwesome 6.4 |



---

## 📁 Project Structure

```text
nexus-analytics-dash/
├── index.html      # Main Entry Point (React Frontend)
├── server.js       # Node.js/Express Server Logic
├── package.json    # Dependencies & Scripts
├── vercel.json     # Deployment Configuration
└── README.md       # Project Documentation
