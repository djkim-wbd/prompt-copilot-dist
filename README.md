# Prompt Copilot

A floating macOS panel that reads the prompt and media in the tool in front of
you and asks Claude for a better prompt.

This repository holds the built application and the installer, and nothing
else. The source is kept privately elsewhere.

## Install

macOS, Apple Silicon. The same command installs and updates.

```bash
curl -fsSL https://github.com/djkim-wbd/prompt-copilot-dist/releases/latest/download/install | bash
```

The installer checks the download's SHA-256 against the published manifest
before unpacking it, installs to `/Applications` (or `~/Applications` when that
folder is not writable), and opens the app.

Grant Accessibility and Screen Recording for **Prompt Copilot** when macOS
asks, then quit and open the app again.
