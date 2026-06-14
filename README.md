# SkyWatch — Weather Information System
## UNILAK HCI CAT Assessment 2026

### Overview
A Weather Information System built with HTML, CSS, and JavaScript (vanilla), integrating the OpenWeatherMap API to display real-time weather data.

---

### How to Run
1. Extract the ZIP folder
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge)
3. No server setup required — runs entirely in the browser

---

### Project Structure
```
weather_system/
├── index.html          ← Guest user: weather search page
├── images/
│   └── bg.png          ← Background image
├── admin/
│   ├── login.html      ← Admin login page
│   └── dashboard.html  ← Admin dashboard
└── README.md
```

---

### Features

#### Guest User (No Login Required)
- Search weather by **City Name** (e.g. Kigali, London, New York)
- Search weather by **Latitude & Longitude** (e.g. -1.9441, 30.0619)
- Displays: Temperature, Weather Condition, Humidity, Wind Speed, Feels Like, Pressure, Visibility, Cloud Cover, Weather Icon, Date & Time

#### Administrator (Login Required)
- **Default credentials:** `admin` / `admin123`
- Secure login with error feedback
- Dashboard with overview statistics
- Full search history log
- Usage statistics with top-cities bar chart
- Manage records: delete individual or all records
- Logout functionality

---

### HCI Principles Applied
- **Visibility of System Status**: Loading indicators, success/error toast messages
- **Match Between System and World**: Intuitive icons, familiar weather terminology
- **User Control & Freedom**: Tab switching, back navigation, clear/delete options
- **Consistency & Standards**: Uniform color palette, typography, and layout patterns
- **Error Prevention & Handling**: Input validation, descriptive error messages
- **Recognition over Recall**: All options visible; no need to memorize commands
- **Aesthetic & Minimalist Design**: Clean glassmorphism UI with focused content

---

### API
- Provider: OpenWeatherMap
- Key: `4b9919c655a867d3bb739b1f6c37893f`
- Endpoint: `https://api.openweathermap.org/data/2.5/weather`

---

*UNILAK — Faculty of CIS, Software Engineering Dept. — 2026*
