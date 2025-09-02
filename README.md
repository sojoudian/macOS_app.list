# macOS App List

Essential apps for developers on macOS, installable via Homebrew.

## About

This repository contains a curated list of essential applications for developers working on macOS. All applications can be installed using [Homebrew](https://brew.sh/).

## Installation

To install all apps at once:
```bash
brew install --cask $(cat app.list | grep -v '^$')
```

To install individual apps:
```bash
brew install --cask <app-name>
```

## Applications List

### Code Editors & IDEs
- **Visual Studio Code** - Popular code editor with extensive extensions
- **Sublime Text** - Fast, sophisticated text editor
- **Brackets** - Modern, open-source text editor
- **Atom** - Hackable text editor
- **Neovim** - Hyperextensible Vim-based text editor

### Development Tools
- **Node.js** - JavaScript runtime
- **Lua** - Lightweight scripting language
- **jq** - Command-line JSON processor
- **htop** - Interactive process viewer
- **gping** - Ping with graph

### Browsers
- **Firefox** - Privacy-focused browser
- **Firefox Developer Edition** - Browser for developers
- **Google Chrome** - Popular web browser
- **Chromium** - Open-source browser
- **Opera** - Feature-rich browser
- **Brave Browser** - Privacy-focused Chromium browser

### Terminal & Shell
- **iTerm2** - Terminal emulator for macOS

### Media Tools
- **VLC** - Universal media player
- **FFmpeg** - Multimedia framework for conversion and streaming

### AI Tools
- **LM Studio** - Run LLMs locally
- **Ollama** - Run large language models locally
- **OpenAI Whisper** - Speech recognition
- **ChatGPT** - OpenAI's ChatGPT desktop app
- **Claude** - Anthropic's Claude desktop app
- **Grok** - xAI's Grok desktop app

### Utilities
- **UnRAR** - Archive extraction utility
- **Windows App** - Run Windows apps on macOS

## Contributing

Feel free to suggest additional essential developer tools by creating an issue or pull request.

## Author

Created by [sojoudian](https://github.com/sojoudian)

## Repository

[https://github.com/sojoudian/macOS_app.list](https://github.com/sojoudian/macOS_app.list)