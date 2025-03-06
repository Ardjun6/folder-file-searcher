# Folder File Searcher

## Description

A Python script to recursively search for specific folders or files with certain extensions within a given directory. This tool helps locate files or directories across nested folders efficiently.

## Features

- Search for a specific folder name within subdirectories.
- Search for files with specified extensions (e.g., `.txt`, `.jpg`, `.pdf`).
- Supports multiple file extensions.
- Returns full file or folder paths for easy access.

## Installation

Ensure you have Python installed (Python 3 recommended).

Clone the repository:

```bash
git clone https://github.com/Ardjun6/folder-file-searcher.git
cd folder-file-searcher
```

## Usage

Run the script with user inputs:

```bash
python search_folder_file.py
```

You will be prompted to enter:

- The starting directory
- The folder name to search for (leave blank if not needed)
- File extensions (comma-separated, e.g., `.txt,.pdf`)

## Example

```
Enter the starting directory: /Users/example/Documents
Enter the folder name to search for (leave blank if not searching for a folder): Projects
Enter file extensions to search for (comma-separated, e.g., .txt,.pdf): .py,.md
```

### Output Example

```
Found items:
/Users/example/Documents/Projects
/Users/example/Documents/code/script.py
/Users/example/Documents/notes/README.md
```

## License

This project is licensed under the MIT License.

