# Shamrock Transportation — handoff at ~60%

**Live:** https://10elizabethbell.github.io/shamrockTransparentPricing/ · **Repo:** https://github.com/10elizabethbell/shamrockTransparentPricing · **Built:** 2026-10-14 from Muse brief (run 2026-10-13, "Vibe 3 — Transparent pricing", approved by Ellie 2026-10-14)

## What's built
- One short page, single `index.html`, no images in the page itself, no animation, ~20KB. The world is an interstate at dusk: guide-sign green panels with an inset white border, lane-line yellow for the call buttons, highway-concrete light section, dusk sky. The page ground is deep roadside green, not black.
- **Simplified 2026-10-14 for a 40-70 audience (Ellie):** nothing moves, nothing to figure out, sections with little detail cut. Removed: the moving road dividers, the separate rate board, the "before you say yes" list, "Pack the car full", "How the trip goes", and the closing sign (its content now lives in the footer).
- **Applied Ellie's 40-70 research brief (2026-10-14, `~/Downloads/NJ_Florida_Vehicle_Delivery_Website_Research_and_Design_Brief_Ages_40_to_70.pdf`):** full phone number in the header, a static three-step "How it works", mixed-case section headings (hero stays sign caps), "When" made optional in the form, and a "Who will I be dealing with?" answer naming Ed.
- **Header:** shamrock and name on the left, the full number 732-300-3835 on the right (tap to call). On phones under 430px the name shrinks to 14px so the number fits; under 340px only the shamrock shows.
- **Hero (replaced 2026-10-14, Ellie: the road hero was too much for this audience):** one still guide sign on a dusk-to-green sky: "I'll drive your car. You fly." over "New Jersey ⇄ Florida". Under it: "One flat rate, said up front. I'm Ed Brannagan, owner and driver." One yellow Call Ed button (`tel:`) and a plain "or text me for a rate" link to the form. A still strip of highway (yellow edge, white dashes) runs along the hero's bottom edge. Centered on desktop.
- **No animation anywhere.** The animated road and all its code are gone; the only script left is the text-message form. This overrides the pitch-site "signature motion" rule for this site, by Ellie's call.
- **How it works:** three plain numbered steps, no animation: call or text me / set your pickup / fly, your car follows.
- **One flat rate per trip** (the form, on a guide sign): four big trip choices (New Jersey to Florida, Florida to New Jersey, Florida airport run, Somewhere else), then when (optional), car and name. "Text this to Ed" opens a pre-written text to 732-300-3835, with a line under the button explaining exactly that. A fallback box shows the text if Messages doesn't open. There's also a "Call 732-300-3835" link beside the form.
- **Straight answers:** five questions with the answers always showing (no tapping to open): who you'll be dealing with (Ed), packing the car full, airport runs, other routes, and when a truck carrier is the better call.
- **Footer as the close:** shamrock, "You fly. I'll drive.", "I'm Ed Brannagan, owner and driver", a Call Ed button, the card tagline, and the services line.
- Favicon and iPhone icon: a shamrock on a guide-sign green tile. og:image is the hero at 1200x630.

