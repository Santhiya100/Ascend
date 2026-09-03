# ASCEND - Smart Transit & Fleet Intelligence System

ASCEND is an advanced AI-powered transit and fleet intelligence management platform designed for modern urban public transit, bus safety, live tracking, crowd analytics, road defect detection, ANPR evidence, and emergency response management.

---

## 🚀 Key Features

- **Live Fleet Tracking & Interactive GIS Map**: Real-time vehicle positions, route progress, and status alerts.
- **AI Passenger & Crowd Density Analytics**: Computer vision-based passenger counts and peak hour flow optimization.
- **AI Road Defect & Pothole Detection**: Automated hazard tracking and maintenance task dispatch.
- **Women Safety & SOS Alert System**: Emergency panic button integration, CCTV live feed escalation, and rapid response monitoring.
- **ANPR & License Plate Recognition**: Automated incident log and vehicle surveillance evidence capture.
- **Predictive Maintenance Engine**: AI-driven failure prediction, sensor telemetry, and component lifecycle health scores.
- **Audio & Visual Alerts**: Real-time synthesized audio chimes and interactive demo scenario simulations.

---

## 🛠️ Tech Stack

- **Framework**: React 19 + TypeScript
- **Bundler & Build Tool**: Vite
- **Styling**: Tailwind CSS v4 + Lucide Icons + Custom Glassmorphism UI
- **Mapping**: Leaflet + React Leaflet
- **Charts & Visualization**: Recharts

---

## 📦 Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Start Local Development Server
```bash
npm run dev
```
Open your browser at `http://localhost:5173`.

### 3. Build for Production
```bash
npm run build
```

---

## 📁 Project Structure

```
├── public/                # Static assets (logos, bus imagery)
├── src/
│   ├── assets/            # Project image resources
│   ├── components/        # Reusable UI components (Sidebar, TopBar, Maps, Modals)
│   ├── context/           # App state & alert context
│   ├── data/              # Mock transit data & incident logs
│   ├── pages/             # Route views (Dashboard, LiveFleet, Safety, Maintenance, etc.)
│   ├── utils/             # Helper utilities and audio synthesizers
│   ├── App.tsx            # Main application routing & layout
│   ├── index.css          # Styling & theme variables
│   └── main.tsx           # Application entry point
├── package.json           # Dependencies and scripts
├── tsconfig.json          # TypeScript configuration
└── vite.config.ts         # Vite build configuration
```

---

## 🔒 Security & Git Upload Note
- `node_modules/` and `dist/` are properly excluded in `.gitignore`.
- Total project payload is ~3.4 MB (well under GitHub's 25 MB web upload limit).
