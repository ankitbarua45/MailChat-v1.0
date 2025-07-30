# MailChat

MailChat is a modern Flutter chat application that leverages Firebase for real-time messaging, authentication, and cloud storage. Designed for both private and group conversations, MailChat offers a seamless, cross-platform chat experience.

---

## Features

- **Real-time Messaging**: Instant communication using Firebase Cloud Firestore.
- **Authentication**: Secure sign-in and registration via Firebase Auth (supports email/password, Google, etc.).
- **Cloud Storage**: Share images, files, and media using Firebase Cloud Storage.
- **Group and Private Chats**: Effortlessly manage group conversations or one-on-one messages.
- **Responsive UI**: Beautiful Material Design, optimized for Android, iOS, and web.
- **Push Notifications**: Stay updated with real-time notifications.
- **User Presence**: See online/offline status of contacts.
- **Message Reactions & Replies**: Interact with messages in a modern way.
- **Profile Customization**: Users can update profile pictures and display names.
- **Dark Mode**: Automatically adapts to system theme.

---
## Downloads

> **Sorry!** I couldn't upload the entire project folder directly to GitHub because the total size is too large (5.14 GB).  
> Instead, you can download the complete project and APK from the links below:

- 🔹 [📱 Download MailChat APK (256 MB)](https://mailchat-android-app.netlify.app)
- 🔸 [🗂️ Download Full Project Source Code (5.14 GB)](https://drive.google.com/drive/folders/18dfucu9V9_5WHrNpyNNeH5uvzQYD9PJZ?usp=sharing)

> If the links expire or you need alternate access, feel free to contact me.


## Screenshots

📸 [View all screenshots here](https://github.com/ankitbarua45/MailChat-v1.0/tree/main/App%20Screenshots)


---

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Firebase Account](https://firebase.google.com/)
- Android Studio, VS Code, or any preferred IDE

### Setup Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ankitbarua45/MailChat-v1.0.git
    cd MailChat-v1.0
    ```

2. **Install dependencies:**
    ```bash
    flutter pub get
    ```

3. **Configure Firebase:**
    - Create a new project in [Firebase Console](https://console.firebase.google.com/).
    - Add Android/iOS/web apps and download respective configuration files:
        - `google-services.json` for Android (place in `android/app`)
        - `GoogleService-Info.plist` for iOS (place in `ios/Runner`)
        - `firebase_options.dart` (generated via [FlutterFire CLI](https://firebase.flutter.dev/docs/cli/))
    - Enable **Authentication** (e.g., Email/Password, Google).
    - Enable **Cloud Firestore** and **Cloud Storage**.

4. **Run the app:**
    ```bash
    flutter run
    ```

---

## Folder Structure

```
mailchat/
├── android/           # Android platform-specific files
├── assets/            # App assets (images, icons)
│   └── icon/
│       └── icon.png
├── build/             # Generated build files (auto-generated)
├── ios/               # iOS platform-specific files
├── lib/               # Main Dart source code
│   ├── main.dart                  # App entry point
│   ├── auth_page.dart             # Authentication UI/logic
│   ├── home_page.dart             # Home screen
│   ├── contacts_list_page.dart    # Contacts list
│   ├── group_chat_page.dart       # Group chat UI/logic
│   ├── private_chat_page.dart     # Private chat UI/logic
│   ├── group_create_page.dart     # Group creation
│   ├── user_profile_page.dart     # User profile
│   ├── profile_setup_page.dart    # Profile setup
│   ├── email_verification_page.dart # Email verification
│   ├── login_page.dart            # Login screen
│   ├── search_page.dart           # Search functionality
│   ├── chat_page.dart             # Chat UI
│   ├── message_list.dart          # Message list widget
│   ├── firebase_options.dart      # Firebase config
│   └── chat_service.dart          # Chat service logic
├── linux/              # Linux platform-specific files
├── macos/              # macOS platform-specific files
├── test/               # Test files
│   └── widget_test.dart
├── web/                # Web platform-specific files
├── windows/            # Windows platform-specific files
├── pubspec.yaml        # Project metadata & dependencies
├── pubspec.lock        # Dependency lockfile
├── README.md           # Project documentation
├── .gitignore          # Git ignore rules
└── ...                 # Other config and project files
```

---

## Key Packages Used

- [`firebase_core`](https://pub.dev/packages/firebase_core)
- [`firebase_auth`](https://pub.dev/packages/firebase_auth)
- [`cloud_firestore`](https://pub.dev/packages/cloud_firestore)
- [`firebase_storage`](https://pub.dev/packages/firebase_storage)
- [`provider`](https://pub.dev/packages/provider)
- [`flutter_local_notifications`](https://pub.dev/packages/flutter_local_notifications)
- [`google_sign_in`](https://pub.dev/packages/google_sign_in)
- [`image_picker`](https://pub.dev/packages/image_picker)
- [`cached_network_image`](https://pub.dev/packages/cached_network_image)

---

## Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to [open an issue](https://github.com/ankitbarua45/MailChat-v1.0/issues) or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For queries, suggestions, or collaborations:

- **GitHub:** [ankitbarua45](https://github.com/ankitbarua45)
- **Email:** imank9762@gmail.com

---

## ⚠️ Warning & Responsible Use Notice

This application is built for educational and personal use only. Please use MailChat responsibly and respectfully.

- ❌ Do not use this app to send spam, offensive, or inappropriate content.
- ❌ Do not attempt to exploit, hack, or misuse any feature.
- ❌ Do not upload copyrighted or harmful material.
- ✅ Always respect privacy, safety, and community guidelines.

The developer is **not responsible** for any misuse or illegal activity carried out using this application. Any violations may result in restricted access or deletion of content.

Let’s keep this a safe and positive space for everyone. ❤️

---

> **Note:** This project is under active development. Features and UI may change.
