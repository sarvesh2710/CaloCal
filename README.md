# 🥑 CaloCal - Daily Calorie Tracker

CaloCal is a beautiful, intuitive, and mobile-first daily calorie tracking application. It features a stunning modern UI, fully automatic daily macro calculations, a built-in interactive food database, and seamless dynamic grouping of meals across Breakfast, Lunch, Snacks, and Dinner.

Built completely from scratch using purely native web technologies!

## ✨ Key Features
- **App-like Aesthetic Design:** Crafted primarily for mobile interfaces with custom fonts (*Inter*), soft shadows, and dynamic pill-styling. 
- **Dark Mode Support:** A gorgeous, built-in dark theme toggle that switches seamlessly and is persistent across sessions.
- **Dynamic Semicircular Tracker:** Watch your calorie intake fill a custom SVG semi-circle gauge in real-time as you add foods.
- **Cart-style Food Library:** A built-in modal database of popular foods. Users can add or subtract serving quantities manually before committing them to a meal.
- **Smart Grouping & Macros:** Repeated selections (like "Dosa x4") automatically group themselves beautifully whilst effortlessly tracking exact quantities of Protein, Carbs, Fats, **and** Fibre!
- **Persistent Local Storage:** The application operates entirely inside the user's browser securely, relying purely on LocalStorage. No database or internet connection required!

## 💻 Tech Stack
- **HTML5:** Pure native skeletal construction.
- **Vanilla CSS3:** Highly responsive styling utilizing CSS variables for theme-switching.
- **Vanilla JavaScript:** Clean, framework-free state management spanning data ingestion, UI manipulation, and local persistence.
- **CapacitorJS:** Bridging the web code to fully native Android architectures.

## 📱 How to Run Native Android Locally
Because CaloCal uses [Capacitor](https://capacitorjs.com/), packing this into an `.apk` is simple:
1. Ensure the `www/` directory contains your updated `index.html` and `images/`.
2. Run `npm install` in your terminal to fetch Capacitor's core files.
3. Run `npx cap sync android` to inject your web updates perfectly into the native package.
4. Run `npx cap open android` to boot up Android Studio.
5. Hit the **"Play"** button to start the emulator, or go to `Build > Build Bundle(s) / APK(s) > Build APK(s)` to pull the raw install file!

## 🤝 Contributing
Since this application relies heavily on its internal `foodDatabase` Javascript array, one major opportunity for impact is significantly expanding the dataset with new meals, snacks, and precise macros!

---
*Created meticulously with vanilla web development.*
