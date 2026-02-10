# Emotica - Your Premium Mindful Companion

**Emotica** is a beautifully designed, high-performance mood tracking and wellness companion built with **Expo** and **React Native**. It focuses on a premium user experience with smooth animations, local-first privacy, and immersive wellness features.

## ✨ Features

- 📊 **Dynamic Mood tracking** - Log your vibe with a sleek, intuitive interface.
- � **Interactive Timeline** - View your emotional journey in a clean, scrollable timeline.
- 📈 **Wealth of Insights** - Visualize your patterns with beautiful bar and line charts powered by `react-native-chart-kit`.
- � **Zen Soundscape** - Immersive, high-quality audio environments for relaxation and focus.
- 🎮 **Tactile Games** - De-stress with custom-built interactive games like *Stress Pop* and *Phoenix Fly*.
- � **Smart Reminders** - A robust, time-neutral notification system that adapts to your logging habits.
- 🌐 **Privacy First** - All data is stored locally on your device using `expo-sqlite`. No cloud syncing required.
- � **Data Export** - Export your history as professional PDF reports or Excel spreadsheets.

## 🚀 Optimized Performance

- **Lightweight Build**: Optimized bundle sizes (~25MB AAB / ~38MB APK).
- **Asset Perfection**: All audio and high-resolution icons are compressed for fast loading and minimal disk footprint.
- **Vibrant UI**: Smooth 60fps animations powered by `react-native-reanimated` (Worklets enabled).

## 🛠 Tech Stack

- **Framework**: Expo SDK 54 (SDK 54)
- **Language**: TypeScript
- **Database**: `expo-sqlite` (Local persistent storage)
- **Animations**: `react-native-reanimated` v4
- **Icons**: Lucide & Ionicons
- **Audio**: `expo-av`
- **Charts**: `react-native-chart-kit`

## 📦 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

1. **Clone & Install**:
   ```bash
   npm install --legacy-peer-deps
   ```

2. **Start the Engine**:
   ```bash
   npx expo start -c
   ```

3. **Run on Device**:
   - Use **Expo Go** for rapid development.
   - For a production-ready experience, build an APK/AAB using EAS.

## 📂 Project Structure

```
emotica/
├── src/
│   ├── components/       # Reusable UI (Modals, Premium Cards, Charts)
│   ├── screens/          # Core views (Home, Journey, Insights, Games, Settings)
│   ├── navigation/       # Type-safe navigation stacks
│   ├── services/         # Storage (SQLite) and Notification logic
│   ├── theme/            # Centralized design system
│   └── types/            # TypeScript definitions
├── assets/               # Compressed high-res icons and splash screens
├── music/                # Optimized OGG/MP3 soundscapes
└── package.json          # Clean, dependency-optimized configuration
```

## 📜 License

MIT
