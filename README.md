## StocksETFS

## About the Project
This Android application provides users with real-time data and insights into stocks and ETFs. It includes two main screens and utilizes the Alpha Vantage API for data fetching.


### Explore Screen
- Displays Top Gainers and Losers in separate tabs.
- Each tab features a grid of cards with detailed stock/ETF information.


### Details Screen
- Shows basic information and a price line graph for selected stocks/ETFs.
  <br>
<img src="https://github.com/user-attachments/assets/6d2419f7-5a39-4dfe-9460-1b2195675a2d" width="200" height="450">


## Demo
<img src="https://github.com/user-attachments/assets/e28fad4f-0f91-4cc0-8464-ec939aa4cd5e" width="200" height="450">
https://github.com/user-attachments/assets/d7c32344-7ad2-4041-be31-3e1214c32fc1






## Features

- **API Integration**: Utilizes [Alpha Vantage](https://www.alphavantage.co/support/#) for data endpoints and [Api Ninjas](https://api-ninjas.com/api/logo) For logo .
- **Error Handling**: Manages loading, error, and empty states effectively.
- **Caching**: Implements API response caching using [Room](https://developer.android.com/training/data-storage/room) with expiration.
- **Dependency Injection**: Uses dependency injection for efficient management (Kotlin + Android).
- **UI/UX**: Includes a basic yet intuitive user interface.


## Technologies Used
- Kotlin (Android)
- Jetpack compose
- Graph [MpAndroidChart](https://github.com/PhilJay/MPAndroidChart)
- Alpha Vantage API
- [Api Ninjas](https://api-ninjas.com/api/logo) For logo 

## Getting Started

To run the app:

1. Clone the repository.
2. Generate an API key and replace it in the app. Place it in `local.properties` like this:
```
sdk.dir= ...
STOCK_API_KEY= ...
LOGO_API_KEY= ...
```
3. Apis can be generated from here [STOCK_API_key](https://www.alphavantage.co/support/#) and [LOGO_API_KEY](https://api-ninjas.com/profile)
4. Build and run the app on an Android device or emulator.

## Tech Stack

- **Kotlin:** For development
- **Android Studio:** The integrated development environment (IDE) for Android app development.
- **Compose:** an open-source, Kotlin-based toolkit for building native Android user interfaces (UIs)
- **Dependency Injection:** Employed for efficient management of app dependencies.
- **MVVM (Model-View-ViewModel):** Architecture pattern for separating UI from business logic.

Thankyou 



