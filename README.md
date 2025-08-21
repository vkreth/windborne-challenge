# windborne-challenge

This project is my submission for the Windborne Systems Flight Team Web Developer role.

🚀 What it does

Fetches live balloon positions from Windborne’s constellation API (00.json = now, 01.json = 1 hour ago, etc.).

Combines the balloon data with Open-Meteo (free weather API).

Shows each balloon on an interactive world map (Leaflet + OpenStreetMap).

Click a balloon to see current weather at its location (temperature, wind speed, direction).

Displays the last 24 hours of history as faded dots (darker = more recent).

Auto-refreshes every 5 minutes.

🛠 How it works

Plain HTML + JavaScript + Leaflet (no frameworks).

Hosted with GitHub Pages at:
👉 Live Demo

📡 Why Open-Meteo?

I chose Open-Meteo because:

It’s free and doesn’t need an API key.

Provides reliable weather by latitude/longitude.

Complements balloon telemetry naturally (wind + temperature matter for flight).
