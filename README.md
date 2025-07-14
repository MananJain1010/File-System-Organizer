# 📁 File System Organizer (Node.js CLI Tool)

## 📌 Overview
The **File System Organizer** is a **Node.js Command Line Interface (CLI)** tool that helps you **organize messy directories** by automatically sorting files into folders based on file types, and it can also display the folder structure in a **tree-like format**.

This tool is useful to clean up large folders like **Downloads**, categorize files, and manage system storage efficiently.

---

## ✅ Features
- 📂 **Organize**: Sort files into folders like `media`, `documents`, `archives`, `apps`, and `others`.
- 🌳 **Tree Structure**: Display a tree-like view of a directory.
- 🆘 **Help Command**: List available commands and their usage.
- 🖥️ **Simple Node.js CLI tool** using built-in modules (`fs`, `path`).

---

## 🛠️ Tech Stack
- **Node.js**
- **JavaScript**
- Node.js core modules: `fs`, `path`
- Modular code with separate files for each command

---

## 📂 Folder Structure

File-System-Organizer/
├── commands/
│ ├── help.js
│ ├── organize.js
│ └── tree.js
├── main.js
├── utility.js
└── package.json


---

## ⚙️ How to Setup and Run

### 1. Clone Repository
git clone https://github.com/MananJain1010/File-System-Organizer.git
cd File-System-Organizer
npm install

2. Run Commands
✅ Show Directory Tree Structure
node main.js tree <directory-path>

✅ Organize Files in Folder
node main.js organize <directory-path>

✅ Show Help Guide
node main.js help





🎁 Future Improvements

Support for custom file type categories
Option to move instead of copy files
Option to undo the last organize operation


✨ Author
Manan Jain
GitHub: https://github.com/MananJain1010
