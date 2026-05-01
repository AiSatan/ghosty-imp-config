# Ghostty config

Personal [Ghostty](https://ghostty.org) terminal config: Chromium-style merged-titlebar tabs (libadwaita), Sweet color palette ported from Konsole, and a `tabs.css` that compresses the tab bar past libadwaita's enforced minimums.

<img width="800" height="381" alt="image" src="https://github.com/user-attachments/assets/b9ce6a0c-1ac4-49e2-92c4-e9d93bdab773" />


## Install

Back up any existing config, then clone into place:

```bash
mv ~/.config/ghostty ~/.config/ghostty.bak  # if you have one
git clone https://github.com/AiSatan/ghosty-imp-config.git ~/.config/ghostty
```

Reload at runtime with `ctrl+shift+,`, or restart Ghostty.

## Requirements

- Ghostty 1.2+ (Linux/GTK build with libadwaita)
- `CommitMono Nerd Font Mono` — change `font-family` in `config` if you don't have it

## Files

- `config` — main Ghostty config
- `tabs.css` — GTK custom CSS loaded via `gtk-custom-css = tabs.css`
