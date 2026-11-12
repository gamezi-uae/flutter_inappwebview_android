# flutter_inappwebview_android 1.1.3 (local copy)

A copy of the pub.dev package with one change: `android/build.gradle` uses
`getDefaultProguardFile('proguard-android-optimize.txt')` instead of `'proguard-android.txt'`,
which AGP 9 refuses. Used through `dependency_overrides` in the app's `pubspec.yaml`.

Remove this folder and the override once a stable flutter_inappwebview release ships the fix
(6.2.0-beta.3 already has it).
