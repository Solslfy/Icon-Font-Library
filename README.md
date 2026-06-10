# Solslfy Icon Font Library

A small, dependency-free SVG icon set organized by **style** and **category**.
Every icon is a clean 24×24 vector that uses `currentColor`, so it picks up the
surrounding text color automatically — drop it inline, in CSS, or in a font build.

**131 icons** · outline 84 · filled 47

## Styles

- **Outline** — stroked, 2px, rounded caps. Good for UI chrome and light themes.
- **Filled** — solid shapes. Good for emphasis, small sizes, and dark themes.

Many outline icons are sourced from the [solslfy.gg](https://github.com/solslfy/solslfy.gg)
media set and normalized to `currentColor`.

## Categories

- **Commerce** — cart, credit-card, dollar, gift, tag, wallet
- **Communication** — mail, phone, send
- **Design** — palette
- **Development** — actions, code, github, issue, pr, terminal
- **Devices** — desktop, mobile
- **Files** — book, folder, quote
- **Gaming** — gamepad, trophy
- **Interface** — bell, bookmark, briefcase, calendar, check, clock, cog, copy, download, edit, eye, filter, flag, globe, lock, minus, plus, trash, upload, zap
- **Media** — camera, film, image, mic, music, pause, play, volume
- **Navigation** — arrow-down, arrow-left, arrow-right, arrow-up, chevron-down, chevron-left, chevron-right, chevron-up, close, external-link, home, link, menu, more, refresh, search, settings
- **Social** — chat, heart, share, star, user, users
- **Status** — activity, check-circle, info, shield, warning
- **Weather** — cloud, moon, rain, snow, sun

## Structure

```
icons/
├── outline/
│   ├── commerce/ (6)
│   ├── communication/ (3)
│   ├── design/ (1)
│   ├── development/ (6)
│   ├── devices/ (2)
│   ├── files/ (3)
│   ├── gaming/ (2)
│   ├── interface/ (20)
│   ├── media/ (8)
│   ├── navigation/ (17)
│   ├── social/ (6)
│   ├── status/ (5)
│   ├── weather/ (5)
│   └── index.html        # style preview gallery
├── filled/
│   ├── commerce/ (6)
│   ├── communication/ (3)
│   ├── interface/ (9)
│   ├── media/ (5)
│   ├── navigation/ (14)
│   ├── social/ (5)
│   ├── weather/ (5)
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
