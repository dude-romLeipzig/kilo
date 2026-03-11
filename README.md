# kilo

Pretty sure you all know this one:

A minimal text editor for the terminal, built in C from scratch by following the
[Build Your Own Text Editor](https://viewsourcecode.org/snaptoken/kilo/) tutorial
(based on antirez's original [kilo](https://github.com/antirez/kilo)).

Currently at **step 48**.

---

## Features (so far)

- Terminal rendering with proper screen refresh (no flicker)
- Cursor movement via arrow keys or WASD
- Clean exit without leaving the terminal in a broken state
- Centered welcome screen

---

## Build

```bash
gcc -o kilo kilo.c -Wall -Wextra
```

## Run

```bash
./kilo
```

---

## Controls

| Key | Action |
|-----|--------|
| `W` / `↑` | Move cursor up |
| `S` / `↓` | Move cursor down |
| `A` / `←` | Move cursor left |
| `D` / `→` | Move cursor right |
| `Ctrl+Q` | Quit |

---

## About
Started this to keep me busy during the boring parts of retraining.
Now these parts have become sparse, or, atleast they demand my attention more than they used to. 
So now the commits have become sparse as well. 

This project is a learning exercise — building a text editor step by step to understand
how terminals, raw input, and screen rendering actually work under the hood.
Progress is tracked publicly as it develops.

---

## Author

**ghostKid**
