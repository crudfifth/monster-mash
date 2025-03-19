# Panopticon

## Overview
**Panopticon** is a research-grade keylogging system designed for security analysis and forensic investigations. Inspired by the philosophical concept of omnipresent surveillance, this tool allows researchers to study input capture techniques in a controlled environment.

## Features
- **Cross-platform support**: Works on both Windows and Linux environments.
- **Low-level input capturing**: Hooks into system-level APIs for precise keystroke logging.
- **Customizable logging options**: Store logs locally or transmit them securely.
- **Stealth mode capabilities**: Operate discreetly for undisturbed research.
- **Security-focused design**: Intended for ethical security research and private auditing.

## Installation
### Windows (Python-based)
```
pip install pynput
python keylogger.py
```

### Linux (C-based)
```
gcc panopticon.c -o panopticon
sudo ./panopticon
```

## Ethical Considerations
Panopticon is strictly for **security research and personal educational use**. Unauthorized deployment or misuse of this tool may violate laws and ethical guidelines. Always ensure you have explicit permission before testing in any environment.

## License
This project is licensed under the **MIT License**. You are free to use, modify, and distribute the code under the terms of the license.

---
**Panopticon: Seeing beyond the surface.**
