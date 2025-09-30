# Flutter Firebase AI Chat App 🤖

Firebase AI (Gemini) entegrasyonu ile geliştirilmiş akıllı sohbet uygulaması.

## 🚀 Özellikler

- **Gemini AI Entegrasyonu**: Google'ın AI modeli ile güçlendirilmiş
- **Real-time Chat**: Anlık mesajlaşma deneyimi
- **Firebase Backend**: Güvenli ve ölçeklenebilir altyapı
- **Cross Platform**: iOS, Android ve Web desteği

## 🔧 Kurulum

### 1. Repository'yi klonlayın
```bash
git clone https://github.com/cengizhankkaya/flutter_firbase_ai.git
cd flutter_firbase_ai
```

### 2. Bağımlılıkları yükleyin
```bash
flutter pub get
```

### 3. Firebase Kurulumu

#### ⚠️ ÖNEMLİ: Firebase Options Dosyası
Bu proje güvenlik nedeniyle `firebase_options.dart` dosyasını içermez. Kendi Firebase projenizi kurmanız gerekiyor:

1. **Firebase Console**'da yeni proje oluşturun
2. Android ve iOS uygulamaları ekleyin
3. `firebase_options.template.dart` dosyasını `firebase_options.dart` olarak kopyalayın
4. Firebase Console'dan aldığınız değerlerle güncelleyin

```bash
# Template dosyasını kopyalayın
cp lib/firebase_options.template.dart lib/firebase_options.dart
```

#### Firebase CLI Kurulumu:
```bash
# Firebase CLI
npm install -g firebase-tools
firebase login

# FlutterFire CLI
dart pub global activate flutterfire_cli
flutterfire configure
```

### 4. Platform Konfigürasyonu

#### Android:
- `android/app/google-services.json` dosyasını Firebase Console'dan indirin

#### iOS:
- `ios/Runner/GoogleService-Info.plist` dosyasını Firebase Console'dan indirin

## 🚀 Çalıştırma

```bash
flutter run
```

## 🔐 Güvenlik Notları

- **Asla** gerçek API anahtarlarınızı GitHub'a yüklemeyin
- `firebase_options.dart` dosyası `.gitignore`'da yer alır
- Firebase güvenlik kurallarınızı production için yapılandırın

## 📞 İletişim

- **GitHub**: [@cengizhankkaya](https://github.com/cengizhankkaya)
