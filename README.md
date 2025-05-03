# 🎬 VideoToText Converter
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=flat&logo=python)](https://www.python.org)
[![Tkinter](https://img.shields.io/badge/GUI-Tkinter%20%2B%20TTKBootstrap-yellow)](https://ttkbootstrap.readthedocs.io/)
[![FFmpeg](https://img.shields.io/badge/FFmpeg-4.4%20%2B%20-%23FF0000)](https://ffmpeg.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)


---

## 📖 Introduction

The **VideoToText Converter** is a simple and efficient desktop application that helps users convert spoken content from video files into readable text. It leverages speech recognition technology to transcribe audio from video files in various formats such as `.mp4`, `.avi`, `.mov`, and `.mkv`. This tool is perfect for creating subtitles, transcribing lectures or meetings, and more. With no setup or Python knowledge required, users can easily extract and transcribe text with just a few clicks.



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

Download the latest `.exe` installer from the [Releases](https://github.com/Mobeen-01/VideoToText-DesktopApp/releases) tab and run:

- ✅ No installation of Python or libraries needed  
- ✅ Works out of the box on Windows  
- ✅ Optional: Create a desktop shortcut during installation  

➡️ **Quick Download**:  
Use the direct link below to download the full installer:

> [Download VideoToText_Installer.exe](https://github.com/Mobeen-01/VideoToText-DesktopApp/releases/download/v1.0/VideoToText_Installer.exe)

Or if you'd like to browse other versions:  
Go to [v1.0 Release](https://github.com/Mobeen-01/VideoToText-DesktopApp/releases/tag/v1.0), scroll to **Assets**, and download `VideoToText_Installer.exe`.

> If you downloaded the portable `script.exe`, simply double-click to run.

---

## 🎥 Demo Video

📺 Watch how to **download, install, and use** the app:  
[🔗 Installation Guide (Video)](https://github.com/Mobeen-01/VideoToText-DesktopApp/blob/main/Intsallation_Guide.mp4)

▶️ See a **demo of how to use the app and get the output**:  
[🔗 App Demo Video](https://github.com/Mobeen-01/VideoToText-DesktopApp/blob/main/App_demo.mp4)

---

## 📦 Download

➡️ [Latest Release (v1.0)](https://github.com/Mobeen-01/VideoToText-DesktopApp/releases/tag/v1.0)

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
| ![Dark](https://github.com/Mobeen-01/VideoToText-DesktopApp/blob/main/GUI_Dark_Theme.png) | ![Light](https://github.com/Mobeen-01/VideoToText-DesktopApp/blob/main/GUI_Light_Theme.png) |

---
