# Weather-App
🌤️ Weather App – Android (Kotlin)

A simple and clean Weather Forecast Android App built using Kotlin, Retrofit, and OpenWeather API.
This project demonstrates my skills in Android development, API integration, UI design, and clean architecture.

**ABOVE WE CAN GIVE THE APK FILE MY ANDROID APPLICATION SO DOWNLOAD IT AND CHECK IT!**

🚀 Features :-

🔍 Search weather by city name
🌡️ Real-time temperature, humidity, wind speed, and weather conditions
☁️ Displays weather icons based on current conditions
📡 Uses Retrofit with async API calls
📱 Modern Android UI with View Binding

🛠️ Tech Stack :-

Category	Technology
Language	Kotlin
Architecture	MVVM (optional), View Binding
Networking	Retrofit2, Gson Converter
API Provider	OpenWeatherMap API
IDE	Android Studio

🔧 Requirements :-

Android Studio Iguana / Jellyfish or newer
Minimum SDK: 24
Internet connection
OpenWeather API Key

📦 How It Works :-

User enters a city name in the SearchView
App sends a GET request using Retrofit to the OpenWeather API
API returns JSON weather data
App displays temperature, humidity, wind speed, and condition
Weather image changes dynamically based on response

🏗️ Project Structure :-

app/
 ├── api/
 │    ├── ApiInterface.kt
 │    └── ApiUtilities.kt
 ├── model/
 │    └── WeatherModel.kt
 ├── ui/
 │    └── MainActivity.kt
 └── resources/
      ├── layout/
      └── drawable/

📌 Future Enhancements :-

🌍 Auto-detect location (GPS)
📊 7-day forecast
🎨 Light/Dark theme
💨 Air quality index (AQI)

🤝 Contributions :-

Pull requests are welcome.
If you find a bug or want a feature, create an issue.
