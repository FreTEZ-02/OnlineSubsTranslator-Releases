# OnlineSubsTranslator

**English** · [Русский](README.ru.md) · [Releases](https://github.com/FreTEZ-02/OnlineSubsTranslator-Releases/releases)

OnlineSubsTranslator is a desktop app for translating subtitles by hand. The editor opens in your browser. Import YouTube captions or an SRT file, edit the text and timing, and download your translation as an SRT. Whisper can also transcribe speech on your device.

## Get the app

Encrypted update packages are available on the [Releases page](https://github.com/FreTEZ-02/OnlineSubsTranslator-Releases/releases). To join closed testing, get the installer for your system and a signed `.ostkey` access file from the project owner. The installer selects the build for your computer.

## Install and open

- **Windows.** Select **Extract All** to unpack the ZIP. Open `Install-OnlineSubsTranslator.cmd` in the extracted folder.
- **macOS 13 Ventura or later.** Unpack the ZIP in Finder and open `OnlineSubsTranslator.app`. macOS may ask you to confirm the first launch of a trusted copy. [Apple’s first-launch instructions](https://support.apple.com/en-us/102445)
- **Linux.** Unpack the archive and run `Install-OnlineSubsTranslator.sh` from the extracted folder. If the file manager opens it as text, open a terminal in that folder and run `sh ./Install-OnlineSubsTranslator.sh`.

On the first launch, select your `.ostkey` in the browser and click **Install**. Open the same launcher to use the editor again. Downloaded updates take effect on the next launch.

After installation, the editor opens in your default browser. If the tab does not open automatically, go to `http://127.0.0.1:4174/`. Use the language menu at the top to choose **English** or **Русский**.

## Translate and export

1. Paste a video link and import a caption track, or open an SRT from your computer.
2. Select a caption, enter its translation, and adjust the timing as needed.
3. Click **Download SRT** to save the translated captions.

Before using Whisper for the first time, open **Self-check → Check and repair**. Downloading the models requires an internet connection.
