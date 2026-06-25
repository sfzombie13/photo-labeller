# 📸 Photo Labeller

[![Python](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[![Privacy: 100% Offline](https://img.shields.io/badge/Privacy-100%25_Offline-success.svg)](#)

A simple, offline Python script that takes a folder of inspection photos, asks you what they are, and writes the labels directly onto the images. 

### 🛑 Why I built this
I've been a hacker since I was 13 and have owned/operated an IT security company for the last 13 years. Recently, I started a new chapter as a home inspector.

When I looked for a tool to simply label my inspection photos, everything I found was bloated junk. It either required a cloud subscription, had ads, or tracked telemetry just to paste text onto a JPEG. I don't like bloatware and I value privacy. So, I wrote this script, assisted by AI.

I'm putting it up here for free. It does exactly one thing, it does it offline, and it doesn't track you. 

## 🛠️ What it does
* Prompts you in the console for the Address, Room, and Amount of Work Completed.
* Writes that information directly onto the image.
* Saves the details to a file.
* **Auto-Repeat:** Saves you from typing the same thing over and over.
* **Pause & Resume:** Never lose your spot in a massive folder of photos.

---

## 📸 Before & After

![Before](https://github.com/user-attachments/assets/7c8b55da-c720-417c-b756-79c67cd88766)

![After](https://github.com/user-attachments/assets/80994206-ef90-4c5d-90bb-bed6a5d8ab4c)

---

## 💻 How to use it

*(Note: You just need Python installed on your computer, and the Pillow library, which you can get by opening your command prompt and typing `pip install Pillow`)*

1. Drop the script into the folder with your images and run it.
2. It will open an interactive shell you can use to answer the questions (Address, Room, Work Completed).
3. **Save time:** If you have several images in a row with the exact same information, just hit "Enter" and it will use the same information from the previous photo (shown in parentheses).
4. **Pause & Resume:** If you need to stop in the middle, just hit "q". It will write what you have already done and save your progress so you can resume exactly where you left off when you return.

---

## 📜 License

This is free and unencumbered software released into the **Public Domain** via **The Unlicense**.

I'm just sharing this to help out other inspectors. You are free to copy, modify, use, compile, or distribute this script however you want. No permission required, no attribution required.

See the `LICENSE` file for full details, or visit [http://unlicense.org/](http://unlicense.org/).
