# Copy Link

An Obsidian plugin that adds commands to quickly copy links to files, headings, and blocks.

## Features

This plugin adds context menu commands for creating and copying wikilinks with smart path disambiguation to avoid ambiguity when multiple files share the same name.

### File Commands

Available in the file context menu (right-click on files):

- **Copy note link** - Copies a wikilink to the note using the shortest unique path
- **Copy note link as footnote** - Copies the note link wrapped in an inline footnote: `^[[[link]]]`

### Block Commands

Available in the editor context menu (right-click in editor):

- **Copy block link** - Automatically adds or finds a block ID and copies a link to it: `[[note#^blockid]]`
- **Copy block embed** - Same as block link but prefixed with `!` for embedding: `![[note#^blockid]]`

## Settings

All commands can be toggled on/off individually in the plugin settings:

- **File commands** - Enable/disable file context menu commands
- **Block commands** - Enable/disable editor context menu commands
- **Notifications** - Toggle clipboard notifications on/off

## Installation

### From Obsidian Community Plugins

1. Open Settings → Community plugins
2. Search for "Copy Link"
3. Click Install, then Enable

### Manual Installation

1. Download the latest release from the [Releases](https://github.com/greetclammy/copy-link/releases) page
2. Extract the files to your vault's `.obsidian/plugins/copy-link` folder
3. Reload Obsidian and enable the plugin in Settings → Community plugins

## License

MIT
