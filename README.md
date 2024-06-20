# Clima Weather App ☀️🌧

Clima is a sleek and simple weather app that provides current weather information. It utilizes the OpenWeatherMap API to fetch real-time weather data based on your current location or a city of your choice. Whether you're planning your day or just curious about the weather in a new city, Clima has you covered.

## Features 🌟

- **Current Location Weather**: Automatically fetches and displays the weather of your current location using GPS.
- **Search by City**: Allows you to manually search for a city and view the weather there.
- **Weather Details**: Shows temperature, weather condition, and custom messages based on the weather (e.g., "It's 🍦 time" for hot days).
- **Simple and Clean UI**: Easy to navigate interface with a beautiful background that reflects the current weather condition.

## How to Use 🛠

To use the Clima Weather App, follow these steps:

1. Clone the repository to your local machine:
```bash
git https://github.com/Mohanish-25/clima.git
```

2. **Navigate to the project directory:**

```bash
cd clima
```

3. **Install dependencies:**

Make sure you have Flutter installed on your machine. Then, run the following command:

```bash
flutter pub get
```

4. **API Key 🔑**

Get an API key from [OpenWeatherMap](https://openweathermap.org/api) and add it to your `.env` file as `API_KEY`.

```bash
API_KEY=your_openweathermap_key_here
```

5. **Run the app:**

Connect your device or use an emulator, then execute:

```bash
flutter run
```

## Dependencies 📦

- `http` for network requests
- `geolocator` for fetching the current location
- `flutter_dotenv` for managing environment variables

Stay weather-aware with Clima! ☔️☀️