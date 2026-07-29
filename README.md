# Princewill Web Design — Portfolio Site

Personal portfolio site for **Che Princewill Anengbah** — Web Design, Cartoon Animation, and Graphic Design services.

**Live structure:** a homepage with a services "slide deck", plus one example page per service.

## Files

| File | Purpose |
|---|---|
| `index.html` | Homepage — hero, services slide deck, about, contact |
| `style.css` | Shared stylesheet for every page (colors, fonts, components) |
| `web-design.html` | Example page for the Web Design service |
| `animation.html` | Example page for the Cartoon Animation service (live CSS-animated mascot) |
| `graphic-design.html` | Example page for the Graphic Design service (brand board mockup) |

All files must stay in the same folder — the pages link to each other with relative paths (e.g. `web-design.html`, `style.css`).

## Design

- **Colors:** white background, blue (`#0b5fbf`) and green (`#189a5f`) accents, black (`#12181f`) body text
- **Fonts:** Space Grotesk (headings), IBM Plex Sans (body), IBM Plex Mono (labels)
- **Logo:** two signal bars merging into a play triangle — a nod to a background in radio/telecom communications now channeled into web, motion, and design work

## Contact

- Email: cheanengbah@gmail.com
- Phone / WhatsApp: +237 659 775 459
- Phone: +237 671 812 905

## Updating content

- Service copy and the "See an example" links live in `index.html`, inside each `.slide` block.
- Each example page (`web-design.html`, `animation.html`, `graphic-design.html`) currently shows a placeholder client example — swap these for real project work as it becomes available.

## Viewing locally

Open `index.html` directly in a browser, or serve the folder with any static file server (e.g. `python3 -m http.server`) so relative links resolve correctly.
