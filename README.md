<div align="center">

# 🌍 Wildfire Tracker

### Explore wildfire activity on an interactive map

[![React](https://img.shields.io/badge/React-Application-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Google Maps](https://img.shields.io/badge/Google%20Maps-Map%20Visualization-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)](https://developers.google.com/maps)
[![NASA API](https://img.shields.io/badge/NASA-Open%20Data-0B3D91?style=for-the-badge&logo=nasa&logoColor=white)](https://api.nasa.gov/)

**A React-based project for visualizing wildfire locations on a Google Map, using NASA's public API as a data source.**

[View Source Code](https://github.com/manvendrasingh19/wildfire-tracker)

</div>

---

## 🔎 Overview

Wildfire Tracker brings wildfire information into a map-based interface. The project combines a React application, Google Maps visualization, and NASA API data to help users explore reported wildfire locations geographically.

## ✨ Project Focus

- **Map-based exploration:** View wildfire locations in a geographic context.
- **External data integration:** Use NASA's public API as a wildfire data source.
- **Interactive frontend:** Build the experience as a React application.
- **Geospatial visualization:** Present location-based information on Google Maps.

## 🧰 Technology

| Technology | Purpose |
|---|---|
| React | User interface |
| Google Maps | Map visualization |
| NASA API | Wildfire data source |
| JavaScript | Application logic |

## 🚀 Getting Started

### Prerequisites

- Node.js and npm
- A Google Maps API key
- A NASA API key from [api.nasa.gov](https://api.nasa.gov/)

### Install dependencies

```bash
git clone https://github.com/manvendrasingh19/wildfire-tracker.git
cd wildfire-tracker
npm install
```

### Configure API keys

The existing project instructions place the Google Maps key in the `Map.js` component and require a NASA API key. Before deploying or sharing a public build, move credentials into an appropriate environment-based configuration and restrict browser keys to the required APIs and domains. Never commit private credentials.

### Run locally

```bash
npm start
```

### Create a production build

```bash
npm run build
```

## 🗺️ How It Fits Together

```text
NASA API
   │
   ▼
React application
   │
   ▼
Google Maps visualization
   │
   ▼
Explore wildfire locations
```

## 🛣️ Possible Next Steps

- Add filters for date, intensity, or event category when supported by the data source.
- Provide a detail panel for a selected map marker.
- Add loading, empty, and API-error states.
- Move API configuration out of source files and document deployment setup.
- Add screenshots and a short walkthrough of the interface.

## 👨‍💻 Project

Maintained in [Manvendra Singh's GitHub repositories](https://github.com/manvendrasingh19).

[Open repository](https://github.com/manvendrasingh19/wildfire-tracker)

---

<div align="center">

*Mapping data. Understanding events. Building useful tools.*

</div>
