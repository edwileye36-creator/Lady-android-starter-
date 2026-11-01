# Project LADY Android Starter — v0.2

This is a starter Android app project intended for a phone-first workflow.
The included GitHub Actions workflow builds a debug APK in the cloud.

## Build from your phone
1. Create a GitHub repository (Private is fine).
2. Upload the contents of this folder to the repository's root.
3. Open the **Actions** tab and allow workflows if GitHub asks.
4. Run **Build LADY Android APK** from the Actions tab.
5. When the run finishes successfully, open the run and download the `lady-debug-apk` artifact.
6. Extract the downloaded artifact ZIP; install the APK on your Android phone.

## Notes
- This is a starter shell app, not a finished assistant.
- The APK is a debug build for testing.
- Do not upload passwords, signing keys, or other secrets to the repository.
