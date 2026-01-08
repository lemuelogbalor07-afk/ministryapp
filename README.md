# 📖 Ministry Master Ultra

A lightweight, privacy-focused web application for tracking field ministry activity. Designed for mobile use, this app allows you to log hours, manage a student directory, and sync data across devices.

## ✨ Features
* **⏱️ Smart Timer:** Track your service time with a live stopwatch.
* **☁️ Firebase Sync:** Securely sync your reports to the cloud using Google Authentication.
* **📊 Progress Tracking:** Visual progress bars for your monthly goals.
* **📓 Student Directory:** Manage your return visits and Bible studies with integrated notes.
* **📥 CSV Export:** Download your monthly report as a spreadsheet for easy submission.
* **🌓 Dark Mode:** Optimized for use in any lighting condition.

## 🚀 Getting Started
1.  **Host on GitHub Pages:** Upload `index.html` to a GitHub repository and enable "Pages" in the settings.
2.  **Firebase Setup:** * Create a project at [firebase.google.com](https://firebase.google.com/).
    * Enable **Google Auth** and **Firestore Database**.
    * Update the `firebaseConfig` object in `index.html` with your project credentials.
3.  **Install as PWA:** Open the URL on your phone and select "Add to Home Screen" to use it like a native app.

## 🔒 Privacy
All data is stored in your private Firebase instance. No data is shared with third parties.