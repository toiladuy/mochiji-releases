# Mochiji releases

Builds of [Mochiji](https://github.com/toiladuy/mochiji), a system-wide dictionary and translator for macOS (Apple silicon, macOS 15+).

## Install

1. Download `Mochiji_<version>_aarch64.dmg` from the [latest release](https://github.com/toiladuy/mochiji-releases/releases/latest) and drag Mochiji to Applications.
2. Open it. macOS says it cannot verify the developer, because Mochiji is not notarized. Open **System Settings > Privacy & Security**, scroll down and click **Open Anyway**. Or run:

   ```sh
   xattr -dr com.apple.quarantine /Applications/Mochiji.app
   ```

This is needed only once. Mochiji then updates itself: it checks this repository at start and daily, installs a new version in the background, and runs it from the next start. **Settings > About > Check for updates** applies one at once.
