# 🌍 SierraMaps - Free & Open Geospatial API Platform

**SierraMaps** is a robust, developer-friendly platform offering free and scalable Maps APIs. Designed with accessibility, performance, and flexibility in mind, it provides a wide range of geolocation, routing, and real-time data services — ideal for developers, startups, students, and research projects.

---

## 💡 Why SierraMaps?

Most commercial mapping platforms limit developers with restrictive quotas and high pricing.  
**SierraMaps offers a generous free tier of 1 million requests per user per month** — with no payment information required.

SierraMaps is built to **enable innovation** without barriers, giving every developer access to high-quality mapping and spatial tools, completely free.

---

## 🚀 Core Features

| Feature                     | Description                                                                              | Endpoint Format                                                                                      |
|----------------------------|------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| 🔍 **Geocoding**            | Convert address text to latitude and longitude                                           | `/api/geocoding/<address>/?api_key=`                                                                 |
| 📍 **Reverse Geocoding**    | Get address details from latitude and longitude                                          | `/api/reverse_geocoding/<lat>,<lng>/?api_key=`                                                       |
| 🗺️ **Routing & Directions** | Find routes between two points with time and distance details                            | `/api/route/<lat1>,<lng1>/<lat2>,<lng2>/<max_sol>/?api_key=`                                        |
| 📏 **Elevation Data**       | Get the elevation (altitude) of any coordinate                                           | `/api/elevation/<lat>,<lng>/?api_key=`                                                               |
| 🧭 **Places API (POI)**     | Fetch nearby Points of Interest (POIs) using a bounding box query                        | `/api/spatialdata/?south=<>&west=<>&north=<>&east=<>&top=<>&api_key=`                               |
| 🌦️ **Real-Time Weather**    | Retrieve current weather details (temperature, wind, humidity, etc.) by coordinates     | `/api/weather/<lat>/<lng>/metric/?api_key=`                                                          |
| 🚧 **Traffic Incidents**    | Get real-time traffic incident data within a specific area                              | `/api/traffic/<south>/<west>/<north>/<east>/?api_key=`                                               |
| 🌐 **Timezone API**         | Get the local timezone information of any coordinate                                    | `/api/timezone/<lat>,<lng>/?api_key=`                                                                |

---

## 📦 Use Cases

- 🧭 Navigation and routing apps
- 🏙️ Smart city and IoT systems
- ☁️ Real-time weather monitoring
- 🚦 Traffic alert systems
- 🧠 Educational and research tools
- 🗺️ Custom geospatial analytics dashboards
- 💼 Business directories and local search engines

---

## 📁 Examples

You’ll find working HTML demos inside the `web/` folder. These examples are designed using **Bootstrap** and **Leaflet.js** to showcase real-time functionality of SierraMaps APIs.

### ✅ Available Examples

| File                                  | Description                                                 |
|--------------------------------------|-------------------------------------------------------------|
| `PlacesWithRealtimeWeather.html`     | 📌 Shows nearby POIs + real-time weather for each location  |
| `RouteWithRealtimeTrafficIncident.html` | 🛣️ Routes between two points with real-time traffic alerts |
| `RoutesAndElevation.html`            | 📐 Shows routes and elevation profiles along the path       |

Each example can be opened directly in the browser and requires an **API key**, which can be appended to the URL as `?api_key=YOUR_API_KEY`.

---

## 📜 API Authentication

All SierraMaps endpoints require an API key to function.

To use:
```
https://sierramaps.ftp.sh/api/route/12.9716,77.5946/13.0827,80.2707/1/?api_key=YOUR_API_KEY
```

## 📬 Contact & Contribution

Want to contribute, collaborate, or ask a question?

**Developer:** [Ojas Gupta](mailto:sierramapsdev@gmail.com)  
**Website:** [sierramaps.ftp.sh](https://sierramaps.ftp.sh)

PRs, suggestions, and feature requests are always welcome.  
Let’s build the **future of free and open maps** — together.
