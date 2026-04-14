# KU Travel 📍🍃

**Navigator Kasetsart** — A React Native mobile application designed to help students, staff, and visitors navigate the **Kasetsart University (Bang Khen campus)** with ease. Find buildings, get walking/bus directions, and track campus welfare bus routes — all in one app.

![React Native](https://img.shields.io/badge/React_Native-0.74.2-61DAFB?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?logo=node.js)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-lightgrey)

---

## 📖 Table of Contents

- [About](#about)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Database & Data Sources](#-database--data-sources)
- [Bus Lines](#-bus-lines)
- [Design Document](#-design-document)

[//]: # (- [Contributing]&#40;#-contributing&#41;)

[//]: # (- [License]&#40;#-license&#41;)

---

## About

KU Travel is a mobile campus navigation app built for **Kasetsart University, Bang Khen campus**. The app provides:

- **Building-to-building navigation** using Google Maps Directions API
- **Optimal campus bus route suggestions** (Lines 1, 3, and 5)
- **Interactive campus map** with geofencing to ensure all points stay within university boundaries
- **Bus route visualization** with polyline overlays and bus stop markers
- **Motorcycle taxi stand locations** around campus
- **Search & filter** buildings by faculty

The app intelligently recommends whether to **walk** or **take a campus bus** based on the distance and available bus routes between origin and destination.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗺️ **Interactive Campus Map** | Google Maps integration with KU campus boundaries enforced |
| 🔍 **Building Search** | Search & filter buildings by name or by faculty (16+ faculties supported) |
| 📍 **Origin/Destination Navigation** | Set origin & destination via text search, dropdown picker, or tap on map |
| 🚌 **Smart Bus Route Recommendation** | Automatically suggests the optimal bus line (1, 3, or 5) with fewest stops |
| 🚶 **Walking Directions** | Falls back to walking directions when bus is unnecessary (short distance) |
| 🔄 **Multi-Line Transfers** | Supports route planning that transfers between different bus lines |
| 🚏 **Bus Stop Visualization** | Displays bus stops on the map with color-coded line markers |
| 📍 **Current Location** | Uses GPS to set your current location as origin or destination |
| 🏍️ **Motorcycle Taxi Stands** | Shows locations of motorcycle taxi stands around campus |
| 🚌 **Bus Route Viewer** | Dedicated tab to view full bus routes (Lines 1–5) with polyline paths |
| ⏱️ **ETA & Distance** | Displays estimated travel time (minutes) and distance (km) |
| 🎯 **Geofencing** | Modal alert when selecting a point outside the university boundary |

---

## 📸 Screenshots

<!-- Add your screenshots here -->
> _Screenshots coming soon_

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | [React Native](https://reactnative.dev/) 0.74.2 |
| **Navigation** | React Navigation 5 (Bottom Tabs) |
| **Maps** | [react-native-maps](https://github.com/react-native-maps/react-native-maps) (Google Maps) |
| **Directions** | [react-native-maps-directions](https://github.com/bramus/react-native-maps-directions) (Google Directions API) |
| **Geolocation** | [react-native-geolocation-service](https://github.com/Agontuk/react-native-geolocation-service) |
| **Geo Utilities** | [geolib](https://github.com/manuelbieh/geolib) (distance calc, point-in-polygon, radius check) |
| **UI Components** | [NativeBase](https://nativebase.io/) 2.x, React Native Paper |
| **Icons** | [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) (Ionicons) |
| **Search** | [react-native-search-filter](https://github.com/AresPan/react-native-search-filter) |
| **Backend** | Node.js + Express (serves building data from MySQL) |

[//]: # (| **Database** | MySQL &#40;`final_project` database&#41; |)

---

[//]: # (## 📁 Project Structure)


### Detailed design documentation is available here:
[https://docs.google.com/document/d/1Bxr5clLstrgj5rJr1Tb00FW74aEL9XZwvIb_NOMsqI4/edit?usp=sharing](https://docs.google.com/document/d/1rPl4IxEUWnTWFHY5GkUhR4vOd9FK0FpxhYHUHAkT5d0/edit?usp=sharing)
