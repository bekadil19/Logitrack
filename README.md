# LogiTrack

A mobile app for tracking and managing logistics requests. Lets users create requests, track their status, and manage a list of active tasks.

## Functionality

- User can create a new request (title, description, priority)
- User can view a list of all requests
- User can open a request and see its details
- User can change a request's status (New/In Progress/Completed)
- User can delete a request
- App persists data locally
- Empty state screen shown when there are no requests
- List displays request priority visually

## Project Structure

LogiTrack/
├── app/
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/com/yourname/logitrack/
│ │ │ │ └── MainActivity.kt
│ │ │ ├── res/
│ │ │ │ ├── layout/
│ │ │ │ └── values/
│ │ │ └── AndroidManifest.xml
│ └── build.gradle.kts
├── build.gradle.kts
├── settings.gradle.kts
├── .gitignore
└── README.md


## Build & Run Instructions

1. Open the project in Android Studio (File → Open → select the LogiTrack folder)
2. Wait for Gradle sync to finish
3. Connect an emulator or physical device
4. Click Run (▶) or press Shift+F10