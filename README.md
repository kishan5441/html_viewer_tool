# 🚀 HTML Live Preview Tool

A lightweight, browser-based HTML editor with **live preview**, **import/export**, and **mobile-friendly tabs** — installable as a PWA-style app on your phone's home screen.

> **Live Demo:** [https://your-username.github.io/html-preview-tool/](https://your-username.github.io/html-preview-tool/)

---

## ✨ Features

| Feature | Description |
|---|---|
| 📝 **Live Preview** | Real-time HTML/CSS/JS rendering with 350ms debounce |
| 📂 **Import** | Load `.html` / `.htm` files from your device |
| 💾 **Export** | Download the current editor content as an HTML file |
| 🗑️ **Clear** | Wipe the editor with confirmation (disk file stays safe) |
| 🔍 **Full Preview** | Open the rendered page in a new tab |
| 📑 **Tab System** | Mobile-friendly Code/Preview tabs with saved preference |
| ↔️ **Resizable Split** | Drag the divider on desktop · double-click to reset |
| 🌙 **Dark Mode** | Toggle between light and dark themes |
| 💾 **Auto-save** | Content + theme + active tab saved in `localStorage` |
| ⌨️ **Shortcuts** | `Ctrl/Cmd + S` to export · `Tab` inserts 2 spaces |
| 🖱️ **Drag & Drop** | Drop an HTML file anywhere to import it |
| 📱 **Installable** | Add to home screen as a fullscreen app |

---

## 🎯 Use Cases

- Test HTML/CSS/JS snippets quickly
- Preview email templates
- Debug a webpage without saving to disk
- Mobile-friendly HTML playground

---

## 🚀 Deploy on GitHub Pages

### Step 1: Create a repository

1. Go to [github.com/new](https://github.com/new)
2. **Repository name:** `html-preview-tool` (or anything you like)
3. **Visibility:** Public *(required for free GitHub Pages)*
4. **Initialize:** No README (we'll add it separately)
5. Click **Create repository**

### Step 2: Upload the tool

**Option A — Web UI (easiest)**

1. Click **"Add file" → "Upload files"**
2. Drag & drop `index.html`
3. Commit changes

**Option B — Git CLI**

```bash
git clone https://github.com/your-username/html-preview-tool.git
cd html-preview-tool
# copy index.html here
git add index.html
git commit -m "Initial commit: HTML Live Preview Tool"
git push origin main
