# 💜 Vantoryn Desk — Free Windows Desktop Widgets

**Your Desktop, Your Way.** | [Downloads and updates](https://github.com/DavidV20230/vantoryn-desk/releases) | [Report an issue](https://github.com/DavidV20230/vantoryn-desk/issues)

Vantoryn Desk is a free desktop widget application for **Windows 10/11 (64-bit)**. Choose the tools you actually need, move and resize windows, and use compact or collapsed layouts to keep system information, gaming performance, network status, market data, and productivity tools close at hand.

This is a **personal project created and revised with extensive assistance from generative AI**, then adjusted based on hands-on testing. I am sharing it simply because others might find it useful. There is **no fee or donation requirement**, and it is not presented as a professionally supported commercial product. The current build is **Public Preview v6**.

## 📥 Download the right package

| Download | What it contains | How to use it |
|---|---|---|
| `VantorynDesk-Setup-v6-Windows-x64.exe` | **Windows installer**, recommended for most users | Run setup, choose a folder, then launch using the desktop shortcut |
| `VantorynDesk-Windows-x64-Portable-v6-Trilingual.zip` | **Complete portable application**, prepared separately | **Extract the entire ZIP** and run `VantorynDesk.exe` |
| Automatically generated `Source code (zip)` or `Source code (tar.gz)` | A snapshot of the GitHub repository | **Not the Windows app** and not a substitute for the portable package |

Open the [GitHub v6 Release](https://github.com/DavidV20230/vantoryn-desk/releases/tag/preview-v6) and check the **Assets** section. If the trilingual Portable ZIP is not listed there yet, it has not been uploaded. Do not substitute GitHub's automatic Source code ZIP.

## 🧩 Customization and desktop layouts

- **Choose widgets:** Use the tool-selection screen to display just the functions you want for work, games, or everyday tasks.
- **Place them freely:** Drag a widget to your preferred location. The draggable region can differ between widgets.
- **Resize supported widgets:** Drag their edges or corners to adjust the layout. v6 includes attempts to reduce redraws and clipping during resizing, but results still depend on the device and widget content.
- **Use compact and collapsed modes:** Minimize the screen area used by supported tools. The Gaming Performance widget includes a compact screen-edge tab layout.
- **Adjust appearance:** Some widgets offer opacity, background, or display options. Available controls depend on the specific widget.
- **Personalize content:** Add tasks, change focus and break durations, follow selected stocks and indices, or add frequently used web links where supported.
- **Switch languages:** A fresh installation defaults to **English**. Use the dropdown in the **top-right of the tool-selection screen** to select **English / Traditional Chinese / Japanese**. Your choice is retained in your user settings.

## ✨ Features at a glance

| Category | Purpose |
|---|---|
| 🎮 Gaming Performance | View supported FPS, network latency, and selected GPU information, with compact and edge-tab options |
| 🖥️ System monitoring | View available CPU, GPU, VRAM, memory, and storage information depending on your hardware |
| 🌐 Network status | Observe connection information and network activity where available |
| 📈 Stocks and market data | Set up watchlists or indices and view supported quotes and charts |
| ₿ Cryptocurrency | Reference prices and changes for selected coins; no built-in trading |
| 🌤️ Weather and news | Weather forecasts and news from available external sources |
| ✅ Tasks and notes | Maintain personal tasks, reminders, and notes |
| ⏱️ Focus timer | Use preset work/break intervals or adjust timing yourself |
| 🕒 Clock, calendar, alerts | Everyday time and reminder utilities |
| 🔗 Web links and controller tools | Add web shortcuts and inspect compatible game controllers where supported |

**Limitations:** Feature availability depends on the preview version, Windows configuration, device hardware, system permissions, external websites, and APIs. FPS, ping, GPU, and market readings may differ from other applications. This preview does **not** provide CPU or GPU temperature monitoring.

## 🖥️ Installing with Setup EXE

1. Open the [v6 Release page](https://github.com/DavidV20230/vantoryn-desk/releases/tag/preview-v6) and download `VantorynDesk-Setup-v6-Windows-x64.exe` under **Assets**.
2. Run Setup and select the **exact destination folder** you want. The progress indicator tracks local installation work, not network download speed.
3. After successful installation, Setup is designed to launch the application and close automatically.
4. On later launches, use the desktop or Start menu shortcut rather than reopening Setup.
5. To uninstall, find the corresponding installed application in Windows Settings.

## 📦 Running the Portable ZIP

1. Download the Portable ZIP explicitly listed under the release **Assets**. Do not select the generated Source code ZIP.
2. In File Explorer, choose **Extract All** and put the folder somewhere convenient, for example `D:\Apps\VantorynDesk`.
3. Open the extracted `VantorynDesk-Portable-v6` folder and double-click `VantorynDesk.exe`.
4. **Keep the files together.** Do not pull the EXE out by itself; the `sounds/` folder and other resources must stay in their relative locations.
5. Portable does not run an installation wizard, create desktop shortcuts automatically, or register an uninstaller. You may create your own shortcut.
6. Back up settings before deleting the application folder; some user preferences may also be stored in Windows AppData.

## 🔧 Troubleshooting and FAQs

**Q: The EXE inside the ZIP does not open.** First extract the complete archive. Check Windows 10/11 x64 compatibility, ensure the application files are together, and review any Windows security warnings. Do not disable antivirus protection just to run this software.

**Q: Why is GitHub's Source code ZIP different?** GitHub creates it automatically from repository contents. The separately uploaded Portable ZIP is intended to contain the Windows executable and its resources.

**Q: Setup keeps appearing.** Launch the installed app from its desktop shortcut rather than running Setup again. The installer may check whether the same build is already intact; other builds may require repair or update.

**Q: Resizing is still choppy or clips the display.** Report the affected widget, which edge you dragged, your Windows version, and a privacy-safe screenshot through [Issues](https://github.com/DavidV20230/vantoryn-desk/issues).

**Q: No FPS or market value is shown.** The service, hardware, game, or required permissions may be unavailable. A blank value is not the same as zero, and it is not a hardware failure diagnosis.

## 🤖 AI-assisted development and disclaimer

Vantoryn Desk is a **free personal sharing project created with substantial help from generative AI**. I define the desired functions and test changes, but the generated code has **not been independently audited for all security and compatibility risks**. I am not charging for the program or asking for donations; I cannot promise a release schedule, continuous support, or operation on every Windows PC.

- As a **public preview**, it may still contain bugs, performance problems, compatibility limitations, or undiscovered security issues. Back up important data before use.
- Financial quotes, cryptocurrency prices, news, and weather rely on external providers and may be late, unavailable, or incomplete. They are **not investment or trading advice**.
- Hardware and gaming readings are informational and do not replace professional diagnostics.
- The application may save preferences locally; never include passwords, tokens, private keys, or personal data in issue reports or public screenshots.
- The current Windows preview is **not code-signed and has not completed extensive real-device security validation**. Download from the official release and verify the file origin; stop if you have safety concerns.
- To the extent permitted by applicable law, this program is provided **as-is**, without a promise of uninterrupted operation, error-free performance, or fitness for a particular purpose. This statement does not waive rights that cannot legally be waived.
- **Freeware is not the same as open source.** The repository does not currently contain the complete corresponding source code or a stated open-source license. Do not assume unrestricted redistribution or modification rights.

## 📸 Screenshots and feedback

Screenshots on the project page will be **real Windows application captures**, with private information cropped or obscured. AI-generated interface mockups will not be presented as actual product screenshots. The screenshot gallery is still being prepared.

Bug reports and suggestions: [GitHub Issues](https://github.com/DavidV20230/vantoryn-desk/issues). Please include steps to reproduce the issue, but no private data.

**Created and freely shared by David_V / DavidV20230 💜**
