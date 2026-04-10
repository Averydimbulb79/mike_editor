
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
