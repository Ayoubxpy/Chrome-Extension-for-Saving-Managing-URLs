# Lead Tracker - Chrome Extension

This project is a simple but powerful Chrome extension designed to save and track website URLs. It was built as the capstone project for the "JavaScript Fundamentals" course on Scrimba, demonstrating a wide range of web development skills, from DOM manipulation to working with browser APIs.


## 🌟 Features

*   **Save Leads Manually:** Type or paste a URL into the input field and click "Save Input" to add it to your list.
*   **Save Current Tab:** Click the "Save Tab" button to automatically capture the URL of your active browser tab.
*   **Persistent Storage:** All saved leads are stored in `localStorage`, so they remain available even after closing the browser or restarting your computer.
*   **Clickable Links:** The saved leads are rendered as a clickable list of `<a>` tags for easy access.
*   **Delete All:** A "Delete All" button allows you to clear the entire list of leads with a double-click confirmation.

## 📚 Concepts & Skills Covered

This project was a deep dive into creating a real-world browser utility and covered a broad set of essential JavaScript concepts.

### HTML & CSS
*   **Extension UI:** Structuring the popup's user interface with HTML (`input`, `button`, `ul`).
*   **Basic Styling:** Applying CSS to create a clean and functional layout for the extension.

### Core JavaScript
*   **DOM Manipulation:**
    *   Capturing elements with `document.getElementById()`.
    *   Responding to user actions with `addEventListener`.
    *   Dynamically rendering the list of leads into the DOM, progressing from `innerHTML` to the more performant `createElement()` and `append()` methods.
*   **Data Structures:** Using arrays to store and manage the list of leads.
*   **Functions & Logic:**
    *   Refactoring code into modular functions with parameters for better organization (e.g., a `render()` function).
    *   Using template strings for efficient string construction.
    *   Understanding truthy and falsy values for conditional rendering.

### Browser Storage & APIs
*   **`localStorage`:**
    *   Persisting data locally by saving the leads array to `localStorage`.
    *   Using `JSON.stringify()` to convert the array into a string for storage.
    *   Using `JSON.parse()` to retrieve and convert the string back into an array upon loading.
*   **Chrome Extension API:**
    *   Creating the `manifest.json` file to define the extension's properties and permissions.
    *   Using the `chrome.tabs.query` method to access the browser's tab system and get the URL of the active tab.

## 🚀 How to Install and Use

To install this extension locally:

1.  Clone this repository to your machine.
2.  Open Google Chrome and navigate to `chrome://extensions`.
3.  Enable "Developer mode" using the toggle switch in the top-right corner.
4.  Click the "Load unpacked" button.
5.  Select the folder where you cloned this repository.
6.  The "Lead Tracker" extension should now appear in your browser's toolbar!

---

_This project was built following the "JavaScript Fundamentals" course on [Scrimba](https://scrimba.com/). It showcases the ability to build a complete, interactive application that interfaces directly with the browser._
