# EcoRoute Analytics 🌱

A web-based eco-friendly route finder that estimates travel distance, time,
fuel cost, and CO₂ emissions using free OpenStreetMap-based APIs (Nominatim + OSRM).

## Tech Stack
- PHP (Core, procedural)
- MySQL
- Leaflet.js + OpenStreetMap
- HTML/CSS/JS

## Features
- User registration & login (bcrypt password hashing)
- Route search with real map + directions
- Fuel cost & CO₂ emission calculator
- Eco Score rating
- Route history
- Admin panel (manage users, trips, analytics)

## Setup
1. Import `database/ecoroute.sql` into MySQL.
2. Update credentials in `includes/config.php`.
3. Place project in `htdocs` (XAMPP) and run via `localhost/EcoRoute`.
4. Admin login: `admin / admin123`

## Future Scope
- Live traffic updates
- Weather integration
- EV route support
- Mobile app