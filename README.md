# 🎬 VideoToText Converter

A powerful and user-friendly desktop application that converts spoken content from video files into readable text using speech recognition. No Python or setup required — just download and run!

![App Screenshot](https://user-images.githubusercontent.com/your-screenshot-path/video-to-text-ui.png)

---

## 📌 Features

- ✅ Extract audio from video (`.mp4`, `.avi`, `.mov`, `.mkv`, etc.)
- ✅ Automatically transcribe speech to text
- ✅ Dark and light themes (toggle with one click)
- ✅ No Python or external dependencies required
- ✅ Progress bar and real-time status updates
- ✅ Clean, modern interface with `ttkbootstrap`

---

## 🖥️ Built With

- [Python](https://www.python.org/)
- [Tkinter + ttkbootstrap](https://ttkbootstrap.readthedocs.io/)
- [moviepy](https://github.com/Zulko/moviepy)
- [pydub](https://github.com/jiaaro/pydub)
- [SpeechRecognition](https://github.com/Uberi/speech_recognition)
- [FFmpeg](https://ffmpeg.org/)

---

## 🚀 Getting Started

### 🔧 For End Users

Download the latest `.exe` installer from the [Releases](https://github.com/your-username/your-repo-name/releases) tab and run:

- ✅ No installation of Python or libraries needed
- ✅ Works out of the box on Windows
- ✅ Optional: Create a desktop shortcut during installation

> If you downloaded the portable `script.exe`, simply double-click to run.

---

## 📦 Download

➡️ [Latest Release (v1.0)](https://github.com/your-username/your-repo-name/releases/latest)

- 🔹 `VideoToText_Installer.exe` – Full Windows installer
- 🔹 `script.exe` – Portable single-file executable

---

## 📁 How It Works

1. Select a video file.
2. Choose an output folder.
3. Click **"Extract Text"**.
4. The app:
   - Extracts audio using FFmpeg
   - Splits audio into 1-minute chunks
   - Transcribes each chunk with Google's speech API
   - Saves a final text file in the chosen directory

---

## 📸 Screenshots

| Dark Theme | Light Theme |
|------------|-------------|
| ![Dark](https://user-images.githubusercontent.com/your-path/dark-mode.png) | ![Light](https://user-images.githubusercontent.com/your-path/light-mode.png) |

---
