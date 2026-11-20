# Youmy

**A prayer-centered habit tracking and personal productivity app.**

Youmy is a cross-platform mobile application built with **React Native CLI and TypeScript**. Its goal is to help users stay consistent with their five daily prayers while building positive habits and organizing their everyday routines.

> **Status:** Early development. The React Native project has been initialized and launched successfully on the iOS Simulator. The features below are planned, not yet implemented.

## Vision

Youmy brings prayer tracking and personal productivity together in one daily experience. Rather than managing spiritual routines and everyday habits separately, users will be able to see and develop their consistency in one place.

## Planned Features

- **Daily prayers:** Track completion of the five daily prayers.
- **Habit tracking:** Create and manage recurring habits.
- **Daily overview:** See prayers and habits together.
- **Progress insights:** Review consistency over time.
- **Reminders:** Receive timely prompts for routines and activities.

## Tech Stack

| Technology | Role |
| --- | --- |
| React Native CLI | Cross-platform mobile application |
| TypeScript | Type-safe development |
| React | Component-based UI |
| CocoaPods | iOS native dependencies |

Additional libraries and services will be documented as they are added.

## Development Progress

- [x] Initialize React Native CLI project with TypeScript
- [x] Install iOS dependencies
- [x] Run the starter application in the iOS Simulator
- [ ] Define application architecture and navigation
- [ ] Design prayer and habit tracking screens
- [ ] Implement prayer tracking
- [ ] Implement habit management and local persistence
- [ ] Add progress insights and reminders
- [ ] Test and refine the experience

## Getting Started

### Prerequisites

Follow the [React Native environment setup guide](https://reactnative.dev/docs/set-up-your-environment). iOS development requires macOS, Xcode, and CocoaPods.

### Install

```bash
git clone https://github.com/mohammed-yassien15/Youmy.git
cd Youmy
npm install
```

### Run on iOS

```bash
cd ios
pod install
cd ..
npm start
```

In a second terminal:

```bash
npm run ios
```

### Run on Android

Start an Android emulator or connect a configured device, then run:

```bash
npm run android
```

## Roadmap

1. **Foundation:** App structure, navigation, reusable components and visual design.
2. **Core experience:** Prayer tracking, habit management and local data persistence.
3. **Insights:** Daily progress, consistency statistics and reminders.
4. **Quality:** Accessibility, testing, performance and UI refinements.

## Author

**Mohammed Yassien** — React Native Developer

[GitHub Profile](https://github.com/mohammed-yassien15)

---

*Youmy — Building better habits, one day at a time.*
