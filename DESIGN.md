<!-- Design decision for Facials by Vanessa CT / Skin Journey by Vanessa (DEV). Source: Claude Code homepage concept A - Noir Atelier,
     rebuilt as static HTML for Kora (homepage + 404). Concept file: homepage-variants/variant-a-noir.html -->

# DESIGN.md: Skin Journey by Vanessa

archetype: noir-atelier
interaction_level: L2

typography:
  display: "Cormorant Garamond"
  body: "Jost"
  script: "Great Vibes"   # accents only (a hero line, signature, CTA)

palette:
  primary: "#D9AE5F"
  secondary: "#0B0A09"
  accent: "#F4EEE3"
  application: |
    Near-black #0B0A09 ground with #14120F / #1D1A16 bands, cream #F4EEE3 text, gold #D9AE5F with a #F7E3A1→#B7832F gradient for accents and primary buttons. Cormorant Garamond display (gold-gradient italics), Great Vibes script accents used sparingly, Jost light body. Pill buttons, hairline rules, wide-tracked uppercase eyebrows.

composition: |
  Arched hero portrait with gold ring and badge; trust strip; three 'where to begin' path cards; tabbed price menu (Facials / Peels / Virtual); Complete Skin Journey program; About Vanessa with her real studio photo; real treatment clips; review grid; first-visit steps; FAQ accordion; journal; contact with hours + dark map; script CTA.

content_rules:
  - Display name "Facials by Vanessa CT". Logo: gold seven-petal lotus + FACIALS BY / Vanessa CT / SKIN JOURNEY™ (from the owner's flyer); favicon = the lotus alone. One logo file and one favicon only. Owner: Vanessa Gordon-McFarlene.
  - Prices, durations and deposits exactly as on the Zoca menu (15 services, 3 categories). $30 deposit for in-studio; virtual paid at booking.
  - Reviews are verbatim Google excerpts (surnames initialised); rating 4.9 from 66 Google reviews.
  - Hours from the Google Business Profile: Mon/Wed/Thu 11–7, Tue 11:30–7, Fri 4–7, Sat 11–5, Sun 3–6; virtual 10–5 daily.
  - Book CTAs -> https://facialsbyvanessactskinjourney.zoca.com/services (Zoca booking). No on-site forms.
  - "7+ years" (GBP) — the old site said 9; owner to confirm. About copy is a draft pending owner approval.
  - Stock lifestyle photos are Unsplash (free licence); the at-work photo and four clips are the owner's own.

files:
  - index.html / 404.html share byte-identical kora:shell header/footer blocks (header includes the top bar and mobile menu; footer includes the mobile Call/Book bar).
  - src/input.css holds @theme tokens and the page CSS in @layer components; assets/styles.css is compiled at deploy.
  - assets/site.js: header state, mobile menu, tabs, today's hours/open status, reveal, clips, 404 anchor rewrite.
  - Images are local WebP in assets/img, clips are MP4 + WebP posters in assets/video, one lotus logo + one lotus favicon (PNG) in assets/logo.
