# 🎙️ Eloquent — AI Speaking Trainer

**Eloquent** is a single-file, client-side web application designed to be your personal AI English speaking coach. It provides real-time feedback on grammar, vocabulary, fluency, pronunciation, and coherence using advanced AI APIs.

![License](https://img.shields.io/badge/license-MIT-green)
![Tech](https://img.shields.io/badge/tech-HTML%20%7C%20CSS%20%7C%20JS-blue)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20PWA-orange)

## ✨ Features

*   **Real-time Speech-to-Text:** Instant transcription of your speech sessions using Deepgram.
*   **5-Dimension Scoring:** Get IELTS-style scores (0-10) on:
    *   📐 **Grammar:** Detects errors and suggests corrections (LanguageTool).
    *   📖 **Vocabulary:** Analyzes unique word count and suggests advanced synonyms (WordsAPI).
    *   🗣️ **Fluency:** Tracks WPM (Words Per Minute) and filler words (*um, uh, like*).
    *   🔊 **Pronunciation:** Phoneme-level analysis (SpeechSuper).
    *   🌀 **Coherence:** Checks for discourse markers, intros, and conclusions.
*   **Topic Generator:** Over 30+ generated topics covering Debates, IELTS Parts 1-3, Daily Life, and Abstract concepts.
*   **Progress Tracking:** Visual graphs, heatmaps, streak counters, and XP leveling system.
*   **Weakness Detection:** The AI identifies recurring issues (e.g., "Frequent filler words" or "Basic vocabulary") and suggests targeted lessons.
*   **100% Client-Side:** No backend server required. All progress data is stored in your browser's `localStorage`.
*   **Mobile Ready (PWA):** Installable as a native-like app on iOS and Android.
*   **Themes:** Choose between *Parchment* (Day), *Midnight* (Night), and *Forest* (Focus).

## 🚀 Quick Start

Since Eloquent is a **Single File Application**, you don't need to install Node.js, Python, or set up a database.

### Option 1: Run Locally
1.  Download the `index.html` file.
2.  Open it directly in any modern browser (Chrome, Safari, Edge).
3.  **Note:** For microphone access to work strictly correctly, some browsers require the file to be served over `localhost` or `https`. You can use a simple extension like "Live Server" in VS Code, or just drag and drop (Microphone permission policies vary by browser for local files).

### Option 2: Deploy for Free (Recommended)
1.  **GitHub Pages:** Upload `index.html` to a repository and enable GitHub Pages in Settings.
2.  **Netlify Drop:** Drag and drop the file into [Netlify Drop](https://app.netlify.com/drop) for an instant HTTPS link.

## 🔑 API Configuration

Eloquent uses third-party APIs to provide its AI features. You can use the app in **Demo Mode** (simulated data) without keys, but for full functionality, you need to add your own keys in the **Settings** menu.

| Service | Feature | Free Tier Availability |
| :--- | :--- | :--- |
| **Deepgram** | Speech-to-Text | ~$200 Free Credit (plenty for personal use) |
| **SpeechSuper** | Pronunciation | Free Trial available |
| **WordsAPI** | Synonyms (via RapidAPI) | 2,500 requests/day free |
| **LanguageTool** | Grammar | Free public API (No key required for basic use) |

*All keys are stored locally in your browser's LocalStorage and are never sent to any server other than the respective API provider.*

## 📱 Mobile Installation (iPhone/Android)

Eloquent is a **Progressive Web App (PWA)**.

1.  Host the file (using GitHub Pages or Netlify).
2.  Open the URL in **Safari** (iOS) or **Chrome** (Android).
3.  Tap **Share** (iOS) or **Menu** (Android).
4.  Select **"Add to Home Screen"**.
5.  Launch it from your home screen like a native app.

## 🛠️ Tech Stack

*   **Core:** Semantic HTML5, CSS3 (Variables, Grid, Flexbox), Vanilla JavaScript (ES6+).
*   **Storage:** `localStorage` (Persists data across sessions).
*   **Audio:** Native Browser `MediaRecorder` API.
*   **Design:** Custom CSS architecture (No Bootstrap/Tailwind). Font: *Lora* and *Plus Jakarta Sans*.

## 🛡️ Privacy Policy

*   **No Data Collection:** The developer of this code collects no data.
*   **Local Storage:** Your progress, streaks, and settings live on your device.
*   **Audio Data:** Audio is streamed temporarily to Deepgram/SpeechSuper for analysis and is **not** stored permanently by the application.
*   **Export:** You can export your progress as a `.json` file from the Progress page for backup.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests!
1.  Fork the repo.
2.  Create a feature branch (`git checkout -b feature/NewFeature`).
3.  Commit your changes (`git commit -m 'Add NewFeature'`).
4.  Push to the branch (`git push origin feature/NewFeature`).
5.  Open a Pull Request.

## 📄 License

This project is open-source and available under the **MIT License**.

---

**Made with ❤️ for English Learners.**
