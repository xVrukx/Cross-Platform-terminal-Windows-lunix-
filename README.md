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

🚀 Getting Started
Clone the repo:

bash
Copy
Edit
git clone https://github.com/vrukcodes/custom-python-terminal
cd custom-python-terminal
Run the terminal:

bash
Copy
Edit
python terminal.py
Start typing commands:

bash
Copy
Edit
> help
> list
> clear
> cd D:\Projects
> ls
🧠 Built-in Commands
Command	Description
help	Show available commands
clear	Clear the terminal screen
list	List current directory
exit	Exit the terminal

✅ Supports executing any valid system command too.

🛠 Future Enhancements
 Piping and redirection (ls | grep, > support)

 Config file for custom commands

 Bash-style scripting support

 Portable .exe build for Windows

 Audio command support (using Vosk)

💡 Use Cases
Raspberry Pi cyberdeck terminals

Lightweight CLI for custom OS setups

Command-line tools launcher

Educational terminal project

📸 Screenshots


---![1750579824146](https://github.com/user-attachments/assets/2e5abba0-cd4b-4d57-836e-3e832393d3b8)

---![1750579833437](https://github.com/user-attachments/assets/0da78ba2-ca0b-4e47-9b7d-44220fc46f71)


👨‍💻 Author
Vruk (a.k.a vrukcodes)
Student | Python Dev | Cyberdeck Builder
📫 Connect on GitHub

📄 License
MIT License – free to use, modify, and distribute.


