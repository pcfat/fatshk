# 發Sir數學 Flutter App

跨平台版本（Android + iOS）

## 📱 功能

- ✅ 內嵌 https://fats.hk 網頁
- ✅ 支援 Android 5.0+
- ✅ 支援 iOS 12.0+
- ✅ 返回按鈕功能
- ✅ 下拉刷新
- ✅ 移除點擊藍色效果
- ✅ 白色 status bar

## 🏗️ Build

### Android
```bash
flutter build apk --release
```

### iOS
```bash
flutter build ios --release --no-codesign
```

## 📦 Package Info

- **Package Name (Android)**: hk.fats.fatshk
- **Bundle ID (iOS)**: hk.fats.fatshk
- **版本**: 1.0.0+1

## 🔄 GitHub Actions

每次 push 到 main/master 會自動 build：
- iOS (unsigned IPA)
- Android (APK)

---

Created by Jessica for 發Sir 🎓
