# TTY/STUDIO v0.1

A design tool that outputs terminal TUI interfaces. Compose screens on a character grid — panels, tables, menus, tabs, progress bars, sparklines, inputs, status bars — then export them as real artifacts.

**Live:** https://edwin607.github.io/tty-studio/

## Exports
- `.ansi` — truecolor snapshot (`cat` it in a modern terminal)
- `.py` — faithful ANSI render, zero dependencies
- `textual.py` — semantic [Textual](https://textual.textualize.io) app (absolute-positioned widgets)
- `.png` — 2x screenshot
- `.json` — project file (re-importable)

## Stack
Single self-contained `index.html`. No build, no dependencies.
