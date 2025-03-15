# TagEditor
A lightweight, browser-based text editor designed for editing structured text (HTML/XML) with customizable, reusable tags and efficient handling of long documents.

Check out the live version of the app here: https://jackychan122.github.io/TagEditor/

## Features ✨

### **Tag Customization & Management**
- 🎨 **Create Custom Tags**: Define tags with unique names and colors (HEX/RGB).
- 📚 **Tag Library**: Save, view, and manage tags in a sidebar. Delete tags with confirmation.
- 💾 **Persistent Storage**: Tags saved to `localStorage` for reuse across sessions.

### **Text Editing**
- 🔗 **Wrap Text**: Highlight text → Select tag → Wrap with `<tag>...</tag>` (supports nesting!).
- 🔍 **Tag Pair Highlighting**: Click a tag to highlight its opening/closing pair.
- ⚡ **Optimized Performance**: Virtual scrolling for large files + debounced syntax highlighting.

### **User Interface**
- 📋 **Top Toolbar**: Copy all text or save new tags with one click.
- 🖥️ **Editor Area**: Syntax highlighting, line numbers, and smooth scrolling (powered by CodeMirror Lite).
- 📱 **Responsive Design**: Collapsible sidebar for mobile-friendly use.

### **Security & Accessibility**
- 🔒 **Input Sanitization**: Prevents XSS risks in exported content.
- ⌨️ **Keyboard Shortcuts**: `Ctrl+S` (save tags), `Ctrl+C` (copy text).
- ♿ **ARIA Labels**: Accessible buttons and modals.

---

## Quick Start 🚀

1. **Create a Tag**:
   - Click **"Save Tag"** in the toolbar.
   - Enter a name (e.g., `<note>`) and pick a color.
   
2. **Wrap Text**:
   - Highlight text in the editor.
   - Select a tag from the sidebar → Click **"Wrap"**.

3. **Copy & Save**:
   - Use **"Copy All"** to export your text.
   - Content auto-saves to `sessionStorage` (recoverable on page reload).
