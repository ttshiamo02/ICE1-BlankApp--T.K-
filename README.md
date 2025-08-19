# My First Expo React Native App

A simple "Hello World" React Native application built with Expo, displaying a personalized greeting message.

##  App Overview

This is my first React Native application created as part of learning mobile development. The app displays a simple greeting message with my name on the screen.

##  Features

- Displays personalized greeting: "Hello, Tshiamo!"
- Clean, centered layout with custom styling
- Cross-platform compatibility (iOS, Android, Web)

##  Technologies Used

- **React Native**- Mobile app framework
- **Expo** - Development platform and tools
- **TypeScript** - Type-safe JavaScript
- **React** - UI library

##  Prerequisites

Before running this app, make sure you have:

- Node.js (version 16 or later)
- Expo Go app on your mobile device OR an emulator/simulator

## 🔧 Installation & Setup

1. **Clone the repository**
   git clone https://github.com/ttshiamo02/my-app.git
   cd my-app
 
3. **Start the development server**
   npx expo start
  

4. **Run the app**
   - **On physical device**: Open Expo Go app and scan the QR code
   - **On iOS Simulator**: Press `i` in the terminal
   - **On Android Emulator**: Press `a` in the terminal
   - **On Web**: Press `w` in the terminal

##  Running on BlueStacks

If you're using BlueStacks Android emulator:

1. Install Expo Go from Google Play Store within BlueStacks
2. Enable Developer Options and USB Debugging
3. Use the QR code or enter the development server URL manually

##  Project Structure


my -app
├── App.tsx              # Main application component
├── app.json            # Expo configuration
├── package.json        # Dependencies and scripts
├── babel.config.js     # Babel configuration
├── assets/            # Images and static files
└── README.md          # Project documentation
```

## Key Code

The main greeting is displayed in `App.tsx`:

```typescript
export default function App() {
  return (
    <View style={styles.container}>
      <Text style={styles.greeting}>Hello, [Your Name]!</Text>
      <StatusBar style="auto" />
    </View>
  );
}
```

## Learning Objectives Achieved

- [x] Successfully set up Expo development environment
- [x] Created and modified React Native components
- [x] Applied basic styling with StyleSheet
- [x] Tested app on emulator/device
- [x] Version controlled with Git and pushed to GitHub
