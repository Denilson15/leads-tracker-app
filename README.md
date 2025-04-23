# Leads Tracker App

This is a custom-built Chrome extension developed from scratch using **HTML**, **CSS**, and **JavaScript**. While the project idea was inspired by Scrimba’s Frontend Developer Career Path, the entire design and codebase were independently created to practice building browser extensions and managing user data.

> 💡 No AI was used in the development of this project. AI tools were utilized solely for documentation purposes, such as generating this README. I believe in building a strong foundation in programming while also learning how to effectively use AI tools as part of a modern developer workflow.

## ✨ Overview

Live Demo: [https://leads-tracker-app.netlify.app/](https://leads-tracker-app.netlify.app/)

This project showcases a functional Chrome extension that allows users to save and manage a list of leads (URLs). It includes:

- An input field to manually add URLs
- A button to save the current tab's URL
- A list display of saved leads
- A delete button to clear all saved leads

## ⚙️ How It Works

- Users can enter a URL manually or click a button to save the current browser tab's URL.
- Saved leads are displayed in a list format with clickable links.
- Leads are stored in the browser's local storage, ensuring data persistence across sessions.
- A delete button allows users to clear all saved leads from both the display and local storage.

## 🛠️ Personalization

Although the initial concept was provided by Scrimba, the following customizations were implemented:

- Built the extension's layout and styling from scratch
- Implemented local storage functionality for data persistence
- Added features to save the current tab's URL and clear all saved leads

## 🚧 Planned Updates

- Add functionality to delete individual leads
- Implement search or filter options for the leads list
- Enhance the user interface with improved styling and animations

## 🗂️ File Structure (basic)

- `index.html` – Main structure of the extension's popup
- `style.css` – Styling for layout and design
- `script.js` – JavaScript for handling user interactions and data management
- `manifest.json` – Configuration file for the Chrome extension

## ⚙️ Getting Started

To run the extension locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Denilson15/leads-tracker-app.git
