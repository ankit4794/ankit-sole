# ANKIT SOLE

A cinematic sneaker showcase recreating the "Coffee Drift" three-layer slider technique (from a Doc Mo build guide) with fully original branding, product names, and assets.

**Not affiliated with Nike or any real shoe brand.** The original guide this technique is adapted from documents a Nike fan-build; this site uses an invented brand ("ANKIT SOLE") and invented product names/colorways instead, since Nike's brand and product names are trademarked and this site is public.

## The Coffee Drift technique
Three independent GSAP animation layers tuned to land at the same visual frame:
1. **The shoe** — spins out with a small anticipation dip, full rotation exit; incoming shoe arrives pre-rotated and unwinds to center.
2. **The background word** — flips on the Y axis like a card turning edge-on.
3. **Floating detail badges** — ghost-cloned, animated out with a larger dip, then removed; new ones fly in offset in time so all three layers disappear together.

## Stack
Vanilla HTML/CSS/JS, GSAP (slider animation), Motion (motion.dev, scroll reveals), Google Fonts (Poppins). All 4 shoe illustrations are original flat SVGs built from simple primitives (no traced photography, no borrowed brand assets).

## Run locally
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Notes
- The "Notify me" form is a front-end-only demo — submissions are not sent anywhere.
- No real checkout — this is a visual/interaction demo.
