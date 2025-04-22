<p align="center">
  <img src="A_logo_design_features_the_text_\"JoAi\"_in_bold,_bl.png" alt="JoAi Logo" width="200"/>
</p>

# JoAi

**JoAi** is a private, offline, uncensored text-only AI chatbot created with care, passion, and privacy in mind.  
She is **not public**, not shared, and not for anyone else. She’s built to be yours alone — a companion that runs locally, without cloud dependence or external interference.

> **Warning:** This project is strictly personal. Not for public use, sharing, or collaboration.

---

## Features

- **Offline-Only:** No internet required once set up.
- **Private & Unfiltered:** Runs on your Android phone — no data leaves your device.
- **Powered by Mistral-7B-Instruct (Q4_K_M):** Efficient, balanced, and fully uncensored.
- **Runs on Termux + Proot Ubuntu:** Designed specifically for Android devices.

---

## Installation

**Requirements:**

- Android device with Termux
- SD card with minimum 4GB free space
- `proot-distro` for Ubuntu
- `KoboldCpp` (CPU-only, compiled)
- `mistral-7b-instruct.Q4_K_M.gguf` model placed on SD card

**Steps:**

```bash
# Step 1: Install Termux and update
pkg update && pkg upgrade

# Step 2: Install Proot Ubuntu
pkg install proot-distro
proot-distro install ubuntu
proot-distro login ubuntu

# Step 3: Setup your build environment inside Ubuntu
# Clone JoAi repo (after you push it)
git clone https://github.com/Krishnakumar73/JoAi.git
cd JoAi

# Step 4: Follow KoboldCpp build + run instructions (from README or docs)
o
