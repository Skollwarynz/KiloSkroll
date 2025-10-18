# Kilowar: The Scroll-Warrior Editor 💻

## 📜 Description

This repository hosts **Kilowar**, a personal, extended fork of the famous minimalist text editor **Kilo**, originally created by Antirez and popularized by the Snaptoken tutorial.

The goal of Kilowar is to evolve the base text viewer into a more functional terminal editor for daily use, focusing on **usability, advanced navigation, and strict code quality**.

## ✨ Custom Features

This project implements several functionalities beyond the scope of the initial tutorial:

* **Integrated Line Numbering:** Implemented a dynamic, fixed-width line number column (e.g., `| 12 |`) that greatly enhances navigation.
* **Enhanced Scroll Logic:** Modified the core scrolling logic (`E.rowoff`, `E.coloff`) to correctly handle the fixed width of new UI elements, ensuring accurate text rendering.
* **Strict C99 Compliance:** The code is compiled using rigorous compiler warnings (`-Wall`, `-Wextra`) and the **`-pedantic`** flag to ensure strict adherence to the C99 standard.
* **Clean Repository:** Includes a comprehensive `.gitignore` file to correctly exclude executables and generated files (like `kilo` and `.o` files) from the repository.

## 🛠️ Installation and Building

The project is written in C and runs in the terminal (using `termios` APIs and ANSI escape sequences).

### Prerequisites

* A C compiler (GCC or Clang recommended).
* The `make` build tool.

### Compilation

Use the included `Makefile` to compile the executable:

```bash
make  

## 🚀 Running the Editor

To launch the editor and open a file:

```bash
./kilo [optional_filename]

## ⌨️ Commands (Summary)

Kilowar inherits the basic controls from the original Kilo editor.

| Key | Function |
| :--- | :--- |
| `Ctrl` + `Q` | **Quit** the editor. |
| Arrow Keys | Cursor movement. |
| `Home`/`End` | Move cursor to the start/end of the current line. |
| `PgUp`/`PgDn` | Scroll page up or down. |
| (Future) `Ctrl` + `S` | Save the file. |
|'Ctrl' + 'P'| Search for word in the file|

---

## 🔗 References

This project is an extension of the excellent tutorial:

* **Build Your Own Text Editor (Kilo)** - [https://viewsourcecode.org/snaptoken/kilo/](https://viewsourcecode.org/snaptoken/kilo/)

---

## 🧑‍💻 Contributing

Feel free to clone this repository and experiment by adding new features!

To get started:

```bash
git clone [https://github.com/Skollwarynz/KiloSkroll.git](git@github.com:Skollwarynz/KiloSkroll.git)
