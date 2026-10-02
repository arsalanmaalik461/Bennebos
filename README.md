# Bennebos

> **Developed by [Arslan Malik](https://github.com/arsalanmaalik461)**
> 📱 WhatsApp: [+92 300 8987448](https://wa.me/923008987448) · 🌐 Website: [arslanmalik.tech](https://arslanmalik.tech)

A Flutter-based multi-vendor delivery app for food, grocery, eCommerce, pharmacy, and parcel services.

## 📌 About

Bennebos is a cross-platform mobile and web app built with Flutter (based on the 6amMart multi-vendor codebase). It connects customers with nearby stores and vendors for on-demand ordering and delivery — covering food, groceries, pharmacies, online shops, and parcel delivery — with map-based tracking and push notifications.

## ✨ Features

- 🛒 Multi-vendor marketplace — food, grocery, eCommerce, pharmacy & parcel
- 🗺️ Google Maps integration — store locations, delivery tracking, animated markers
- 🔔 Push notifications via Firebase Cloud Messaging + local notifications
- 🔑 Social login — Google, Facebook, and Apple sign-in
- 📱 OTP verification with pin code fields
- 🌍 Multi-language support
- 🖼️ Image picker, caching, and photo viewer for products
- 💳 In-app webview for payments and web content
- 🎠 Carousels, shimmer loading, and smooth animated UI

## 🛠️ Tech Stack

- **Framework:** Flutter (Dart, SDK >= 3.0.6)
- **Backend services:** Firebase (Core, Messaging, Crashlytics)
- **Maps & location:** google_maps_flutter, geolocator
- **State management:** GetX
- **Other:** http, shared_preferences, url_launcher, image_picker, video_player

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (>= 3.0.6)
- Android Studio or VS Code with Flutter extensions

### Installation

```bash
git clone https://github.com/arsalanmaalik461/Bennebos.git
cd Bennebos
flutter pub get
```

### Run the app

```bash
# Android / iOS (emulator or device connected)
flutter run

# Web
flutter run -d chrome
```

> **Note:** Add your own Firebase configuration files (`google-services.json` for Android, `GoogleService-Info.plist` for iOS) and a Google Maps API key before building.

## 📁 Project Structure

```
lib/            # Dart source code (screens, controllers, models, widgets)
assets/         # Images, language files, fonts
android/        # Android native project
ios/            # iOS native project
web/            # Web build support
test/           # Widget tests
```

## 📄 License

Developed and maintained by Arslan Malik.

---

<div align="center"><b>Developed with ❤️ by <a href="https://github.com/arsalanmaalik461">Arslan Malik</a></b><br>📱 <a href="https://wa.me/923008987448">WhatsApp</a> · 🌐 <a href="https://arslanmalik.tech">arslanmalik.tech</a></div>
