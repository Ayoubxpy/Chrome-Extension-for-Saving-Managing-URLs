# LeadSaver ![LeadSaver Icon](image1)

A simple and powerful Chrome extension to save and organize your favorite URLs ("leads") directly from your browser.

## Features

- **Save current tab:** Instantly store the active tab’s URL with one click.
- **Save custom URLs:** Input and save any URL you want.
- **View saved leads:** See your saved links as clickable items.
- **Delete all:** Double-click to remove all saved leads.
- **Persistent storage:** Your leads are saved using `localStorage`—they won’t disappear when you close your browser!

## How It Works

- Click **SAVE TAB** to save your current browser tab’s URL.
- Enter a URL and click **SAVE INPUT** to save a custom link.
- Your leads appear as a clickable list.
- Double-click **DELETE ALL** to clear your saved leads.

## Installation

1. Clone or download this repository.
2. Go to `chrome://extensions` in your browser.
3. Enable **Developer Mode** (top right).
4. Click **Load unpacked** and select your project folder.
5. The LeadSaver extension will appear in your Chrome toolbar!

## Project Structure

- `index.html` – Extension popup UI
- `index.js` – Main logic for saving, viewing, and deleting leads
- `index.css` – Styles for a clean, modern look
- `manifest.json` – Chrome Extension manifest (permissions, icon, etc.)
- `icon.png` – Extension icon ![LeadSaver Icon](image1)

## Screenshots

![LeadSaver Icon](image1)

## Permissions

- **Tabs:** Used to read the URL of the current tab for saving leads.

## License

MIT

---

**Created by [Ayoubxpy](https://github.com/Ayoubxpy)**