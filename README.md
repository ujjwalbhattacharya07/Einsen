
![einsen_cover](https://user-images.githubusercontent.com/118751588/231177810-e56d1e10-42f0-491d-bdce-8081b19af8d4.png)

# 🎯 Einsen

Einsen is a prioritization app that uses Eisenhower matrix technique as workflow to prioritize a list of tasks. Designed for students for effective task management in between their academics and co-curricular activities.
 
 
 ***Try latest Einsen app apk from below 👇***

[![Einsen](https://img.shields.io/badge/Einsen-APK-black.svg?style=for-the-badge&logo=android)](https://github.com/Spikeysanju/Einsen/releases/download/v1.0.0-alpha04/Einsen.apk)

<br />

<br />

## 🌞 Day Mode

|   Dashboard    | All Tasks    |   Task Details   
|---	|---	|---
|  ![](https://github.com/Spikeysanju/Einsen/blob/master/art/dashboard_day.png)    |  ![](https://github.com/Spikeysanju/Einsen/blob/master/art/all_task_day.png)    |   ![](https://github.com/Spikeysanju/Einsen/blob/master/art/task_details_day_v2.png)    

|   Add Task  |   Emoji    | Empty State    |
|---    |---	|---	|
|   ![](https://github.com/Spikeysanju/Einsen/blob/master/art/add_task_day.png)    |   ![](https://github.com/Spikeysanju/Einsen/blob/master/art/choose_emoji_day.png)      |   ![](https://github.com/Spikeysanju/Einsen/blob/master/art/empty_state_day.png)

<br />

## 🌚 We Support Dark Mode Too

|   Dashboard    | All Tasks    |   Task Details      
|---	|---	|---		
|  ![](https://github.com/Spikeysanju/Einsen/blob/master/art/dashboard_night.png)    |  ![](https://github.com/Spikeysanju/Einsen/blob/master/art/all_task_night.png)    |   ![](https://github.com/Spikeysanju/Einsen/blob/master/art/task_details_night.png)      

|   Add Task  |   Emoji   | Empty State    |
|---    |---	|---	|
|   ![](https://github.com/Spikeysanju/Einsen/blob/master/art/add_task_night.png)  |   ![](https://github.com/Spikeysanju/Einsen/blob/master/art/choose_emoji_night.png)     |   ![](https://github.com/Spikeysanju/Einsen/blob/master/art/empty_state_night.png)

<br />

## 🛠 Built With

- [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android
  development.
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) -
  Collection of libraries that help you design robust, testable, and maintainable apps.
    - [Stateflow](https://developer.android.com/kotlin/flow/stateflow-and-sharedflow) - StateFlow is
      a state-holder observable flow that emits the current and new state updates to its collectors.
    - [Flow](https://kotlinlang.org/docs/reference/coroutines/flow.html) - A flow is an asynchronous
      version of a Sequence, a type of collection whose values are lazily produced.
    - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores
      UI-related data that isn"t destroyed on UI changes.
    - [Jetpack Compose Navigation](https://developer.android.com/jetpack/compose/navigation) - The
      Navigation component provides support for Jetpack Compose applications.
    - [DataStore](https://developer.android.com/topic/libraries/architecture/datastore) - Jetpack
      DataStore is a data storage solution that allows you to store key-value pairs or typed objects
      with protocol buffers. DataStore uses Kotlin coroutines and Flow to store data asynchronously,
      consistently, and transactionally.
- [Material Components for Android](https://github.com/material-components/material-components-android)
    - Modular and customizable Material Design UI components for Android.
- [Accompanist](https://github.com/google/accompanist)
    - A collection of extension libraries for Jetpack Compose.
- [Figma](https://figma.com/) - Figma is a vector graphics editor and prototyping tool which is
  primarily web-based.

<br />

## 📦 Package Structure

 ```
dev.spikeysanju.einsen
├── app                   # Application class
├── components            # All resuable components for this app
├── data                  # For data handling
│   ├── local               # Local Persistence Database. Room (SQLite) database
│   │   ├── Dao               # Data Access Object for Room
│   │   └── Database          # Database Instance
│   └── datastore
│       └── ThemePref         # Datastore Theme Preference 
├── di                        # Hilt DI Modules
├── model                     # Model class for [Task] & [Emoji]
├── navigation                # For navigation handling
│   ├── Routes                # All unique navigation routes of this app
│   └── NavGraph              # Single source for Navigation Routes of this app
├── repository                # Used to handle all data operations
├── ui.theme                  # Theme setup for this app
├── utils                     # Extension functions
├── view                      # All composables screens root folder
│   ├── add                   # Add Task Screen
│   ├── edit_task             # Edit Task Screen
│   ├── dashboard             # Dashboard Screen
│   ├── all_task              # All Task Screen
│   ├── task_details          # Task Details Screen
│   ├── emoji                 # Choose Emoji Screen
│   ├── webview               # WebView Screen
│   ├── animation             # Animation Placeholders for State handling(Loading, Error, Empty etc.)
│   ├── about                 # About Screen
│   └── viewmodel             # ViewModel 
└── MainActivity.kt           # MainActivity 

```

<br />

## 🗼 Architecture
![ANDROID ROOM DB DIAGRAM](https://user-images.githubusercontent.com/118751588/231180948-f6bb7171-8e79-41b7-8aa8-537b58e6b37f.jpg)


## 🧰 Build-tool

You need to
have [Android Studio Beta 3 (BumbleBee) or above](https://developer.android.com/studio/preview) to
build this project.
<br>

<img src="./beta_android.png" height="200" alt="Beta-studio"/>


<br>
