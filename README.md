# 💻 Kilowar: The Scroll-Warrior Editor

## 📜 Description

This repository hosts Kilowar, a personal, extended fork of the famous minimalist text editor Kilo, originally created by Antirez and popularized by the Snaptoken tutorial.

The goal of Kilowar is to evolve the base text viewer into a more functional terminal editor for daily use, focusing on usability, advanced navigation, and strict code quality.

---

## ✨ Custom Features

Kilowar adds several features beyond the original tutorial:

- Integrated Line Numbering:
  Implements a dynamic, fixed-width line number column (e.g., 12 |) to enhance navigation.
- Config file for configuration:
  Inside the project there is a Config/ directory with different config file to color different hotkeys, the file are oganized based on the extenstion of file and are fully costumizable. 
---

## 🧩 Future Features (Planned)

The following features are planned for future releases of Kilowar:

- Word Suggestion:
  Implement a simple inline word suggestion system that predicts and completes words based on file context.

- Auto Parenthesis Insertion:
  Automatically insert closing parentheses, brackets, and braces when an opening one is typed.

- Auto Indentation:
  Maintain consistent indentation levels when writing structured code, with automatic tab alignment.

---

## 🛠️ Installation and Building

The project is written in C and runs entirely in the terminal, using termios APIs and ANSI escape sequences.

### Prerequisites

- A C compiler (GCC or Clang recommended)
- The make build tool

### Compilation

Use the included Makefile to compile the executable:

`make`

---

## 🚀 Running the Editor

To launch Kilowar and open a file:

`./kilo [optional_filename]`

---

## ⌨️ Commands (Summary)

Kilowar inherits most controls from the original Kilo editor.

| Key Combination | Function                                  |
| --------------- | ----------------------------------------- |
| Ctrl + Q        | Quit the editor                           |
| Arrow Keys      | Move the cursor                           |
| Home / End      | Move to the start/end of the current line |
| PgUp / PgDn     | Scroll one page up or down                |
| Ctrl + S        | Save the file                             |
| Ctrl + P        | Search for a word in the file             |

---

## 🔗 References

This project is an extended implementation of the tutorial:

- Build Your Own Text Editor (Kilo) – https://viewsourcecode.org/snaptoken/kilo/

---

Author: Skollwarynz (https://github.com/Skollwarynz)
