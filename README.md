<div align="center">

# ♡ Pixel Precision

### A little desktop aim trainer to practice your flicks and precision. ✧

<img src="https://img.shields.io/badge/Windows-desktop-F7B7C8?style=flat-square&labelColor=F7B7C8&logo=windows&logoColor=6B4F5F" alt="Windows">
<img src="https://img.shields.io/badge/Python-3.10%2B-F4A6C1?style=flat-square&labelColor=F4A6C1&logo=python&logoColor=6B4F5F" alt="Python">
<img src="https://img.shields.io/badge/built%20with-Flet-E8A4B8?style=flat-square&labelColor=E8A4B8&logoColor=6B4F5F" alt="Built with Flet">

<br>

<img src="https://img.shields.io/badge/✿%20made%20with%20care%20by%20ME-✿-F7B7C8?style=flat-square&labelColor=F7B7C8" alt="Made with care by ME">

<br><br>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=F7B7C8" width="80%" alt="pink divider">

</div>

## about

**Pixel Precision** is a lightweight 2D aim trainer made with Python and Flet. Practice hitting moving targets, adjust your crosshair, and keep track of your progress in one desktop window.

> **Language:** The app's interface is available in **English** and **Brazilian Portuguese (Português do Brasil)**. This README is in English.

## features

- Practice in 60-second sessions with targets that move after each hit.
- Customize crosshair color and size.
- Set your VALORANT sensitivity and mouse DPI; view your calculated eDPI.
- Earn 200 points for hitting the white center or 100 points for hitting the outer ring.
- Pause a session, adjust your crosshair, resume, or return to the lobby.
- Save your personal best and session history locally.
- View your progress from the last seven days.
- Export a monthly progress chart as an SVG file.
- Resize the app window; the lobby and training area adapt to its size.

## installation · Windows

1. Download or clone this repository, then open the project folder.
2. Install Python if it is not already installed.
3. Run `instalar.bat`.

The installer creates a local `.venv` environment and installs the app's dependencies. To start the app, open a terminal in the project folder and run:

```powershell
.\.venv\Scripts\python.exe lobby.py
```

To remove the virtual environment and installed dependencies, run `desinstalar.bat`. Your local settings and records will be kept.

## using the trainer

1. Choose a language in the lobby.
2. Select **Start Training**.
3. Move the mouse to move the crosshair, then click to shoot.
4. Press **Esc** or click the pause button to open the pause menu.

## sensitivity notes

Enter the sensitivity and mouse DPI you use in VALORANT. Pixel Precision displays eDPI using:

```text
eDPI = sensitivity × mouse DPI
```

Sensitivity matching is an approximation for this 2D trainer. It does not reproduce VALORANT's 3D camera rotation or raw input.

## local data

The app stores `aim_settings.json` and `progress.json` in the project folder. They contain your preferences and training history and are created as you use the app.

