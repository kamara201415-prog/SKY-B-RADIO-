# SKY B RADIO – By DJ SKY B
## Android MVP prototype 0.1.0

Design: black & gold. Interface language: French/English labels.
Roles shown in prototype: listener, DJ, administrator.

### Included
- Android Studio project using Kotlin + Jetpack Compose
- Home screen and demo play/pause state
- Direct, Programs, DJ Studio and Admin screens
- Editable stream URL field (not yet connected to an audio player)
- Internet permission

### Important limitations
This is a UI prototype, not a production radio system and not a compiled APK.
The play/pause control is a demo state only. Real streaming, live microphone,
DJ mixing, authentication, remote administration, AutoDJ scheduling, cloud
storage and listener analytics still require backend integration and testing.
Do not enter real passwords or private server credentials in this prototype.

### Build APK
1. Install Android Studio on a Windows/Mac/Linux computer.
2. Open this folder as an existing project.
3. Let Gradle sync complete (internet required for dependencies).
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The debug APK is normally created at:
   app/build/outputs/apk/debug/app-debug.apk

### Next production steps
- Choose and verify a radio hosting endpoint.
- Add a real streaming player (e.g. Media3/ExoPlayer) and background playback service.
- Add secure backend authentication with separate admin and DJ permissions.
- Connect AutoDJ scheduler and live source failover.
- Test with actual Android devices and mobile data/Starlink.
