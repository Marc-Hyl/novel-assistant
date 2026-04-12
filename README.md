# Novel Writing Assistant

A browser-based AI-powered novel writing tool. No server required — open `novel-writing-assistant.html` directly in any modern browser.

## Features

- **Chapter management** — create, rename, reorder, and navigate chapters from a sidebar
- **AI analysis** — per-chapter plot and pacing analysis powered by the Claude API
- **AI assistant** — chat panel for help with character development, dialogue, world-building, and structure
- **Character cards** — track characters with notes and traits alongside your manuscript
- **Writing goals** — word-count progress bar per chapter
- **Autosave** — content saved automatically to `localStorage`; snapshot history available
- **Export** — download individual chapters or the full manuscript as `.txt`
- **Dark mode** — toggle for comfortable night-time writing sessions

## Getting Started

1. Open `novel-writing-assistant.html` in your browser (or double-click `open-novel-assistant.bat` on Windows).
2. Paste your [Anthropic API key](https://console.anthropic.com/) into the **AI Assistant** panel.
3. Start writing. Everything autosaves in your browser.

## Desktop Shortcut (Windows)

Run `setup-desktop-access.bat` once to create a desktop shortcut.

## Requirements

- A modern browser (Chrome, Edge, Firefox, Safari)
- An Anthropic API key for AI features (free tier works)

## Privacy

Your manuscript is stored only in your browser's `localStorage`. It is never uploaded anywhere unless you explicitly use the AI features, which send only the selected chapter text to the Anthropic API.
