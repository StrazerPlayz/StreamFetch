# 🎬 YouTube Downloader

> Fetch your media. Fast.

A powerful and easy-to-use YouTube downloader built with **yt-dlp**.
Download videos, audio, playlists, and more — all in one clean interface.

---

![Version](https://img.shields.io/badge/version-1.0.4-blue)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Powered by](https://img.shields.io/badge/powered%20by-yt--dlp-red)

---

## 🚀 Features

* 🎬 Download videos in multiple qualities (up to best available)
* 🎵 Extract audio (MP3, WAV, etc.)
* 📋 Queue multiple URLs
* 📊 Real-time download progress
* 📁 Automatic file organization
* 🎨 Clean and user-friendly interface
* 🔐 Member-only content support (with authentication)

---

## 🆕 Version 1.0.4

### 🚨 Critical Fixes

* Fixed startup crash on some systems:

  * `Failed to load Python DLL from _MEI... temp path`

* Switched internal app packaging from **PyInstaller onefile → onedir** for improved runtime reliability

* Updated installer to deploy the full stable app runtime folder

---

### ⚙️ Stability

* Improved compatibility across different Windows environments

* Continued using bundled Visual C++ runtime dependencies for safer launch behavior

---

## 🆕 Version 1.0.3

### 🛠️ Fixes

* Rebuilt the app using **python.org Python (3.14)** instead of Microsoft Store Python for improved packaging reliability

* Fixed startup crash on some systems:

  * `Failed to load Python DLL (python313.dll)`

* Bundled required Visual C++ runtime dependencies:

  * `MSVCP140.dll`
  * `VCRUNTIME140.dll`
  * `VCRUNTIME140_1.dll`

---

## 🔐 Member-Only Content

This downloader supports restricted or member-only videos **only if you have access**.

To use this feature:

* You must be a member of the channel
* Authentication (cookies/login) is required

---

## 📥 Download

Go to the **Releases** tab and download the latest version.

---

## ⚙️ Built With

* [yt-dlp](https://github.com/yt-dlp/yt-dlp)
* Python

---

## ⚠️ Disclaimer

This tool is intended for personal use only.
Please respect YouTube’s Terms of Service and support content creators.

---
