# React-app
A simple React application, a basic template for starting React projects with default settings.

To launch the project, navigate to the project's root folder (mine is `react-app`).  

You can do this with the command:  `cd react-app`  

Then run:  `npm start`  

# Project Structure Overview

This document describes the structure of the project and explains the purpose of each folder and file.

## 📁 Folders

### `node_modules/`
- **Purpose**: Contains all dependencies (libraries and packages) installed for the project via `npm` or `yarn`.
- **Note**: This folder should not be committed to Git (it is listed in `.gitignore`).

### `public/`
- **Purpose**: Contains static files that are directly accessible at the root of the web application.
- **Files**:
  - `favicon.ico` — Website icon displayed in browser tabs.
  - `index.html` — Main HTML file where the React app is injected.
  - `logo192.png`, `logo512.png` — Logo images used for PWA (Progressive Web App).
  - `manifest.json` — Configuration file for PWA (defines app metadata).
  - `robots.txt` — File for search engine crawlers (specifies which pages to index).

### `src/`
- **Purpose**: Main folder containing the source code of the React application.
- **Files**:
  - `App.css` — Styles for the main `App` component.
  - `App.js` — Main application component rendered into `index.html`.
  - `App.test.js` — Tests for the `App` component (uses Jest).
  - `index.css` — Global styles applied throughout the application.
  - `index.js` — Entry point of the application where React renders the component into the DOM.
  - `logo.svg` — SVG logo image (typically used in `App.js`).
  - `reportWebVitals.js` — Script for collecting performance metrics (e.g., load speed).
  - `setupTests.js` — Setup configuration for testing (e.g., importing test libraries).

## 📄 Root Files

### `.gitignore`
- **Purpose**: Specifies which files and folders Git should ignore when committing (e.g., `node_modules`, `.env`).

### `package-lock.json`
- **Purpose**: Automatically generated file that locks exact versions of dependencies to ensure consistent builds.

### `package.json`
- **Purpose**: Main configuration file for the project.
  - Contains project metadata.
  - Defines scripts like `start`, `build`, and `test`.
  - Lists project dependencies.

### `README.md`
- **Purpose**: This file — contains a description of the project, setup instructions, usage guidelines, and other important information.
