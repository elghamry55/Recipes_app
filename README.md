# Recipes App

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/Dio-00A98F?style=for-the-badge" alt="Dio" />
  <img src="https://img.shields.io/badge/Cubit-764ABC?style=for-the-badge" alt="Cubit" />
</p>

A Flutter application for discovering recipes using data from the [DummyJSON Recipes API](https://dummyjson.com/recipes). The app retrieves recipe information and presents it through a dedicated recipes experience.

## Features

- Fetch recipe data from the DummyJSON API.
- Display recipe information and images.
- Present ingredients and cooking instructions.
- Show recipe ratings and preparation/cooking time data.
- Manage recipe loading state using Cubit.

## Technology Stack

| Technology | Usage |
| --- | --- |
| Flutter & Dart | Cross-platform mobile application |
| Dio | HTTP requests to the recipes API |
| flutter_bloc / Cubit | Application state management |
| DummyJSON Recipes API | Recipe data source |

## Getting Started

### Requirements

- Flutter SDK
- Dart SDK compatible with the project's `pubspec.yaml`
- Android Studio, VS Code, or another Flutter-supported IDE

### Run locally

```bash
git clone https://github.com/elghamry55/Recipes_app.git
cd Recipes_app
flutter pub get
flutter run
```

## API

The application requests recipe data from:

```
https://dummyjson.com/recipes
```

## Developer

**Mahmoud Elghamry** · Flutter Developer
