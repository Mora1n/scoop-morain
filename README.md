# Scoop Bucket

A personal Scoop bucket for various applications and tools.

## Installation

Add this bucket to your Scoop installation:

```powershell
scoop bucket add scoop-morain https://github.com/Mora1n/scoop-morain
```

## Available Apps

### Weasel

Rime Input Method Engine for Windows - A powerful and customizable Chinese input method.

**Install:**
```powershell
# Requires administrator privileges
scoop install sudo
sudo scoop install scoop-morain/weasel
```

**Features:**
- Rime input method engine with extensive customization
- Support for multiple input schemas (Pinyin, Cangjie, etc.)
- Highly configurable through YAML files
- Active community and schema ecosystem

**Version:** 0.17.4

**Note:** Please restart or log out of Windows after installation for the input method to take effect.

---

### Taskwarrior TUI

A terminal user interface for Taskwarrior - An elegant and efficient task management interface.

**Install:**
```powershell
scoop install scoop-morain/taskwarrior-tui
```

**Features:**
- Beautiful terminal UI for Taskwarrior
- Fast and responsive task management
- Full Taskwarrior functionality in an intuitive interface
- Keyboard-driven workflow

**Version:** 0.26.5

**Note:** Requires Taskwarrior to be installed separately:
```powershell
scoop install main/task
```

---

### Kanata Wintercept

A cross-platform software keyboard remapper with Interception driver support (GUI version).

**Install:**
```powershell
scoop install scoop-morain/kanata_wintercept
```

**Features:**
- GUI wintercept variant with Interception driver
- Automatic dependency handling (interception.dll)
- Low-level keyboard input interception
- Configuration files persist across updates

**Version:** 1.10.1

**Executable:** `kanata_windows_gui_wintercept_x64.exe`

**Configuration Location:** `$SCOOP/persist/kanata_wintercept/`

Place your `kanata.kbd` and other configuration files in the persist directory.

---

## Usage

After adding the bucket, install any app with:

```powershell
scoop install scoop-morain/<app-name>
```

Update apps:

```powershell
scoop update
scoop update <app-name>
```

## Repository Structure

```
scoop-morain/
├── bucket/
│   ├── kanata_wintercept.json
│   ├── taskwarrior-tui.json
│   └── weasel.json
├── README.md
└── LICENSE
```

## Uninstallation

Remove an app:

```powershell
scoop uninstall <app-name>
```

Remove this bucket:

```powershell
scoop bucket rm scoop-morain
```

## Contributing

This is a personal bucket, but suggestions and bug reports are welcome via Issues.

## License

MIT License

## Links

- [Scoop](https://scoop.sh/) - A command-line installer for Windows
- [Weasel](https://github.com/rime/weasel) - Rime Input Method Engine for Windows
- [Taskwarrior TUI](https://github.com/kdheepak/taskwarrior-tui) - Terminal UI for Taskwarrior
- [Kanata](https://github.com/jtroo/kanata) - Keyboard remapper

