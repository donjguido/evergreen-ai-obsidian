# Release v1.0.0

## What's New

Welcome to Wonderland! This is the initial release of an AI-powered Obsidian plugin that helps you build a connected knowledge base using the evergreen notes methodology.

### Features

- **AI Note Generation**: Generate comprehensive, linked notes from any prompt using OpenAI, Anthropic (Claude), Ollama, or custom endpoints
- **Auto-expanding Links**: Click any unresolved [[wiki-link]] to automatically generate a new note exploring that concept
- **Wonderland Folders**: Designate any folder as a "Wonderland" with its own custom settings and instructions
- **Folder Goals**: Configure each Wonderland for different purposes (learning, action-oriented, critical reflection, research, creative)
- **Global & Folder Instructions**: Set custom instructions that guide how AI generates content across all or specific Wonderlands
- **"Down the Rabbit Hole" Suggestions**: Get AI-generated exploration suggestions at the end of each note
- **Knowledge Enrichment**: Automatically or manually enrich notes with insights from related notes
- **Enrichment Blacklist**: Exclude specific notes from automatic enrichment
- **Auto-Organization**: Let AI organize your notes into intuitive subfolders
- **Rabbit Holes Index**: Generate an index of all unexplored paths in your knowledge base
- **External References**: Optionally include links to external sources in generated notes
- **Personalized Suggestions**: Customize exploration suggestions based on your interests
- **Mobile Support**: Full compatibility with iOS and Android (cloud AI providers only)

### Technical Features

- **Multiple AI Providers**: OpenAI, Anthropic, Ollama (local), or any OpenAI-compatible endpoint
- **Smart Error Handling**: Automatic retry with exponential backoff for rate limits and network errors
- **Folder Tracking**: Automatically updates settings when folders are renamed or deleted
- **Welcome Modal**: First-time user onboarding

## Installation

### From Obsidian Community Plugins
1. Open Settings → Community Plugins
2. Search for "Wonderland"
3. Click Install, then Enable
4. Configure your AI provider in Settings

### Manual Installation
1. Download the attached files (`main.js`, `manifest.json`, `styles.css`)
2. Create folder: `<vault>/.obsidian/plugins/wonderland/`
3. Copy the downloaded files into that folder
4. Enable the plugin in Settings → Community Plugins

## Getting Started

1. **Configure AI**: Go to Settings → Wonderland and enter your API key for OpenAI or Anthropic
2. **Create a Wonderland**: Add an existing folder or create a new one as your first Wonderland
3. **Enter Wonderland**: Click the rabbit icon in the ribbon or use the command palette
4. **Start Exploring**: Enter any topic and watch your knowledge garden grow!

## Privacy

Wonderland does not collect any data. Your notes stay on your device. When generating content, your prompts are sent only to your configured AI provider. See [PRIVACY.md](https://github.com/donjguido/evergreen-ai-obsidian/blob/master/PRIVACY.md) for details.

## Support

If you enjoy Wonderland, consider [supporting development](https://ko-fi.com/donjguido)!

## Requirements

- Obsidian v1.4.0 or higher
- API key for OpenAI, Anthropic, or a running Ollama instance (desktop only for Ollama)

---

"Curiouser and curiouser!" - Let your knowledge grow.
