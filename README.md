# Solslfy Icon Font Library

A small, dependency-free SVG icon set organized by **style** and **category**.
Every icon is a clean 24×24 vector that uses `currentColor`, so it picks up the
surrounding text color automatically — drop it inline, in CSS, or in a font build.

**202 icons** · outline 121 · filled 81

## Styles

- **Outline** — stroked, 2px, rounded caps. Good for UI chrome and light themes.
- **Filled** — solid shapes. Good for emphasis, small sizes, and dark themes.

Some line-based icons (e.g. `wind`, `paperclip`, `at-sign`) ship in outline only.
Many outline icons are sourced from the [solslfy.gg](https://github.com/solslfy/solslfy.gg)
media set and normalized to `currentColor`.

## Categories

- **Commerce** — cart, credit-card, dollar, gift, package, percent, shopping-bag, tag, wallet
- **Communication** — at-sign, mail, phone, send, video
- **Design** — palette
- **Development** — actions, code, database, git-branch, github, issue, pr, terminal
- **Devices** — desktop, laptop, mobile, printer
- **Files** — book, clipboard, file, file-text, folder, paperclip, quote
- **Gaming** — gamepad, trophy
- **Interface** — bell, bookmark, briefcase, calendar, check, clock, cog, copy, download, edit, eye, filter, flag, globe, grid, key, list, lock, maximize, minus, plus, power, sliders, trash, upload, zap
- **Media** — camera, film, image, mic, music, pause, play, skip-back, skip-forward, stop, volume, volume-x
- **Navigation** — arrow-down, arrow-left, arrow-right, arrow-up, chevron-down, chevron-left, chevron-right, chevron-up, close, compass, external-link, home, link, log-in, log-out, map-pin, menu, more, refresh, search, settings
- **Social** — award, chat, heart, share, smile, star, thumbs-up, user, users
- **Status** — activity, battery, check-circle, help-circle, info, shield, warning, wifi, x-circle
- **Weather** — cloud, droplet, moon, rain, snow, sun, thermometer, wind

## Structure

```
icons/
├── outline/
│   ├── commerce/ (9)
│   ├── communication/ (5)
│   ├── design/ (1)
│   ├── development/ (8)
│   ├── devices/ (4)
│   ├── files/ (7)
│   ├── gaming/ (2)
│   ├── interface/ (26)
│   ├── media/ (12)
│   ├── navigation/ (21)
│   ├── social/ (9)
│   ├── status/ (9)
│   ├── weather/ (8)
│   └── index.html        # style preview gallery
├── filled/
│   ├── commerce/ (9)
│   ├── communication/ (4)
│   ├── development/ (2)
│   ├── devices/ (2)
│   ├── files/ (3)
│   ├── interface/ (15)
│   ├── media/ (9)
│   ├── navigation/ (18)
│   ├── social/ (8)
│   ├── status/ (4)
│   ├── weather/ (7)
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
