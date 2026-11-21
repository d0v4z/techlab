# TechLab website

PS5 SSD storage upgrades in Lebanon: pickup, install, test and return, paid on return.

Live at https://d0v4z.github.io/techlab/ (GitHub Pages, `main` branch, root folder).

## Editing

- **Prices:** in `index.html`, search `230` and `430`. Update the visible prices, the `P = { 1: 230, 2: 430 }` line in the script at the bottom (used by the booking picker and WhatsApp message), and the `"price"` values in the `application/ld+json` block near the top.
- **WhatsApp number:** search `96171127767`.
- **Arabic text:** every translatable line has a `data-i` key; the Arabic version of each key is in the `AR` list in the script at the bottom.
- **Your photo:** replace `<div class="av" aria-hidden="true">A</div>` with `<div class="av"><img src="img/adnan.jpg" alt="Adnan from TechLab" style="width:100%;height:100%;border-radius:50%;object-fit:cover"></div>` and add `img/adnan.jpg`.
- **Analytics:** paste your Google Analytics 4 ID (and Meta Pixel if you use one) in the commented block in `<head>`. Clicks on "Book on WhatsApp" are reported automatically once it is installed.
- **Custom domain:** buy a domain, add it under Settings → Pages → Custom domain, then update the `canonical`, `og:url` and `og:image` addresses and the JSON-LD `url`.
