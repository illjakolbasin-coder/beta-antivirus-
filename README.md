# beta-antivirus-
# Harden System Security (BETA)

**Harden System Security** is a custom antivirus for Windows, written in C++.

⚠️ **This is a BETA version.** Bugs, false positives, and a rough GUI are possible. The project is under active development.

## Features

- File scanning (SHA-256, MD5, entropy, PE analysis, signature check, dangerous API search)
- Process, folder, registry, task, and network monitoring
- Anti-Ransomware (encryption detection)
- Quarantine with restore
- File logging (`harden_log.txt`)
- Graphical interface (Win32 + GDI+)

## How to Run

1. Download the `.exe` from the **Releases** section.
2. Run as Administrator.
3. Click the button you need: "Scan", "Processes", "Folders", "Registry", "Tasks", "Network".

## False Positives

The file may be flagged by antiviruses as `Trojan` or `HackTool`. This is a **false positive** — antivirus ML models react to behavior (memory reading, process monitoring) that resembles a virus. The source code is open, you can verify it.
## Feedback

Found a bug or have a suggestion? Contact me:

- **Telegram:** forfedback

## License

MIT License.
