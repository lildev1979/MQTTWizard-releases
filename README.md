# MQTT Wizard

A free tool from [LCD Wizard](https://lcdwizard.com) for Windows, macOS and Linux, for everyone who builds a screen that talks MQTT. There's no account and no licence key.

**[Download the latest release](https://github.com/lildev1979/MQTTWizard-releases/releases/latest)**

| System | File |
|---|---|
| Windows 10/11 (64-bit) | `MQTTWizard-<version>-windows-x64.zip` |
| macOS, Apple silicon (M1 and later) | `MQTTWizard-<version>-macOS-AppleSilicon.zip` |
| macOS, Intel | `MQTTWizard-<version>-macOS-Intel.zip` |
| Linux x64 | `MQTTWizard-<version>-linux-x64.tar.gz` |
| Linux ARM64 (Raspberry Pi 4/5 with a 64-bit OS) | `MQTTWizard-<version>-linux-arm64.tar.gz` |

Each download is one self-contained program, with nothing else to install. Every release has `SHA256SUMS.txt` and `MD5SUMS.txt`.

## What it does

- **Grab:** saves every topic on your broker, plus Home Assistant's discovered entities, to one file that LCD Wizard's designer imports.
- **Live:** a topic explorer, a publish pad with saved buttons, and a live plotter with CSV export.
- **Broker:** a one-click broker on this computer, and a simulated house to design against.
- **Check:** "Why won't my board connect?", board watch, a design check and a Home Assistant inspector.
- **Tools:** record and replay, and a retained-message cleaner that always confirms first.

Passwords are held in memory only, never written to disk or to any file.

## First run

- **Windows:** not code-signed yet, so SmartScreen may warn you. Choose **More info**, then **Run anyway**.
- **macOS:** unsigned. Move the app to Applications, then run `xattr -cr "/Applications/MQTT Wizard.app"` once, or right-click it and choose **Open**.
- **Linux:** on Debian or Ubuntu, `sudo apt install libice6 libsm6`.

This repository holds the downloads only. Questions and design help: [lcdwizard.com](https://lcdwizard.com).
