# Scoop Bucket

A personal Scoop bucket for various applications and tools.

## Installation

Add this bucket to your Scoop installation:

```powershell
scoop bucket add scoop-bucket https://github.com/YOUR_USERNAME/scoop-bucket
```

## Available Apps

### Weasel

Rime Input Method Engine for Windows - A powerful and customizable Chinese input method.

**Install:**
```powershell
# Requires administrator privileges
scoop install sudo
sudo scoop install scoop-bucket/weasel
```

**Features:**
- Rime input method engine with extensive customization
- Support for multiple input schemas (Pinyin, Cangjie, etc.)
- Highly configurable through YAML files
- Active community and schema ecosystem

**Version:** 0.17.4

**Note:** Please restart or log out of Windows after installation for the input method to take effect.

---

### Kanata Wintercept

A cross-platform software keyboard remapper with Interception driver support (GUI version).

**Install:**
```powershell
scoop install scoop-bucket/kanata_wintercept
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
scoop-bucket/
├── bucket/
│   ├── weasel.json
│   └── kanata_wintercept.json
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
scoop bucket rm scoop-bucket
```

## Contributing

This is a personal bucket, but suggestions and bug reports are welcome via Issues.

## License

MIT License

## Links

- [Scoop](https://scoop.sh/) - A command-line installer for Windows
- [Kanata](https://github.com/jtroo/kanata) - Keyboard remapper

