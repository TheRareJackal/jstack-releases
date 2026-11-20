# JStack

JStack is a browser for Windows that lays your pages out as cards side by side, grouped into stacks and Flows.

This repository holds the downloads and the update feed only. There is no source code here.

## Download

**[Download JStack for Windows](https://github.com/TheRareJackal/jstack-releases/releases/latest/download/JStack-windows-x64.zip)** (Windows 10 or 11, 64-bit)

1. Unpack the zip into a folder you can write to, for example your Documents folder (not `Program Files`).
2. Run `JStack.exe`.

Later versions install from inside the app: Settings, General, "Check for updates…".

## Good to know

- The builds are not code-signed yet. Windows SmartScreen may warn before the first start: choose "More info", then "Run anyway".
- Each release lists the SHA-256 of its zip in `SHA256SUMS.txt`. The app checks the same value before it installs an update.
- Your cards and settings are kept in `%LOCALAPPDATA%\JStack`, outside the app's folder, so updating or moving the app does not touch them.
- To remove JStack, delete its folder and, for its data, `%LOCALAPPDATA%\JStack`.
- There is no macOS or Linux build.
