# Web Annotator

## Overview
Web Annotator is a Chrome extension that allows users to seamlessly add, edit, and manage notes directly on any webpage.

![WhatsApp Image 2024-06-09 at 22 57 40_b4adb15d](https://github.com/VictoryVortex6/Web_Annotator/assets/149820466/105e6273-0913-4310-a152-e5df9b690afd)


## Features
- **Highlight Text**: Select text and apply highlights using right-click or keyboard shortcuts.
- **Customize Highlights**: Change highlight colors to suit your preferences.
- **Add Notes**: Attach sticky notes to highlighted text for additional context.
- **Delete Highlights**: Easily remove highlights and associated notes.
- **Manage Highlights**: Access and organize all highlighted texts and notes from the extension's popup.
- **Search and Sort**: Find specific highlights using the search bar, and sort them by style or date.
- **Export Highlights**: Download all highlighted texts in HTML, PDF, or text format.

## How It Works

### Highlighting Text
1. Select the text and right-click to choose "Highlight Text" or use keyboard shortcuts.
2. Select your desired highlight color from the submenu.

### Managing Highlights
1. Click on a highlighted text to reveal options for changing color, adding notes, or deleting.

### Using the Extension
1. Click the Web Annotator icon in the Chrome toolbar.
2. Access all highlights and notes from the popup window.
3. Utilize search and sorting options for efficient organization.
4. Download highlights in your preferred format.

## Installation
1. Download the extension files.
2. Open Chrome and go to `chrome://extensions/`.
3. Enable "Developer mode" in the top right corner.
4. Click "Load unpacked" and select the extension directory.
5. The Web Annotator icon will appear in the Chrome toolbar.

## File Descriptions

### `manifest.json`
Defines the extension's metadata, permissions, background scripts, and content scripts.

### `background.js`
Handles the background logic for context menu actions and keyboard shortcuts.

### `content.js`
Injects the script into web pages to handle text highlighting and notes functionality.

### `popup.html`
Defines the structure of the extension's popup window.

### `popup.js`
Handles the logic for the popup window, including displaying highlights, search, sort, and export functionality.

### `styles.css`
Contains the styling for the extension's popup window.

[For more details, visit the overall project description](https://github.com/VictoryVortex6/Web_Annotator/blob/main/overall_project_description.md)
