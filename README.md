# 🎨 Wallz - Premium Flutter Wallpaper App

A sophisticated **Flutter wallpaper application** featuring premium Material 3 design, Unsplash API integration, and advanced wallpaper management capabilities across all platforms.

## ✨ Features

### 🖼️ **Premium Wallpaper Collection**
- **Unsplash API Integration** - Access to millions of high-quality wallpapers
- **Smart Categories** - Nature, Abstract, Space, Animals, Minimal, and more
- **Advanced Search** - Find wallpapers with intelligent suggestions
- **Favorites System** - Save and manage your preferred wallpapers

### 🎨 **Modern UI/UX Design**
- **Material 3 Design** with sophisticated gradients and glassmorphism effects
- **Premium Typography** with perfect letter spacing and font weights
- **Smooth Animations** and micro-interactions throughout the app
- **Responsive Design** optimized for all screen sizes and orientations

### 📱 **Multi-Platform Support**
- **Android** (Full wallpaper setting functionality)
- **iOS** (Viewing and downloading)
- **macOS, Windows, Linux** (Desktop viewing experience)
- **Web** (Browser-based wallpaper discovery)

### 🚀 **Advanced Functionality**
- **Wallpaper Setting** (Home/Lock/Both screens on Android)
- **Smart Caching** for offline viewing and performance
- **Download Management** with organized storage
- **Staggered Grid Layout** for optimal visual presentation

## 🏗️ Architecture

### **Clean Architecture Pattern**
```
lib/
├── models/          # Data models and entities
├── providers/       # State management with Provider
├── screens/         # UI screens and pages
├── services/        # API and business logic
├── utils/           # Helper functions and utilities
└── widgets/         # Reusable UI components
```

### **State Management**
- **Provider Pattern** for efficient state management
- **Separation of Concerns** with dedicated providers
- **Reactive UI** with automatic rebuilds

## 🛠️ Technical Stack

- **Flutter 3.35.2** with **Dart 3.9.0**
- **Material 3** design system
- **Unsplash API** for wallpaper content
- **Provider** for state management
- **Cached Network Image** for performance optimization
- **Permission Handler** for system permissions
- **Photo View** for wallpaper preview with zoom

## 🚀 Getting Started

### Prerequisites
- Flutter SDK 3.35.2+
- Dart SDK 3.9.0+
- Android Studio / VS Code
- Unsplash API key (free)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/afzalimdad9/wallz.git
   cd wallz
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Unsplash API**
   - Get your free API key from [Unsplash Developers](https://unsplash.com/developers)
   - Update `lib/utils/api_config.dart` with your API key

4. **Run the app**
   ```bash
   flutter run
   ```

### Building for Production

```bash
# Android APK
flutter build apk --release

# Android App Bundle
flutter build appbundle --release

# iOS (requires macOS with Xcode)
flutter build ios --release
```

## 📱 Platform-Specific Features

### Android
- ✅ **Full wallpaper setting** (Home/Lock/Both screens)
- ✅ **Download to gallery**
- ✅ **Permission management**
- ✅ **Background wallpaper service**

### iOS
- ✅ **Wallpaper viewing and preview**
- ✅ **Save to Photos app**
- ❌ **Direct wallpaper setting** (iOS limitation)

### Desktop (macOS, Windows, Linux)
- ✅ **Full browsing experience**
- ✅ **Download wallpapers**
- ✅ **Large screen optimization**

## 🎨 Design Highlights

- **Sophisticated Gradients** with multi-layer color transitions
- **Glassmorphism Effects** for modern, premium feel
- **Advanced Shadow Systems** for depth and elevation
- **Color-Coordinated Themes** matching wallpaper categories
- **Smooth Hero Animations** between screens
- **Professional Typography** with optimal readability

## 🔧 Configuration

### API Configuration
Edit `lib/utils/api_config.dart`:
```dart
static const String apiKey = 'YOUR_UNSPLASH_ACCESS_KEY';
```

### App Customization
- **Theme Colors**: Update `lib/main.dart` color scheme
- **Categories**: Modify `lib/models/category.dart`
- **API Settings**: Adjust `lib/utils/api_config.dart`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Unsplash** for providing beautiful, high-quality wallpapers
- **Flutter Team** for the amazing framework
- **Material Design** for the design guidelines
- **Community Contributors** for packages and inspiration

---

**🚀 Generated with [Claude Code](https://claude.ai/code)**

*Building premium mobile experiences with AI assistance*