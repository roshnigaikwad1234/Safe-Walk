# 🚶 SafeWalk – Smart & Safe Route Planner

## 📌 Project Overview

SafeWalk is an intelligent route planning web application designed to help users choose safer routes while travelling. Unlike normal navigation applications that mainly focus on distance and travel time, SafeWalk also considers crime data while suggesting routes.

The application provides users with **Fastest** and **Safest** route options and displays crime-prone areas using an interactive heatmap. This helps users make better-informed decisions before starting their journey.

---

## ✨ Features Implemented

- 🗺️ **Interactive Map** – View locations, routes, and important map information.
- 🔥 **Crime Heatmap** – Visualize areas with higher crime levels.
- 🛡️ **Safest Route** – Suggest routes that reduce exposure to high-crime areas.
- ⚡ **Fastest Route** – Find the shortest/fastest available route.
- 🚶 **Multiple Transportation Modes** – Supports walking, cycling, and driving.
- 📍 **Location Search** – Search for starting and destination locations.
- 📌 **Custom Markers** – Clearly identify the starting point and destination.
- ⏱️ **Travel Information** – View estimated travel time and distance.
- 🧠 **AI Route Assistant** – Provides route guidance and safety recommendations.
- 🕐 **Route History** – Save and access previously searched routes.
- 📱 **Responsive Design** – Works across desktop and mobile screen sizes.

---

## 🛠️ Tech Stack

### Frontend
- Next.js 14
- React.js
- TypeScript
- Tailwind CSS

### Maps & Routing
- Leaflet.js
- React-Leaflet
- OpenStreetMap
- OSRM API
- Nominatim API

### Crime Data
- NYC Open Data
- NYPD Complaint Data

### Storage
- Browser Local Storage

### AI
- AI Route Assistant
- Weighted crime-scoring system

---

## 📂 Project Structure

```text
SafeWalk/
│
├── app/
├── components/
├── public/
├── styles/
├── package.json
├── package-lock.json
├── next.config.js
├── tsconfig.json
└── README.md
```

> The exact folder structure may vary depending on the project version.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Soulemane12/SafeWalk.git
```

### 2. Navigate to the Project Folder

```bash
cd SafeWalk
```

### 3. Install Dependencies

Using npm:

```bash
npm install
```

Or using Yarn:

```bash
yarn install
```

Or using Bun:

```bash
bun install
```

### 4. Configure Environment Variables

If the project requires API keys or environment variables, create a `.env.local` file in the project root.

Example:

```env
NEXT_PUBLIC_API_KEY=your_api_key_here
```

Replace the placeholder with the required credentials.

> Never upload private API keys or secret credentials to GitHub.

### 5. Run the Development Server

Using npm:

```bash
npm run dev
```

Or using Bun:

```bash
bun dev
```

### 6. Open the Application

Open the following URL in your browser:

```text
http://localhost:3000
```

---

## 🔑 Credentials / Setup Instructions

SafeWalk uses external services such as mapping, routing, geocoding, and crime-data APIs.

Before running the project, check whether the current project version requires any API keys or environment variables.

If required:

1. Create the required API credentials.
2. Add them to `.env.local`.
3. Do not commit `.env.local` to GitHub.
4. Restart the development server after adding or changing environment variables.

---

## 📊 How SafeWalk Works

The basic working process of SafeWalk is:

```text
User enters starting location
            ↓
User enters destination
            ↓
Location is converted into coordinates
            ↓
Routing API calculates available routes
            ↓
Crime data is analyzed around the routes
            ↓
Safety score is calculated
            ↓
Fastest & Safest routes are provided
            ↓
Routes are displayed on the interactive map
```

---

## 🛡️ Safety Score

SafeWalk uses crime information to calculate a safety score for routes.

Different types of crimes can have different levels of severity. The system uses a **weighted scoring approach** to give more importance to serious crimes.

The route with lower exposure to higher-risk crime areas can receive a better safety score.

> The SafeWalk safety score is an informational estimate and should not be considered a guarantee of personal safety.

---

## 🗺️ Crime Heatmap

The application displays crime information using a heatmap.

The heatmap helps users identify areas where reported crime levels are relatively higher or lower. This information is also considered while generating safer route recommendations.

---

## 🤖 AI Route Assistant

SafeWalk includes an AI Route Assistant that provides users with route-related guidance and safety recommendations.

It is designed to help users understand their route and make better decisions based on the available route and safety information.

---

## 📸 Screenshots

Add screenshots of the working application below.

### Home Page

```text
Add your screenshot here
```

### Route Planning

```text
Add your screenshot here
```

### Crime Heatmap

```text
Add your screenshot here
```

### Fastest & Safest Routes

```text
Add your screenshot here
```

### AI Route Assistant

```text
Add your screenshot here
```

To add an image stored in the repository, use:

```markdown
![SafeWalk Screenshot](./screenshots/home.png)
```

---

## 🌐 Deployment Link

**Live Demo:**  
Add your deployed SafeWalk link here.

Example:

```text
[https://your-safewalk-deployment-link.com](https://safe-walk-nu.vercel.app/route)
```

---

## 🚧 Current Limitations

- Crime data is currently focused on NYC Open Data.
- The available crime data may not represent the latest real-world situation.
- Safety scores depend on the quality and availability of crime data.
- The safety score cannot guarantee that a route is completely safe.
- Routing and location services depend on external APIs.
- The current prototype does not use a separately trained machine-learning model for crime prediction.

---

## 🚀 Future Scope

Future versions of SafeWalk can include:

- 🌎 Crime data from more cities and countries.
- 🤖 Machine-learning-based crime risk prediction.
- 🔔 Real-time safety alerts.
- 👥 Community-based safety reporting.
- 📱 Dedicated Android and iOS applications.
- 🚌 Public transportation integration.
- 🕐 Time-based safety prediction.
- ♿ Improved accessibility features.
- 📍 More personalized route recommendations.

---

## 📚 Data Sources

SafeWalk uses the following sources:

- **NYC Open Data / NYPD Complaint Data** – Crime-related information.
- **OpenStreetMap** – Map and geographic data.
- **OSRM** – Route calculation.
- **Nominatim** – Location search and geocoding.

---

## 🤝 Contributing

Contributions are welcome.

To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test the changes.
5. Commit your changes.
6. Create a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Project

**Project Name:** SafeWalk  
**Category:** AI / Smart Navigation / Personal Safety  
**Purpose:** Safety-aware route planning and navigation
