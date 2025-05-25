# app_incubator
# Flutter Project

This project is built using **Flutter 3.27.1**. Follow the steps below to set up and run the project on your local machine.

---

## 🔧 Prerequisites

Make sure you have the following installed:

* [Flutter SDK 3.27.1](https://docs.flutter.dev/release/whats-new#flutter-3271)
* Android Studio or VS Code (with Flutter & Dart extensions)
* Android SDK / iOS setup
* A connected device or emulator

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-flutter-project.git
cd your-flutter-project
```

### 2. Set Flutter Version (if using `fvm`)

If you're using [FVM](https://fvm.app):

```bash
fvm use 3.27.1
fvm flutter pub get
```

Or set the version in your `pubspec.yaml` and `.tool-versions`.

### 3. Install Dependencies

```bash
flutter pub get
```

### 4. Run the App

Make sure a device/emulator is running:

```bash
flutter run
```

---

## 📦 Build APK (Android)

```bash
flutter build apk --release
```

## 📱 Build for iOS

```bash
flutter build ios --release
```

> 💡 For iOS, you must have a macOS system with Xcode installed.

---

## 💪 Run Tests

```bash
flutter test
```

---

## 🛡️ Troubleshooting

* Run `flutter doctor` to check for missing dependencies or issues.
* If packages are not resolving, try:

```bash
flutter clean
flutter pub get
```

---

## 📁 Project Structure

```
lib/
├── main.dart
├── screens/
├── widgets/
├── models/
└── controllers/
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
