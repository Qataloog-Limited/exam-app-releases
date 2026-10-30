# Qataloog eXam: download and install

Qataloog eXam is the desktop app for taking proctored exams. Version **1.2.2**.

## 1. Download

Click the file for your computer to download it, or see all files on the **[Releases page](https://github.com/Qataloog-Limited/exam-app-releases/releases/latest)**:

| Your computer | File to download |
|---|---|
| Mac with Apple chip (M1, M2, M3, M4) | [`QataloogeXam-1.2.2-arm64.dmg`](https://github.com/Qataloog-Limited/exam-app-releases/releases/latest/download/QataloogeXam-1.2.2-arm64.dmg) |
| Mac with Intel chip | [`QataloogeXam-1.2.2-x64.dmg`](https://github.com/Qataloog-Limited/exam-app-releases/releases/latest/download/QataloogeXam-1.2.2-x64.dmg) |
| Windows 10 / 11 (64-bit) | [`QataloogeXam-1.2.2-setup.exe`](https://github.com/Qataloog-Limited/exam-app-releases/releases/latest/download/QataloogeXam-1.2.2-setup.exe) |
| Linux: Ubuntu / Debian | [`QataloogeXam_1.2.2_amd64.deb`](https://github.com/Qataloog-Limited/exam-app-releases/releases/latest/download/QataloogeXam_1.2.2_amd64.deb) |
| Linux: any other (64-bit) | [`QataloogeXam-1.2.2.AppImage`](https://github.com/Qataloog-Limited/exam-app-releases/releases/latest/download/QataloogeXam-1.2.2.AppImage) |

Not sure which Mac you have? Click the Apple menu → **About This Mac**. If it says "Chip: Apple M…", pick the Apple chip file. If it says "Processor: Intel", pick Intel.

## 2. Install

### macOS
1. Open the `.dmg` file and drag **Qataloog eXam** into **Applications**.
2. The first time, open **Applications**, **right-click** Qataloog eXam and choose **Open**, then click **Open** again.
   A normal double-click shows "cannot be verified" the first time. Right-click → Open only needs to be done once.
3. Allow the app in **System Settings → Privacy & Security**:
   - **Camera**: on
   - **Microphone**: on
   - **Screen & System Audio Recording**: on
4. **Quit the app (⌘Q) and open it again** after turning on Screen Recording, or screen sharing will fail.

### Windows
1. Run `QataloogeXam-1.2.2-setup.exe`.
2. If Windows shows "Windows protected your PC", click **More info → Run anyway**.
3. Allow camera and microphone when the app asks.

### Linux
- **.deb (Ubuntu / Debian):** `sudo apt install ./QataloogeXam_1.2.2_amd64.deb`
- **AppImage:** `chmod +x QataloogeXam-1.2.2.AppImage`, then run `./QataloogeXam-1.2.2.AppImage`

## 3. Before your exam

- **Use one screen only.** Unplug external monitors and projectors and turn off screen mirroring.
- **Close these apps:** Zoom, Microsoft Teams, Skype, WhatsApp, Telegram, Discord, AnyDesk, TeamViewer, OBS, ChatGPT, Claude, Copilot, Gemini, Perplexity.
  The exam will not start while any of them is open. If one is opened during the exam, it is closed and your proctor is told.
- Check that your camera, microphone and screen sharing all show **Ready** on the device check page.
- Use a stable internet connection.

Once the exam starts, the app stays locked in full screen until you submit or the time runs out.

## Check your download (optional)

[`SHA256SUMS.txt`](https://github.com/Qataloog-Limited/exam-app-releases/releases/latest/download/SHA256SUMS.txt) lists a checksum for every file. To check a file:

- **macOS / Linux:** `shasum -a 256 <file>` and compare with the line in `SHA256SUMS.txt`
- **Windows (PowerShell):** `Get-FileHash <file> -Algorithm SHA256`

## Help

Use the **Need help?** chat inside the app, or contact your exam organiser.
