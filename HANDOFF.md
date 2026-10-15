# Shamrock Transportation — handoff at ~60%

**Live:** https://10elizabethbell.github.io/shamrockTransparentPricing/ · **Repo:** https://github.com/10elizabethbell/shamrockTransparentPricing · **Built:** 2026-10-14 from Muse brief (run 2026-10-13, "Vibe 3 — Transparent pricing", approved by Ellie 2026-10-14)

## What's built
- One short page, single `index.html`, no images in the page itself, no animation, ~36KB. The world is an interstate at dusk: guide-sign green panels with an inset white border, lane-line yellow for the call buttons, highway-concrete light section, dusk sky. The page ground is deep roadside green, not black.
- **Simplified 2026-10-14 for a 40-70 audience (Ellie):** nothing moves, nothing to figure out, sections with little detail cut. Removed: the moving road dividers, the separate rate board, the "before you say yes" list, "Pack the car full", "How the trip goes", and the closing sign (its content now lives in the footer).
- **Applied Ellie's 40-70 research brief (2026-10-14, `~/Downloads/NJ_Florida_Vehicle_Delivery_Website_Research_and_Design_Brief_Ages_40_to_70.pdf`):** full phone number in the header, mixed-case section headings (hero stays sign caps), "When" made optional in the form, and a "Who will I be dealing with?" answer naming Ed (now replaced by Meet your driver).
- **Header:** shamrock and name on the left, the full number 732-300-3835 on the right (tap to call). On phones under 430px the name shrinks to 14px so the number fits; under 340px only the shamrock shows.
- **Hero:** "You fly, I'll drive." (Ed's own line, Ellie's pick 2026-10-15; was "One rate. No surprises.") and "I'm Ed, and I take your car between New Jersey and Florida for $1 a mile." (the price in yellow) One button: Get a rate by text (yellow, scrolls to the form). The hero Call Ed button was removed 2026-10-15 (Ellie): the header number is the call action at the top; the footer still has a Call Ed button. Behind and below: a dusk view down I-95 (pines, reflector posts, a distant green sign) drawn once as a still picture.
  - History, all 2026-10-14: steerable animated road (first build) → self-driving calm road → replaced by a still guide-sign hero ("I'll drive your car. You fly.") → Ellie brought the road hero back, static. The sign hero is in git history (commit 1d0b58a) if wanted.
