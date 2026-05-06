# WinX360 Dashboard
<img width="1550" height="873" alt="image" src="https://github.com/user-attachments/assets/a382ea84-2c73-4e56-a498-9b055f1d33e8" />



> ⚠️ **ALPHA VERSION NOTICE**  
> This project is currently in an early **Alpha** stage. Many features may still be incomplete or non-functional. However, the core functionality is fully operational: you can successfully navigate the dashboard, add and launch games, listen to music, and use apps. Please note that **Controller Support is not working yet** (mouse and keyboard are required).

An interactive dashboard for Windows inspired by the classic Xbox 360 Metro interface. Built with modern web technologies and packaged with Electron, this application allows you to organize and launch your PC games, apps, music, and videos directly from an immersive and nostalgic interface.

## Features

*   **Home Page:** Dynamic tiles showing your recent games, pinned games, and random suggestions from your library. The main tiles are customizable with your own images and shortcuts.
*   **Games:** 
    *   Add any executable (`.exe`) from your PC.
    *   **IGDB API Integration** to automatically fetch original game covers and banners.
    *   Pin your favorite games and keep track of your last played game.
*   **Media (Video & Music):** 
    *   Built-in video and music players.
    *   Select local folders on your PC and the app will automatically scan for `.mp4`, `.mp3`, etc.
    *   Music tracks can have custom covers and can be pinned to the main music screen.
*   **Apps:** Add website links (YouTube, Netflix) or shortcuts to other PC programs.
*   **Portable Configuration:** All your data, saved games, covers, and directories are stored in a portable `config.json` file in the project's root. This means you won't lose your setup if you move the application folder!

## How to Use

1. Go to the **[Releases](../../releases)** page of this repository.
2. Download the latest compiled version.
3. Extract the folder (if downloaded as a zip) to your desired location.
4. Run the executable file (e.g. `winx360.exe`) to launch the dashboard. No extra installation required!

## How to Setup IGDB API (Optional, for automatic game covers)

For the automatic game cover search to work, you can configure the Twitch/IGDB API keys inside the application:
1. Go to the **Games** tab and click on **Add Games**.
2. When trying to search for a game online without keys, the system will prompt you for a `Client ID` and an `App Access Token`.
3. You can get these for free by creating an application in the [Twitch Developer Portal](https://dev.twitch.tv/).

## Built With

*   [React](https://reactjs.org/) + [Vite](https://vitejs.dev/) for the UI/UX.
*   [Electron](https://www.electronjs.org/) for local file system access, launching executables, and window management.
*   Vanilla CSS for authentic Metro visuals, smooth animations, and navigation sound effects.

---
*Made with nostalgia for those who miss the golden era of the Xbox 360 dashboard.*
