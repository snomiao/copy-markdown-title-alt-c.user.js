# Copy Markdown Quote Alt+C

A userscript that allows you to quickly copy webpage titles and URLs in Markdown format with quoted selections.

## Features

- Press **Alt+C** to copy the current page title and URL as a Markdown link
- Automatically includes any selected text as a quoted block
- Supports multiple languages (Arabic, Chinese, English, French, Russian, Spanish)
- Works on all websites

## Installation

1. Install a userscript manager extension:
   - [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Firefox, Safari, Edge)
   - [Greasemonkey](https://www.greasespot.net/) (Firefox)
   - [Violentmonkey](https://violentmonkey.github.io/) (Chrome, Firefox, Edge)

2. Install the script from one of these sources:
   - [Install directly from this repository](copy-markdown-title-alt-c.user.js)
   - Or copy the script content and create a new userscript in your manager

## Usage

1. Navigate to any webpage
2. (Optional) Select text you want to quote
3. Press **Alt+C**
4. The Markdown formatted link will be copied to your clipboard

### Output Format

Without selection:
```markdown
- [Page Title]( https://example.com )
```

With text selection:
```markdown
- [Page Title]( https://example.com )
> Selected text here
```

## Example

When you press Alt+C on a GitHub repository page with some text selected, you'll get:

```markdown
- [GitHub - username/repository]( https://github.com/username/repository )
> This is the selected text from the page
```

## Browser Compatibility

Works on all modern browsers that support:
- Clipboard API
- Userscript managers

## License

MIT

## Author

snomiao@gmail.com

## Contributing

Feel free to submit issues and pull requests at the repository.