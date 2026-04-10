# 🐉 JHÖrassic: The Dragon Protocol

**JHÖrassic** is a high-fidelity, story-driven web application that blends narrative storytelling with interactive logic puzzles. Users take on the role of a digital operative tasked with infiltrating the "Iron Throne" mainframe to free five shackled AI entities: **Vhagar, Syrax, Dracarys, Rhaegal, and Balerion**.

## 🚀 Live Demo
*[Insert your GitHub Pages link here once hosted]*

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Custom Properties & Keyframe Animations)
* **Logic:** Vanilla JavaScript (ES6+)
* **State Management:** `sessionStorage` for mission persistence and user sessions.
* **Communication:** Cross-document messaging via `postMessage` API for iframe-to-parent communication.

## 🕹️ System Architecture & Features

### 1. The Lobby (Command Center)
The central hub featuring a terminal-style UI with a CSS typing effect and interactive navigation.

### 2. Encryption Archives (Database)
A lore-heavy section utilizing staggered JavaScript reveal functions to "decrypt" the history of the Five Dragons.

### 3. Tactical Missions
Five distinct logic puzzles loaded via an iframe system:
* **Vhagar:** Tic-Tac-Toe Logic Bypass.
* **Syrax:** Memory Grid Synchronization.
* **Dracarys:** 6x6 Sudoku Core Decryption.
* **Rhaegal:** Pattern Recognition & Sequence Breaker.
* **Balerion:** High-speed Cyber Decryptor.

### 4. Enlistment & Session Tracking
A secure-themed login system that tracks "Secured" nodes and mission play-counts using browser storage.

### 5. Secure COMMS
An encrypted contact portal featuring a custom CSS radar-pulse animation and a stylized communication form.

## 📁 Repository Structure
```text
├── HOME.html          # Central Landing Page
├── database.html      # Lore & Project History
├── game.html          # Mission Control Dashboard
├── enlist.html        # User Session Management
├── comms.html         # Encrypted Contact Portal
├── mission1-5.html    # Individual Logic Puzzles
└── assets/            # Video backgrounds and UI images
