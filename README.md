# Albany Plurigrid
Albany Plurigrid uses Augmented Bonding Curve together with
- `$cUSD` ABC Reserve Currency on Celo (following [Token Engineering Commons](https://token-engineering-commons.gitbook.io/tec-handbook/budgeting-and-reward-system/abc-and-the-common-pool) principles)
- iPhone and Android e-apps built in Flutter

# Running e-app in simulator ⚡️
## iOS
```
cd packages/flutter-app
flutter pub get
open -a Simulator
flutter run
```
## Troubleshooting
```
flutter doctor
```

Should see similar output:
```
Doctor summary (to see all details, run flutter doctor -v):
[✓] Flutter (Channel stable, 3.3.2, on macOS 13.0.1 22A400 darwin-arm, locale en-US)
[✓] Android toolchain - develop for Android devices (Android SDK version 33.0.0)
[✓] Xcode - develop for iOS and macOS (Xcode 14.1)
[✓] Chrome - develop for the web
[✓] Android Studio (version 2021.2)
[✓] VS Code (version 1.73.1)
[✓] Connected device (3 available)
[✓] HTTP Host Availability

• No issues found!
```
