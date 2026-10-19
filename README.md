# FlowBench

Downloads for the FlowBench desktop app: flow cytometry, cell, extracellular-vesicle and
nanoparticle analysis of FCS files. Research use only; not for clinical or diagnostic use.

## Download

Get the latest version from **[Releases](../../releases/latest)**:

| System | File |
| --- | --- |
| Windows 10/11 (64-bit) | `FlowBench-Setup-<version>.exe` (recommended) |
| Windows, without installing | `FlowBench-<version>-windows-x64.exe` |
| macOS (Apple silicon) | `FlowBench-<version>-mac-arm64.dmg` |
| macOS (Intel) | `FlowBench-<version>-mac-x86_64.dmg` |

**Windows:** run `FlowBench-Setup-<version>.exe`. It installs FlowBench for your Windows account (no
administrator rights needed), puts **FlowBench** on your Desktop and in the Start menu, and adds it to
Settings → Apps, where you can uninstall it. If Windows shows "Windows protected your PC", choose
**More info → Run anyway**. The `…-windows-x64.exe` file is the same app without installing (no shortcuts);
keep it in a folder you can write to, such as Documents, so it can update itself.

**macOS:** open the `.dmg` and drag FlowBench into Applications. The first time you open it, right-click
FlowBench and choose **Open** (or System Settings → Privacy & Security → **Open Anyway**).

Your data stays on your computer, in the `.flowbench` folder in your home folder.

## Updates

FlowBench checks for a new version when it starts (this can be switched off in Settings). When one is
available it asks first. If you choose **Update now** it downloads the new version, checks it against the
SHA-256 checksum published with the release, replaces the app and restarts. Your data is not touched.
