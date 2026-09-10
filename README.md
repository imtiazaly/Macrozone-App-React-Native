# MacroZone 🥗💪

**MacroZone** is a sleek, modern React Native & Expo mobile application designed for effortless daily nutrition and macronutrient tracking. Track your daily intake of Calories, Protein, Carbs, and Fat with an intuitive dark-themed interface, instant haptic feedback, and local offline storage.

---

## 📱 App Screenshots

<div align="center">
  <img src="assets/projectPreview/home.PNG" height="550" alt="Home Dashboard" style="margin: 0 12px; border-radius: 12px;" />
  <img src="assets/projectPreview/add-meal.PNG" height="550" alt="Add Meal Screen" style="margin: 0 12px; border-radius: 12px;" />
  <img src="assets/projectPreview/All-meals.PNG" height="550" alt="All Meals Screen" style="margin: 0 12px; border-radius: 12px;" />
</div>

---

## ✨ Features

- **📊 Dynamic Macro Dashboard**: Track daily intake against target goals:
  - 🔴 **Calories**: Target ~ 2,000 kcal
  - 🔵 **Protein**: Target ~ 150g
  - 🟡 **Carbs**: Target ~ 250g
  - 🟢 **Fat**: Target ~ 65g
- **➕ Easy Meal Logging**: Quickly log meal details including meal name, calories, protein, carbs, and fat with real-time input validation.
- **📋 Recent & Full Meal History**:
  - View your 5 most recent meals directly on the homepage.
  - Explore complete meal history on the **All Meals** tab.
  - **Long Press to Delete**: Tap and hold any meal item to delete it with a confirmation prompt.
  - **Clear All**: Bulk clear all logged meals with a single tap.
- **📤 Copy & Share Summaries**:
  - **Copy Summary**: Instantly format and copy daily totals to clipboard.
  - **Share Summary**: Share your daily nutritional breakdown via native system share menu.
- **📳 Haptic Feedback**: Tactile responses powered by `expo-haptics` for actions like adding/deleting meals and copying data.
- **🔔 Meal Reminders**: Built-in daily reminder notifications (Lunch & Dinner) to help stay on track.
- **💾 Offline-First Local Storage**: All data is saved locally on device using `@react-native-async-storage/async-storage` for speed, privacy, and offline accessibility.
- **🌙 Dark UI Design**: Clean, high-contrast dark theme optimized for mobile screens.

---

## 🛠 Tech Stack

- **Framework**: [Expo](https://expo.dev) (v57) & [React Native](https://reactnative.dev)
- **Language**: TypeScript
- **Routing**: [Expo Router](https://docs.expo.dev/router/introduction) (File-based navigation)
- **State & Storage**: React Hooks & `@react-native-async-storage/async-storage`
- **UI & UX**: `@expo/vector-icons`, `expo-haptics`, custom responsive dark theme
- **Notifications**: `expo-notifications`
- **Utilities**: `expo-clipboard`

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/imtiazaly/Macrozone.git
   cd Macrozone
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npx expo start
   ```

4. **Run on device/emulator**:
   - Press `a` for Android Emulator
   - Press `i` for iOS Simulator
   - Scan QR code with Expo Go app (Android/iOS)

---

## 📁 Project Structure

```text
Macrozone/
├── assets/             # Project assets & preview screenshots
│   └── projectPreview/ # Screenshots used in documentation
├── src/
│   ├── app/            # Expo Router file-based screens ((tabs), layouts)
│   ├── components/     # Reusable UI components (MacroCard, MealItem, etc.)
│   ├── storage/        # AsyncStorage helpers for meal management
│   ├── styles/         # Global color palettes and shared styles
│   └── utils/          # Notifications & helper functions
├── package.json
└── tsconfig.json
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
