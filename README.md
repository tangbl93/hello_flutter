# Hello Flutter

A Flutter Web application - runs in your browser!

## 🌐 Live Demo

Visit the live app at:
**https://你的用户名.github.io/hello_flutter**

*(Note: Update this URL after enabling GitHub Pages)*

## 🚀 Quick Start

### Run Locally
```bash
cd /home/Projects/hello_flutter
flutter pub get
flutter run -d chrome
```

### Build Web
```bash
cd /home/Projects/hello_flutter
flutter build web
```

### Preview Web Build
```bash
cd /home/Projects/hello_flutter
flutter build web
cd build/web
python3 -m http.server 8080
# Then open http://localhost:8080
```

## 📦 CI/CD

This project uses GitHub Actions for automated builds and deployment:

- **Analyze**: `flutter analyze`
- **Test**: `flutter test`
- **Build Web**: `flutter build web --release`
- **Deploy**: Automatically deploys to GitHub Pages

Build artifacts are available in the Actions tab.

## 📱 Features

- [ ] Counter demo
- [ ] Material Design 3
- [ ] Responsive layout

## 🛠️ Project Structure

```
lib/
├── main.dart          # App entry point
└── ...
test/
├── widget_test.dart   # Widget tests
└── ...
```

## 🎯 Supported Platforms

- ✅ Web (Primary)
- ✅ Android
- ✅ iOS
- ✅ Windows
- ✅ macOS
- ✅ Linux

## 📚 Resources

- [Flutter Documentation](https://flutter.dev/docs)
- [Flutter Web](https://flutter.dev/web)
- [Material Design 3](https://m3.material.io/)

## 🤝 Contributing

This project is developed with remote AI assistance via GitHub Actions.

---

**Built with Flutter** | **Hosted on GitHub Pages**
