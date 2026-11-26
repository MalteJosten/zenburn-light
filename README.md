# Zenburn Light
A light, paper-toned VS Code theme built from [Zenburn](https://github.com/jnurmine/Zenburn)'s darker hues.

## Palette

| Role | Color | Where it is used |
|---|---|---|
| surface | `#fbfaf4` | editor, panel, terminal, inputs |
| bg | `#efeee4` | side bar, tab strip, hover/suggest widgets |
| sunk | `#e3e2d6` | title bar, activity bar, status bar |
| line / line-strong | `#dcdccc` / `#bdbdab` | borders, indent guides, scrollbars |
| fg / muted / faint | `#3f3f3f` / `#656555` / `#8a8a7a` | text, punctuation and secondary UI, line numbers |
| accent | `#3d6b6e` | focus, buttons, links, cursor, numbers and constants |
| good | `#4a6b4a` | added files, diff insertions |
| warn | `#80621f` | keywords (bold), modified files, warnings |
| risk | `#8c4f4f` | strings, errors, deleted files |

| Token | Color | Zenburn source |
|---|---|---|
| comments (italic) | `#597259` | green `#7f9f7f` |
| functions | `#66652b` | function yellow `#efef8f` |
| types, classes, JSON/YAML keys | `#46648a` | blue+1 `#94bff3` |
| decorators, `self`, attributes | `#885736` | orange `#dfaf8f` |
| escapes, regex, f-string braces | `#835375` | magenta `#dc8cc3` |

Selection, find, diff and merge highlights reuse the original dark Zenburn colors (`#8cd0d3`, `#9fc59f`, `#dca3a3`, `#d0a85f`) at low alpha over the paper. Rainbow CSV columns get the same palette.

## Install

Download `zenburn-light-<version>.vsix` from the [latest release](https://github.com/MalteJosten/zenburn-light/releases/latest), then run `code --install-extension zenburn-light-<version>.vsix`.

To build from source instead:

```sh
python3 build_vsix.py
code --install-extension zenburn-light-0.1.0.vsix
```

Then choose **Preferences: Color Theme → Zenburn Light**. After you edit the theme JSON, run both commands again and reload the window.

---

This theme was made with Claude Code.
If something looks off or if you have other problems/suggestions, please open an issue.