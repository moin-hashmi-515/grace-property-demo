# Grace Property Consultant — Demo + CMS Plan (2026-10-30)
## Pitch issue (verified live 2026-10-30, graceproperty.pk)
- Do NOT pitch as "no website" or "no experience" — polished brochure, 15+ years, 300+ families claimed, founder Anwar AD.
- Pitchable problems: (1) brochure only — no listings search, filters or prices; (2) no on-site enquiry form — WhatsApp/phone/email only, so leads are lost if the visitor does not message immediately, and enquiries arrive unstructured; (3) recent work is 4 unpriced samples (one label repeated twice), not inventory.
- Offer mapping: WordPress listings + lead-capture site (search by area/type, price-on-enquiry until real prices added, structured enquiry form with area/budget/type, WhatsApp routing preserved), local SEO for Faisal/Model/Johar Town, plus Listings CMS.
- Tracker estimate: PKR 35,000–60,000 (estimate only), SEO from PKR 10,000/month separate. No real listings/prices invented — samples are layouts with "price on enquiry".
## Demo architecture (same limit as previous demos)
- GitHub Pages is static only. Front-end demo CMS: data in browser localStorage under gr_* keys (separate from sl_*, bc_*, ie_* on the same origin), no server, no real login, no real notifications. Production needs a backend/WordPress build.
- Files: index.html (public demo portal), admin.html (CMS: Dashboard, Listings, Enquiries, Articles, Settings), GRACE-PLAN.md (this file).
- Brand: black/charcoal + pale-gold accent as seen (no verified hex — gold in code is a visual approximation). Logo recreated as text in the demo; the real logo file is https://graceproperty.pk/logos/gp-logo-white.png (white GP monogram + house, on black) — not copied into the demo.
- Contact (verified): WhatsApp/phone 0321 8823656 (wa.me/923218823656), email contact@graceproperty.pk, address 188/A HBFC near Jinnah Hospital Block A Faisal Town Lahore 54770, hours Mon–Sat 11am–8pm Sun closed, founder Anwar AD, socials Facebook anwar.adgraceproperty, YouTube @gracepropertyofficial, TikTok @gracepropertyconsultant.
- Tests: JS syntax checked with node --check.
- Outstanding: enable GitHub Pages (main, root) for the new repo, verify live URLs, owner to confirm real listings/prices.

## Update 2026-10-30 — logo colour pattern + Connect
- Header and CMS now use the business's own logo image (https://graceproperty.pk/logos/gp-logo-white.png, white-on-black) for this pitch demo only, with the DEMO banner retained.
- Added a Logo Colour Pattern strip: Black (header/footer), White (logo monogram/headings), Pale Gold (buttons/accents as seen — no hex verified from code).
- Added a "Connect with Grace Property" section: WhatsApp / Call / Email buttons that in the demo show a sample confirmation and send nothing; in the live version they would open wa.me/923218823656, tel:+923218823656 and mailto:contact@graceproperty.pk respectively, as on the live site.
