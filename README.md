# Bookmark Buddy

**Bookmark Buddy** is a Chrome extension that helps users save and organize their favorite links or tabs directly within the browser. Save links manually or capture the current tab's URL with a click, making it easier to access frequently visited sites without cluttering bookmarks.

![Bookmark Buddy Screenshot](./Output.png)

## Features

- **Save Input**: Manually enter URLs to save.
- **Save Tab**: Automatically save the URL of the current tab with one click.
- **Delete All**: Clear all saved links with a double-click for easy cleanup.
- **Persistent Storage**: Saved links are stored in local storage, ensuring they remain available after browser restarts.

## Installation

1. Clone or download this repository.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** in the top right corner.
4. Click on **Load unpacked** and select the downloaded project folder.

## Usage

1. **Save a link manually**:
   - Type the URL in the input field and click **Save Input**.
2. **Save the current tab**:
   - Click the **Save Tab** button, and the current tab’s URL will be saved.
3. **View saved links**:
   - Links are displayed as a list under the buttons, each as a clickable link.
4. **Delete all links**:
   - Double-click **Delete All** to clear the saved links list.

## Files

- **manifest.json**: The configuration file for the Chrome extension.
- **index.html**: The HTML structure for the extension's UI.
- **index.css**: Styling for the extension.
- **index.js**: JavaScript for handling functionality, such as saving and deleting URLs.
