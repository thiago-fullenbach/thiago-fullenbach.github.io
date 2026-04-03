---
layout: post
title: DroidDissect
---

Android application designed to analyze APK files and identify potential security risks before installation.
Focused on helping users make safer decisions when dealing with unknown or external APKs.

🔗 **GitHub:** [View Repository](https://github.com/thiago-fullenbach/DroidDissect)

### 🚀 Features
- Analyze APK files (local)
- Detection of common security risks:
  - `allowBackup` enabled
  - `debuggable` flag active
  - `usesCleartextTraffic` (HTTP allowed)
- Clear report with findings categorized by risk level
- History of previous analyses stored locally
- Modern UI built with Jetpack Compose (Material 3)

### 🏗️ Architecture & Tech

- Kotlin
- Jetpack Compose (Material 3)
- Hilt (Dependency Injection)
- Room (local database)
- Coroutines & Flow (async handling)
- Timber (logging)
- Firebase Crashlytics

### ⚙️ Highlights
- User-focused approach: simple and direct risk visibility without technical complexity
- Lightweight and fully offline-capable
- Structured findings system with risk categorization
- Clean architecture separating UI, domain, and data layers
- Designed for extensibility with new security checkers

### 🔮 Future Improvements
- Expand risk detection (permissions, components, deeper APK inspection)
- Introduce overall security scoring system
- CI/CD pipelines for automated testing and delivery
- Exportable analysis reports (PDF/JSON)

### 📱 UI Preview
<div style="display: flex; gap: 10px; flex-wrap: wrap;">
  <img src="./assets/droiddissect.png" width="300"/>
</div>