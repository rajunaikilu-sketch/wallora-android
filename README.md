# Wallora Android App

This repository is prepared to import the uploaded **wallpaper-android-main.zip** Android Studio project and attempt a free debug APK build using GitHub Actions.

## Import source from Android phone

1. Open this repository in your browser.
2. Select **Add file → Upload files**.
3. Upload the original file named **wallpaper-android-main.zip** (do not rename or unpack it).
4. Select **Commit changes** to `main`.
5. Go to **Actions → Import Wallora ZIP and Build Debug APK**. The workflow starts automatically on the ZIP upload. The import job unpacks the project into its usual Android Studio layout, commits its source files to this repository, and removes the ZIP.
6. The build job then tries to build a debug APK. Once successful, download the **Wallora-debug-apk** artifact from the workflow run.

**Note:** A debug APK is for personal testing, not a Play Store release. An APK has not been built or verified yet.

Source license: MIT according to the supplied project. The included example wallpaper images are demo assets; check their licenses or replace them before public distribution. AdMob IDs are test IDs and must be replaced before a production release.

## Android Studio

After the import, clone the repository or download its source ZIP, open the project in Android Studio, and run `./gradlew assembleDebug` to build locally.
