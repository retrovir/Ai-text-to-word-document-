# Smart Text-to-Word Telegram Bot 📝

A lightweight, intelligent Telegram bot that converts plain text messages into cleanly formatted Microsoft Word (`.docx`) documents. 

Designed to handle AI-generated text or long copy-pasted notes, this bot bypasses Telegram's character limits by accepting multiple messages and compiling them into a single document. It features a "Smart Auto-Detect" system that identifies headings, bullet points, and paragraphs based on text shape and punctuation—no Markdown symbols required!

## ✨ Features
* **Smart Formatting:** Automatically detects Headings (short lines without periods) and standard bullet points (`•`, `-`, `*`).
* **Multi-Message Compilation:** Send as many text blocks as you need; the bot stitches them together perfectly.
* **Professional Output:** Generates ready-to-use `.docx` files formatted with standard fonts (Arial, 12pt).
* **Auto-Cleanup:** Deletes local files immediately after sending to save server storage.

## 🛠️ Prerequisites
* Python 3.7 or higher
* A Telegram Bot Token (Get this from [@BotFather](https://t.me/BotFather) on Telegram)

