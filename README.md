# EcoVision

EcoVision is a responsive environmental intelligence dashboard prototype built with React, Vite, Tailwind CSS, Leaflet, and Recharts. It includes a premium dashboard, environmental score analysis, map exploration, city comparison, prediction view, and demo report submission.

## Features

- Environmental overview dashboard with eight environmental factor cards
- Location-aware demo city switching across Chennai, Bangalore, Coimbatore, Hyderabad, Mumbai, and Delhi
- Interactive map with environmental layer toggles and popups
- City comparison table and grouped comparison chart
- Simulated AI prediction page for future forecasting workflows
- Environmental issue report form with validation and local demo storage
- Responsive dashboard layout for desktop, tablet, and mobile screens
- Data transparency with Demo Data labels throughout the interface

## Tech stack

- React + Vite
- JavaScript
- Tailwind CSS
- Lucide React
- Recharts
- React Leaflet + OpenStreetMap
- FastAPI-ready frontend structure

## Local installation

1. Install dependencies:
   npm install
2. Start the app:
   npm run dev
3. Open the local address shown in the terminal, typically http://localhost:5173

## Production build

npm run build

## Notes

- All dataset values are demonstration values intended for UI prototyping.
- The app is structured to support future backend integration with a Python FastAPI service and real environmental APIs.
- The score is a project-defined analytical indicator and is clearly labelled as such in the interface.
