# 🌍 World History Map Project
## 📖 Overview

The World History Map is an interactive application that lets users explore world history day by day on a global map. Inspired by platforms like Running Reality, it combines historical events with dynamic geographic borders, allowing users to see how the world has evolved over time.

Users can pick a specific date (e.g., 28 July 1914) and instantly view:

🏴 Country borders as they were at that time.

🏙️ Cities and regions, with evolving boundaries and names.

📌 Historical events tied to specific locations.

📅 A timeline slider to animate changes across years, wars, and revolutions.

## 🎯 Goals

Provide an educational tool for students, teachers, and history enthusiasts.
Visualize geopolitical changes (borders, countries, cities) over time.
Link events to geography so users can understand where history happened.
Allow search and filtering by date, country, or theme (e.g., wars, discoveries, culture).

## 🛠️ Tech Stack
- Backend: Java Spring Boot (REST API for events, timeline data, user queries).
- Database: PostgreSQL (with Docker for containerized setup).
- Frontend: Angular + Leaflet.js (interactive map, timeline slider, event display).

#### Data:
- Open Historical Map (for borders and place names).
- Wikipedia/Wikidata (for events, linked by date & place).
- Custom curated datasets for testing.

## 🚀 Features (MVP)
- 🌍 World Map: Display entire world with zoom & pan.
- 📅 Timeline Slider: Move through years and watch borders/events change.
- 📌 Events Overlay: Show markers and popups for daily events.
- 🏳️ Dynamic Borders: Switch between modern and historical maps.
- 🔍 Search: Find specific countries, cities, or historical events.

## 🔮 Future Enhancements

- 🎞️ Animated playback of history (year-by-year progression).
- 📖 Thematic layers (wars, empires, culture, inventions).
- 🗂️ User-contributed events with moderation.

## 📌 Example Use Case

#### A user selects 28 July 1914. The app shows:
- Austria-Hungary declares war on Serbia.
- Bombing of Belgrade.
- France: Henriette Caillaux is acquitted.
- Sweden, Romania, Spain, Netherlands declare neutrality.
- Borders update to reflect Europe at the outbreak of WWI.
