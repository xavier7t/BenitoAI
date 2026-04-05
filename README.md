# BenitoAI

BenitoAI is a local-only macOS chat app for Ollama models, built with SwiftUI for Apple silicon.

<img width="1196" height="879" alt="FeatureDemo-v0.1.0" src="https://github.com/user-attachments/assets/dada9b79-9f7d-43fd-b1e0-8b51f204d2b6" />


## Key Features

- Native SwiftUI interface designed for desktop usage, including sidebar, window resizing
- Streaming responses for a more live conversation feel
- Markdown and code block message rendering
- Chat organization (folders/chats)
- Chat- and/or folder-specific system prompt
- Super lightweighted, app size < 5MB (not including saved chats and folders).
- Dark mode

## Prerequisites

- Ollama installed and running locally
- macOS 26

## Current Limitations

- No localization support yet (planned)
- No settings panel yet (planned)
- No cloud model support (local models only)
- No LaTeX rendering support yet
- Supporting macOS 26+ for now. (min support for faster relase, planning to support older versions later)

## If You Found an Issue

Please open an issue in this repository with:

- What happened
- Steps to reproduce
- Expected behavior
- Your macOS version and Ollama version
- Screenshots or logs (if available)

## If You Need a Feature

Feature requests are welcome. Open an issue and include:

- The problem you are trying to solve
- Why it matters for your workflow
- A suggested UX or behavior

## Third-Party Library Usage

- [swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui): used for Markdown rendering in chat messages. Big shout out to its contributors!

## About the Name

"BenitoAI" is the current working name of the project. Its the middle name of primary developer. It has the meaning of "Blessed" in Spanish. It represents the idea of a friendly, local AI companion on macOS. Branding and naming may evolve as the product matures.
