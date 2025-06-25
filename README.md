# Unsplash_Photo_Browser


An Android app built with **Kotlin** that allows users to search and view high-quality photos from the Unsplash API.

## Features

- Search for photos by keyword using the Unsplash REST API
- Display results in a smooth, scrollable 2-column grid using `RecyclerView`
- View selected photos in full-screen mode via fragment navigation
- Persistent navigation with saved state using `ViewModel` and `LiveData`
- Glide image loading with placeholders and error handling
- Graceful handling of network failures and loading errors
- Maintains search results and scroll position across orientation changes

## Tech Stack

- **Language:** Kotlin
- **Networking:** Retrofit, Moshi
- **UI:** RecyclerView, Glide, ConstraintLayout
- **Architecture:** ViewModel, LiveData, Jetpack Navigation
- **API:** [Unsplash API](https://unsplash.com/documentation)


## Getting Started

1. Download the zip file from GitHub.
2. Unzip the downloaded file.
3. Open the project in Android Studio.
4. Build and run the app on an emulator or physical Android device.
