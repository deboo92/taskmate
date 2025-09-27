# 🚀 TaskMate

**AI-Powered Productivity Suite for Flutter**

[![Flutter Version](https://img.shields.io/badge/Flutter-3.8.1+-blue.svg)](https://flutter.dev/)
[![Dart Version](https://img.shields.io/badge/Dart-3.0+-blue.svg)](https://dart.dev/)
[![Android](https://img.shields.io/badge/Android-5.0+-green.svg)](https://developer.android.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Transform your productivity with TaskMate - the ultimate AI-powered cross-platform app for notes, tasks, flashcards, and intelligent assistance.

## ✨ Features

### 🧠 AI-Powered Intelligence
- **Smart Notes**: AI-powered search, organization, and context-aware suggestions
- **Intelligent Chat**: Built-in AI assistant for content help and suggestions
- **Voice-to-Text**: Accurate speech recognition for quick note capture
- **Auto-Organization**: Smart categorization and tagging of content

### 📋 Task Management
- **Priority Suggestions**: AI-driven task prioritization
- **Deadline Tracking**: Smart reminders and notifications
- **Progress Analytics**: Detailed insights into productivity patterns
- **Cross-Device Sync**: Seamless synchronization across all devices

### 🎓 Learning Tools
- **Adaptive Flashcards**: Learning system that adjusts to your progress
- **Interactive Quizzes**: Personalized difficulty adjustment
- **Study Analytics**: Track learning progress and optimize study sessions
- **Spaced Repetition**: Scientific learning algorithms

### 🔒 Security & Privacy
- **End-to-End Encryption**: Complete data protection
- **Biometric Authentication**: Fingerprint and face recognition
- **Local Storage**: Data remains on your device
- **Privacy First**: No tracking, no ads in premium version

## 📱 Supported Platforms

- ✅ **Android 5.0+** (API 21+)
- 🔄 **iOS** (Coming Soon)
- 🔄 **Web** (In Development)
- 🔄 **Windows/macOS** (Planned)

## 🛠 Installation

### Prerequisites
- Flutter SDK 3.8.1+
- Dart SDK 3.0+
- Android Studio / VS Code
- Android SDK (API 35)

### Clone Repository
git clone https://github.com/deboo92/taskmate.git
cd TaskMate



### Install Dependencies
flutter pub get



### Run the App
Debug mode
flutter run

Release mode
flutter run --release



## 🏗 Architecture

TaskMate follows **Clean Architecture** principles with:

- **BLoC Pattern** for state management
- **Repository Pattern** for data access
- **Dependency Injection** with Provider
- **Modular Structure** for scalability

lib/

├── core/ # Core utilities and constants

├── data/ # Data sources and repositories

├── domain/ # Business logic and entities

├── presentation/ # UI and BLoC components

└── main.dart # App entry point



## 🔧 Configuration

### Firebase Setup
1. Create a new Firebase project
2. Add your `google-services.json` to `android/app/`
3. Configure authentication and analytics

### Environment Variables
Create a `.env` file in the root directory:
API_BASE_URL=your_api_url
OPENAI_API_KEY=your_openai_key
ENCRYPTION_KEY=your_encryption_key



## 📦 Building for Release

### Android App Bundle (Recommended)
flutter build appbundle --release



### Android APK
flutter build apk --release



## 🧪 Testing

### Run All Tests
flutter test



### Run Widget Tests
flutter test test/widget_test.dart



### Run Integration Tests
flutter drive --target=test_driver/app.dart



## 📊 Performance

- **App Size**: ~52MB (optimized with R8)
- **Startup Time**: <2 seconds
- **Memory Usage**: <150MB average
- **Battery Optimized**: Minimal background processing

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md).

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **Website**: [https://deboo92.github.io/taskmate/](https://deboo92.github.io/taskmate/)
- **Privacy Policy**: [Privacy Policy](https://deboo92.github.io/taskmate/taskmate_privacy_policy.html)
- **Google Play**: [Download on Play Store](https://play.google.com/store/apps/details?id=com.malky.taskmate)
- **Support**: [support@malky-apps.com](mailto:support@malky-apps.com)

## 👨‍💻 Developer

**Mahmoud Elmalky**
- GitHub: [@deboo92](https://github.com/deboo92)
- Email: [privacy@malky-apps.com](mailto:privacy@malky-apps.com)
- Location: Alexandria, Egypt

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- Firebase for backend services
- OpenAI for AI integration
- Material Design for UI guidelines

---

**Made with ❤️ by Malky Dev**

*TaskMate - Transform your productivity with AI*
