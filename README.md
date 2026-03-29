# cmdv

Paste formatter for AI output. Converts Claude CLI / markdown output into clean, copy-ready text for WhatsApp, Discord, and X.

**Live:** [phuaky.github.io/cmdv](https://phuaky.github.io/cmdv/)

## What it does

- **Input formats:** CLI terminal output, Markdown
- **Output formats:** WhatsApp, Discord, X (Twitter)
- Strips CLI indentation and block characters (`▎`)
- Rewraps paragraph lines broken by terminal width
- Preserves list items as separate lines
- Converts markdown bold/italic/headers to platform-native formatting
- Replaces em dashes (`—`) with hyphens (highlighted in output so you can review)
- One-click copy to clipboard

## Usage

1. Paste Claude output into the left panel
2. Select input type (CLI or Markdown) and target platform
3. Review the formatted output on the right
4. Click **Copy**

## Stack

Single `index.html` file. No dependencies, no build step. Hosted on GitHub Pages.

## Author

[Kuan Yu](https://ns.com/kuan)
