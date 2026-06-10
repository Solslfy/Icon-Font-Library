# Solslfy Icon Font Library

A small, dependency-free SVG icon set organized by **style** and **category**.
Every icon is a clean 24×24 vector that uses `currentColor`, so it picks up the
surrounding text color automatically — drop it inline, in CSS, or in a font build.

**50 icons** · 2 styles × 5 categories × 5 icons each.

## Styles

- **Outline** — stroked, 2px, rounded caps. Good for UI chrome and light themes.
- **Filled** — solid shapes. Good for emphasis, small sizes, and dark themes.

## Categories

- **Navigation** — arrow-right, home, menu, search, settings
- **Media** — camera, music, pause, play, volume
- **Weather** — cloud, moon, rain, snow, sun
- **Social** — chat, heart, share, star, user
- **Commerce** — cart, credit-card, gift, tag, wallet

## Structure

```
icons/
├── outline/
│   ├── navigation/
│   ├── media/
│   ├── weather/
│   ├── social/
│   ├── commerce/
│   └── index.html        # style preview gallery
├── filled/
│   ├── navigation/
│   ├── media/
│   ├── weather/
│   ├── social/
│   ├── commerce/
│   └── index.html        # style preview gallery
```


## Usage

Inline (inherits text color):

```html
<span style="color:#6c5ce7">
  <!-- paste the contents of icons/outline/navigation/home.svg -->
</span>
```

As an `<img>`:

```html
<img src="icons/filled/social/heart.svg" width="24" height="24" alt="heart">
```

Recolor in CSS when used inline:

```css
.icon { width: 24px; height: 24px; color: #1e90ff; }
```

## Preview

Open [`index.html`](index.html) in a browser for the full gallery, or browse a
single style at `icons/<style>/index.html`. Each category folder also has a
`README.md` table that renders inline on GitHub.

## License

MIT — free to use, modify, and redistribute.
