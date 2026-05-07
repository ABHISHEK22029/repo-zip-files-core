# 📦 repo-zip-files-core

A personal archive repository containing portable, ready-to-run project ZIPs for transfer across machines.

---

## 📁 Contents

| File | Project | Description |
|------|---------|-------------|
| `poc_COMPLETE_FINAL.zip` | **Construction POC** | Full-stack Construction Project Management Platform (React + Node.js + SQLite) |
| `sinfra_COMPLETE.zip` | **Sinfra Website** | Static HTML website — Sahasra Infra (electrical/civil manufacturing) with all images |
| `kbs-site_COMPLETE.zip` | **KBS Site** | Static HTML website — KBS company site with full image gallery, products, machinery, services pages |
| `ssp_COMPLETE.zip` | **SSP Website** | Static HTML website — SSP company site with hero images, sectors, projects, business pages |

---

## 🏗️ POC — Construction Project Management Platform

A full-stack web application for managing infrastructure/construction projects end-to-end.

### Tech Stack
- **Frontend:** React 19 + Vite + TailwindCSS + React Router
- **Backend:** Node.js + Express 5
- **Database:** SQLite (file-based, included in zip)
- **Charts:** Recharts
- **Maps:** Leaflet + React-Leaflet
- **Process Flow:** ReactFlow + Dagre

### Features Included
- ✅ Project Management
- ✅ Work Orders
- ✅ Vendor Registry (with PAN, GSTIN, ratings)
- ✅ Bill of Quantities (BOQ)
- ✅ Material Indents
- ✅ Purchase Orders
- ✅ Goods Receipt Notes (GRN)
- ✅ Measurement Book
- ✅ RA Bill Generation
- ✅ Inventory Tracking
- ✅ Interactive ORR Map
- ✅ Process Flow Diagram
- ✅ Activity Log / Audit Trail
- ✅ Dashboard with KPI charts

---

## 🚀 How to Run (Windows / Mac / Linux)

### Prerequisites
- Install **[Node.js LTS](https://nodejs.org)** (v18+)
  - On Windows: ✅ tick **"Install tools for native modules"** during setup

### Steps

1. **Download and unzip** `poc_COMPLETE_FINAL.zip`

2. **Start the Backend** (Terminal 1):
```bash
cd backend
npm install
node index.js
# ✅ Backend running on http://localhost:5000
```

3. **Start the Frontend** (Terminal 2):
```bash
cd frontend
npm install
npm run dev
# ✅ Frontend running on http://localhost:5173
```

4. Open your browser → **http://localhost:5173** 🎉

### Optional: Re-seed the database
```bash
cd backend
node seed_massive.js       # Large-scale test data
node seed_edge_cases.js    # Edge case scenarios
```

> **Note:** The SQLite database (`backend/database.sqlite`) is included in the zip with pre-loaded demo data. If you want a fresh start, delete it and restart the backend.

---

## 📥 Downloading

To download any zip from this repo:
1. Click on the zip file name above
2. Click the **"Download raw file"** button (⬇️ icon) on GitHub
3. Or use: `git clone https://github.com/ABHISHEK22029/repo-zip-files-core.git`

---

*Created by Abhishek Gupta — May 2026*
