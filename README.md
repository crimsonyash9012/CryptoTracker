# 📈 Crypto Tracker App

A simple yet powerful Crypto Tracker App built with Jetpack Compose that fetches real-time cryptocurrency data from the CoinCap API and displays it in a user-friendly UI. The app follows clean architecture principles and uses Koin for dependency injection.
The app is built with the help of the course The Best Practice Guide to Android Architecture

## 🚀 Features

Fetch real-time cryptocurrency prices from CoinCap API.

Display a list of cryptocurrencies with their name, symbol, price, and percentage change.

Smooth UI built with Jetpack Compose.

Dependency Injection using Koin for better architecture.

Efficient state management.

Light and Dark theme support.

## 🛠️ Tech Stack

Language: Kotlin

UI: Jetpack Compose

Dependency Injection: Koin

Networking: Retrofit + Gson

State Management: ViewModel + LiveData

## 📦 API Used

The app fetches real-time cryptocurrency data from CoinCap API:

Base URL: https://api.coincap.io/v2/

Endpoint: /assets (Fetches cryptocurrency list and prices)

## 📸 Screenshots

Include screenshots of your app here

## 🏗️ Project Structure

com.example.cryptotracker
│── di (Koin modules)
│── model (Data classes for API response)
│── network (Retrofit API service)
│── repository (Handles API calls and caching)
│── ui (Jetpack Compose UI components)
│── viewmodel (Handles UI logic)
│── MainActivity.kt

## 🔧 Installation

Clone the repository:

git clone https://github.com/yourusername/CryptoTrackerApp.git

Open the project in Android Studio.

Build and run the app on an emulator or physical device.


## 💡 Future Enhancements

Implement search functionality.

Add a favorites feature to track selected coins.

Include historical price charts.

Improve UI animations.
