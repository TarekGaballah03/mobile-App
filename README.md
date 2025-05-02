[UI](https://github.com/user-attachments/assets/98af1b5a-d875-431f-ad9f-c4eb2bd5072b)
NAME : TAREK MOHAMED ABDALLAH / ID :230537240
آآآآآآn
ىآ
Track your project changes using git status.  
For a fresh start or to run your project smoothly, use:

flutter clean
flutter pub get
flutter run
````

---

## 🌱 **About the Project**

Welcome to an innovative Flutter application tailored to eco-friendly creativity and personal expression.
This app includes seasonal UI elements, profile customization, and engaging interface features.

---

## 🗂 Project Directory Overview

lib/
├── firstScreen.dart
├── home/
│   └── home_screen/
│       └── home_page.dart
│       └── home_widget/
│           └── home_widget.dart
├── profile/
│   └── profile_page/
│       └── profile_page.dart
└── my_season.dart

---

## 🔍 Feature Highlights

### 🏠 Home Page (`home_page.dart`)

* Displays a dynamic hero image (gallery-picked or default).
* Title and description overlay for context.
* Favorite and share functionality included.
* Grid or list of seasonal images or uploaded gallery content.
* A floating action button enables quick navigation to the welcome screen.

### 👤 Profile Page (`profile_page.dart`)

* Lets users upload a profile image via camera or gallery.
* Supports image editing and deletion.
* Circular avatar with a camera icon overlay for easy access.

### ✨ First Screen (`firstScreen.dart`)

* Acts as the opening screen, perfect for onboarding or welcome messages.

### 🌸 MySeason Widget (`my_season.dart`)

A modular UI component showing a seasonal photo with text below.

#### ✅ Usage Example:

```dart
MySeason(url: "assets/imagetree2.jpg", text: "Winter")

#### 🧠 Why Use This?

* Built using a Stack to overlay text onto an image.
* Helpful for showcasing categories like seasons, moods, or gallery sets.
* Maintains a clean 100x100 image display with BoxFit.cover.

---

## 🛠 Getting Started

Follow these steps to set up and run the app:

1. Clone this repo:

git clone <your-repo-url>
cd <your-repo>

2. Install packages:

flutter pub get

3. Launch the application:

flutter run

---

## 🙋 Author

Tarek
