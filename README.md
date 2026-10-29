# Mac Space

macOS-inspired fullscreen Spaces for Windows 11 (x64).

## Download

[Download the latest installer](https://github.com/Samosmao/MacSpace/releases/latest).

Run MacSpace_Setup_v1.0.6.exe. The .NET runtime is included. Installation is for the current Windows user; desktop and Windows startup shortcuts are optional.

Desktop 0 holds ordinary windows. Fullscreen apps get dedicated Spaces. Minimizing, restoring, or closing a window returns it to Desktop 0 and removes its Space. Existing secondary desktops without fullscreen apps are consolidated into Desktop 0 in this mode.

## Updates

The app checks version.json at startup and every 30 minutes while running. It asks before downloading and installing a newer version, verifies its SHA-256 checksum, and exits gracefully for the installer.

For each future update, the maintainer must publish the new installer to a matching GitHub release, then update version.json on main. Editing files only on the developer's computer does not update other users.

Use Quit from the tray menu to exit completely. Closing the dashboard hides it in the tray.

## Requirements and limits

Windows 11 x64. Virtual desktop animation is supplied by Windows. Compatibility with every Windows build, elevated application, exclusive-fullscreen game, or multi-monitor arrangement is not guaranteed. This installer is not digitally signed.

Only installer releases, documentation, and update metadata are published here. Application source code and personal logs are not included.
