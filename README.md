# 🎨 Wallora Android Wallpaper App

The Android source files from the supplied `wallpaper-android-main.zip` have been successfully imported into this repository. The complete ZIP passed an SHA-256 integrity check during GitHub Actions import.

## What's included
- Kotlin Android app, original layouts, test classes, resources and the 12 supplied wallpaper images
- Gallery, search, favorites, set wallpaper, share and save
- AdMob integration with **test IDs** for development
- Gradle wrapper and Android Studio project

## Build a testing APK on GitHub

Open [GitHub Actions](https://github.com/rajunaikilu-sketch/wallora-android/actions/workflows/build-apk.yml). The **Build Wallora Debug APK** workflow runs automatically for source-code changes and can be started with **Run workflow**. Open a successful workflow run and download **Wallora-debug-apk** from **Artifacts**. GitHub Actions stores APK artifacts as a ZIP; extract that download to obtain the `.apk`.

The app has **not** been published to Google Play. A debug APK is for your personal testing only; it is not a signed production release.

## Build in Android Studio

1. Clone this repository, or download the source ZIP.
2. Open the project folder in Android Studio.
3. Install Android SDK components requested by Android Studio.
4. Choose **Build → Build APK(s)**, or run `./gradlew assembleDebug`.

## Important before publishing

- The 12 example wallpaper images from the supplied archive may have independent licensing restrictions. Check rights or replace them before releasing publicly.
- Keep AdMob test IDs until development testing finishes. Configure your own production IDs only before publishing.
- Update app ID, branding, privacy policy, permissions and store listing as needed.
- The source license appears in [LICENSE](LICENSE); review third-party asset licenses separately.
- Original project notes are preserved in [ORIGINAL_README.md](ORIGINAL_README.md).

This repository is independent of the PETRO-gpt project.
