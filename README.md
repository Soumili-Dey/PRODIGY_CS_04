# 🔐 Keylogger – Prodigy Infotech Cybersecurity Internship Project 4

This project is part of my cybersecurity internship at **Prodigy Infotech**. The goal of this task was to understand how keyloggers work, how they can be developed using Python, and the importance of detecting and preventing such tools in real-world cybersecurity scenarios.

## 💡 Project Overview

This Python-based keylogger captures every keystroke made by a user and logs it into a file named `keystrokes.log`. It runs silently in the background and terminates when the user presses the `ESC` key.

### ✨ Features

- Captures and logs all keypress events
- Handles special keys (e.g., Enter, Space, Tab, etc.)
- Automatically timestamps the start and end of logging
- Easy to read and understand logs
- Uses the `keyboard` library for real-time key event capture

### 🛠️ How It Works

- On execution, the script begins listening to keyboard input.
- Each key is logged in real-time to a `.log` file.
- Pressing `ESC` stops the logger and appends the stop time to the file.

### 🔧 Requirements

- Python 3.x
- `keyboard` module

To install the required module:

```bash
pip install keyboard
