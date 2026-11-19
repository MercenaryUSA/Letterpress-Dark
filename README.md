# Letterpress Dark

A darker, cobalt-ink variant of [Letterpress](https://github.com/MercenaryUSA/letterpress-theme) for Discord: near-black card stock, inked outlines, hard printed shadows and cobalt ink for everything that reacts to you, with cream stickers. Red is saved for destructive actions only.

- Buttons and reactions press into the page
- New messages get stamped on; menus and popouts drop in like paper slips
- Your user panel wears a **"HELLO my name is"** sticker
- Clicking into the message box pops up a **"✎ go on, say it"** note
- Rubber-stamp timestamps, index-card code blocks, dog-eared embeds, washi-tape member groups
- Respects Discord's and your OS's "Reduce motion" setting

Works with Vencord and BetterDiscord. Best with Discord's Dark appearance.

## Install

**Vencord (online theme):** Settings → Themes → Online Themes, and paste:

```
https://raw.githubusercontent.com/MercenaryUSA/Letterpress-Dark/main/LetterpressDark.theme.css
```

**Vencord or BetterDiscord (local):** download `LetterpressDark.theme.css` and drop it into your themes folder, then enable it.

## Customize

Everything is driven by the knobs at the top of the file (`:root { --lp-... }`):

| Knob | What it does |
|---|---|
| `--lp-accent`, `--lp-cream` | Cobalt ink and sticker paper |
| `--lp-danger` | Colour for destructive actions |
| `--lp-paper-0` … `--lp-paper-4` | Card stock, darkest to lightest |
| `--lp-grain` | Paper grain strength (`0` = smooth) |
| `--lp-nametag`, `--lp-say-it` | Set to `none` to hide a sticker |
| `--lp-nametag-text`, `--lp-say-it-text` | Change what the stickers say |

Fonts: Bricolage Grotesque, Fraunces, Caveat and Space Mono (loaded from Google Fonts).

> Discord's class names change with updates. If something stops being styled, the selectors probably need refreshing.
