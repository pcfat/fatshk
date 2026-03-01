# 發Sir數學 Android App

簡單嘅 WebView App，內嵌 https://fats.hk 網頁。

## 功能
- ✅ 內嵌網頁 (https://fats.hk)
- ✅ 返回按鈕功能（瀏覽歷史）
- ✅ 下拉刷新
- ✅ 支援 JavaScript
- ✅ 本地存儲支援

## 技術規格
- **Package Name**: com.fatshk.app
- **App 名稱**: 發Sir數學
- **Min SDK**: 21 (Android 5.0)
- **Target SDK**: 34 (Android 14)

## 如何編譯

### 方法 1: 使用 Android Studio
1. 下載並安裝 [Android Studio](https://developer.android.com/studio)
2. 打開 Android Studio
3. File → Open → 選擇 `FatSirMathApp` 資料夾
4. 等待 Gradle sync 完成
5. 連接 Android 裝置或啟動模擬器
6. 點擊 Run (綠色播放按鈕)

### 方法 2: 使用命令列
```bash
cd FatSirMathApp
./gradlew assembleDebug
# APK 會生成在：app/build/outputs/apk/debug/app-debug.apk
```

## 安裝到手機
1. 將生成嘅 APK 傳送到手機
2. 開啟手機設定 → 安全性 → 允許安裝未知來源應用程式
3. 點擊 APK 檔案安裝

## 如果需要修改網址
打開 `app/src/main/java/com/fatshk/app/MainActivity.java`，修改呢一行：
```java
private static final String URL = "https://fats.hk";
```

## 注意事項
- 需要網絡連接
- 首次開啟會要求網絡權限
- 支援 Android 5.0 或以上版本

---
Created by Jessica for 發Sir 🎓
