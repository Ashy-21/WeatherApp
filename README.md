# 🌦️ WeatherApp

A sleek and **minimalistic weather application** built using **React Native CLI (TypeScript)**.
WeatherApp delivers real-time weather updates through a beautiful, modern UI featuring customizable themes, intuitive navigation, and offline-safe design.

---

## 🌟 Highlights

* ⚡ Built with **React Native CLI (TypeScript)** for native performance
* 📍 Real-time weather updates based on user location
* 🎨 Dual theme support — Light & Dark
* 🕹️ Fully responsive, touch-friendly UI
* 🔔 Integrated notification shortcut
* 🌐 Works smoothly on **Android** and **iOS**

---

## 🚀 Features

### 🏠 **Home Screen**

* Displays **current weather** with temperature, condition, and city name
* Shows **hourly forecast** and **upcoming daily forecasts**
* Modern layout with large, elegant typography
* Auto-detects location for instant updates

### 🔍 **Search Screen**

* Search any city instantly (results as you type)
* Pin and manage favorite locations
* Tap on cities for detailed weather data
* Displays pinned and searched cities as stylish cards

### ⚙️ **Settings Screen**

* **Customization:** Choose font styles with live previews and switch between °C / °F
* **Themes:** Toggle between Dark (default) and Light modes
* **Privacy Policy:** Access privacy details
* **Notification Shortcut:** Tap 🔔 to navigate directly to “Privacy Policy”

---

## 🎨 Themes

| Theme                 | Background | Text Color |
| :-------------------- | :--------- | :--------- |
| 🌑 **Dark (default)** | Black      | White      |
| ☀️ **Light**          | White      | Black      |

Toggle easily from the **Settings Screen** using icons `theme-on.svg` / `theme-off.svg`.

---

## 🧠 Tech Stack

| Layer      | Technology                                 |
| ---------- | ------------------------------------------ |
| Framework  | React Native CLI (TypeScript)              |
| Navigation | React Navigation                           |
| State      | Context API                                |
| API        | Free Weather API (no API key required)     |
| UI         | SVG Icons, Custom Fonts, Responsive Layout |

---

## 🗂️ Folder Structure

```
WeatherApp/
├── assets/
│   ├── fonts/
│   └── icons/
├── src/
│   ├── api/                # Weather API integration
│   ├── components/         # Reusable UI components
│   ├── context/            # Theme & unit context providers
│   ├── navigation/         # App navigation setup
│   └── screens/            # Home, Search, Settings screens
├── android/
├── ios/
├── App.tsx
└── package.json
```

---

## 🪛 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Ashy-21/WeatherApp.git
cd WeatherApp
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Start Metro

```bash
npx react-native start
```

### 4️⃣ Run the App

**For Android:**

```bash
npx react-native run-android
```

**For iOS:**

```bash
npx react-native run-ios
```

---

## 🖼️ Assets

This project includes:

* 10+ custom fonts located in `/assets/fonts/`
* 15+ weather and UI icons located in `/assets/icons/`
* Supports both `.svg` and `.ttf` formats

If adding new assets:

```bash
# Add fonts to /assets/fonts/
# Update react-native.config.js if necessary
module.exports = {
  assets: ['./assets/fonts/'],
};
```

For older React Native versions:

```bash
npx react-native link
```

---

## 🌡️ Units & Fonts

* Default Unit: **°C**
* Alternative Unit: **°F**
* Font selection includes live horizontal scrolling previews in Settings.

---

## ⚙️ Developer Notes

* Uses no paid or API-key-restricted services
* Fully compatible with **Android & iOS**
* Designed for **scalable, modular development**
* Optimized for **performance** and **minimal dependencies**
* Easy to extend — add weather alerts, radar maps, or widgets

---

## 📜 License

This project is licensed under the **MIT License** — you’re free to use, modify, and distribute it.

---

## 👨‍💻 Author

**Asish Shaji**
📍 India
GitHub: [Ashy-21](https://github.com/Ashy-21)

> 💬 “A clean interface for clear skies — WeatherApp keeps you informed with style.”
