<div align="center">
  <img src="assets/logo.png" alt="Fluento Logo" width="88" height="88" />
  <h1>Fluento</h1>
  <p><strong>Offline-First English Learning, Dictionary &amp; Bilingual AI Studio</strong></p>
  <p><strong>English</strong> Â· <a href="./README.vi.md">Tiáº¿ng Viá»‡t</a></p>

  <p>
    <a href="https://github.com/hieutm-software/fluento/releases">
      <img src="https://img.shields.io/badge/Android-Release_APK-4F46E5?style=for-the-badge&logo=android&logoColor=white" alt="Android APK (Releases)" />
    </a>
    <img src="https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
    <img src="https://img.shields.io/badge/Storage-Isar_Offline-10B981?style=for-the-badge" alt="Offline-First Isar" />
  </p>
  <sub>Install directly from GitHub Releases or build from source below.</sub>
</div>

---

## ðŸ§© Core Modules

- ðŸ›¤ï¸ **291-Day Learning Path** â€” Sequential daily curriculum starting from Day 1 with Flashcards, Daily Tests, Streak tracking, and **Endless Arena** arcade challenges.
- ðŸ“– **Offline Dictionary** â€” 5,823 local Isar entries with CEFR levels (`A1`â€“`C2`), UK/US IPA phonetics, definitions, examples, and audio pronunciation.
- ðŸŒ **Bilingual Translation Studio** â€” Instant EN â‡„ VI translation across **Standard**, **Reflex (`/situ`)**, and **Tech / IT (`/it`)** modes using free Google Translate or BYOK Gemini / Groq API keys.
- ðŸŽ§ **Listening & Speaking Practice** â€” CEFR `A1`â€“`C2` listening drills, adjustable TTS reading speed, voice capture, and speech recognition feedback.
- ðŸŽ¨ **Adaptive Light & Dark UI** â€” Carbon Neutral & Indigo-Periwinkle Material 3 theme, responsive layout, and built-in `EN` / `VI` interface switching.

## âš™ï¸ Tech Stack

`Flutter (Dart)` Â· `Riverpod` Â· `Isar Database` Â· `GoRouter` Â· `Material 3` Â· `flutter_tts / audioplayers / speech_to_text`

## ðŸš€ Build & Test

```bash
flutter pub get
flutter test
flutter build apk --release
```

<sub>Release APK output: `build/app/outputs/flutter-apk/app-release.apk`</sub>
