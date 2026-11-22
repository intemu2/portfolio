# Portfolio — Firt (Temu In)

Static portfolio site for offering website services to small US businesses.
Plain HTML/CSS/JS, no framework, no build step, mobile-friendly.

## Status: DRAFT — DO NOT PUBLISH YET
Prepared 22 Nov 2026. Publishing (GitHub Pages) and any outreach wait for Firt's GO.
Prices in the site and in PRICING.md are DRAFT — Firt's approval needed before they are quoted to anyone.

## Files
- `index.html` — main portfolio page (services, example websites, process, pricing, FAQ, contact)
- `styles.css` — all styling
- `script.js` — mobile menu only
- `samples/sample-mechanic.html` — example mobile mechanic website (fictional "Rapid Road Mobile Mechanics": dark industrial design, fixed-price services, service area, booking by phone)
- `samples/sample-vintage.html` — example vintage &amp; antiques website (fictional "The Copper Kettle": warm retro design, item gallery with prices, hours, location)
- `samples/sample-grooming.html` — example dog grooming website (fictional "Happy Paws Grooming": bright friendly design, grooming packages &amp; prices, groomer profiles, booking)
- `samples/sample-foodtruck.html` — example BBQ food truck website (fictional "Smoke &amp; Wheels BBQ": bold street design, menu board, day-by-day location schedule)
- `PRICING.md` — draft price list with rationale (entry-level $25 / $50 / $75)

Note (22 Nov 2026, Firt's decision): the old "Selected work" section was removed — no real past projects are shown. The portfolio now shows 4 example websites instead. Per Firt's feedback the first 3 examples (diner, barbershop, café) were replaced with 4 more varied, less common business types, each with a different design. All example businesses are fictional with generic names; no real business names or brands are used.

## Preview locally
```bash
cd ~/workspace/portfolio-firt
python3 -m http.server 8000
# open http://localhost:8000/ in a browser
```

## Publish to GitHub Pages (ONLY after Firt's GO)
1. Create a repo on GitHub (account `intemu2`), e.g. `portfolio` — do NOT create it yet.
2. Push this folder's contents to the repo's `main` branch (root, not a subfolder).
3. In the repo: Settings → Pages → Source: "Deploy from a branch" → branch `main`, folder `/ (root)` → Save.
4. The site goes live at `https://intemu2.github.io/portfolio/` (free, no domain purchase).
5. Optional later: connect a custom domain in the same Pages settings (domain ~$10–15/year, only if Firt approves the spend).

## Contact shown on the site
- Email: intemu2@gmail.com
- GitHub: https://github.com/intemu2
- Agensi: https://agensi.io/users/firt
