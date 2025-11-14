Advanced Hybrid Android WebView App - Instructions

What is included:
- Android project skeleton (Kotlin) with MainActivity, SplashActivity.
- WebView loads online URL if device has internet, else loads local assets/index.html.
- Placeholder dependency for Firebase Messaging is included but you must configure FCM yourself.

To build APK:
1. Open Android Studio (Electric Eel or newer recommended).
2. Import this folder as a project.
3. Add google-services.json in app/ if you want Firebase Messaging (notifications).
   - Create Firebase project, register app package com.selectionway.harendra
   - Download google-services.json and place in app/
   - Add Firebase Gradle plugin as needed (not included by default).
4. Build > Build Bundle(s) / APK(s) > Build APK(s)

Notes on Notifications:
- I included firebase-messaging in dependencies as a placeholder.
- To enable push notifications you must create Firebase Cloud Messaging credentials and optionally a server to send messages.
- Alternatively, use OneSignal or similar (they provide easier setup).

If you want, I can further:
- Provide a GitHub Actions workflow that builds the APK automatically when you push to the repo.
- Help step-by-step to build on your PC / in GitHub Actions to produce APK automatically.
