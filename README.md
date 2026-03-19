# AuroraNotes.AI - Windows AI Note Editor and Desktop Writing Assistant, Windows's Notepad with AI

AuroraNotes.AI is a lightweight Windows AI note editor and desktop writing assistant for creating, editing, summarizing, translating, and improving text. This folder contains the compiled Windows build of AuroraNotes, including `AuroraNotes.exe`, bundled runtime libraries, the built-in help file, and the local error log.

If you are searching for an **AI notes app for Windows**, an **AI text editor with grammar check and summarization**, or a **desktop note-taking app that can open TXT and DOCX files**, this build is designed for that workflow.

## Table of Contents

- [What AuroraNotes.AI Does](#what-auroranotesai-does)
- [Key Features](#key-features)
- [Supported File Types](#supported-file-types)
- [How to Run AuroraNotes on Windows](#how-to-run-auroranotes-on-windows)
- [How to Use the AI Tools](#how-to-use-the-ai-tools)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Files in This Build](#files-in-this-build)
- [Troubleshooting](#troubleshooting)
- [FAQ](#faq)
- [Who This Build Is For](#who-this-build-is-for)

## What AuroraNotes.AI Does

AuroraNotes.AI combines a simple note editor with built-in AI writing tools. You can use it as a fast desktop editor for everyday notes, drafts, and text cleanup, then apply AI actions directly inside the same app.

Common use cases include:

- Writing and expanding rough notes into complete paragraphs
- Correcting grammar and readability
- Summarizing long notes into shorter takeaways
- Translating selected text into another language
- Opening Word documents for text extraction and editing

## Key Features

### AI writing tools

- **Generate Text**: Expand or create text from the current selection
- **Grammar Check**: Correct grammar in the selection or the whole document
- **Summarize**: Add a concise summary to the end of the note
- **Translate**: Translate text into a target language

### Editor features

- Create new notes
- Open `.txt` files
- Open `.docx` files and extract their text
- Save notes as UTF-8 text
- Undo and redo
- Cut, copy, paste, and delete
- Find, find next, and replace
- Go to a specific line
- Insert the current time and date
- Zoom in, zoom out, and reset zoom
- Toggle the status bar

### Text formatting

- Bold
- Italic
- Underline
- Font family and font size selection
- Formatting of future text when no selection is active

## Supported File Types

AuroraNotes.AI currently supports these primary note workflows:

- **Open**: `.txt`, `.docx`
- **Save**: UTF-8 plain text

If you need a lightweight Windows note editor that can read Word documents and save clean text output, this build is set up for that purpose.

## How to Run AuroraNotes on Windows 11/10

1. Keep all files in this folder together.
2. Launch `AuroraNotes.exe`.
3. Use the **File** menu to create a new note or open an existing `.txt` or `.docx` file.
4. Save your work as UTF-8 text.

This is a desktop distribution build, so the bundled `.dll` files are expected and should remain next to the executable.

## How to Use the AI Tools

AuroraNotes includes built-in AI commands for writing assistance.

1. Open the app.
2. Set your API key in the **AI** menu before using AI features.
3. Select text if you want the action to apply to a specific passage.
4. Run `Generate Text`, `Grammar Check`, `Summarize`, or `Translate`.

If no specific text is selected, some commands may apply to the full document or add new output to the note.

## Keyboard Shortcuts

### AI shortcuts

- `Ctrl+G`: Generate Text
- `Ctrl+R`: Grammar Check
- `Ctrl+T`: Summarize
- `Ctrl+L`: Translate

### Editing shortcuts

- `Ctrl+Z`: Undo
- `Ctrl+Y`: Redo
- `Ctrl+X`: Cut
- `Ctrl+C`: Copy
- `Ctrl+V`: Paste
- `Ctrl+F`: Find
- `F3`: Find Next
- `Ctrl+H`: Replace
- `Ctrl+Shift+G`: Go To Line
- `Ctrl+A`: Select All
- `F5`: Time/Date

### Formatting and view shortcuts

- `Ctrl+B`: Bold
- `Ctrl+I`: Italic
- `Ctrl+U`: Underline
- `Ctrl+Shift+F`: Font
- `Ctrl+0`: Reset Zoom
- `Ctrl++`: Zoom In
- `Ctrl+-`: Zoom Out

## Files in This Build

- `AuroraNotes.exe`: Main Windows application
- `AuroraNotes_Help.txt`: Built-in help and shortcut reference
- `AuroraNotes_error.log`: Local error log for troubleshooting
- `*.dll`: Required runtime dependencies for the packaged desktop build

## Troubleshooting

### The app does not open

- Make sure `AuroraNotes.exe` stays in the same folder as the bundled `.dll` files.
- Do not move the executable away from its dependencies.

### AI features do not work

- Confirm that you added your API key in the **AI** menu.
- Confirm that your configured AI service is reachable over the network.

### You need support details

- Check `AuroraNotes_Help.txt` for the in-app command reference.
- Review `AuroraNotes_error.log` in the same folder for runtime errors.

## FAQ

### Can AuroraNotes open DOCX files?

Yes. AuroraNotes can open `.docx` files and extract their text into the editor.

### Can AuroraNotes save Word documents?

This build is documented to save notes as UTF-8 plain text, not as `.docx`.

### Does AuroraNotes include AI grammar check and summarization?

Yes. The built-in AI tools include text generation, grammar correction, summarization, and translation.

### Do I need to keep the DLL files?

Yes. The `.dll` files in this folder are part of the packaged Windows build and should remain next to `AuroraNotes.exe`.

## Who This Build Is For

AuroraNotes.AI is a fit for users who want:

- A lightweight Windows AI notes app
- A desktop text editor with built-in grammar correction
- An AI summarizer for notes, drafts, and documents
- A translation tool inside a simple writing interface
- A TXT and DOCX note workflow without a heavy editor

## version
- Verison 1.0: first version that check grammar, generate text, translate and summarize. **Bug**: after run check grammar, generate text, translate and summarize, can't select the text anymore. Slow response after using AI.
- Version 2.0: Optimized code and fix bugs from verison 1.

## Summary

AuroraNotes.AI is a compact Windows AI note-taking and writing tool focused on fast editing, AI-assisted drafting, grammar cleanup, summarization, translation, and simple document handling. This distribution folder is ready to run locally as long as the executable and bundled libraries stay together.
