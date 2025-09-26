# Basic Keystroke Logger

A simple Python-based keystroke logger that captures keyboard inputs and logs them to a file with timestamps. Built using the pynput library for cross-platform compatibility.

## Features
- Captures alphanumeric keys and special keys (space, enter, tab, backspace, ESC).
- Logs each keystroke with a timestamp in the format: `YYYY-MM-DD HH:MM:SS: 'key'`.
- Appends to `keystrokes.log` without overwriting previous sessions.
- Stops logging on ESC key press.
- Displays the full log contents in the console after stopping for immediate review.

## Requirements
- Python 3.6+
- pynput==1.7.6 (install via `pip install -r requirements.txt`)

## Installation
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`

## Usage
Run the script:
```
python keystroke_logger.py
```

- Type keys to log them.
- Press ESC to stop and view the session log in the console.
- Check `keystrokes.log` for persistent logs.

## Example Log Output
```
Keystroke log started
2025-09-26 13:39:00: 'h'
2025-09-26 13:39:00: 'e'
2025-09-26 13:39:01: 'l'
2025-09-26 13:39:01: 'l'
2025-09-26 13:39:01: 'o'
2025-09-26 13:39:02: ' '
2025-09-26 13:39:02: '[ESC]'
```

## Notes
- This is a basic logger for educational purposes. Use responsibly and ethically.
- On Windows, may require running as administrator for full key capture in some applications.
- No data encryption or remote transmission; logs are local only.

## License
MIT License
