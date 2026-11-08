# Grok Theme for Zed

An unofficial Zed theme family distilled from the Grok interface: neutral
graphite surfaces, warm ivory type, and a single desaturated steel accent.
No orange chrome, no bronze syntax.

Two variants ship together:

- **Grok Obsidian** — near-black graphite with warm ivory text.
- **Grok Parchment** — neutral paper light theme with the same restrained syntax palette.

## Install

Open the Extensions view in Zed (`ctrl-shift-x` / `cmd-shift-x`), search for
**Grok Theme**, and install it. Then pick either variant from the theme selector
(`theme selector: toggle`).

### Install from source

1. Clone this repository.
2. Run `zed: install dev extension` from the command palette.
3. Select the repository directory.

## Design

The reference UI is almost entirely monochrome. This theme treats it that way:

| Role | Obsidian | Parchment |
| --- | --- | --- |
| App / editor | `#121212` / `#101010` | `#F4F3F0` / `#FBFBF9` |
| Raised surface | `#1E1E1E` | `#FFFFFF` |
| Text / muted | `#E6E4DF` / `#9A9892` | `#242422` / `#686866` |
| Accent (focus, links, selection) | `#A9BCCB` | `#4C6478` |
| Keyword | `#A6B8C6` | `#4C6478` |
| Function | `#D4C8B4` | `#4E6A5A` |
| String | `#AEBE9C` | `#5C6B3F` |
| Type | `#9DBFB6` | `#2F5F5A` |
| Number | `#C7A9A0` | `#8A5A52` |

Syntax uses five muted hues over a neutral ground. Accent color is reserved for
interactive state; it never appears in tabs, borders, gutters, or syntax.

## License

MIT. This is an independent, unofficial theme and is not affiliated with xAI.
