# Mochiji

Mochiji is a dictionary and translator that works in every app on your computer. Select a word or a sentence, press a shortcut, and a small window opens next to it with answers from several translators at once. Words you want to remember go into a notebook you can review later.

It runs on macOS, Windows and Linux. Downloads are on the [Releases page](https://github.com/toiladuy/mochiji-releases/releases/latest). The macOS build is there now; Windows and Linux builds come with the next releases.

## What it does

- Translate selected text in any app, or just select it with the mouse and click the small icon that appears.
- Type something to translate in a quick input window.
- Take a screenshot of any part of the screen and translate the text in it, or copy that text out.
- Translate the selection and paste the translation back in its place, or have AI fix the grammar of what you wrote.
- See results from Google, Bing, DeepL, Microsoft and other translators side by side. Some work right away, others need your own account key. AI assistants such as ChatGPT, Claude and Gemini can answer too, and you can give each one its own instructions, for example "explain this like a teacher".
- Use your own dictionary files.
- Work without internet: translation, reading text from screenshots, reading results aloud and voice typing can all run on your computer for Vietnamese, English, Chinese and Japanese, after a one-time download in Settings.
- Keep a history of lookups, mark favorites, and save words to a vocabulary notebook with a simple review routine. Words can be sent to Anki, and everything can be exported or backed up to one file.
- Hear the pronunciation of a word or a whole sentence.
- Pick the look, the size of the text, where the window opens, and which services show up. Every shortcut can be changed.

Default shortcuts:

| | macOS | Windows and Linux |
|---|---|---|
| Translate selected text | `Option+D` | `Ctrl+Alt+D` |
| Type to translate | `Option+A` | `Ctrl+Alt+A` |
| Translate a screenshot | `Option+S` | `Ctrl+Alt+S` |
| Translate and replace | `Option+R` | `Ctrl+Alt+R` |

## Install

### macOS (Apple silicon)

1. Download `Mochiji_<version>_aarch64.dmg`, open it and drag Mochiji into Applications.
2. Open Mochiji. The first time, macOS says it cannot check the developer. Go to System Settings > Privacy & Security, scroll down and click Open Anyway. Or run this once in Terminal:

   ```sh
   xattr -dr com.apple.quarantine /Applications/Mochiji.app
   ```

3. Mochiji asks for Accessibility permission so it can read the text you select. Turn it on for Mochiji in System Settings > Privacy & Security > Accessibility.

### Windows

1. Download `Mochiji_<version>_x64-setup.exe` and run it.
2. If Windows shows "Windows protected your PC", click More info, then Run anyway.

### Linux

Download one of these:

- `Mochiji_<version>_amd64.AppImage`: make it executable with `chmod +x Mochiji_*.AppImage`, then run it.
- `Mochiji_<version>_amd64.deb` for Ubuntu, Debian and similar: `sudo apt install ./Mochiji_*.deb`.

## Updates

Mochiji checks for new versions by itself and downloads them. When one is ready, Restart to update shows up in the tray menu and in Settings > About.

- On macOS and with the Linux AppImage, the new version is already installed, and it also starts by itself the next time you open Mochiji.
- On Windows, clicking Restart to update closes Mochiji, installs the new version and opens it again.
- With the Linux `.deb`, Linux asks for your password to install it.

You can also check right away with Settings > About > Check for updates.
