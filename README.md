
# JARVIS AI — Personal AI Assistant

JARVIS AI is a futuristic, mobile-first personal AI assistant built as a Progressive Web App (PWA).

It is designed to provide a modern JARVIS-style experience with AI chat, voice interaction, local memory, conversation history and a secure cloud-based AI connection.

## ✨ Features

- 🤖 AI-powered JARVIS assistant
- 🎙️ Hindi/Hinglish voice input
- 🔊 Text-to-speech voice response
- 🧠 Automatic memory commands
- 💬 Conversation history
- 💾 Local memory storage
- 📱 Mobile-first futuristic interface
- ⚡ Progressive Web App (PWA)
- 🔐 Secure Gemini API connection through Cloudflare Worker
- 🚫 Gemini API key is NOT stored in the frontend
- 🌐 GitHub Pages deployment

## 🧠 Memory

JARVIS can remember information when you use commands such as:

- "मेरा नाम Raju है, इसे याद रखो"
- "याद रखो कि मुझे video editing पसंद है"
- "Remember that I use Hindi"

You can also manage saved memories manually from the Memory section.

## 🔐 Security

The Gemini API key is kept securely as a Cloudflare Worker Secret.

The frontend communicates with the secure Worker instead of exposing the Gemini API key inside the website.

### Architecture

Phone / JARVIS PWA
        ↓
HTTPS
        ↓
Cloudflare Worker
        ↓
Gemini API

## 🚀 Deployment

The JARVIS PWA can be hosted using GitHub Pages.

The application is designed primarily for mobile use and can also be installed as a PWA on supported devices.

## 🛠️ Technologies

- HTML
- CSS
- JavaScript
- Web Speech API
- LocalStorage
- PWA
- Cloudflare Workers
- Google Gemini API
- GitHub Pages

## 📱 Project

JARVIS AI is a personal AI assistant project focused on creating a futuristic, secure and mobile-friendly AI experience.

---

**Built with ❤️ for a personal JARVIS-style AI experience.**
