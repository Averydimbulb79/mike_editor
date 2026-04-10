# Mike Markdown Editor (MME)

Multi-Ribbon Markdown Editor with Mermaid Support

Live Demo  
https://averydimbulb79.github.io/mike_editor/index.html

---

## Overview

Mike Markdown Editor (MME) is a browser-based Markdown writing environment designed to behave more like a document editor than a plain text editor.

It treats Markdown as a structured document surface rather than raw syntax, focusing on layout integrity, predictable rendering, and clean export output.

Runs entirely as a single HTML file. No backend.

Now supports Progressive Web App (PWA) installation for desktop and mobile use.

---

## Current Version

v7.6

This version refines the ribbon interface, expands editing capability, and introduces installable app support.

---

## Key Improvements in v7.6

### Ribbon UI Overhaul
• Compact, horizontal-first ribbon layout  
• Reduced vertical height for better workspace visibility  
• Heading controls consolidated into a dropdown selector  
• Removal of oversized tile buttons  
• Introduction of overflow handling via “More” menus  

### Expanded Toolbar Functions
• Additional formatting tools integrated into ribbon groups  
• Insert tools consolidated into structured groups  
• Export options more directly accessible  

### Layout Optimisation
• Maximum two rows per ribbon group  
• Improved spacing and alignment consistency  
• Reduced visual clutter across tabs  

### PWA Support
• Installable as desktop or mobile app  
• Runs in standalone window (no browser UI)  
• Basic offline capability via service worker  
• App install button integrated into UI  

### Stability
• Built directly on v7.5 working base  
• No regression in core editing, preview, or export logic  

---

## Core Features

### Editing
• Markdown editor with structured formatting tools  
• Ribbon-based command execution  
• Keyboard shortcuts support  
• Inline and block formatting  

### Preview
• Real-time rendered preview  
• Clean typography and spacing  
• Mermaid diagram support  

### Document Structure
• Outline panel with heading navigation  
• Expand and collapse sections  
• Structured document flow  

### Export
• Copy Markdown  
• Copy HTML  
• Print-ready layout  
• Web and minimal export presets  

### View Controls
• Toggle Outline / Editor / Preview  
• Adjustable pane widths  
• Zoom controls  
• Dark mode  

---

## PWA Installation

MME can be installed as a native-like app.

### Requirements
• HTTPS environment (GitHub Pages works)  
• Supported browser (Chrome, Edge, Safari)  

### How to Install
Option 1  
Click the Install App button inside the editor  

Option 2  
Use browser install prompt (address bar icon)

### Notes
• Service worker is required for installability  
• App works offline after first load  
• Updates require refresh after new deployment  

---

## Project Structure (Important)
/mike_editor/
│
├── index.html
├── mme-pwa-sw.js
Both files must be in the same directory.

If the service worker path is wrong, installation will silently fail.

---

## Demo Document Behaviour

The demo document is not loaded by default on initial app launch.

To load the full showcase document:
Click New → Load Demo

This design ensures:
• Faster initial load  
• Clean workspace by default  
• Demo content only loaded when needed  

---

## Design Philosophy

MME prioritises document quality over raw editing speed.

Key principles:
• Structured over raw  
• Predictable over flexible chaos  
• Print-ready by default  
• Desktop-first interaction model  

---

## Roadmap Direction (v8 and Beyond)

### Ribbon System
• Single-row adaptive ribbon  
• Priority vs overflow grouping  
• Customisable tool visibility  

### Editing Experience
• Optional inline (pseudo-WYSIWYG) rendering  
• Improved selection-aware formatting  
• Smarter insertion behaviours  

### Document Features
• Templates system  
• Snippets and reusable blocks  
• Improved table and layout tools  

### PWA Enhancements
• Versioned caching and update prompts  
• Full offline document persistence  
• App icon and splash screen refinement  

### Performance
• Faster render pipeline  
• Better large-document handling  

---

## Known Limitations

• Demo document requires manual loading  
• Ribbon still expanding toward full feature set  
• No plugin system yet  
• No persistence beyond localStorage  
• Offline cache currently limited to core files  

---

## Tech Stack

• HTML  
• CSS  
• Vanilla JavaScript  
• Marked.js  
• Mermaid.js  
• Service Worker (PWA support)  

---

## Usage

1. Open the app via GitHub Pages or local server  
2. Start writing or load demo  
3. Use ribbon tools for formatting  
4. Install as app if desired  
5. Export or print as needed  

---

## Philosophy in One Line

Markdown, treated like a real document.
