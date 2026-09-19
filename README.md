# Git & GitHub Setup Tutorial

Created by Sylux.

A beginner-friendly tutorial that walks through Git and GitHub setup from
scratch — installation, configuration, authentication, and submitting a
project from both the command line and VS Code.

The written content (`t2.md`) is authored in Markdown. The web version
(`index.html`) is a small single-page viewer built with
[OpenCode](https://opencode.ai) that renders that Markdown with a
sidebar, dark mode, and syntax highlighting.

## What's inside

| File | Purpose |
| ---- | ------- |
| `t2.md` | The tutorial itself, written in Markdown. Edit this to change content. |
| `index.html` | Self-contained web viewer. Renders the Markdown with styling, table of contents, and dark mode. Includes a print button (🖨️) that produces a clean PDF. |
| `README.md` | This file. |

## How to open it

There are two ways, and they behave slightly differently.

### Option A — Double-click `index.html`

Just double-click the file, or drag it into a browser.

- **Works with no setup, no server, no internet** (the browser may still
  fetch fonts/highlighting from a CDN on first load).
- Uses a **snapshot** of the Markdown that is embedded inside the HTML.
  Edits you make to `t2.md` will **not** show up this way.
- This is the easiest way to just read the tutorial.

### Option B — Serve the folder over HTTP

Run a tiny local web server in the folder, then open the page from your
browser. This makes the viewer load `t2.md` live, so any edits appear on
refresh.