# KAMFA Ai Solutions — one page site

A single static page. No build step, no dependencies. `index.html` is the whole site.

## Deploy

Import this repository on Vercel. Leave every setting at its default — it is plain
HTML, so Vercel serves it as-is with no framework or build command.

## Pictures

All in `images/`, and all used by the page:

| File | Where it appears |
|---|---|
| `logo-mark.jpg` | header and footer (the mark, cropped from `logo.jpeg`) |
| `logo-dark.jpeg` | on the dark band, inside a cream shape |
| `speaking.jpeg` | top of the page, beside the headline |
| `working.jpeg` | beside the section about Shabir |
| `profile.jpg` | small and round, beside the name |

`logo.jpeg` and `logo-dark.jpeg` are the same cream-background artwork at different
sizes. If you ever get a version of the logo on a transparent background (a PNG),
swap it in where the dark band and the footer use it.

## Placeholders to fill in

Three slots are deliberately left blank. Search `index.html` for `[` to find them:

- `[YOUR TIMELINE]` — how long the build takes, in the "How it works" section
- `[YOUR RESULT]` — a real result, in the section about Shabir
- `[CLIENT QUOTE]` — a real client quote, in the same section

## Contact details currently wired in

- Booking — https://cal.com/faz-shab-kamfa/intake-enquire
- WhatsApp — https://wa.me/971551018507
- Email — fazshab65@gmail.com

If the booking link is not ready, replace it in `index.html` with the text
`BOOKING_LINK_GOES_HERE`. It appears once, on the main button in the contact
section, and once in the button at the top of the page.
