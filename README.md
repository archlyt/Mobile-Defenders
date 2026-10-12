MalwareScanner — Android Studio project (Kotlin, Compose, Lottie)
================================================================

This project is a prototype demonstrating:
- Animated Scan screen with percentage (Lottie)
- Basic static heuristics scanning of installed apps
- Results screen with Quarantine and Backup actions
- Ransomware watcher using FileObserver
- Wi-Fi info & nearby network scan
- Simple phishing URL heuristics (placeholder for Safe Browsing API)

Notes:
- Min SDK is 30 (Android 11).
- Lottie animation file is a simple placeholder at app/src/main/res/raw/scan_anim.json.
- Encryption code is a prototype; use AndroidKeyStore for production.
- To run Wi-Fi scanning on modern Android devices you must allow Location permission and enable Location services.

To run:
- Open this folder in Android Studio (File → Open → select the folder).
- Let Gradle sync and run on a real device for full Wi-Fi scanning support.
