# CLAUDE.md

This file provides guidance for an AI coding assistant when working in this workspace.

## Project Status

This workspace contains a **static** (no Node) web app for a local lucky draw tool.

## Development Commands

Run a local static server:

```bash
python3 -m http.server 5173
```

Then open:

- `http://localhost:5173`

## Architecture

- `index.html`: single-page app (UI + logic) using CDN dependencies
  - Tailwind CSS (CDN)
  - SheetJS/xlsx (CDN) for Excel parsing
- `README.md`: usage instructions

