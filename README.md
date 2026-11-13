# Description

This is a pretty basic weather app done as a course end project. It is an Android application that uses OpenMeteo weather API to get weather data, and OpenStreetMap to display a map to select locations from. The app has one day and seven day forecast, and a graph for the temperature of the next 24 hours.
Due to time issues and technical priorities I ended up not having time to finish some features like the favourites page or dark/light mode. The UI is pretty bad at places but this was never my focus.

The app uses the following for it's main features:

- OpenStreetMap: https://www.openstreetmap.org/
- OpenMeteo weather API: https://open-meteo.com/
- OpenMeteo Geocoding API: https://open-meteo.com/en/docs/geocoding-api

## Requirements

To run this app, install the .apk file included in the releases section on an Android SDK34+ device ( Android 14+ ).

## Permissions

The app requires internet and location permissions to function properly.

## Libraries and Frameworks Used

- **Kotlin**: The primary language used for development.
- **Gradle**: Used for dependency management and build automation.
- **Android Jetpack Compose**: Primary UI toolkit used to build the interfaces for the application.
- **Ktor**: Used for making network requests and handling responses.
- **Kotlinx Serialization**: Used for serializing and deserializing JSON data.
- **Room**: Used for data persistence. SQLite based database.
- **Kotlin Coroutines**: Used for managing background threads.
- **Osmdroid**: OpenStreetMap - Used for displaying and interacting with a map.
- **Lottie**: Animating Lottie files in the application.
- **Animated Weather Icons**: Lottie icons by basmilius (https://basmilius.github.io/weather-icons/)
- **Accompanist Swipe Refresh**: Provides a SwipeRefresh layout for Jetpack Compose.
- **Vico**: Used for creating graphs in Jetpack Compose.

## Images

![image](https://github.com/user-attachments/assets/bbba24fd-53bf-4c25-a5ac-6be692781679)
![image](https://github.com/user-attachments/assets/bd4b165f-5319-4952-96a9-b8f276e0f3d4)
![image](https://github.com/user-attachments/assets/20931d94-535f-4edf-81d0-477c3720fbcf)
![image](https://github.com/user-attachments/assets/df2f8219-e1a6-49bc-af77-3a80395135a2)
