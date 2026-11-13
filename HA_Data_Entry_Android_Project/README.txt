HA DATA ENTRY TRACKER - ANDROID APK PROJECT

This package contains the Android Studio project source. It is NOT the APK itself.
The APK is built by the included GitHub Actions workflow.

PHONE/LAPTOP BUILD STEPS (requires a GitHub account and internet):
1. Extract this ZIP on your laptop.
2. Create a new empty repository on github.com (for example: ha-data-entry-tracker).
3. Upload the CONTENTS of this folder to the repository (including the hidden .github folder).
4. Open the repository's Actions tab. Select "Build Android APK" and click "Run workflow".
5. Wait for the workflow to finish successfully.
6. Open the completed workflow run, scroll to Artifacts, and download HA-Data-Entry-Tracker-APK.
7. Extract the downloaded artifact ZIP. It contains app-debug.apk.
8. Transfer app-debug.apk to your Android phone and open it to install. If Android blocks it, allow your file manager/browser to install unknown apps for this one installation.

IMPORTANT DATA NOTE:
The app stores records in the app's local WebView storage on that phone. Uninstalling or clearing app data can erase records. Use BACKUP DATA regularly and keep the JSON backup somewhere safe. Do not share client PINs or backups publicly.
