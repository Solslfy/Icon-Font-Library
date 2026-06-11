# Solslfy Icon Font Library

A clean, dependency-free SVG icon set — **421 icons** (**270** outline · **151** filled) across
13 categories. Every icon is a 24×24 vector that uses
`currentColor`, so it inherits the surrounding text color automatically.

```
👉  Open  index.html  in a browser to search, preview, copy and download icons.
```

## Quick start

**Get the icons**

- **Whole library:** click the green **Code → Download ZIP** button above, or
  `git clone https://github.com/solslfy/icon-font-library.git`
- **One icon:** open any `.svg` under `icons/…`, click **Raw**, then save — or use
  the **download** / **copy** buttons in the interactive gallery.

**Use an icon**

```html
<!-- as an image -->
<img src="icons/outline/navigation/home.svg" width="24" height="24" alt="home">

<!-- inline, inherits text color -->
<span style="color:#6c5ce7"><!-- paste the SVG markup here --></span>
```

```css
.icon { width: 24px; height: 24px; color: #1e90ff; }
```

## Interactive gallery

[`index.html`](index.html) is a self-contained page (no build step, works
offline) that lets you:

- 🔍 **Search** by icon or category name
- 🎚️ **Filter** by style (outline / filled) and category
- 📋 **Copy** an icon's SVG markup with one click
- ⬇️ **Download** any icon as an `.svg` file

> Tip: enable **GitHub Pages** (Settings → Pages → deploy from `main`) to browse
> the gallery online without downloading.

## Styles

- **Outline** — stroked, 2px, rounded caps. Great for UI chrome and light themes.
- **Filled** — solid shapes. Great for emphasis, small sizes and dark themes.

A few line-based icons (e.g. `wind`, `hash`, `loader`) ship in outline only.
Many outline icons come from the [solslfy.gg](https://github.com/solslfy/solslfy.gg)
media set, normalized to `currentColor`.

## Browse by category

| Category | Description | Icons | Browse |
|----------|-------------|------:|--------|
| **Commerce** | Shopping, money and analytics | 34 | [outline](icons/outline/commerce/README.md) · [filled](icons/filled/commerce/README.md) |
| **Communication** | Mail, messaging and feeds | 24 | [outline](icons/outline/communication/README.md) · [filled](icons/filled/communication/README.md) |
| **Design** | Drawing, editing and layout | 15 | [outline](icons/outline/design/README.md) · [filled](icons/filled/design/README.md) |
| **Development** | Code, git and infrastructure | 25 | [outline](icons/outline/development/README.md) · [filled](icons/filled/development/README.md) |
| **Devices** | Screens, hardware and peripherals | 24 | [outline](icons/outline/devices/README.md) · [filled](icons/filled/devices/README.md) |
| **Files** | Documents, folders and storage | 29 | [outline](icons/outline/files/README.md) · [filled](icons/filled/files/README.md) |
| **Gaming** | Play, chance and rewards | 10 | [outline](icons/outline/gaming/README.md) · [filled](icons/filled/gaming/README.md) |
| **Interface** | Controls, toggles and common UI actions | 75 | [outline](icons/outline/interface/README.md) · [filled](icons/filled/interface/README.md) |
| **Media** | Playback, audio and video controls | 39 | [outline](icons/outline/media/README.md) · [filled](icons/filled/media/README.md) |
| **Navigation** | Arrows, chevrons, menus and wayfinding | 56 | [outline](icons/outline/navigation/README.md) · [filled](icons/filled/navigation/README.md) |
| **Social** | People, reactions and sharing | 33 | [outline](icons/outline/social/README.md) · [filled](icons/filled/social/README.md) |
| **Status** | Alerts, connectivity and feedback | 31 | [outline](icons/outline/status/README.md) · [filled](icons/filled/status/README.md) |
| **Weather** | Sky, temperature and forecast | 26 | [outline](icons/outline/weather/README.md) · [filled](icons/filled/weather/README.md) |

## Folder layout

```
icon-font-library/
├── index.html          ← interactive gallery (start here)
├── icons.json          ← manifest of every icon (name, style, category, path)
├── icons/
│   ├── outline/<category>/<name>.svg
│   └── filled/<category>/<name>.svg
└── README.md
```

## Manifest

[`icons.json`](icons.json) lists every icon with its `name`, `style`,
`category` and `path` — handy for building your own picker or font pipeline.

## License

MIT — free to use, modify and redistribute.
