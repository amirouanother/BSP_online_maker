# TF2 Map BSP online

A user-friendly, browser-based map editor for Team Fortress 2.  
Design maps visually with drag-and-drop entities, configure game modes (CTF, KOTH, CP), choose skyboxes without void errors, and import/export in VMF, BSP, or a custom WBSP format for easy sharing and collaboration.

## Features

- **Hammer-style interface**  
  Split view with entity sidebar, top-down canvas, and property panel.  
- **Drag & drop entities**  
  Place spawn points, props, logic entities, and more.  
- **Game mode presets**  
  One-click setup for Capture the Flag, King of the Hill, or Control Point.  
- **Skybox control**  
  Select any TF2 skybox—auto-generate brushes to prevent void holes.  
- **Import & export**  
  Load existing VMF or BSP files, edit in-browser, then export VMF, compile to BSP, or save as WBSP (JSON) for versioned, collaborative editing.  
- **Light/Dark mode**  
  Editor theme toggles for day or night design sessions.

## Getting Started

1. **Clone the repo**  
   ```bash
   git clone [https://github.com/YourUsername/tf2-map-forge.git](https://github.com/amirouanother/BSP_online_maker/)
   cd BSP_online_maker
   Install dependencies


# Backend
cd backend && npm install
# Frontend
cd ../frontend && npm install
Run editor

bash
Copy
Edit
npm run start
Frontend: http://localhost:8080

Backend API: http://localhost:3000

Project Structure
