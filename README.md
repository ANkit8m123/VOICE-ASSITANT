# Auralis

A browser-based voice assistant with a glowing reactive orb UI, natural-language intent parsing, speech recognition + synthesis, and live weather lookups.

## Features
- 🎙️ Voice input via the Web Speech API (with graceful text-input fallback)
- 🔊 Text-to-speech responses
- 🌤️ Live weather via the free [Open-Meteo](https://open-meteo.com/) API (no key required)
- ⏰ Time / date queries
- 🔍 Web search shortcut
- ⏱️ Simple reminders (in-session, with delay parsing e.g. "in 5 minutes")
- 😄 Jokes, greetings, help, and a few other intents
- ✨ Animated orb UI that reacts to listening/speaking state
- 📱 Responsive layout

## Tech
- Pure HTML/CSS/JavaScript — no build step, no dependencies
- Web Speech API (`SpeechRecognition`, `SpeechSynthesisUtterance`)
- Open-Meteo Geocoding + Forecast APIs
- Google Fonts (Space Grotesk, Space Mono, Inter)

## Usage
Just open `index.html` in a modern browser (Chrome or Edge recommended for full speech recognition support). No server or install required.

## Browser support notes
Speech *recognition* currently only works in Chromium-based browsers (Chrome, Edge). Speech *synthesis* (the assistant talking back) works more broadly. If recognition isn't available, Auralis automatically falls back to text input.

## License
MIT
