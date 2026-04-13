# Crypto Price Tracker Android App

This project is an Android application built with Kotlin using an MVVM-style architecture. It fetches Bitcoin price data from the CoinGecko API and displays filtered daily prices in a RecyclerView.

## Features
- Fetches Bitcoin price history from API
- Displays daily price entries in a list
- Uses RecyclerView with adapter
- Checks internet connectivity before loading data
- Shows last updated time
- Filters and sorts price data by date

## Architecture
- MVVM-style structure
- View: MainActivity
- ViewModel: MainViewModel
- Repository: CoinGeckoRepository
- Data/service/model separation

## Technologies
- Kotlin
- Android SDK
- MVVM
- RecyclerView
- Coroutines
- CoinGecko API

## Note
This project was created as a technical/demo task for practice and learning purposes.

## Author
Nirali Kachhadiya