## Assumptions I made
- **The shamrock is mine, drawn in SVG.** I don't have the card photo, and the brief says to ask before using a card scan publicly. Swap in Ed's real emblem when Ellie clears it; it's used in the header, the close, the favicon and `apple-touch-icon.png`.
- **Green:** the brief said to sample the card's green, else use a deep Irish green. I used interstate guide-sign green (#0d6a43) because it is both. Re-sample it from the card.
- **"One flat rate, said up front" and "One flat rate per trip"** are the brief's suggested positioning. Ed hasn't confirmed he quotes flat rates. The form lead promises he'll say who pays gas and tolls and the pickup and drop-off days before booking; confirm he's fine saying that.
- **"Trailer shippers make you empty it. I don't."** The brief names "pack the car full" as the #1 differentiator. Ed hasn't confirmed his own packing policy or any weight limit.
- **"I'm Ed Brannagan, owner and driver"** comes from the card. Nothing on the page says he's the only driver.
- **First-person voice as Ed.** The tone is plain-spoken, from the brief's notes; no social presence exists to match.
- **The hero sign names New Jersey and Florida.** The finishing rules keep service areas out of the hero, but here the route is the product and the research brief asks the first screen to say where. Cut it if you disagree.
- **One outline color (#8fd6ff) everywhere.**

## Placeholders and gaps
- **Rates (critical, Ed confirms Thursday).** When he does, the clearest place is a short, plain list of the four trips with the price next to each, just above the form (or the price inside each trip choice). There's an `<!-- RATES -->` comment at the trip choices.
- **What a rate includes.** Once known, replace the second sentence of the form's lead with the plain answer (`<!-- CONFIRM -->` comment in place).
- **Missing facts:** insurance, hours, years in business, service area beyond NJ ↔ FL and "anywhere in Florida". None of these are on the page.
- **No email and no Facebook exist**, so the footer email and the "see more of my work" Facebook link are absent by design.
- **No photos at all.** A photo of Ed with his car (or the card) would do more for trust than anything else on the page.

## Questions for the owner
1. Is it only you who drives customers' cars? (The page says customers deal with you; it doesn't say you're the only driver.)
2. Your flat rates: NJ → FL, FL → NJ, Florida airport runs, local / long distance.
3. Does the rate include gas, tolls and your trip home? How do you get back?
4. Can your number take texts? (The estimate form sends a text; call is the main button.)
5. Can customers pack the car full? Any limits?
6. Are you insured for driving customers' cars? What should the page say?
7. Which months do you run south and north? Do you have set dates or go whenever someone books?
8. Can we use the shamrock from your card, and a photo of you (ideally you beside a car)? How long have you been doing this?
9. Do you want youflyilldrive.com registered and pointed here? (It was unregistered as of 2026-10-13.)

## From the research brief, not done (needs Ed or your call)
- **Photo of Ed ("Meet your driver").** The brief's top trust signal. No photo exists, so no section and no placeholder. With a photo, put it in the hero or as a short "Meet your driver" block above How it works.
- **Insurance, years of experience, reviews, credentials.** The brief wants them; none are confirmed, so none are on the page. Its FAQ list (insurance, mileage, timing, what happens if there's a problem) needs Ed's answers first.
- **Sticky mobile Call button.** The brief recommends one; your finishing rules ban sticky bars. I kept your rule and put the number in the header instead. Say if you want the brief's version.
- **Warm-white background and Inter / Atkinson Hyperlegible fonts.** Skipped to keep the dusk-highway look you asked to keep and the system-font house style. Atkinson Hyperlegible would be the one to try if you want it.
- **Eyebrow line above the headline** ("PERSONAL VEHICLE DELIVERY | NJ & FL"). Skipped: the hero already says it in the promise line, and Impeccable bans eyebrows.
- **"Call for a Free Quote" as the button label.** Kept "Call Ed" since "free" isn't confirmed; it's a one-word change if Ed agrees.
- **Usability test with 5-6 people aged 40-70** (the brief's section 10). Worth doing before handing it to Ed.

## Ideas not built (yours to pick)
- **Brought back if wanted:** the cut sections are in git history (commit before "Simplify for a 40-70 audience"): the animated road hero (steerable in the first build, self-driving in the second), the moving road dividers, the rate board, "Pack the car full" with its list, and the four exit-sign steps.
- **Runner-up world:** an AAA TripTik strip map, with the route as flip-strips from NJ to FL and the rate per strip. Very familiar to this audience.
- **Highway Gothic look:** Overpass (a free Highway Gothic cousin) for the headings. I kept the system font stack per house style.
- **When rates exist,** show the flat number the moment a trip is picked, before texting.
- **Former headline "One rate. No surprises."** Could come back as the sign's headline once Ed confirms flat rates; the current one says what he does instead.

## Not verified
- Real devices, including Facebook's in-app browser. Tested with Playwright at 390, 360 and 1440: no overflow, no JS errors, the Call Ed button sits in the first screen on phones (bottom at about 500px).
- The SMS handoff on real iOS and Android (`sms:+17323003835?&body=…`). The body is URL-encoded and decodes correctly in testing; the Messages app itself wasn't opened.
- Note for the skill: `scripts/shoot.sh` now produces blank canvases in this Chrome. Both its `--disable-accelerated-2d-canvas` flag and the rAF-to-setTimeout shim cause it. Playwright full-page capture (`isMobile`, real viewport) worked and also avoids the iframe making `100svh` the iframe's height.
