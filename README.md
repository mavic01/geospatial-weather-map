# 🌍 Geospatial Weather Map

*A weather map built by a geographer who codes.*

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://your-portfolio.vercel.app/weather-map)
[![Leaflet](https://img.shields.io/badge/leaflet-1.9.4-green)](https://leafletjs.com/)

![Map Preview](https://ibb.co/5g5hfj3Z)

## 🗺️ What Is This?

This is an interactive weather map that shows real-time precipitation data. I built it to bring together two things I genuinely love: **weather observation** and **frontend development**.

The blue overlay you see over the United States is live MRMS (Multi-Radar Multi-Sensor) data—the same kind of weather radar information I first learned to interpret during my training at the Nigerian Meteorological Agency (NIMET).

## 👨‍💻 Who Built This?

I'm Victor Iberi:

- **MSc in Geography** – University of Ibadan, 2018
- **Frontend Engineering Diploma** – AltSchool Africa, 2025
- **Weather Observer Training** – NIMET (during my undergraduate SIWES program)

I've spent the last few years learning to code, and this project is me finally connecting my geography background with my frontend skills.

## ✨ What Can It Do?

Right now:

- **Live precipitation radar** over the US (updated every 5–10 minutes from Iowa Environmental Mesonet)
- **Multiple base layers** – switch between satellite view, dark theme, street maps
- **Interactive markers** – click to see sample weather station data
- **Real-time coordinates** – move your mouse and watch the lat/lng update
- **GeoJSON layers** – points, lines, and polygons to demonstrate geospatial data handling
- **Layer controls** – toggle everything on and off

## 🛠️ Built With

- **Leaflet.js** – the heart of the map
- **WMS** – for pulling live weather raster data
- **HTML, CSS, JavaScript** – no frameworks, just vanilla code
- **MRMS data** – from Iowa Environmental Mesonet (free and reliable)
- **GeoJSON** – for geographic features

## 🚀 Live Demo

[https://your-portfolio.vercel.app/weather-map](https://your-portfolio.vercel.app/weather-map)

## 📦 Running It Locally

This is a static site—no build steps, no package managers, nothing to install.

```bash
git clone https://github.com/victoriberi/geospatial-weather-map.git
cd geospatial-weather-map
