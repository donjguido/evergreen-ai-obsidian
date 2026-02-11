# Privacy Policy for Wonderland

**Last updated: February 2025**

## Overview

Wonderland is an Obsidian plugin that uses AI to generate and enhance your notes. Your privacy is important to us. This policy explains what data is collected, how it's used, and your choices.

## Data Collection

### What We Collect
- **Nothing.** Wonderland does not collect, store, or transmit any of your data to us.

### What Your AI Provider Receives
When you use Wonderland to generate notes, the following is sent to your configured AI provider (OpenAI, Anthropic, or your custom endpoint):

- The text prompt you enter
- Relevant context from existing notes in your Wonderland folders (titles and excerpts)
- Your custom instructions and folder settings

This data is sent directly to your AI provider and is subject to their privacy policy.

## AI Provider Privacy Policies

Please review the privacy policy of your chosen AI provider:

- **OpenAI**: [privacy.openai.com](https://privacy.openai.com)
- **Anthropic**: [anthropic.com/privacy](https://www.anthropic.com/privacy)
- **Ollama**: Runs locally on your machine - no data leaves your computer
- **Custom endpoints**: Subject to the privacy policy of your custom provider

## Data Storage

### API Keys
Your API key is stored locally in your Obsidian vault's plugin data folder (`.obsidian/plugins/wonderland/data.json`). It is:
- Never sent to us or any third party
- Only sent to your configured AI provider when making requests
- Stored unencrypted on your local device (as is standard for Obsidian plugins)

### Generated Content
All generated notes are stored locally in your Obsidian vault. Wonderland does not sync, backup, or transmit your notes anywhere.

### Settings
Your plugin settings are stored locally in your vault's plugin data folder.

## Network Requests

Wonderland only makes network requests to:
1. Your configured AI provider's API endpoint to generate content
2. No analytics, telemetry, or tracking requests are made

## Local Processing

The following operations are performed entirely on your device:
- Note organization and classification
- Link detection and tracking
- File management (creation, moving, renaming)
- All plugin settings and configuration

## Third-Party Services

Wonderland does not integrate with any third-party services other than your chosen AI provider.

## Your Choices

You have full control over:
- **Which AI provider to use** (including local-only options like Ollama)
- **What data to include** in prompts via custom instructions
- **Which folders** to designate as Wonderland folders
- **Deleting** the plugin and all associated data at any time

## Data Retention

We retain none of your data. Your AI provider's data retention policies apply to any data sent to them.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be noted in the changelog and the "Last updated" date above.

## Contact

For questions about this privacy policy or the plugin, please:
- Open an issue on [GitHub](https://github.com/donjguido/evergreen-ai-obsidian)
- Contact the author at the repository

## Summary

**TL;DR**: Wonderland doesn't collect any data. Your notes and settings stay on your device. When you generate content, your prompts go to your AI provider (OpenAI, Anthropic, or Ollama). That's it.
