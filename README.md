# Solslfy Icon Font Library

A clean, dependency-free SVG icon set — **545 icons** (**370** outline · **175** filled) across
13 categories. Every icon is a 24×24 vector that uses
`currentColor`, so it inherits the surrounding text color automatically.

## 🔗 Live gallery

**[https://solslfy.github.io/Icon-Font-Library/](https://solslfy.github.io/Icon-Font-Library/)**

Browse, search and filter every icon, then **click any icon to copy its image
link**, grab the raw **SVG code**, or **download** the file.

## Use an icon on your site (no download needed)

Every icon has a permanent public URL:

```
https://solslfy.github.io/Icon-Font-Library/icons/<style>/<category>/<name>.svg
```

```html
<!-- e.g. the outline "home" icon, straight from the live URL -->
<img src="https://solslfy.github.io/Icon-Font-Library/icons/outline/navigation/home.svg" width="24" height="24" alt="home">
```

Prefer local files? Download the whole set with **Code → Download ZIP** above, or
`git clone https://github.com/solslfy/icon-font-library.git`.

Recolor when used inline:

```css
.icon { width: 24px; height: 24px; color: #1e90ff; }
```

## Styles

- **Outline** — stroked, 2px, rounded caps. Great for UI chrome and light themes.
- **Filled** — solid shapes. Great for emphasis, small sizes and dark themes.

A few line-based icons (e.g. `wind`, `hash`, `loader`) ship in outline only.
Many outline icons come from the [solslfy.gg](https://github.com/solslfy/solslfy.gg)
media set, normalized to `currentColor`.

## Browse by category

| Category | Description | Icons | Browse |
|----------|-------------|------:|--------|
| **Commerce** | Shopping, money and analytics | 40 | [outline](icons/outline/commerce/README.md) · [filled](icons/filled/commerce/README.md) |
| **Communication** | Mail, messaging and feeds | 32 | [outline](icons/outline/communication/README.md) · [filled](icons/filled/communication/README.md) |
| **Design** | Drawing, editing and layout | 21 | [outline](icons/outline/design/README.md) · [filled](icons/filled/design/README.md) |
| **Development** | Code, git and infrastructure | 29 | [outline](icons/outline/development/README.md) · [filled](icons/filled/development/README.md) |
| **Devices** | Screens, hardware and peripherals | 27 | [outline](icons/outline/devices/README.md) · [filled](icons/filled/devices/README.md) |
| **Files** | Documents, folders and storage | 41 | [outline](icons/outline/files/README.md) · [filled](icons/filled/files/README.md) |
| **Gaming** | Play, chance and rewards | 18 | [outline](icons/outline/gaming/README.md) · [filled](icons/filled/gaming/README.md) |
| **Interface** | Controls, toggles and common UI actions | 94 | [outline](icons/outline/interface/README.md) · [filled](icons/filled/interface/README.md) |
| **Media** | Playback, audio and video controls | 53 | [outline](icons/outline/media/README.md) · [filled](icons/filled/media/README.md) |
| **Navigation** | Arrows, chevrons, menus and wayfinding | 73 | [outline](icons/outline/navigation/README.md) · [filled](icons/filled/navigation/README.md) |
| **Social** | People, reactions and sharing | 42 | [outline](icons/outline/social/README.md) · [filled](icons/filled/social/README.md) |
| **Status** | Alerts, connectivity and feedback | 42 | [outline](icons/outline/status/README.md) · [filled](icons/filled/status/README.md) |
| **Weather** | Sky, temperature and forecast | 33 | [outline](icons/outline/weather/README.md) · [filled](icons/filled/weather/README.md) |

## Folder layout

```
icon-font-library/
├── index.html          ← interactive gallery (start here)
├── icons.json          ← manifest: name, style, category, path, live url
├── icons/
│   ├── outline/<category>/<name>.svg
│   └── filled/<category>/<name>.svg
└── README.md
```

## Manifest

[`icons.json`](icons.json) lists every icon with its `name`, `style`,
`category`, `path` and a ready-to-use live `url` — handy for building your own
picker, docs or font pipeline.

## License

MIT — free to use, modify and redistribute.
