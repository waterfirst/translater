# 🎓 Conference Helper (학회 도우미)

**Real-time Speech Recognition & Translation for International Conferences**

국제 학회에서 실시간 음성 인식과 번역을 제공하는 웹앱입니다.

## 🌐 Live Demo

**[👉 https://waterfirst.github.io/International-conference-helper/](https://waterfirst.github.io/International-conference-helper/)**

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎤 **Speech Recognition** | Real-time speech-to-text in multiple languages |
| 🌍 **Translation** | Automatic translation to your preferred language |
| 📺 **Live Subtitles** | Display subtitles over camera view |
| 📷 **Camera Support** | Front/back camera with toggle option |
| 💾 **Save Records** | Export translation log as text file |
| 📱 **PWA Support** | Install as app on mobile devices |

## 🗣️ Supported Languages

### Recognition Languages
- 🇺🇸 English
- 🇰🇷 한국어 (Korean)
- 🇯🇵 日本語 (Japanese)
- 🇨🇳 中文 (Chinese)
- 🇩🇪 Deutsch (German)
- 🇫🇷 Français (French)
- 🇪🇸 Español (Spanish)

### Translation Languages
- All of the above

## 📱 How to Use

### On Mobile (Recommended)

1. Open the link in **Chrome** or **Edge** browser
2. Tap **"Add to Home Screen"** for app-like experience
3. Select recognition language (speaker's language)
4. Select translation language (your language)
5. Toggle camera on/off as needed
6. Tap **Start** and point at the speaker
7. See real-time subtitles and translations!

### On Desktop

1. Open the link in Chrome or Edge
2. Allow microphone (and camera if needed) permissions
3. Configure languages and start

## 🎯 Use Cases

- **International Conferences**: Understand presentations in foreign languages
- **Academic Seminars**: Follow along with translated subtitles
- **Business Meetings**: Real-time translation for multilingual teams
- **Language Learning**: Practice listening with subtitle support

## ⚙️ Technical Details

- **Speech Recognition**: Web Speech API
- **Translation**: Google Translate API (free tier)
- **Camera**: MediaDevices API
- **PWA**: Service Worker for offline capability

## ⚠️ Requirements

- **Browser**: Chrome or Edge (Safari has limited support)
- **Permissions**: Microphone required, Camera optional
- **Internet**: Required for speech recognition and translation

## 📝 Output Example

```
=== Conference Helper - Translation Log ===
Saved: 12/1/2025, 3:30:00 PM
Recognition: 🇺🇸 English
Translation: 🇰🇷 한국어
==========================================

[3:25:10 PM]
Original: Today I will talk about OLED technology
Translated: 오늘 저는 OLED 기술에 대해 이야기하겠습니다

[3:25:25 PM]
Original: The main advantage is power efficiency
Translated: 주요 장점은 전력 효율성입니다
```

## 🔒 Privacy

- All processing happens in your browser
- No data is stored on any server
- Camera feed is not recorded or transmitted

## 📄 License

MIT License - Free to use and modify

## 🙏 Credits

Created for international conference attendees who need real-time translation assistance.

---

**Made with ❤️ for the global academic community**
