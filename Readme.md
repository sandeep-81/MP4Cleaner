# 🎬 ReelMover

**ReelMover** is a Windows batch automation tool that helps you clean and organize large numbers of folders by automatically extracting `.mp4` video files and deleting the rest.

---

## 🧩 Problem

When you have **thousands of folders (like 1000 to 10,000)** containing a mix of **photos and videos**, separating just the video files manually becomes tedious and time-consuming.

---

## 🚀 Solution

This batch script:
- Enters each folder inside the main directory
- Moves all `.mp4` (video) files to a single destination folder
- Deletes the original folder after processing

---

## 🛠️ How It Works

1. The script loops through each folder using a `for` loop.
2. Inside each folder:
   - It attempts to move all `.mp4` files to your chosen destination.
   - It then goes back and deletes the processed folder.
3. No `if` conditions are needed — the script continues even if `.mp4` files are missing.

---

## 📁 Example Directory Structure

**Before:**

