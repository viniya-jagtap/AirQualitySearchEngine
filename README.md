# AQI Search Engine

A simple Air Quality Index (AQI) Search Engine to check real-time AQI of any city using a clean frontend and Node.js backend.

---

## Project Structure
aqi-search-engine/
├── backend/
│ ├── server.js
│ ├── routes/
│ └── controllers/
├── frontend/
│ ├── index.html
│ ├── style.css
│ └── script.js

## Features

- Search real-time AQI of any city  
- Fast performance with caching  
- Clean UI  
- Node.js + Express backend  

---

## Setup

### Backend
```bash
cd backend

###backend/config/apiConfig.js:
module.exports = {
  AQI_API_URL: "https://api.waqi.info/feed",
  API_KEY: "your_api_key_here"
};
Start server:
node server.js

##Frontend
Open frontend/index.html in browser (or use Live Server).

##API Endpoint
GET /api/aqi/:city
Example: http://localhost:5000/api/aqi/pune

##Purpose

Full Stack project (Frontend + Backend)

API Integration & Caching

Real-time AQI search




