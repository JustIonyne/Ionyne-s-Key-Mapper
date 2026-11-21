# FloatKeys
Floating on-screen buttons that press a real keyboard key when tapped (hold = key held).

## Build
1. Open this folder in Android Studio (Koala or newer). Let Gradle sync.
2. Run on a device (Android 8.0+).

## Use
1. Install **Shizuku** from the Play Store and start it (wireless debugging method on Android 11+, no root needed).
2. Open FloatKeys -> grant overlay permission -> grant Shizuku permission.
3. Add a button, choose its key, tap "Show floating buttons".
4. Pull the notification shade -> "Edit layout", drag buttons where you want them, tap "Done editing".

## Get an APK without Android Studio
Push this folder to a new GitHub repo. The "Build APK" workflow runs automatically
(Actions tab). When it finishes, download the `FloatKeys-debug-apk` artifact, unzip it,
and install app-debug.apk on your phone.
