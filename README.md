# TechLab website

PS5 SSD storage upgrades in Lebanon: pickup, install, test and return, paid on return.

Live at https://d0v4z.github.io/techlab/ (GitHub Pages, `main` branch, root folder).

## Editing

- **Prices:** search `$220` and `$430` in `index.html`. Update the visible prices, the WhatsApp links that mention them (`%24220`, `%24430`) and the `"price"` values in the `application/ld+json` block near the top.
- **WhatsApp number:** search `96171127767`.
- **Arabic text:** every translatable line has a `data-i18n` key; the Arabic version of each key is in the `AR` list in the script at the bottom.
- **GTA 6 countdown:** search `Date.UTC(2026, 10, 18, 22` (midnight 19 November, Beirut time). After launch the section switches to a "Storage full?" message on its own.
- **Your photo:** replace `<div class="avatar" aria-hidden="true">A</div>` with `<div class="avatar"><img src="img/adnan.jpg" alt="Adnan from TechLab"></div>` and add `img/adnan.jpg`.
- **Analytics:** paste your Google Analytics 4 ID (and Meta Pixel if you use one) in the commented block in `<head>`. WhatsApp button clicks are reported automatically once it is installed.
- **Custom domain:** buy a domain, add it under Settings → Pages → Custom domain, then update the `canonical`, `og:url` and `og:image` addresses and the JSON-LD `url`.
