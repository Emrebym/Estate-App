<div align="center">

# 🏠 Estate App

**A real estate listing platform with interactive maps, chat, and property search**

![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

</div>

---

## 📖 About

Estate App is a feature-rich real estate platform where users can browse property listings, view locations on an interactive map, chat with agents, and filter properties by type, location, and price. Built with React and Leaflet maps for a smooth, interactive experience.

## ✨ Features

- **Property listings** — browse houses and apartments with image sliders
- **Interactive map** — Leaflet map with pin markers for each property location
- **Property detail pages** — full specs, image galleries, and location view
- **Search & filter** — filter by property type, city, min/max price
- **Real-time chat** — built-in messaging component for agent communication
- **User authentication** — login and registration system
- **User profiles** — profile page with saved listings
- **Responsive design** — SCSS-based styling for all screen sizes
- **Client-side routing** — React Router v6 with nested layouts

## 🏗️ Architecture

```
src/
├── routes/
│   ├── homePage/          # Landing page with search
│   ├── listPage/          # Property listing grid + map
│   ├── singlePage/        # Individual property detail
│   ├── profilePage/       # User profile & saved items
│   ├── login/             # Login page
│   ├── register/          # Registration page
│   └── layout/            # Root layout with navbar
├── components/
│   ├── card/              # Property card component
│   ├── list/              # Property list view
│   ├── map/               # Leaflet map integration
│   ├── pin/               # Map pin markers
│   ├── filter/            # Search filter controls
│   ├── searchBar/         # Main search bar
│   ├── slider/            # Image slider/gallery
│   ├── chat/              # Real-time chat widget
│   └── navbar/            # Navigation bar
└── lib/
    └── loaders.js         # Route data loaders
```

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | React 18 |
| Routing | React Router v6 (data loaders) |
| Maps | Leaflet + React-Leaflet |
| Styling | Sass/SCSS |
| Build | Vite |

## 🚀 Getting Started

```bash
git clone https://github.com/Emrebym/Estate-App.git
cd Estate-App
npm install
npm run dev
```

The app will be available at `http://localhost:5173`

## 📝 License

MIT
