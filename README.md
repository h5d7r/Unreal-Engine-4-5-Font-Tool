# Unreal Engine 4/5 Font Tool

## Description
This is a specialized command-line tool designed to automate the replacement of Unreal Engine font files (`.ufont`). It supports both folders and compressed archives. The tool automatically extracts archives, recursively scans for `.ufont` files, and replaces them with a user-provided `.ttf` or `.otf` file while preserving the original filename and extension.

## Features
- **Archive Support:** Automatically handles ZIP and other archive formats supported by the system.
- **Recursion:** Scans all subdirectories.
- **Database Logging:** All operations are logged in a local SQLite database (`tool_history.db`).
- **Preservation:** Keeps original filenames strict for game engine compatibility.

## Installation
1. Install Python 3.x.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
