# Weather App

## Overview

The Weather App is a Flutter-based application that provides real-time weather information. It features a user-friendly interface displaying temperature, humidity, wind speed, and other weather conditions using visually appealing widgets.

## Features

- Displays current weather conditions with icons.
- Supports temperature, humidity, and wind speed indicators.
- Uses reusable widgets like `WeatherItem` for modular UI design.
- Implements gradient themes for a modern look.
- Easily customizable for additional weather metrics.

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/weather-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd weather-app
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Run the application:
   ```sh
   flutter run
   ```

## Usage

Use the `WeatherItem` widget to display weather details:

```dart
WeatherItem(
  value: 25,
  unit: '°C',
  imageUrl: 'assets/images/sunny.png',
)
```

## Requirements

- Flutter SDK installed
- API key from a weather service (if fetching real-time data)
- Correct image asset paths in the `pubspec.yaml` file

## Customization

- Modify theme colors in `Constants.dart`.
- Replace asset images with network images if needed.
- Add additional weather metrics as required.

## License

This project is open-source and can be modified as needed.

