# Emotica - React Native App

A beautiful daily mood tracking app built with **Expo** and **React Native**.

## Features

- 📊 **Mood Tracking** - Log your daily mood with 5 levels (Very Happy to Very Sad)
- 📝 **Journal Notes** - Add optional notes (up to 300 characters) to capture your day
- 🏷️ **Tags** - Categorize entries with tags like Work, Family, Health, etc.
- 📈 **Insights** - View mood trends with charts (daily, weekly, monthly, yearly)
- 🔥 **Streaks** - Track your consecutive logging days
- 🤖 **AI Analysis** - Get supportive AI insights powered by Gemini
- 💬 **AI Chat** - Talk to your wellness companion
- 🎨 **AI Art** - Generate mood-based vibe art
- 💾 **Backup** - Export/import your data
- 🔒 **Privacy** - All data stored locally on device

## Tech Stack

- **Framework**: Expo SDK 52
- **Language**: TypeScript
- **Styling**: NativeWind (Tailwind CSS for RN)
- **Navigation**: React Navigation
- **Storage**: AsyncStorage
- **Charts**: Victory Native
- **AI**: Google Generative AI (Gemini)

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)
- Android Studio (for Android) or Xcode (for iOS)

### Installation

1. Install dependencies:
   ```bash
   npm install
   ```

2. Set up environment variables:
   ```bash
   cp .env.example .env
   # Add your Gemini API key to .env
   ```

3. Start the development server:
   ```bash
   npx expo start
   ```

4. Run on your device:
   - Scan QR code with Expo Go app
   - Or press `a` for Android emulator
   - Or press `i` for iOS simulator

## Project Structure

```
mood-boost/
├── src/
│   ├── components/       # Reusable UI components
│   ├── screens/          # Screen components
│   │   ├── auth/         # Login, Register, Welcome
│   │   ├── main/         # Dashboard, Check-in, Insights
│   │   ├── ai/           # AI Chat, AI Image
│   │   └── settings/     # Settings, Help, Backup
│   ├── navigation/       # Navigation configuration
│   ├── services/         # API and storage services
│   ├── utils/            # Utility functions
│   ├── types/            # TypeScript definitions
│   └── theme/            # Colors and styling
├── app.json              # Expo configuration
├── tailwind.config.js    # NativeWind configuration
└── package.json
```

## Scripts

- `npm start` - Start Expo development server
- `npm run android` - Run on Android
- `npm run ios` - Run on iOS
- `npm run web` - Run on web browser

## License

MIT
