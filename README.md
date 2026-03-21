# Useless App

![Python](https://img.shields.io/badge/python-3.8+-blue?style=flat-square)
![PyQt6](https://img.shields.io/badge/PyQt6-6.0+-green?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-orange?style=flat-square)
![Purpose](https://img.shields.io/badge/purpose-none-red?style=flat-square)

A desktop application with one function: closing itself.

---

## What it does

A window appears. After a short pause, your cursor begins drifting toward the CLOSE button — slowly, deliberately, against your will. It arrives. It clicks. The app closes.

That's it. That's the whole thing.

## Why

It's a [useless machine](https://en.wikipedia.org/wiki/Useless_machine) as software. Code art. A small existential joke.

## Requirements

- Python 3.8+
- PyQt6

```
pip install pyqt6
```

## Usage

```
python useless_machine.py
```

Or download the standalone `Useless App.exe` from [Releases](../../releases) — no Python required.

## Build from source

```
pip install pyinstaller
pyinstaller --onefile --noconsole --name "Useless App" useless_machine.py
```

Output lands in `dist/`.

## Fun Facts

- The Python source is **7KB**
- The standalone `.exe` is **34MB**
- That's the entire Qt framework, Python runtime, and all supporting libraries bundled together to deliver one button that closes a window
- The bloat is load-bearing

## License

MIT — see [LICENSE](LICENSE)

---

*A [ConsciousNode SoftWorks](https://github.com/ConsciousNode) production.*
