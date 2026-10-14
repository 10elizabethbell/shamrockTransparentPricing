# Shamrock Transportation — handoff at ~60%

**Live:** https://10elizabethbell.github.io/shamrockTransparentPricing/ · **Repo:** https://github.com/10elizabethbell/shamrockTransparentPricing · **Built:** 2026-10-14 from Muse brief (run 2026-10-13, "Vibe 3 — Transparent pricing", approved by Ellie 2026-10-14)

## What's built
- One page, single `index.html`, no images in the page itself, ~50KB. The world is an interstate at dusk: guide-sign green panels with an inset white border and exit tabs, lane-line yellow for the call button, asphalt, highway-concrete light sections, dusk sky. The page ground is deep roadside green, not black.
- **Hero:** "One rate. No surprises." and "You fly. I'm Ed, and I'll drive your car between New Jersey and Florida." Two buttons: Call Ed (filled yellow, `tel:`) and Get my rate (outlined, scrolls to the form).
- **Signature motion:** a live I-95 seen from the driver's seat, with dashes flowing, reflector posts, a pine treeline and a low Florida-peach sun. It bends and crests by itself. Dragging on the road (finger or mouse) steers it: sideways bends it, down dips it over a crest. It springs back and takes over again after 2.2s. Only the road area takes drags, so swiping on the headline still scrolls the page. Every so often a green sign passes: "I-95 SOUTH / FLORIDA" from September to March, "I-95 NORTH / NEW JERSEY" from April to August.
- The same road appears from above as the section dividers: it winds, its dashes flow, and a pointer or finger pushes it aside. The how-it-works spine is a flowing lane line.
- **Rate board** (a guide sign): four routes from the card. Tapping a route jumps to the form with that trip picked. One note: "Tap your route to get my flat rate."
- **Next to it, "Before you say yes, I'll tell you":** who pays for gas, who pays the tolls, how I get back home, your pickup and drop-off days. This is deliberately phrased as questions he'll answer, not as what's included.
- **"Pack the car full"** (the driveaway differentiator), **How the trip goes** (4 exit signs), and the **Get my rate** form. The form takes trip, when, car and name, then opens a pre-written text to 732-300-3835. A fallback box shows the text if Messages doesn't open, plus a call link.
- **FAQ:** when a truck carrier is the better call, airport runs, other routes. Then a closing sign with the card tagline, and the footer.
- Favicon and iPhone icon: a shamrock on a guide-sign green tile. og:image is the hero at 1200x630.

## Assumptions I made
- **The shamrock is mine, drawn in SVG.** I don't have the card photo, and the brief says to ask before using a card scan publicly. Swap in Ed's real emblem when Ellie clears it; it's used in the header, the close, the favicon and `apple-touch-icon.png`.
- **Green:** the brief said to sample the card's green, else use a deep Irish green. I used interstate guide-sign green (#0d6a43) because it is both. Re-sample it from the card.
- **"One rate. No surprises." and "You hear the whole number on the phone, before you book"** are the brief's suggested positioning. Ed hasn't confirmed he quotes flat rates.
- **"Trailer shippers make you empty it. I don't."** The brief names "pack the car full" as the #1 differentiator. Ed hasn't confirmed his own packing policy or any weight limit.
- **"I'm Ed Brannagan, owner and driver"** comes from the card. Nothing on the page says he's the only driver.
- **First-person voice as Ed.** The tone is plain-spoken, from the brief's notes; no social presence exists to match.
- **The manifest ("Winter clothes / Golf clubs / The good pans / Whatever fits") is illustrative**, not something Ed said.
- **The hero sign reads "I-95"**: assumed route.
- **The hero names New Jersey and Florida.** The finishing rules keep service areas out of the hero, but here the route is the product. Cut it if you disagree.
- **One outline color (#8fd6ff) everywhere.** On the light concrete FAQ it sits on a 2px deep-green ring so it still shows up.

## Placeholders and gaps
- **Rates (critical, Ed confirms Thursday).** When he does, add one `<span class="rate">$___ flat</span>` under each route's name in the rate board and delete the `board-note` line. The HTML comment above the list says exactly this, and the CSS for `.rate` is already there.
- **What a rate includes.** Once known, turn "Before you say yes, I'll tell you" into an included / not-included list (`<!-- CONFIRM -->` comment in place).
- **Missing facts:** insurance, hours, years in business, service area beyond NJ ↔ FL and "anywhere in Florida". None of these are on the page.
- **No email and no Facebook exist**, so the footer email and the "see more of my work" Facebook link are absent by design.
- **No photos at all.** A photo of Ed with his car (or the card) would do more for trust than anything else on the page.

## Questions for the owner
1. Your flat rates: NJ → FL, FL → NJ, Florida airport runs, local / long distance.
2. Does the rate include gas, tolls and your trip home? How do you get back?
3. Can your number take texts? (The estimate form sends a text; call is the main button.)
4. Can customers pack the car full? Any limits?
5. Are you insured for driving customers' cars? What should the page say?
6. Which months do you run south and north? Do you have set dates or go whenever someone books?
7. Can we use the shamrock from your card, and a photo of you?
8. Do you want youflyilldrive.com registered and pointed here? (It was unregistered as of 2026-10-13.)

## Ideas not built (yours to pick)
- **Runner-up world:** an AAA TripTik strip map, with the route as flip-strips from NJ to FL, a highlighter route line, and the rate per strip. Very familiar to a 60+ audience. Impeccable's roll assigned "luggage tags / claim checks" (seed b9fde720). I overrode it under the pitch-site rule (brand + a fluid, touchable signature).
- **Highway Gothic look:** the sign lettering would sing in Overpass (a free Highway Gothic cousin). I kept the system font stack per house style.
- **Mile markers on the dividers** showing progress down the page (NJ … FLORIDA). No mileage numbers.
- **A pair of taillights far ahead on the hero road**, only if it reads instantly as a car.
- **Drop the sign treatment from the form panel** (a sign with text boxes isn't a real object). Keep it for the board, the exits and the close.
- **Desktop FAQ left column** is a little empty below its heading.
- **When rates exist,** an instant estimate on the form (pick the route, see the flat number before texting).
- **Tuning:** `SPEED`, `STEER`, `HILL_DOWN`, `AUTO_BACK` at the top of the hero IIFE; `FLOW`, `PUSH_R` in the divider IIFE.

## Not verified
- Real-device touch feel and frame rate on an older Android inside Facebook's in-app browser. Tested with Playwright and real CDP touch events at 390 and 360: headline swipe scrolls, road drag steers without scrolling, hero animates, no overflow, no JS errors.
- The SMS handoff on real iOS and Android (`sms:+17323003835?&body=…`). The body is URL-encoded and decodes correctly in testing; the Messages app itself wasn't opened.
- Note for the skill: `scripts/shoot.sh` now produces blank canvases in this Chrome. Both its `--disable-accelerated-2d-canvas` flag and the rAF-to-setTimeout shim cause it. Playwright full-page capture (`isMobile`, real viewport) worked and also avoids the iframe making `100svh` the iframe's height.
