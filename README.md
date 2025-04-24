# SubsShortcut-Notion

A Chrome extension that provides smart text substitution in Notion with an elegant suggestion bubble interface.

## Features

- Automatically detects patterns like "- >" and suggests replacements like "→"
- Clean, minimal suggestion bubble appears near your text
- Easy one-click application or Tab key to accept suggestions
- Customizable substitution dictionary
- Recent substitutions tracking
- Seamless integration with Notion's interface

## Default Substitutions

| Pattern | Replacement |
|---------|-------------|
| - >     | →           |
| -- >    | -→          |
| <<      | «           |
| >>      | »           |
| <-      | ←           |
| <->     | ↔           |
| :)      | 😊          |
| :(      | 😔          |
| (c)     | ©           |
| (tm)    | ™           |
| +-      | ±           |

## Installation

1. Clone or download this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" in the top right
4. Click "Load unpacked" and select the extension directory
5. The extension will now be installed and active for Notion pages

## Usage

1. Navigate to any Notion page
2. Start typing in a text block
3. When you type a pattern like "- >", a suggestion bubble will appear
4. Click "Apply" or press Tab to accept the suggestion
5. The pattern will be replaced with the corresponding symbol (e.g., "→")

## Customization

You can add, edit, or remove substitution patterns through the extension popup:

1. Click the extension icon in your browser toolbar
2. Use the "Substitutions" tab to manage your patterns
3. Add new patterns with the form at the bottom
4. Remove patterns by clicking the "✕" button

## License

MIT License