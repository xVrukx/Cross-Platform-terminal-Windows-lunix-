# 🔧 Cross-Platform Python Terminal (Custom Shell)

A fully functional, customizable terminal application written in Python. Designed to work across platforms (Windows, Linux, Raspberry Pi) with modern features like auto-completion, command history, colored output, and support for system-level commands.

---

## ⚙️ Features

- ✅ Cross-platform compatibility (Windows, Linux, Raspberry Pi)
- ✅ Auto-complete support (using `pyreadline3` or `readline`)
- ✅ Command history with up/down arrows
- ✅ Run built-in and system shell commands
- ✅ `Ctrl + C` interrupt handling (graceful exit or restart)
- ✅ Colored output using `colorama`
- ✅ Lightweight, no GUI — ideal for CLI lovers and embedded devices

---

## 🖥️ Demo

---![1750579824146](https://github.com/user-attachments/assets/2e5abba0-cd4b-4d57-836e-3e832393d3b8)

---![1750579833437](https://github.com/user-attachments/assets/0da78ba2-ca0b-4e47-9b7d-44220fc46f71)


## 📦 Requirements

| Module      | Purpose                        |
|-------------|--------------------------------|
| `colorama`  | Cross-platform colored output  |
| `subprocess`| Run system commands            |
| `pyreadline3` / `readline` | Auto-completion, history |

> 💡 On Linux, use `readline`; on Windows, use `pyreadline3`.

Install dependencies:
```bash
pip install colorama pyreadline3
