# JARVIS Android starter

A simple Android voice assistant starter for Android 7.0+:
- Speech-to-text using Android speech recognition
- Text-to-speech replies
- Basic local demo commands (hello, open YouTube, open camera)
- Optional Gemini API connection for AI answers
- GitHub Actions workflow to build a debug APK in the cloud

## Build an APK with GitHub Actions
1. Create a new GitHub repository and upload the contents of this folder.
2. Open the repository's **Actions** tab and enable Actions if prompted.
3. Run **Build JARVIS APK** (or push to `main` / `master`).
4. Open the successful workflow run and download the `JARVIS-debug-apk` artifact.
5. Extract the ZIP to get `app-debug.apk`.

## Gemini AI
The app works in demo mode without a key. To enable AI answers, obtain a Gemini API key from Google's AI developer platform and paste it into the API-key field in the app. Do not share the key publicly or commit it into source code. API usage may have limits or costs depending on the provider's current terms.

## Current limitations
This is a starter build, not a full movie-style JARVIS. It does not run continuously in the background, control every phone setting, or listen while the app is closed. Speech recognition may use the phone's configured speech service and internet.
