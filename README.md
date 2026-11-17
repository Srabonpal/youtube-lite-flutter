# YouTube Lite (Flutter Assignment)

A beginner-friendly Flutter assignment project featuring:
- Hard-coded YouTube-inspired home UI
- Category chips, video thumbnails, channel details and bottom navigation
- Search screen
- Opens mobile YouTube video and search pages inside Flutter `WebView`
- Loading progress, reload and basic error state

## Requirements
- Flutter SDK 3.38 or newer
- Android Studio / Android SDK
- Internet connection on the device

## Setup

1. Extract the project.
2. Open the folder in VS Code or Android Studio.
3. In the project terminal run:

```bash
flutter pub get
flutter run
```

If Android platform files are missing in your local setup, create a fresh Flutter project and copy this project's `lib/`, `pubspec.yaml`, and `android/app/src/main/AndroidManifest.xml` into it:

```bash
flutter create youtube_lite
```

Then run `flutter pub get` and `flutter run`.

## GitHub upload

```bash
git init
git add .
git commit -m "Initial YouTube Lite Flutter assignment"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/youtube-lite-flutter.git
git push -u origin main
```

## Notes
- The home feed is hard-coded as requested; it is not connected to the YouTube Data API.
- Tapping a video opens its mobile YouTube page using `webview_flutter`.
- YouTube may show consent, sign-in, or browser compatibility pages depending on device, network, region and Google's current policies. This app does not download or rehost YouTube videos.
- Replace the sample video IDs/titles/thumbnails in `lib/main.dart` if your instructor wants different demo content.
