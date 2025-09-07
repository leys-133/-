# Rafiq App — Flutter
**Developer:** Laith Al-Nisr (Syria) —   
**Features working now:** Quran reader (streaming), variable speed, tafsir brief/full, translations (EN/TR/FR), tasbih (persistent), local daily reminders, Qibla compass, voice commands (basic).  
**Offline audio:** Implement via DownloadService (placeholder ready).  
**AR/maps/donations/groups:** require API keys/backends; stubs intentionally omitted to keep app compiling out-of-the-box.

## Run
```bash
flutter pub get
flutter run
```

## Notes
- Qibla uses sensors/location permissions.
- Notifications require runtime permission on Android 13+.
- Voice needs mic permission.
- Replace sample assets with full datasets when ready.
