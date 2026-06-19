
# 🔊 Text to Speech (aka The Voiceinator) 

A fun browser-based experiment using the Web Speech API to synthesize speech from text. This project demonstrates how to list available voices, adjust pitch and rate, and speak custom text directly in the browser.


## 🚀 Features

- Voice selection: Choose from available voices exposed by your browser/OS
- Pitch and rate controls: Adjust how the voice sounds
- Text-to-speech: Type any text and hear it spoken aloud
- Stop/Start buttons: Cancel or replay speech


## 🎙️ Demo

![Demo of Voiceinator](./images/demo.gif)


## ❓ Known Issues

- Voice list may appear empty until the voiceschanged event fires.
- Mobile devices often don’t expose voices, so dropdown may remain blank.
- Different browsers provide different sets of voices.

