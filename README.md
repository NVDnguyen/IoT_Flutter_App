
# IoT App
## Introduction
----it's 40% like blynk (but...)
## Getting Started

### Requirements

Before getting started, ensure you have the following installed:

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/)
- For demo purposes: Use either the Android Studio emulator or connect a physical device via USB debugging with Developer permissions enabled.

### Installation

1. **Clone the Repository**

   ```bash
   https://github.com/NVDnguyen/IoT_Flutter_App
   ```

2. **Navigate to the project directory**

   ```bash
   cd firewise_app
   ```

3. **Install dependencies**

   ```bash
   flutter clean
   flutter pub get
   flutter run
   ```
4. **Set up Firebase**
- Create new project in firebase and follow intruction to change ```android\app\google-services.json```
-  Firebase real time with structure like :
```json
{
  "Virtual Pins": {
    "87Y2HG346729Y7924": {
      "A1": "1",
      "V1": 23.53
    }
  },
  "users": {
    "87Y2HG346729Y7924": {
      "address": "",
      "image": "",
      "user_name": ""
    }
  }
}
```
5. **Run the app on an emulator or physical device**

   ```bash
   flutter run
   ```


### Build for Android:

1. Generate APK file:
   ```bash
   flutter build apk
   ```
   This command will generate an APK file in the `build/app/outputs/apk/release` directory, suitable for installation on Android devices.

2. Generate App Bundle file:
   ```bash
   flutter build appbundle
   ```
   This command will generate an App Bundle (`.aab`) file in the `build/app/outputs/bundle/release` directory. The App Bundle is the recommended format for uploading the app to the Google Play Store.

### Build for iOS:

1. Generate iOS build:
   ```bash
   flutter build ios
   ```
   This command will generate a `build/ios` directory containing all necessary files for deploying the app to an iOS device or packaging it for submission to the App Store.

2. Run release version on iOS device:
   ```bash
   flutter run --release
   ```

## Screenshots

Here are some screenshots illustrating the app:

### Welcome Screen
![Welcome Screen](https://i.ibb.co/rcTM06P/Screenshot-2024-05-14-013307.png)

### Login Screen
![Login Screen](https://i.ibb.co/PC7kCT0/Screenshot-2024-05-14-013321.png)

### Register Screen
![Signin Screen](https://i.ibb.co/G7DscXt/Screenshot-2024-05-14-013335.png)

### Home Screen
![Home Screen](https://i.ibb.co/Z2xXYdQ/Screenshot-2024-05-14-014017.png)

### Create Widget
![Home Screen](https://i.ibb.co/NTfKFYs/Screenshot-2024-05-14-013430.png)

### News Screen
![News Screen](https://i.ibb.co/DCkb3nS/Screenshot-2024-05-14-013503.png)

### Profile Screen
![Profile Screen](https://i.ibb.co/Mp1tJ1J/Screenshot-2024-05-14-013451.png)

### Edit Profile Screen
![Edit Profile Screen](https://i.ibb.co/7zNrLZd/Screenshot-2024-05-14-013514.png)


