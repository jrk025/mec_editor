# mec_editor
MEC Editor (My Editor Car)

MEC Editor is a powerful, lightweight save game editor designed specifically for My Summer Car (MSC) and My Winter Car (MWC). Built with C++ and Dear ImGui, it provides a fast and intuitive interface for modifying your game's binary save files with safety and precision.
🚀 Features

    Binary Save Support: Full compatibility with MSC and MWC binary save formats.

    Intelligent Variable Detection:

        Smart Toggles: Automatically detects boolean-like integers (0/1) for parts, purchases, and mission flags.

        Vector3 Editor: Detects 12-byte data blocks and presents them as [X, Y, Z] coordinates for easy object teleportation.

        Quaternion Support: Handles 16-byte rotation data for precise part orientation.

    Visual Change Tracking: Modified variables are highlighted in Red until saved, allowing you to track unsaved changes easily.

    Safety First: * Auto-Backup: Creates a .bak copy of your save file before every write operation.

        Coordinate Tagging: Displays [POS X/Y/Z] or [ROT] tags next to variables to prevent accidental editing of critical physics data.

    Quick Search: Real-time filtering to find specific variables (e.g., satsuma, money, fluid) instantly.

    Quick Mods (Cheats): A dedicated page for instant modifications.

🛠️ Built With

    Language: C++17

    Graphics API: DirectX 11

    OS: Windows (Win32 API)

🖥️ Getting Started
Prerequisites

    Windows 10 or 11.

    DirectX 11 compatible hardware.

Installation

    Download the latest release.

    Extract the .zip to any folder.

    Run meceditor.exe.

How to Use

    Open: Click "Open Save File" on the Dashboard.

    Locate: Navigate to your save folder (typically AppData/LocalLow/Amistech).

    Edit: Switch to the Variable Editor tab. Use the search bar to find what you want to change.

    Save: Click Save Project in the sidebar. The editor will update your save and keep a backup of the previous state.

⚠️ Disclaimer

This tool is currently in Beta. While it includes safety features like automatic backups, always manually back up your defaultES2File.txt or savefile.txt files before making extensive changes. The developer is not responsible for "lost" items or corrupted saves due to improper use.

Developed by: JrK025
