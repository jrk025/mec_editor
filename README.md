# MEC (My Editor Car)

<img width="606" height="412" alt="appicon-removebg-preview" src="https://github.com/user-attachments/assets/21319a43-a479-41b7-bcbb-2c0e7337ffcd" />

MEC Editor is a powerful, lightweight save game editor designed specifically for My Summer Car (MSC) and My Winter Car (MWC). Built with C++, it provides a fast and intuitive interface for modifying your game's binary save files with safety and precision.

DISCLAIMER!

This tool is currently in Beta. While it includes safety features like automatic backups, always manually back up your defaultES2File.txt or savefile.txt files before making extensive changes. The developer is not responsible for "lost" items or corrupted saves due to improper use.

Features:

    Binary Save Support: Full compatibility with MSC and MWC binary save formats.


    Intelligent Variable Detection:

        Smart Toggles: Automatically detects boolean-like integers (0/1) for parts, purchases, and mission flags.

        Quaternion Support: Handles 16-byte rotation data for precise part orientation.

    Visual Change Tracking: Modified variables are highlighted in Red until saved, allowing you to track unsaved changes easily.

    Safety First: * Auto-Backup: Creates a .bak copy of your save file before every write operation.

    Quick Search: Real-time filtering to find specific variables (e.g., satsuma, money, fluid) instantly.

    Quick Mods (Cheats): A dedicated page for instant modifications.

Built With

    Language: C++17

    Graphics API: DirectX 11

    OS: Windows (Win32 API)

Getting Started
Prerequisites

    Windows 10 or 11.

    DirectX 11 compatible hardware.

Installation

    Download the latest release.

    Run meceditor.exe.

How to Use

    Open: Click "Open Save File" on the Dashboard.

    Locate: Navigate to your save folder (typically AppData/LocalLow/Amistech).

    Edit: Switch to the Variable Editor tab. Use the search bar to find what you want to change.

    Save: Click Save Project in the sidebar. The editor will update your save and keep a backup of the previous state.

Developed by: JrK025

<img width="1266" height="793" alt="Screenshot 2026-01-02 130402" src="https://github.com/user-attachments/assets/47203602-a5b3-4cd3-8664-7c345207977d" />

