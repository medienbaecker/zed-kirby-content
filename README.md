# Zed Kirby Content Extension

Syntax highlighting for [Kirby CMS](https://getkirby.com) content files in [Zed](https://zed.dev).

## Features

- 🎨 Syntax highlighting for field names, separators, and content
- 📝 Supports both `.md` and `.txt` content files
- ⚡ Fast Tree-sitter based parsing

## Installation

### From Source (Development)

1. Clone this repository
2. Open Zed
3. Run `zed: install dev extension` from the command palette
4. Select the `zed-kirby-content` directory

## What it highlights

- **Field names** (e.g., `Title:`, `Date:`, `Url:`)
- **Field separators** (`----`)
- **Field values**

Example:
```
Title: My Website
----
Url: https://example.com
----
Text: Content here
----
```

## Limitations

This extension only provides syntax highlighting. Advanced features from the VSCode extension (smart link pasting, meta file creation) are not available due to Zed extension API limitations.

## Related

- [tree-sitter-kirby-content](https://github.com/medienbaecker/tree-sitter-kirby-content) - The Tree-sitter grammar
- [kirby-content VSCode extension](https://github.com/medienbaecker/kirby-content) - Full-featured VSCode version

## License

MIT
