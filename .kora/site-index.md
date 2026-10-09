# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: Facials in Hartford, CT | Skin Journey by Vanessa
purpose: Homepage for Facials by Vanessa CT (Skin Journey by Vanessa), a Downtown Hartford skin studio — treatments with prices, the virtual Complete Skin Journey Program, Vanessa's story, real studio clips, reviews, FAQ, journal and visit details.
sections:
- `#top` — hero: visually hidden SEO H1, visible headline 'Healthy skin is a journey. Begin yours in Hartford.' (a p.hero__title), intro, booking and virtual-consult buttons, Google rating
- trust strip of five short credentials: Every skin tone, Eco-friendly, Virtual consults
- `#paths-title` "Three ways to start your skin journey" — three treatment-category cards with starting prices linking to the menu: Signature Facials & Targeted Treatments, Clinical Peels & Skin Resurfacing, Virtual Skin Consultations & Routine Planning
- `#treatments` "Clear prices. No surprises." — tabbed treatment menu (Facials / Peels & Resurfacing / Virtual) with price, duration and deposit per service, plus a Cherry pay-over-time note: HydraFacial with Serum, Deep Pore Cleansing Facial, Anti-Acne Facial Treatment, Anti-Acne Back Treatment, Men's Deluxe Facial, Teen Facial, Brightening Pigment Peel, Chemical Peel, Microdermabrasion, Dermaplaning, Complete Skin Journey Program, Virtual Skin Journey Consultation, Teen Virtual Consultation (14–18), Virtual Skin Journey Follow-up, Cherry
- `#virtual` "The Complete Skin Journey Program" — signature three-month virtual program: price, three steps and links to single, teen and follow-up consults: Complete Skin Journey, Single consult, Teen consult, Follow-up
- `#about` "Hello, I'm Vanessa." — founder story in first person with studio photo, signature and three values: Vanessa Gordon-McFarlene, Honest advice, Tailored care, Calm space
- `#results` "Inside the treatment room" — four short looping clips filmed in the studio: HydraFacial infusion, Steam & prep, Detox mask, The after-glow
- `#reviews` "In their own words" — five Google review excerpts with first name and initial, link to all reviews
- `#visit-title` "What to expect" — four first-visit steps and amenity chips: Wheelchair accessible, Valet parking, Pay over time with Cherry
- `#faq` "Questions, answered" — seven-question FAQ accordion
- `#journal` "Skin notes from Vanessa" — three latest journal posts with category and published date, linking to the posts on the Zoca host
- `#contact` "Downtown Hartford" — studio address, directions/phone/email links, weekly hours table with today highlighted, virtual hours note and a Google map
- `#cta-title` "Ready to begin your skin journey?" — closing call to action with booking and call/text buttons
also: Treatment prices and durations appear both in the tabbed menu (#treatments) and in the path cards' 'From' prices, the program section (#virtual) and the hero note.
also: Studio hours live in the hours table (#contact), in site.js (the HOURS object that drives the open/closed status) and in the JSON-LD openingHoursSpecification.
also: Every Book button links to the Zoca booking platform rather than a page on this site, because booking is handled by Zoca.
also: The open/closed status line is written by site.js from its own HOURS object, so an hours change must update site.js as well as the table.
also: The page's only H1 is visually hidden (class sr) and holds the service keywords for search; the large visible hero headline is a p.hero__title, so edit that for on-screen wording and keep exactly one H1.

## 404.html → /404
title: Page not found | Skin Journey by Vanessa
purpose: Platform not-found page (noindex) that sends visitors back to the homepage or to call.
sections:
- `#nf-title` "This page has moved on." — not-found message with homepage and call buttons

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `llms.txt` — business summary for AI crawlers, carried over from the previous site: Virtual Skin Consultations & Routine Planning, Signature Facials & Targeted Treatments, Clinical Peels & Skin Resurfacing  [content]
- `robots.txt` — 95 bytes — too small to hold content
- `sitemap.xml` — sitemap listing the homepage
- `assets/site.js` — behaviour only: header state, mobile menu, tabs, studio hours table highlight and open/closed status (with an HOURS object), scroll reveal, studio clips, 404 anchors: HOURS  [content]

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
