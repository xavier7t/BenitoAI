# BenitoAI

BenitoAI is a local-only macOS chat app for Ollama models, built with SwiftUI for Apple silicon.

<img width="1196" height="879" alt="FeatureDemo-v0.1.0" src="https://github.com/user-attachments/assets/dada9b79-9f7d-43fd-b1e0-8b51f204d2b6" />

## Table of Contents

- [Downlowd](#download)
- [Key Features](#key-features)
- [Prerequisites](#prerequisites)
- [Current Limitations](#current-limitations)
- [If You Found an Issue](#if-you-found-an-issue)
- [If You Need a Feature](#if-you-need-a-feature)
- [Third-Party Library Usage](#third-party-library-usage)
- [About the Name](#about-the-name)
- [Previous Releases](#previous-releases)

## Download
**Download Now**

[BenitoAI-v0.1.2b3.zip](https://github.com/user-attachments/files/26661950/BenitoAI-v0.1.2b3.zip)

## Key Features

- Native SwiftUI interface designed for desktop usage, including sidebar, window resizing
- Streaming responses for a more live conversation feel
- Markdown and code block message rendering
- Chat organization (folders/chats)
- Chat- and/or folder-specific system prompt
- Super lightweighted, app size < 20MB (not including saved chats and folders).
- Dark mode

## Prerequisites

- Ollama installed and running locally
- macOS 26

## Current Limitations
- No cloud model support (local models only)
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

- [Textual](https://github.com/gonzalezreal/textual/): used for Markdown rendering in chat messages. Big shout out to its contributors!

## About the Name

"BenitoAI" is the current working name of the project. "Benito" is the middle name of primary developer. It has the meaning of "Blessed" in Spanish. It represents the idea of a friendly, local AI companion on macOS. Branding and naming may evolve as the product matures.

## Previous Releases
* [20260412 - BenitoAI-v0.1.2.zip](https://github.com/user-attachments/files/26661950/BenitoAI-v0.1.2b3.zip)
  * Added inline selection and copy
  * Added auto-open last opened chat
  * Added folder detail and direct navigation to chat
  * Added folder row to show subfolder count
  * Added cmd + N to create new chat
  * Added reusable prompt by typing "#".
  * Added LaTex rendering support.

* [20260405 - BenitoAI-v0.1.1](https://github.com/user-attachments/files/26491429/BenitoAI-v0.1.1b2.zip)
  * Added settings panel with localization, dark mode preference support
  * Added chat & folder import & export support
  * Added localization support for French, Spanish and Traditional Chinese (More coming soon)
  * Fixed system prompt might not show up
* 20260405 - BenitoAI-v0.1.0
  * First release
