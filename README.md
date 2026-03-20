# Mike Markdown Editor (MME)

Multi-Ribbon Markdown Editor with Mermaid Support

Live Demo  
https://averydimbulb79.github.io/mike_editor/index.html

---

## Overview

Mike Editor is a browser-based Markdown writing environment designed to behave more like a document editor than a plain text editor.

The project began with a simple frustration: most Markdown editors produce poor printable output.

When exporting or printing Markdown documents, many tools generate PDFs with:

• no margins  
• no page borders  
• poor typography  
• diagrams cut off  
• inconsistent formatting  

This makes them unsuitable for producing clean documents, articles, or printable reports.

Mike Editor experiments with a different approach. Instead of treating Markdown as raw text, it treats it as a structured document surface that can be rendered cleanly on screen and exported to a properly formatted page.

The editor includes a print pipeline specifically designed to produce decent PDF output directly from the browser.

---

## Live Demo

You can run the editor directly here:

https://averydimbulb79.github.io/mike_editor/index.html

No installation required.

---

## Why This Editor Exists

Most Markdown tools prioritise editing speed and developer workflows.

Very few prioritise document quality when printing.

The main design goals of Mike Editor are:

• readable document layout  
• clean printable output  
• predictable margins and page flow  
• diagram compatibility  
• a familiar desktop-style interface  

The editor is intentionally built as a single-file browser application so it can run locally without installation.

---

## Secondary Goal: Testing "Vibe Coding"

This project is also an experiment in vibe coding with ChatGPT.

Rather than following a traditional development process, the editor was iteratively built through conversation with AI.

The experiment explores:

• how far AI-assisted development can go  
• how complex a UI tool can be built through iterative prompting  
• whether conversational design can replace traditional planning for certain types of software  

Every feature in the current version was developed through iterative collaboration with ChatGPT.

---

## Current Features

• Multi-tab ribbon interface  
• Split editor and preview layout  
• Mermaid diagram rendering  
• Word, character, and line statistics  
• Markdown export  
• HTML copy export  
• Print-ready document rendering  
• Adjustable editor and preview panes  
• Local autosave  
• Responsive mobile layout  

---

## Running the Editor Locally

Download the file:

index.html

Open it in any modern browser.

No installation is required.

The editor runs entirely locally in the browser.

---

## Technology Stack

HTML  
CSS  
JavaScript  

Libraries used:

Marked.js  
DOMPurify  
Mermaid  

---

## Development Roadmap

Mike Editor is being developed through a structured revision roadmap designed to gradually transform the project into a full Markdown document IDE.

### Mike Editor Development Roadmap

| Revision | Focus | Key Features |
|--------|------|-------------|
| 1 | Core Stabilisation | Ribbon switching, command system cleanup, print pipeline fixes |
| 2 | Ribbon Expansion | Populate ribbon tabs with formatting commands |
| 3 | Desktop UI Upgrade | Collapsible ribbon, document page surface |
| 4 | Document Navigation | Outline sidebar, heading navigator |
| 5 | Workspace Modes | Editor-only, preview-only, focus mode |
| 6 | Editor Intelligence | Find and replace, statistics, document insights |
| 7 | Command Palette | Searchable command palette |
| 8 | Live Markdown Rendering | Obsidian-style inline rendering |
| 9 | Live Editing Engine | Stable block-based Markdown editing |
| 10 | Rich Object Rendering | Inline diagrams, images, editable tables |

---

## Milestones

Milestone A  
Revisions 1–3  
A polished desktop-style Markdown editor.

Milestone B  
Revisions 4–6  
Document-aware writing environment with navigation tools.

Milestone C  
Revisions 7–8  
Modern editing workflow with command palette and live rendering.

Milestone D  
Revisions 9–10  
Full document editor with inline diagrams and rich objects.

---

## Long-Term Vision

The long-term goal is to create a Markdown editor that combines:

• the structure of Markdown  
• the usability of Word  
• the flexibility of Obsidian  
• the simplicity of a single-file web app  

---

## License

MIT License