- **No animation anywhere.** The road is drawn once on load (and again only if the window size changes); there's no animation loop. This overrides the pitch-site "signature motion" rule for this site, by Ellie's call. To pick a different still view, change `FRAME_TIME` (the bend) and `FRAME_TRAVEL` (where the posts and sign sit) at the top of the hero script.
- **How it works was removed** (Ellie, 2026-10-15). It's in git history (commit 535ea56) if wanted.
- **Pricing: $1 a mile** (Ellie, 2026-10-15). In the hero promise, the form heading "$1 a mile. That's the rate.", the meta description, and the pre-written text ("I'd like a price for my trip").
- **Meet your driver** (Ellie, 2026-10-15), right after the hero: a photo frame (guide-sign panel with a person outline and "Photo of Ed coming soon"), then "Hi, I'm Ed Brannagan, owner and driver…", then three paragraphs on how Ed treats the car (rewritten 2026-10-15 at Ellie's ask): careful, steady, "straight to where you're going"; never on a truck, carrier or trailer, winter things packed inside; his own number, ask anything first. **Confirm with Ed** he's comfortable promising "straight to where you're going" and the packed-car line (packing policy is still unconfirmed). Local / long distance / airport runs still appear in the FAQ and footer. To add the photo: replace the frame's contents with `<img src="ed.jpg" alt="…">` (`<!-- PHOTO -->` comment marks it); it fills the frame (4:3 on phones, square on desktop). The FAQ "Who will I be dealing with?" was removed since this section answers it.
- **The form** (on a guide sign): four big trip choices (New Jersey to Florida, Florida to New Jersey, Florida airport run, Somewhere else), then when (optional), car and name. "Text this to Ed" opens a pre-written text to 732-300-3835, with a line under the button explaining exactly that. A fallback box shows the text if Messages doesn't open. There's also a "Call 732-300-3835" link beside the form.
- **Straight answers:** four questions with the answers always showing (no tapping to open): packing the car full, airport runs, other routes, and when a truck carrier is the better call.
- **Footer as the close:** shamrock, "You fly. I'll drive.", "I'm Ed Brannagan, owner and driver", a Call Ed button (shamrock green #178049 with white text, not yellow, by Ellie 2026-10-15), the card tagline, and the services line.
- Favicon and iPhone icon: a shamrock on a guide-sign green tile. og:image is the hero at 1200x630.

## Assumptions I made
- **The shamrock is mine, drawn in SVG.** I don't have the card photo, and the brief says to ask before using a card scan publicly. Swap in Ed's real emblem when Ellie clears it; it's used in the header, the close, the favicon and `apple-touch-icon.png`.
- **Green:** the brief said to sample the card's green, else use a deep Irish green. I used interstate guide-sign green (#0d6a43) because it is both. Re-sample it from the card.
- **Footer close repeats "You fly. I'll drive."** now that it's also the headline. Left as a bookend; swap it if the repeat bothers you. The form section is now just the "$1 a mile. That's the rate." heading and the form: Ellie removed the intro line ("Tell me your trip and I'll tell you the miles and the total") and the "Rather talk? Call 732-300-3835" link on 2026-10-15.
- **"Trailer shippers make you empty it. I don't."** The brief names "pack the car full" as the #1 differentiator. Ed hasn't confirmed his own packing policy or any weight limit.
- **"I'm Ed Brannagan, owner and driver"** comes from the card. Nothing on the page says he's the only driver.
- **First-person voice as Ed.** The tone is plain-spoken, from the brief's notes; no social presence exists to match.
- **The hero names New Jersey and Florida.** The finishing rules keep service areas out of the hero, but here the route is the product and the research brief asks the first screen to say where. Cut it if you disagree.
- **One outline color (#8fd6ff) everywhere.**

## Placeholders and gaps
- **Rates: $1 a mile, on the page.** No example totals are shown, because the miles depend on his exact pickup and drop-off. Whether airport runs or short local trips have a minimum is unknown.
- **What a rate includes.** Once known, add one plain line under the form heading or an FAQ answer.
- **Missing facts:** insurance, hours, years in business, service area beyond NJ ↔ FL and "anywhere in Florida". None of these are on the page.
- **No email and no Facebook exist**, so the footer email and the "see more of my work" Facebook link are absent by design.
- **No photos at all.** A photo of Ed with his car (or the card) would do more for trust than anything else on the page.

## Questions for the owner
1. Is it only you who drives customers' cars? (The page says customers deal with you; it doesn't say you're the only driver.)
2. Is $1 a mile the same for airport runs and short local trips, or is there a minimum? Can we show an example total (e.g. a typical NJ → Orlando trip)?
3. Does the rate include gas, tolls and your trip home? How do you get back?
4. Can your number take texts? (The estimate form sends a text; call is the main button.)
5. Can customers pack the car full? Any limits?
6. Are you insured for driving customers' cars? What should the page say?
7. Which months do you run south and north? Do you have set dates or go whenever someone books?
8. Can we use the shamrock from your card, and a photo of you (ideally you beside a car)? How long have you been doing this?
9. Do you want youflyilldrive.com registered and pointed here? (It was unregistered as of 2026-10-13.)

## From the research brief, not done (needs Ed or your call)
- **Photo of Ed.** The brief's top trust signal. "Meet your driver" exists with a visible "Photo of Ed coming soon" frame; swap in the real photo before handing the site to customers. Years of experience go in that section too once known.
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
- **An example total** next to the price ("North Jersey to Orlando is about 1,000 miles, so about $1,000"), once Ed confirms his usual mileage. Very clear for this audience.

## Not verified
- Real devices, including Facebook's in-app browser. Tested with Playwright at 390, 360 and 1440: no overflow, no JS errors, the road picture renders and stays identical between frames, the Call Ed button sits in the first screen on phones (bottom at about 430px).
- The SMS handoff on real iOS and Android (`sms:+17323003835?&body=…`). The body is URL-encoded and decodes correctly in testing; the Messages app itself wasn't opened.
- Note for the skill: `scripts/shoot.sh` now produces blank canvases in this Chrome. Both its `--disable-accelerated-2d-canvas` flag and the rAF-to-setTimeout shim cause it. Playwright full-page capture (`isMobile`, real viewport) worked and also avoids the iframe making `100svh` the iframe's height.
