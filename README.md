# MVVM News Application

A modern Android news application demonstrating a robust MVVM architecture. The app fetches live data from a REST API and persists it for offline access, highlighting key skills in modern Android development.

**Project Timeline:** January 2025 – April 2025.

## Key Features

- **Live Headlines:** Fetches and displays top headlines from the [NewsAPI.org](https://newsapi.org) service in real-time.
- **Search Functionality:** Users can search for articles on any topic.
- **Saved Articles:** Favorite articles can be saved for offline reading.
- **Web View:** Read full articles within the app via an integrated WebView.

## Tech Stack & Architecture

This project uses a modern technology stack and follows the recommended MVVM architecture pattern.

- **Language:** Kotlin
- **Architecture:** MVVM (Model-View-ViewModel)
- **Asynchronous Programming:** Kotlin Coroutines
- **Networking:** Retrofit2 (REST API communication)
- **Database:** Room (local data persistence for saved articles)
- **UI:** XML layouts, Android Views (RecyclerView with DiffUtil)
- **Navigation:** Jetpack Navigation Component
- **Image Loading:** Glide

## Setup

To run this project, please obtain your own API key from [NewsAPI.org](https://newsapi.org):

1. Sign up and get a free API key from NewsAPI.
2. Open the project in Android Studio.
3. In your `local.properties` file, add:
   ```
   apiKey="YOUR_API_KEY_HERE"
   ```
4. Build and run the app.
