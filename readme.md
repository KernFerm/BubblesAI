
# 🤖 Bubbles-AI-GPT: Multi-AI Chat Application

A secure, web-based chat interface for talking to multiple AI models from different providers—all in one beautiful, easy-to-use application.

## 🌟 What’s New

- **Logout Flow Improved:** After logging out, you’ll see a pop-up asking if you want to exit and close the app or stay on the login screen.
- **Exit Button:** Cleanly shuts down the server from the browser when you choose to exit.
- **Frontend/Backend Integration:** The app now allows the browser to request the backend server to shut down for a seamless exit experience.

## 🚀 Quick Start Guide

1. **Start the Server**
   - Open your terminal/command prompt.
   - Navigate to this folder: `cd path/to/bubbles-ai-gpt`
   - Run: `python server.py`
   - Your browser will automatically open to `http://localhost:8000`

2. **Sign In or Create Account**
   - New users: Click "Create Account" for a free Puter account.
   - Existing users: Click "Sign In" with your Puter credentials.
   - Required: You must be signed in to access AI chat features.

3. **Choose Your AI**
   - Beginners: Keep "Puter.js" selected—it works immediately!
   - Advanced: Click "⚙️ Configure" to add your own API keys.

4. **Start Chatting!**
   - Type your message and press Enter or click the arrow button.
   - Watch the AI respond in real-time!

5. **Logout and Exit**
   - Click the logout button to sign out.
   - After logout, choose to exit (which shuts down the server and closes the app) or stay on the login screen.

## ✨ Key Features

- **🔄 Multiple AI Providers**: Switch between different AI services instantly
  - **Puter.js** (Default - No API key needed!)
  - **OpenAI** (ChatGPT models)
  - **Anthropic** (Claude models)
  - **Google** (Gemini models)
  - **Groq** (Fast, free models)
  - **Hugging Face** (Open-source models)

- **🎯 Smart Model Selection**: Choose from dozens of AI models
  - GPT-4o, GPT-3.5 Turbo
  - Claude 3.5 Sonnet, Opus, Haiku
  - Gemini Pro, Gemini 1.5 Flash
  - Llama 3, Mixtral, and more!

- **🔒 Privacy & Security**: Your conversations stay private
  - Runs locally on your computer
  - Secure Puter.js authentication required
  - No data sent to third parties (except to chosen AI providers)
  - Secure HTTPS connections only

- **💬 Beautiful Chat Interface**
  - Clean, modern design


# 🤖 BubblesAI Electron Desktop App

A beautiful, secure, multi-provider AI chat application for Windows, built with Electron.

---

## 📦 Windows Installer

**Latest Release:**

- `BubblesAI Setup 1.0.0.exe` (93 MB)
- Built: December 1, 2025
- Location: `dist` folder after build

**How to Install:**
1. Double-click `BubblesAI Setup 1.0.0.exe` to start installation.
2. Follow the on-screen instructions.
3. Application will auto launch.
4. After install, BubblesAI will be created in your Start Menu or Desktop shortcut.

**How to Share:**
- You only need to share the installer file (`BubblesAI Setup 1.0.0.exe`).
- No need to send extra folders or files.

---

## ✨ Features

- **Multi-provider AI chat:**
   - OpenAI (ChatGPT, GPT-4, GPT-3.5, etc.)
   - Anthropic (Claude)
   - Google Gemini
   - Groq (Llama, Mixtral)
   - Hugging Face (open-source models)
- **Modern chat UI:** Responsive, clean, and easy to use
- **Custom installer:** Share your app with a single Windows installer
- **Secure:** No local data storage, all API keys are local
- **Custom icon and branding**

---

## 🛠️ Configuration

- **API keys:** Enter your API key/token for each provider in the app UI.
- **Model selection:** Choose your model (e.g., GPT-4, Claude, Gemini, etc.)
- **Provider selection:** Switch between providers instantly.

---

## 🆘 Troubleshooting

- If you see warnings about deprecated packages, update dependencies with `npm update`.
- If you see symbolic link errors, run your terminal as Administrator or ignore (Windows installer will still build).
- If you see icon size errors, ensure `assets/icon.ico` is at least 256x256 pixels.
- For build errors, check your `package.json` for correct build config.

---

## 💡 About

BubblesAI is designed for students, professionals, and creators who want fast, secure access to the world’s best AI models from a single desktop app.

**Happy chatting! 🚀**
- Work through complex problems

- Get different perspectives on decisions

- Plan projects and organize tasks
