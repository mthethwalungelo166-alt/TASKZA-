# TASKZA Android app project

This is an Android Studio project that packages the TASKZA mobile-friendly app inside a native Android WebView. It uses the app's black-and-gold UI and keeps demo jobs/bookings on the device using browser local storage.

## Build an installable APK
1. Install Android Studio on a computer: https://developer.android.com/studio
2. Extract this ZIP.
3. In Android Studio choose **Open** and select the `TASKZA-Android` folder.
4. Allow Gradle sync and install the Android SDK platform requested by the project (API 35).
5. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
6. Android Studio will show a link to the generated APK, normally at `app/build/outputs/apk/debug/app-debug.apk`.
7. Transfer that APK to your Android phone and open it to install. You may need to allow installs from that file manager.

## Current limitations
This is a prototype, not yet a live marketplace. Sample provider listings are demo data; jobs and bookings are saved locally on one device. Real customer/provider authentication, cloud database, notifications, payment processing, and verified live providers still need backend integration. Do not use the demo listings as claims of real provider availability.

## Project details
- Package: `za.co.taskza.app`
- Version: `1.0.0`
- Minimum Android: Android 6.0 (API 23)
- Target SDK: API 35
