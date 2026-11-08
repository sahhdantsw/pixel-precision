<h1 align="center">Pixel Precision</h1>

<h3 align="center">A lightweight desktop aim trainer to practice your flicks and precision</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-555555?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/Python-3.10%2B-555555?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.10+">
  <img src="https://img.shields.io/badge/Built%20with-Flet-555555?style=for-the-badge&logo=flutter&logoColor=white" alt="Built with Flet">
  <img src="https://img.shields.io/badge/Language-English%20%7C%20Portugu%C3%AAs%20(BR)-555555?style=for-the-badge" alt="English and Brazilian Portuguese">
</p>

---

## About

**Pixel Precision** is a lightweight, general-purpose 2D aim trainer made with Python and Flet. Practice hitting moving targets, adjust your crosshair and sensitivity, and keep track of your progress in one desktop window. It can be used alongside different games that let you adjust mouse sensitivity; VALORANT was simply the original reference game for this project.

- 🌐 **Language:** the app's interface is available in **English** and **Brazilian Portuguese (Português do Brasil)**. This README is in English

---

## Features

- 🎯 Practice in 60-second sessions with targets that move after each hit
- 🎨 Customize crosshair color and size
- 🖱️ Set an in-game sensitivity and mouse DPI, and view the calculated eDPI
- 🏆 Earn 200 points for hitting the white center or 100 points for hitting the outer ring
- ⏸️ Pause a session, adjust your crosshair, resume, or return to the lobby
- 💾 Save your personal best and session history locally
- 📈 View your progress from the last seven days
- 📊 Export a monthly progress chart as an SVG file
- 🖥️ Resize the app window; the lobby and training area adapt to its size

---

## Installation (Windows)

1. Download or clone this repository, then open the project folder
2. Install Python if it is not already installed
3. Run `instalar.bat`

The installer creates a local `.venv` environment and installs the app's dependencies. To start the app, open a terminal in the project folder and run:

```powershell
.\.venv\Scripts\python.exe lobby.py
```

To remove the virtual environment and installed dependencies, run `desinstalar.bat`. Your local settings and records will be kept.

---

## Using the trainer

1. Choose a language in the lobby
2. Select **Start Training**
3. Move the mouse to move the crosshair, then click to shoot
4. Press **Esc** or click the pause button to open the pause menu

---

## Sensitivity notes

Enter the sensitivity and mouse DPI you use in your game. Pixel Precision displays eDPI using:

```text
eDPI = sensitivity × mouse DPI
```

> Sensitivity matching is an approximation. Games can interpret sensitivity differently, and this trainer does not read a game's settings or reproduce its 3D camera rotation or raw input. Use the values as a starting point and adjust them to feel comfortable.

---

## Local data

The app stores `aim_settings.json` and `progress.json` in the project folder. They contain your preferences and training history and are created as you use the app.
