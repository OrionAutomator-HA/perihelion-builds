# Perihelion builds

Packaged builds of Perihelion and its launcher. No source code lives here.

**To play:** download `PerihelionLauncher.exe` from the [latest release](https://github.com/OrionAutomator-HA/perihelion-builds/releases/latest) and run it. It installs the game under `%LOCALAPPDATA%\Perihelion`, adds shortcuts, and updates the game and itself whenever you open it.

Each release carries a `manifest.json` listing every game file with its size and SHA-256. Files unchanged since an earlier release are downloaded from that release, so updates only fetch what changed. **Do not delete old releases**: newer manifests may point at their files.
