# Markdown Editors Collection

A collection of single-file Markdown and Rich Text editors, each created by a different AI model. All editors are standalone HTML files with no build process required—just open in any modern browser.

## Quick Links

| Editor | Launch | Features | Best For |
|--------|--------|----------|----------|
| [GPT-5-4 MD Editor](./GPT-5-4-MD-editor.html) | [Open](./GPT-5-4-MD-editor.html) | Markdown parsing, code highlighting, rich text clipboard | Converting AI Markdown to Word/Outlook |
| [Gemini Clipboard Editor](./Gemini-3-1-Pro-Preview-MD-editor.html) | [Open](./Gemini-3-1-Pro-Preview-MD-editor.html) | WYSIWYG editing, toolbar buttons, import/export | Direct rich text editing |
| [Qwen Clipboard Editor](./Qwen-3-Coder-MD-editor.html) | [Open](./Qwen-3-Coder-MD-editor.html) | WYSIWYG editing, toolbar buttons, word counts | Simple rich text editing |
| [Claude UniversalEdit Pro](./Claude-Sonnet-4-6-MD-editor.html) | [Open](./Claude-Sonnet-4-6-MD-editor.html) | Tabs, slots, history, themes, search/replace | Power users, advanced workflows |

---

## Editor Comparison

| Feature | GPT-5-4 | Gemini | Qwen | Claude Pro |
|---------|---------|--------|------|------------|
| **Editor Type** | Markdown → Rich Text | WYSIWYG Rich Text | WYSIWYG Rich Text | Full Markdown IDE |
| **Markdown Support** | ✅ Full | ❌ | ❌ | ✅ Full |
| **Rich Text Editing** | ❌ | ✅ | ✅ | ✅ |
| **Code Syntax Highlighting** | ✅ (highlight.js) | ❌ | ❌ | ✅ (built-in) |
| **Rich Text Clipboard Export** | ✅ ClipboardItem API | ✅ execCommand | ✅ execCommand | ✅ ClipboardItem API |
| **Import Files** | ✅ .MD, .TXT | ✅ .TXT, .MD, .HTML | ✅ .TXT, .MD, .HTML | ✅ .MD |
| **Export Formats** | .MD, .HTML | .HTML | .HTML | .MD, .HTML |
| **Auto-save** | ✅ localStorage | ❌ | ❌ | ✅ localStorage |
| **Tabbed Interface** | ❌ | ❌ | ❌ | ✅ |
| **History/Undo** | ❌ | ❌ | ❌ | ✅ |
| **Theme Toggle** | ❌ | ❌ | ❌ | ✅ Dark/Light |
| **Search & Replace** | ❌ | ❌ | ❌ | ✅ |
| **Word/Char Count** | ✅ Words | ✅ Words, Chars, Lines | ✅ Words, Chars, Lines | ✅ Words, Chars, Lines |
| **Dependencies** | marked.js, highlight.js | None | None | marked.js, DOMPurify |
| **File Size** | ~13 KB | ~16 KB | ~16 KB | ~45 KB |

---

## Detailed Editor Descriptions

### 1. GPT-5-4 MD Editor - "Universal Markdown Bridge"
**File:** `GPT-5-4-MD-editor.html`

A Markdown-to-Rich-Text converter designed to solve the problem of pasting AI-generated Markdown into applications like Microsoft Word, Outlook, or Google Docs while preserving formatting.

**Key Features:**
- Paste Markdown, see live rendered preview
- Copy as rich text (HTML) for pasting into other apps
- Copy raw Markdown
- Syntax highlighting for code blocks
- Import/export .MD files
- Export styled .HTML
- Auto-save to localStorage
- Dark theme editor, white preview (for clean pasting)

**Best For:** Converting AI chat output (ChatGPT, Claude, etc.) into properly formatted documents.

---

### 2. Gemini Clipboard Editor - "Universal Clipboard Editor"
**File:** `Gemini-3-1-Pro-Preview-MD-editor.html`

A WYSIWYG rich text editor with toolbar buttons for common formatting tasks.

**Key Features:**
- Bold, italic, underline
- Heading levels (H1-H3)
- Ordered and unordered lists
- Blockquotes and code blocks
- Link insertion
- Real-time preview pane
- Word, character, and line counts
- Import from .TXT, .MD, .HTML
- Export to .HTML
- Modern gradient dark theme

**Best For:** Quick rich text editing when you don't need Markdown support.

---

### 3. Qwen Clipboard Editor - "Universal Clipboard Editor"
**File:** `Qwen-3-Coder-MD-editor.html`

Similar to the Gemini editor with a WYSIWYG interface and toolbar-based formatting.

**Key Features:**
- Bold, italic, underline
- Heading levels (H1-H3)
- Lists and blockquotes
- Links and code blocks
- Real-time preview
- Word, character, and line counts
- Import/export functionality
- Visual notifications

**Best For:** Simple rich text editing with a clean, modern interface.

---

### 4. Claude UniversalEdit Pro v2
**File:** `Claude-Sonnet-4-6-MD-editor.html`

The most feature-rich editor in the collection—a full Markdown IDE with advanced productivity features.

**Key Features:**
- **Tabbed Interface:** Open multiple documents
- **Slots Panel:** Save and reuse text snippets
- **History Panel:** Track document changes
- **Find & Replace:** Full search functionality
- **Theme Toggle:** Switch between dark and light modes
- **View Modes:** Split view, editor-only, preview-only
- **Export Options:** Markdown, HTML, print-to-PDF
- **Keyboard Shortcuts:** Full shortcut support
- **Code Copy:** One-click copy from code blocks
- **Auto-save:** Persistent localStorage

**Best For:** Power users who need a full-featured Markdown editing environment.

---

## Use Case Guide

| Your Need | Use This Editor |
|-----------|-----------------|
| "I have AI-generated Markdown I need to put into Word" | GPT-5-4 MD Editor |
| "I need to quickly format text with buttons" | Gemini or Qwen Clipboard Editor |
| "I'm writing documentation with multiple files" | Claude UniversalEdit Pro |
| "I need syntax-highlighted code in my output" | GPT-5-4 or Claude Pro |
| "I want to save text snippets for reuse" | Claude UniversalEdit Pro |
| "I need to find/replace in my document" | Claude UniversalEdit Pro |
| "I want the simplest, fastest editor" | Gemini or Qwen Clipboard Editor |

---

## Technical Notes

- All editors are single-file HTML applications
- No build process, Node.js, or installation required
- Editors using CDNs require internet connection for first load
- LocalStorage-based editors persist data in the browser
- Works in all modern browsers (Chrome, Firefox, Safari, Edge)

---

## License

These editors were generated by various AI models and are provided as-is for educational and personal use.
