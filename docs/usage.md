# Usage

## Requirements

- Python 3.12
- Windows 10 or 11 (or the platform listed in the README)

## Install

1. Enable Developer Options and USB debugging.
2. Install platform-tools and scrcpy.
3. Install Droids with pipx install droids-adb.
4. Connect the device and authorize the key.
5. Pick a device and run a preset.

## Configuration

```text
%APPDATA%\Droids\
├── config.ini
├── profiles\
└── logs\
```

- USB debugging must be enabled.
- The dry run prints every command.
- System-critical packages are protected.

## Commands

```text
# install
pipx install droids-adb

# debloat
droids debloat --list
droids debloat --disable com.example.bloat --dry-run

# backup
droids backup --all --out D:/phone-backup
```

## Uninstall

Delete the application folder and `%APPDATA%\Droids`. No services, no
drivers, no scheduled tasks are installed.