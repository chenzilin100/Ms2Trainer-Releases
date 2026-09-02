# Ms2Trainer

An external trainer for **Mortal Shell II**, focused on automatic defensive assistance while preserving the game's original actions and combat flow.

## Download

Download the latest version from [GitHub Releases](https://github.com/chenzilin100/Ms2Trainer-Releases/releases/latest).

The trainer is distributed as a self-contained Windows executable. No separate .NET runtime installation is required.

## Features

- Health recovery for both the body and the currently active shell
- Automatic Perfect Defense using Active Block or Harden
- Automatic Perfect Dodge for verified attacks, with an optional red-mark-focused mode that leaves confirmed guardable attacks untouched
- Supported projectile, radial, explosion, and delayed unblockable attack routes
- Equipment-aware rebinding and manual rebind fallback
- English and Simplified Chinese interface
- Persistent language and theme settings
- Bounded local diagnostic logs for troubleshooting
- Clear unsupported-build status with persistent GitHub and 3DM update links

Parry-based automatic defense is not currently supported.

## Compatibility

- Windows 10 or Windows 11, 64-bit
- Mortal Shell II single-player gameplay
- Verified game builds:
  - `++Sparta-Depot+Main+CL92935+1279-CL-0`
  - `++Sparta-Depot+Main+CL92935+1300-CL-0`

If an unsupported game version is detected, the trainer shows a clear compatibility status in the bottom bar and keeps GitHub and 3DM update links available in the session panel. Future game updates may remain compatible when the required runtime signatures can still be validated.

## Usage

1. Download and extract `Ms2Trainer.zip` from the latest release.
2. Start Mortal Shell II and enter the game.
3. Run `Ms2Trainer.exe`.
4. Enable Lock Health, Automatic Perfect Defense, Automatic Perfect Dodge, or any combination you want.

When Automatic Perfect Dodge is used by itself, the optional **Dodge red-marked attacks only** mode leaves confirmed guardable attacks to normal combat. Attacks that cannot be classified safely may still trigger Dodge.

Settings are stored in `%LOCALAPPDATA%\Nyxeon\Ms2Trainer\settings.json`. Diagnostic logs are stored separately in `%LOCALAPPDATA%\Nyxeon\Ms2Trainer\Logs`.

## Antivirus Notice

The trainer reads and modifies the memory of a running game process. Some antivirus products may classify this behavior as suspicious or report a false positive. Verify downloads using the SHA-256 file included with each release.

## Source Availability

This is a closed-source freeware release repository. It contains public documentation and compiled release files only; the trainer source code is not published here.

## Disclaimer

Use only in single-player gameplay and at your own risk. This project is not affiliated with or endorsed by the developers or publishers of Mortal Shell II. Mortal Shell II and related names are the property of their respective owners.

Copyright (c) 2026 Nyxeon. All rights reserved.
