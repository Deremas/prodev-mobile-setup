# 📱 Mobile Development with React Native, TypeScript & Expo

![React Native](https://img.shields.io/badge/React_Native-2025-blue?style=for-the-badge&logo=react)
![Expo](https://img.shields.io/badge/Expo-Framework-black?style=for-the-badge&logo=expo)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript)
![NativeWindCSS](https://img.shields.io/badge/NativeWindCSS-Utility_Styling-38bdf8?style=for-the-badge&logo=tailwindcss)

---

## 📖 Overview

This repository contains a collection of **mobile development projects** built using **React Native**, **Expo**, **TypeScript**, and **NativeWindCSS**.  

It helps new developers learn how to build **cross-platform mobile applications** for **iOS** and **Android** using modern tools and frameworks.  
Each project introduces new concepts — from setup and styling to navigation, UI components, and layout handling.

---

## 🧩 Tech Stack

- **Framework:** [Expo](https://expo.dev)  
- **UI Library:** React Native + NativeWindCSS  
- **Language:** TypeScript  
- **Icons:** Expo Vector Icons (Ionicons, FontAwesome)  
- **Testing Device:** Expo Go App (Android / iOS)

---

## ⚙️ Setup Instructions

### Prerequisites

Ensure you have these installed on your system:

- **Node.js LTS (v16 or higher)**
- **Expo CLI**
  ```bash
  npm install -g expo-cli
```

### 🧰 Prerequisites

Before running this project, make sure you have the following installed:

- **VS Code** or any other modern code editor  
- **Expo Go App** for testing on your device  
  - 📱 [Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent) (Android)  
  - 🍎 [App Store](https://apps.apple.com/app/expo-go/id982107779)

### 📂 Repository Structure
```bash
prodev-mobile-setup/
│
├── prodev-mobile-app-0x00/    # Setup & first app using Expo Router
│   └── app/(tabs)/index.tsx
│
├── prodev-mobile-app-0x01/    # Basic components and styling
│   └── app/index.tsx
│
├── prodev-mobile-app-0x02/    # Safe areas, images & touchables
│   └── app/index.tsx
│
├── prodev-mobile-app-0x03/    # Core components & login screen UI
│   ├── app/index.tsx
│   ├── app/_layout.tsx
│   ├── styles/index.tsx
│   └── assets/images/
│       ├── logo.png
│       ├── google.png
│       ├── facebook.png
│       ├── splash.png
│       └── background-image.png
│
└── README.md
```
### 📱 Key Learning Highlights
 - Setup and testing with Expo Go
 - Building apps using Expo Router
 - Using React Native core components (View, Text, Image, TouchableOpacity)
 - Styling with StyleSheet and NativeWindCSS
 - Using SafeAreaView and SafeAreaProvider
 - Managing layouts, buttons, and background images
 - Designing a login screen and reusable UI components

 ### 🧠 Example Command Flow
 ```bash
 # Navigate into a project folder
cd prodev-mobile-setup

# Start Expo development server
npx expo start

# Optional: reset template
npm run reset-project
```
