# Markdown Cleaner

A simple, client-side HTML/JavaScript tool for cleaning up Markdown text. It removes trailing whitespace and deletes empty lines (lines containing only whitespace) while preserving all meaningful newline characters.

## Features

* **Remove Trailing Spaces**: Strips any whitespace at the end of each line.
* **Delete Empty Lines**: Filters out lines that are completely blank or consist only of spaces/tabs.
* **Live Preview**: Enter your Markdown in the input area, click **Clean Markdown**, and see the cleaned result instantly.
* **Copy to Clipboard**: One-click button to copy the cleaned Markdown output.

## Getting Started

These instructions will help you run the Markdown Cleaner on your local machine.

### Prerequisites

This is a pure HTML/JavaScript tool—no build process or dependencies required.

### Usage

1. **Download or clone** this repository:

   ```bash
   git clone https://github.com/adnankarim/markdown_cleaner.git
   ```
2. **Open** `index.html` in your favorite web browser.
3. **Paste** your Markdown into the top textarea.
4. Click **Clean Markdown** to process the text.
5. Optional: Click **Copy Cleaned Markdown** to copy the result to your clipboard.

## File Structure

```
markdown-cleaner/
├── index.html      # Main HTML file containing markup and scripts
└── README.md       # This documentation file
```

## Customization

* **Styling**: Modify the CSS in `<style>` block of `index.html` to adjust appearance.
* **Behavior**: Update the cleaning logic in the `<script>` section of `index.html` to tweak how lines are filtered or processed.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for enhancements or bug fixes.

## License

This project is released under the [MIT License](LICENSE).
