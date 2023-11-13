# Flutter Weather App

This is a simple Flutter weather app project developed for educational purposes. The app consumes a weather forecast API and utilizes a location permission plugin to provide weather information specific to the device's location.

## Features

- Display of current weather forecast
- Access to future forecasts
- Location permission for accurate information

## Technologies Used

- Flutter
- Dart
- [Location Permission Plugin Name](https://pub.dev/packages/geolocator)
- [Weather Forecast API Name](https://openweathermap.org/)

## How to Run the Project

1. Make sure you have Flutter installed. If not, follow the instructions at [flutter.dev](https://flutter.dev/docs/get-started/install).
2. Clone this repository: `git clone https://github.com/eduardosamorim/weather-app.git`
3. Navigate to the project directory: `cd weatherapp`
4. 
4. Run the app: `flutter run`

## API and Location Permission Plugin Configuration

Before running the app, ensure you configure the weather forecast API keys and location permissions in the configuration file. You can find more information on obtaining these keys in the links below:

Before running the app, you need to configure your API key in the `weather_page.dart` file.

1. Open the `lib/weather_page.dart` file in your code editor.
2. Locate the line with the API key:

    ```dart
    class _WeatherPageState extends State<WeatherPage> {
      // api key
      final _weatherService = WeatherService('SUA_CHAVE_API_AQUI');
      Weather? _weather;
    ```

3. Replace `'YOUR_API_KEY_HERE'` with your actual API key from the weather service provider.

4. Save the file.

- [Weather Forecast API Configuration](https://openweathermap.org/)
- [Location Permission Plugin Configuration](https://pub.dev/packages/geolocator)