# The Grind Coffee House — Spec Website (build #13)

> Part of It's Already Done Web Co. New builds: read
> `C:\Users\flylo\Documents\Website Business\PLAYBOOK-building-client-sites.md` first.

## What this is

Spec website for **The Grind Coffee House of Garrett** — woman-owned
independent coffee house, est. 2019 in Garrett (DeKalb Co.), famous for
**coffee flights**, now THREE units: the Garrett shop, a Glenbrook Square
(Fort Wayne) location that **replaced a departed Starbucks** (opened Feb 11,
2026), and a custom mobile espresso bar (since 2021). No website at all —
Facebook + joe.coffee ordering only. Owners have NOT seen/approved this site.

## Verified facts (sources: 21Alive, WANE, WFFT, Journal Gazette, KPC, Hull PG, Yelp, Restaurant Guru, joe.coffee)

- Owner: **Kayla Wegman** (21Alive + WFFT; say "owner Kayla Wegman" sparingly —
  fine as press-sourced, but no bio detail beyond press)
- Est. **2019** in Garrett; mobile espresso unit added **2021**; Glenbrook
  Square location opened **Feb 11, 2026** in a former Starbucks space —
  the local-replaces-Starbucks story was covered by 21Alive/WANE/JG
- Phone: **(260) 553-4283** (consistent everywhere)
- Garrett address: **1308 S. Randolph St., Suite F, Garrett, IN 46738** per
  recent journalism + Yelp (May 2026). CONFLICT: joe.coffee/Apple Maps say
  101 S. Randolph — site carries a "double-check on Facebook" note and the
  map embed queries by business name, not street address
- Glenbrook: 4201 Coldwater Rd, Fort Wayne (inside Glenbrook Square)
- Hours (Garrett) CONFLICT across sources: Mon–Thu 6a–5p agreed; Fri close
  5p vs 6p, weekend 8a–3p vs 8a–6p disputed → site shows "Mon–Fri from 6 AM ·
  weekends from 8 AM" + "check today's hours on Facebook." Glenbrook hours
  unknown → "mall hours — check before you go"
- Signature: **coffee flights** (four full-size cups) & cold brew flights,
  seasonal themed (e.g. Girl Scout "Cookie Jar"), twin cups; drinks incl.
  brown sugar shaken espresso, Blackberry Crumble iced coffee, Reese's cold
  brew, Toasted Marshmallow latte, Honey Almond Milk flat white, lavender
  matcha, frappes, teas, boba, smoothies, energy drinks ("Maui Wowie",
  "Cotton Candy Dreams"); NY-style bagels (rainbow, jalapeño, red pepper,
  French toast), breakfast bagels/burritos (sausage/bacon/"The Works"),
  muffins, pastries; sugar-free & dairy-free options
- Ordering: joe app —
  joe.coffee/locations/in/garrett/the-grind-coffee-house-of-garrett-garrett-23b8133d
  and DoorDash
- Reviews: Google 4.5★ (~262), joe.coffee 4.4★ (~296), Facebook 5.0★ (30)
- Facebook: facebook.com/GarrettDrinksCoffee · Instagram: @garrettcoffee
- Mobile bar does events/weddings + YLNI Farmers Market appearances

## WORDING RULES (do NOT violate)

- **NO PRICES anywhere** — the only found prices are delivery-app markups.
  Menu = drink/food names only + "order live on the joe app"
- NEVER mention the 2024 equipment theft / ex-husband court case / "Coffee
  Cabin" — true but absolutely not site material, and not pitch material
  beyond privately understanding the owner
- Don't name a roaster/bean source (unknown); no "voted best" claims
- Don't mention RBT Group; don't assert which Starbucks space beyond
  "a former Starbucks space" (that phrasing is press-sourced and fine)
- Address + hours carry check-Facebook honesty notes (conflicts above)
- Mobile-bar booking: "message us on Facebook for availability" — no terms/prices
- Reviews verbatim, lightly attributed ("— Pam L., Google review")

## Design language

- **Cozy modern coffeehouse** — Instagram-forward but warm. Palette: espresso
  `#33241c`, latte cream `#f4ead9`, caramel `#c98a3d`, steamed-milk white,
  dusty sage accent. Exposed-brick warmth in imagery.
- Display: **DM Serif Display** + body **Karla**.
- Signature motif: **the flight** — a row of four coffee-cup dots (CSS circles,
  varying fill like roast levels) as divider/badge; repeated in section breaks.
- Structure: proven skeleton (topbar → sticky header → hero → info strip →
  alternating blocks → reviews → CTA banner → footer w/ disclaimer).

## Pages

```
index.html      Home — hero (flight), story incl. Starbucks-replacement, three units, reviews
menu.html       The board — flights, espresso, cold brew, energy/boba, bagels (NO prices)
visit.html      Both locations + mobile bar — hours w/ honesty notes, maps, joe app links
css/style.css   single stylesheet
assets/         Gemini imagery (.prompt.txt sidecars gitignored)
```

- GoatCounter analytics on every page (flylow3d.goatcounter.com)
- Relative links only. Repo: flylow3d/grind-coffee-house ·
  Live: https://flylow3d.github.io/grind-coffee-house/

## Footer disclaimer (every page)

"**Concept preview.** This is a demonstration website built on spec by It's
Already Done Web Co. to show what The Grind Coffee House could look like
online. It is not affiliated with or endorsed by The Grind, and the owner has
not reviewed it. Details are drawn from public information and may be out of
date — check Facebook or call (260) 553-4283 to confirm hours and menu."
