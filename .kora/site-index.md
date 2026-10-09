# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: FACIALS BY VANESSA CT SKIN JOURNEY! – Facials & skin care in Hartford, CT
purpose: Home page introducing Vanessa's facial studio in downtown Hartford, CT, featuring client reviews, treatments, story, gallery, FAQ, and a booking request form.
sections:
- `#hero` — Hero introductory block
- `#reviews` "What her clients say" — Customer reviews and testimonials: pree dreams, Tonya Noble, Viola Odenya, Tara Zayac, Judith Charlton-Lewis
- `#story` "About Vanessa" — Personal story and background about the esthetician
- `#gallery` "The work, in good light." — Photo gallery of the studio and treatments
- `#offerings` "Treatments & consultations" — Categorized list of skin care treatments and consultations: Signature Facials & Targeted Treatments, Deep Pore Cleansing Facial, Anti-Acne Facial Treatment, Anti-Acne Back Treatment, Hydrofacial with Serum, Men Deluxe Facial, Teen Facial, Clinical Peels & Skin Resurfacing, Chemical Peel, Brightening Pigment Peel, Microdermabrasion, Dermaplaning, Virtual Skin Consultations & Routine Planning, Virtual Skin Journey Consultation, Virtual Skin Journey Follow-up, Teen Virtual Consultation (14–18 yrs old), Complete Skin Journey Program
- `#faq` "What to know before you come in." — Frequently asked questions about appointments and spa amenities
- `#contact` "Tell me about your skin." — Contact details and booking request form
also: The 14 treatments listed in the offerings section are duplicated as Offer elements inside a structured-data OfferCatalog in the page head.

## services.html → /services
title: Facials & Peels in Hartford, CT | Facials by Vanessa
purpose: Showcase all fourteen treatments and virtual consultations offered by Vanessa in Hartford and worldwide, with detailed guidance and a booking request form.
sections:
- `#hero` "Which one is right for my skin?" — page introduction and a quick starting guide for treatment selection: Anti-Acne Back Treatment, Dermaplaning, Virtual Skin Journey Consultation, Virtual Skin Journey Follow-up, Teen Virtual Consultation
- `#offerings` "All treatments and consultations" — catalog of signature facials, targeted treatments, clinical peels, skin resurfacing, and virtual skin consultations: Signature Facials & Targeted Treatments, Deep Pore Cleansing Facial, Anti-Acne Facial Treatment, Anti-Acne Back Treatment, Hydrofacial with Serum, Men Deluxe Facial, Teen Facial, Clinical Peels & Skin Resurfacing, Chemical Peel, Brightening Pigment Peel, Microdermabrasion, Dermaplaning, Virtual Skin Consultations & Routine Planning, Virtual Skin Journey Consultation, Virtual Skin Journey Follow-up, Teen Virtual Consultation (14–18 yrs old), Complete Skin Journey Program
- `#contact` "Tell me about your skin." — booking request form and studio contact details
also: The page description appears in the standard meta description tag and in the structured-data block.

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `llms.txt` — Business contact information, address, phone number, and website URL: FACIALS BY VANESSA CT SKIN JOURNEY, Hartford  [content]
- `robots.txt` — 45 bytes — too small to hold content
- `sitemap.xml` — 160 bytes — too small to hold content

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
