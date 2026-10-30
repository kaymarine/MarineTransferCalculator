MARINE TRANSFER CALCULATOR — ANDROID STUDIO PROJECT
Package ID: com.marine.transfercalculator
Version: 1.0
Minimum Android: 8.0 (API 26)

BUILD THE APK
1. Install Android Studio on a computer.
2. Install Android SDK Platform 35 and Android SDK Build-Tools 35.x using SDK Manager.
3. Extract this project ZIP.
4. In Android Studio choose File > Open and select the extracted MarineTransferCalculatorAndroid folder.
5. Allow Gradle sync to complete (Android Studio will download the required Gradle/Android Gradle Plugin if internet is available).
6. Select Build > Build Bundle(s) / APK(s) > Build APK(s) for a test/debug APK.
7. Android Studio will show the output location, normally app/build/outputs/apk/debug/app-debug.apk.

CREATE A SIGNED RELEASE APK
1. In Android Studio choose Build > Generate Signed Bundle / APK.
2. Select APK, then Next.
3. Create a new keystore (or select your existing keystore). Keep the keystore, passwords and key alias private and backed up. Do not send them to anyone.
4. Select the release build variant and complete the wizard.
5. The signed APK is normally created under app/build/outputs/apk/release/.

APP DETAILS
- Offline: calculator HTML is packaged inside the APK; no internet permission is requested.
- Quantity input in litres.
- Flow-rate units: m3/hour, litres/minute, litres/hour.
- Optional received quantity calculates remaining time.
- Estimated finish clock time and share-result action.
- Assumes constant flow rate; actual transfer duration may vary.

NOTE
This is the complete Android Studio source project, not a compiled APK. The current build container has Java but no Android SDK, Gradle, or Android build tools, and outbound access to Google's SDK repository is unavailable. Therefore an APK could not be compiled or signed in this session. Use the steps above in Android Studio to build and sign it on a computer.
