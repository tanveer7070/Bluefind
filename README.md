# BlueFind — Bluetooth Device Location Tracker (Android / Kotlin)

BlueFind automatically records the GPS location whenever your Bluetooth devices (earbuds, smartwatches, headphones, etc.) connect or disconnect, helping you locate misplaced devices.

## Features
- **Background Foreground Service** (`BluetoothMonitorService`) listening to `ACTION_ACL_CONNECTED` and `ACTION_ACL_DISCONNECTED`.
- **Automatic GPS + Address Capture** via `FusedLocationProviderClient` and `Geocoder`.
- **Disconnect Alert Notifications** with one-tap navigation to the saved pin.
- **Built-in Interactive Map** using Leaflet + OpenStreetMap (no Google Maps API key required) plus a one-tap **Google Maps Directions** button.
- **Auto-start on Reboot** via `BootCompletedReceiver`.

## How to Build
1. Open the `BlueFind` folder in **Android Studio** (Ladybug / 2024.2+ recommended).
2. Let Gradle sync finish.
3. Click **Build > Build Bundle(s) / APK(s) > Build APK(s)** or run directly on a connected Android device (Android 8.0 / API 26+).
