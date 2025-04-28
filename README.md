# Distraction-Free Markdown Editor with Corkboard

A streamlined, distraction-free writing environment for creating Markdown content without context switching. This single-file web application provides everything you need for focused writing while keeping references and notes within easy reach.

## Features

- **Multi-pane Interface**: Editor, Preview, and Corkboard panes that can be used individually or side-by-side
- **Distraction-Free Writing**: Clean UI with no unnecessary elements
- **Focus Mode**: Full-screen writing environment for maximum concentration
- **Instant Preview**: Real-time Markdown rendering
- **Quick Capture**: Save selections or ideas as notes without breaking flow
- **Flexible Corkboard**: Organize thoughts and references spatially
- **Persistent Storage**: Auto-saves content and notes to localStorage
- **Dark/Light Theme**: Toggle between themes for comfortable writing in any environment
- **Fully Offline**: No external dependencies or network requirements

## Getting Started

1. Download the `index.html` file
2. Open it in any modern web browser
3. Start writing!

That's it! No installation, no dependencies.

## Usage Guide

### Panes and Layout

The editor has three main panes that can be toggled on/off and used in combination:

- **Editor**: Where you write your Markdown content
- **Preview**: Displays rendered Markdown output
- **Corkboard**: Digital pinboard for notes and references

Toggle each pane using the buttons at the bottom or keyboard shortcuts (Ctrl/Cmd + 1/2/3).

### Focus Mode

Need to concentrate? Enter Focus Mode (Ctrl/Cmd + F) to display only your writing area with a dimmed background. This eliminates all distractions while keeping your content front and center.

### Notes System

The Corkboard provides a flexible system for organizing thoughts and references:

- **Create Notes**: Click "Add Note" or use Ctrl/Cmd + N
- **Quick Capture**: Select text and press Ctrl/Cmd + / to create a note from it
- **Edit Notes**: Click to edit title or content
- **Move Notes**: Drag and drop to arrange spatially
- **Delete Notes**: Click the × button on any note
- **Use Notes**: Copy to clipboard or insert directly into your editor

### Markdown Formatting

Use the toolbar buttons or these keyboard patterns for formatting:

- `**bold text**`
- `*italic text*`
- `# Heading 1`, `## Heading 2`, etc.
- `- List item`
- `[link text](url)`
- ````code block````

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Toggle Editor | Ctrl/Cmd + 1 |
| Toggle Preview | Ctrl/Cmd + 2 |
| Toggle Corkboard | Ctrl/Cmd + 3 |
| Create New Note | Ctrl/Cmd + N |
| Toggle Focus Mode | Ctrl/Cmd + F |
| Search | Ctrl/Cmd + K |
| Quick Capture Selection | Ctrl/Cmd + / |
| Toggle Theme | Ctrl/Cmd + T |
| Save | Ctrl/Cmd + S |
| Exit Focus/Search | Esc |

## Search Functionality

Press Ctrl/Cmd + K to activate search. This will find matching text in:

1. Your main document (highlights the match)
2. Your notes (scrolls to and highlights the matching note)

## Technical Details

- **Single HTML File**: All code, styles, and functionality in one file
- **LocalStorage**: Content persists between sessions
- **Vanilla JavaScript**: No frameworks or external dependencies
- **Responsive Design**: Works on desktop and mobile devices
- **Offline-First**: No network connection required

## Development 

This application is built with vanilla HTML, CSS, and JavaScript, making it easy to modify or extend:

- CSS variables for theming
- Modular JavaScript functions
- Simple data structures for state management

## License

This project is released under the MIT License. Feel free to use, modify, and distribute as needed. 
