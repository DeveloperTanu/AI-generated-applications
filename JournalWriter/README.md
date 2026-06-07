# Mood Journal

A modern desktop journaling application built for organizing thoughts, notes, and daily reflections in a clean and distraction-free workspace.

## Features

* Multiple journal tabs
* Auto-save support
* Search across journals
* Dark & Light mode
* 10 customizable page themes
* Version history and restore
* Local data storage
* Desktop application for Windows

## Installation

### Prerequisites

* Node.js (Latest LTS version recommended)
* npm

### Clone the Repository

```bash
git clone <repository-url>
cd mood-journal
```

### Install Dependencies

```bash
npm install
```

### Run the Application

```bash
npm run dev
```

## Build Windows Installer

To create a Windows installer:

```bash
npm run build
```

The generated installer can be found inside:

```text
dist-electron/
```

## Usage

1. Create a journal tab.
2. Start writing.
3. Entries are automatically saved.
4. Use Search to find content across journals.
5. Restore older versions using the History panel.
6. Customize the experience using themes and appearance settings.

## Data Storage

All journal data is stored locally on the user's device. No account or internet connection is required.

## License

This project is provided for educational and personal use.
