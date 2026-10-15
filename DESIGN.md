---
name: Shamrock Transportation
description: A first-person view down I-95 at dusk that the reader's own scroll drives, with a plain promise, one yellow button and every section on an overhead road sign.
colors:
  lane-yellow: "#f5c242"
  lane-ink: "#132a1f"
  focus-sky: "#8fd6ff"
  sign-green: "#0d6a43"
  shamrock-green: "#178049"
  sign-white: "#f7fbf8"
  post-steel: "#8a9399"
  post-shadow: "#4a5157"
  dusk-top: "#132849"
  dusk-mid: "#2c4770"
  dusk-mauve: "#5d4f63"
  dusk-rose: "#8d6c72"
  horizon-peach: "#eaa064"
  sun-glow: "rgba(255,190,120,.6)"
  pine-far: "#2f4a5c"
  pine-near: "#1d3445"
  verge-far: "#284638"
  verge-near: "#1a3d2c"
  road-asphalt: "#2e363f"
  road-haze: "#5c6e74"
  ground: "#0c3a2a"
  ground-deep: "#082a1e"
  ink-soft: "#cfe5d9"
  field-ink: "#10261c"
  field-placeholder: "#6f897d"
  error-stroke: "#ffb199"
  error-text: "#ffd0c2"
  stroke-row: "rgba(247,251,248,.7)"
  rule-sign: "rgba(247,251,248,.22)"
  rule-footer: "rgba(247,251,248,.15)"
  tint-sent: "rgba(8,42,30,.55)"
typography:
  scale:
    xs: "14px"
    sm: "17px"
    base: "18px"
    md: "19px"
    lg: "20px"
    xl: "22px"
    close-min: "1.7rem"
    headline-min: "2rem"
    close-max: "2.8rem"
    headline-max: "3rem"
    display-min: "3rem"
    display-wide-min: "4.4rem"
    display-max: "6rem"
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(3rem,14.5vw,6rem)"
    fontWeight: 900
    lineHeight: 0.94
    letterSpacing: "-0.025em"
  display-wide:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(4.4rem,8.4vw,6rem)"
    fontWeight: 900
    lineHeight: 0.94
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2rem,7.4vw,3rem)"
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  headline-close:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.7rem,7.6vw,2.8rem)"
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(19px,5.2vw,20px)"
    fontWeight: 400
    lineHeight: 1.4
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 800
    lineHeight: 1.3
  control:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 800
    lineHeight: 1.15
  answer:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.55
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 700
    lineHeight: 1.15
  brand:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "0.02em"
rounded:
  link-focus: "6px"
  field: "12px"
  button: "14px"
  sign: "16px"
  dot: "50%"
spacing:
  gutter-tight: "14px"
  gutter-phone: "20px"
  gutter-desk: "40px"
  stack: "22px"
  column-gap: "56px"
  section-phone: "40px"
  section-desk: "56px"
  post-phone: "96px"
  post-desk: "120px"
  container: "1160px"
components:
  button-call:
    backgroundColor: "{colors.lane-yellow}"
    textColor: "{colors.lane-ink}"
    rounded: "{rounded.button}"
    padding: "14px 26px"
    height: "60px"
    typography: "{typography.control}"
  button-call-hero:
    backgroundColor: "{colors.lane-yellow}"
    textColor: "{colors.lane-ink}"
    rounded: "{rounded.button}"
    padding: "14px 30px"
    height: "76px"
    typography: "{typography.control}"
  button-call-footer:
    backgroundColor: "{colors.shamrock-green}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.button}"
    padding: "14px 26px"
    height: "60px"
    typography: "{typography.control}"
  header-call:
    textColor: "{colors.sign-white}"
    height: "48px"
    typography: "{typography.control}"
  sign-panel:
    backgroundColor: "{colors.sign-green}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.sign}"
    padding: "38px 36px"
  gantry-post:
    backgroundColor: "{colors.post-steel}"
    width: "14px"
    height: "92px"
  trip-row:
    textColor: "{colors.sign-white}"
    rounded: "{rounded.field}"
    padding: "10px 18px"
    height: "64px"
    typography: "{typography.control}"
  trip-row-selected:
    backgroundColor: "{colors.lane-yellow}"
    textColor: "{colors.lane-ink}"
    rounded: "{rounded.field}"
  text-field:
    backgroundColor: "{colors.sign-white}"
    textColor: "{colors.field-ink}"
    rounded: "{rounded.field}"
    padding: "14px 16px"
    height: "58px"
  sent-note:
    backgroundColor: "{colors.tint-sent}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.field}"
    padding: "18px"
    typography: "{typography.body}"
  faq-item:
    textColor: "{colors.sign-white}"
    padding: "20px 0"
    typography: "{typography.title}"
  footer-close:
    backgroundColor: "{colors.ground-deep}"
    textColor: "{colors.ink-soft}"
    padding: "56px 0 44px"
    typography: "{typography.small}"
---

# Design System: Shamrock Transportation

## Overview

**Creative North Star: "I-95 at Dusk, Driven by Your Scroll"**

The page opens from the driver's seat: a dusk sky going peach at the horizon, a pine treeline, a two-lane road with white edge lines and yellow center dashes (one right in front of the camera) bending gently right, reflector posts on both shoulders and a green I-95 guide sign just ahead. Over it, in huge uppercase white, "You fly, / I'll drive.", the second line in lane yellow. The road runs behind the whole page, and only the reader moves it: scrolling down backs the camera away so the road, posts and sign recede toward the horizon; scrolling up brings them back. Every section after the hero is an overhead road sign on a real steel structure (Meet your driver on a cantilever from the right, the $1-a-mile form on a span truss, Straight answers on a cantilever from the left), and the solid deep-green footer is where the road ends, closing with the call.

Density is low and type is big for a 40-to-70 reader on a phone. The ground is deep roadside green, never black. Lane yellow is the action color; a sky-blue outline is the one hover/focus voice. Nothing moves on its own.

**Key Characteristics:**
- A fixed canvas road at dusk behind the whole page, driven only by the reader's scroll; still under reduced motion.
- An uppercase two-line headline and one yellow "Get a rate by text" button; the header number is the call action.
- Every section is a guide-sign panel (green, inset white rule, 16px corners) hung on a real steel structure (cantilever from the right, span truss, cantilever from the left); once it climbs past the road it shrinks toward the horizon.
- One yellow for action; one sky-blue outline for hover and focus; shamrock green only for the footer call.
- One system font stack worked by weight: 900 headings, 800 controls, 400 talk.
- Phone-first, big targets (48px links, 58 to 76px controls), 17px text floor.

## Colors

Roadside green for the page, guide-sign green for every section, lane yellow for action, steel grey for sign posts, and a dusk palette that lives only in the road picture.

### Primary
- **Lane-Line Yellow** (lane-yellow): the hero "Get a rate by text" and the form's "Text this to Ed" buttons, the selected trip row, "I'll drive." and "$1 a mile" in the hero, the header phone icon, text selection. In the road picture it is the center dashes and the left posts' reflectors; both edge lines are white.
- **Lane Ink** (lane-ink): text and icons on yellow.
- **Shamrock Green** (shamrock-green): the footer Call Ed button only, with white text (4.8:1). Ellie, 2026-10-15: yellow there felt out of place.
- **Focus Sky** (focus-sky): the hover and focus outline, nothing else.

### Secondary
- **Guide-Sign Green** (sign-green): every section's sign panel and its 7px inset margin, the brand tile, the road's I-95 sign, the input caret.
- **Retroreflective White** (sign-white): text on green and dusk, the sign's inset rule, field fill, the edge lines. At reduced alpha: unselected trip-row stroke (stroke-row), the FAQ dividers on the sign (rule-sign) and the footer hairline (rule-footer).
- **Post Steel / Post Shadow** (post-steel, post-shadow): the sign structures: posts as a horizontal gradient shadow to steel at 45% and back, like a galvanized round post; arms as a vertical steel-to-shadow gradient; truss chords #7d868c and lacing and braces #6c757b; the light rail and its lamps in post-shadow.

### Tertiary (road picture only)
- **Dusk** (dusk-top, dusk-mid, dusk-mauve, verge-far, verge-near): the canvas's CSS fallback gradient, navy to dusk blue at 30%, mauve at 42%, then a hard step into verge green.
- **Canvas sky** (dusk-top, dusk-mid, dusk-rose, horizon-peach, sun-glow): the painted sky, navy through dusk blue at 62% and rose at 90% to peach on the horizon, with a flattened sun glow.
- **Pines, verge, road** (pine-far, pine-near, verge-far, verge-near, road-asphalt, road-haze): back and front pine rows, mown verge bands, asphalt; everything fades toward road-haze with distance.

### Neutral
- **Roadside Green** (ground): page ground under the canvas. **Night Verge** (ground-deep): the solid footer; at 55% the "Messages didn't open?" box (tint-sent), at 35% the photo frame's fill.
- **Soft Sign Ink** (ink-soft): secondary text on green, including FAQ answers.
- **Field Ink / Placeholder** (field-ink, field-placeholder): inside white fields.
- **Warning Peach** (error-stroke, error-text): invalid stroke and the error sentence beneath it.

### Named Rules
**The Never-Black Rule.** The darkest surface is ground-deep. Black appears only inside soft shadows, never as a ground.

**The One Yellow Rule.** In the interface, a yellow rectangle is always a control. Yellow type is reserved for the headline's second line, the price, links and icons. The road picture paints yellow where a real road has it (center dashes, left reflectors).

**The One Outline Rule.** Hover and focus on every control is a 3px focus-sky outline (offset 2 to 3px; 6px radius on text links). No other hover color, fill change or glow.

## Typography

**Display Font:** System UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** Same stack (the PRODUCT.md stack constraint: system fonts only)

**Character:** One family worked by weight like highway lettering: 900 for what a driver reads off a sign, 800 for anything the reader taps, 400 for Ed talking.

### Hierarchy
- **Display** (900, 3rem to 6rem; 4.4rem to 6rem from 760px; 6rem from 1100px; 0.94, uppercase, -0.025em): the hero h1 only, two block lines, second line lane yellow, with a soft dark text-shadow.
- **Headline** (900, 2rem to 3rem, 1.1, sentence case): the h2 on each sign, held to 14ch on the form. The footer's "You fly. I'll drive." uses **Headline Close** (1.7rem to 2.8rem).
- **Promise** (400, 19px to 20px, 1.4, max 32ch on phones): the white line under the h1, with a soft text-shadow.
- **Title** (800, 22px, 1.3): FAQ questions, Ed's greeting line.
- **Control** (800, 20px): button text, form legends, labels, trip rows. The header phone link is 800 at 18px (17px under 480px, 22px from 760px).
- **Answer** (400, 19px): FAQ answers (60ch, ink-soft), the footer Ed line, field text. Ed's introduction runs at 20px, 36ch.
- **Body** (400, 18px, 1.55): running copy, notes, error sentences (700).
- **Small** (17px): a button's second line (700, centered under the first line), footer text.
- **Brand** (900, 17px, uppercase two-line wordmark; 20px from 760px). Under 480px it drops to 14px with no tracking so the full header number fits; that is the one recorded exception to the floor. Under 340px the words go visually hidden and the tile remains.

The road sign's lettering is drawn in the same stack at 800 (route) and 900 (destination), sized to the sign.

### Named Rules
**The 65 MPH Rule.** No text under 17px (the narrow-phone wordmark is the single exception), and nothing a reader acts on is lighter than 700.

## Layout

Phone-first single column, 20px gutters in a 1160px container (40px from 760px; 14px in the header under 480px).

The road canvas is fixed to the viewport behind everything (z 0); main and footer sit above it (z 1) with no section backgrounds, so the road shows between signs. The hero is a tall stage, `max(640px, min(100svh, 1000px))` (560px in short landscape), left-aligned at every width. Copy starts 96px down (132px from 760px, 84px in short landscape): h1, promise 18px below, the button 24px below. On phones the button is full width at 76px; from 760px it sits at its own width. The horizon rides 48px under the hero copy (or 42% of the screen, whichever is lower) and rises with the scroll until it settles at 16% of the screen height.

Each section is a "stop": 84px above and 92px below on phones, 110px and 120px from 760px. The top padding holds the structure above the sign; the bottom padding equals how far the posts run below it. Sign panels pad 26px 22px, 38px 36px from 760px.

The header is absolutely placed over the hero, not sticky: brand top-left, full phone number top-right, 72px tall (88px from 760px). From 760px trip rows pair into two columns. Only from 1024px do the signs split 5fr / 7fr with a 56px gap (Meet: headline across, photo left, copy right; form: headline left, form right; FAQ: headline left, answers right) and When / Your car share a row; landscape phones and small tablets stay single-column, so the form never squeezes. The footer is centered with one call button (max 420px). Breakpoints: 760px, 1024px, 1100px; max-width 479px, 379px (header phone icon hides), 339px; max-height 500px landscape.

## Elevation & Depth

Flat, with mounted signs and lifted call buttons. Depth comes from the road picture itself: perspective, haze toward the horizon, a darker front pine row, and signs that recede along the road as they scroll past. Shadows are soft with negative spread, never hard offsets; text over the dusk carries soft dark halos.

### Shadow Vocabulary
- **Sign Mount** (`box-shadow: inset 0 0 0 7px #0d6a43, inset 0 0 0 10px #f7fbf8, 0 18px 40px -18px rgba(0,0,0,.6)`): every sign panel.
- **Button Lift** (`box-shadow: 0 8px 22px -8px rgba(0,0,0,.55)`): call buttons.
- **Headline Halo** (`text-shadow: 0 2px 18px rgba(0,0,0,.28)`): the hero h1.
- **Promise Halo** (`text-shadow: 0 1px 10px rgba(0,0,0,.4)`): the promise line.
- **Dusk Legibility** (`text-shadow: 0 1px 8px rgba(0,0,0,.45)`): the header phone link.

### Named Rules
**The Reader Drives Rule.** Motion comes only from the reader's own scroll; nothing is ever autonomous. Scrolling down backs the camera away (travel falls) so the dashes, posts and the I-95 sign recede toward the horizon; scrolling up brings them back. The camera scale is fixed at its top-of-page value, so the road slides up and never zooms. Once a sign's foot rises above 30% of the road height it shrinks toward the horizon along the road (scale from its bottom center, translate along the road, fading out between scale 0.42 and 0.12). The canvas redraws once per scroll frame and on a real resize, nothing more: no loop, no autoplay, no entrance effects. Control transitions: button press (translateY 1px, scale .99 over .2s cubic-bezier(.2,.8,.2,1)), outline color (.15s), trip-row color (.15s). The jump to the form scrolls smoothly. Under prefers-reduced-motion the road is one still frame, signs never transform, the jump is instant and transitions are off.

**The Mounted Sign Rule.** The only raised surfaces are the sign panels and the call buttons. Content on a sign stays flat, divided by space or rules, never cards inside the sign.

## Shapes

Softly rounded rectangles stepping down with size: sign panel 16px, buttons 14px, trip rows, fields, the photo frame and the sent box 12px, text-link outlines 6px. Circles only for each trip row's 22px radio ring (7px stroke when selected). Sign posts are square-ended bars (12px wide, 96px tall; 16px and 120px from 760px) at 12% in from each side of the sign. Icons are inline stroked SVG (2.4 to 2.6 stroke, round caps): 24px in buttons, 20px in the header. The shamrock sits in a 44 to 52px rounded sign tile in the header and alone at 64px in the footer. In the picture, the guide sign is a rounded green panel with an inset white rule on two posts; the reflector posts are thin white bars with a colored reflector near the top.

## Components

### Call Button
Heavy, wide, unmistakable. Lane-yellow fill and 3px border, lane-ink text, 14px radius, Button Lift, a 24px down-arrow or SMS icon. 60px tall; 76px in the hero. Used as the hero's "Get a rate by text" (the only hero action) and the form's "Text this to Ed". The footer's Call Ed is the same shape in shamrock green with white text, a phone icon on the number line and the number as a second 17px line.

### Road (signature)
A full-viewport fixed canvas behind the page, decorative and hidden from assistive tech: the dusk sky and sun glow, two rows of pines, mown verge bands, a two-lane road bending right with white edge lines on both sides and yellow center dashes (1.2 on, 3.8 off, one starting just in front of the camera), reflector posts (white-reflector right, yellow-reflector left) and one green guide sign on the right shoulder just ahead at the top of the page. The sign reads I-95 NORTH / NEW JERSEY from April through August and I-95 SOUTH / FLORIDA the rest of the year. Driven by scroll per the Reader Drives Rule; the opaque footer ends it.

### Overhead Sign (gantry)
Every section after the hero is a Sign Panel hung on a real interstate structure, drawn in CSS behind the panel (`.gantry > .rig` + `.sign`), modelled on Ellie's reference photos (2026-10-15):
- **Cantilever from the right** (Meet your driver): one tall post on the right shoulder (14px, 20px from 760px), an arm reaching over the sign's top, a second arm behind it at 55%, a diagonal brace from the post top to the upper arm. The panel leaves 30px (64px from 760px) on the post side so the arms show.
- **Span truss** (the rate form): a post on each shoulder in the page gutter and a lattice truss across the road (two chords, crossed lacing) with the sign mounted on its face.
- **Cantilever from the left** (Straight answers): the mirror of the first.
- All three carry a light rail with lamps under the panel. The whole structure scales with the panel from its bottom center, so it recedes along the road like a real overhead sign.

### Meet Your Driver
The first sign: the headline, then a photo frame (night-verge tint at 35%, 2px white stroke at 35%, 12px radius; 4:3, max 520px; square from 1024px) holding a 96px person outline and "Photo of Ed coming soon" in ink-soft, swapped for a cover-fit photo later; then a 22px/800 greeting and 20px lines, 36ch max.

### Rate Form (sign)
"$1 a mile. That's the rate." and the form on one sign: trip rows, When / Your car / Your name fields, the yellow "Text this to Ed" button and a soft-white note; 5fr / 7fr from 1024px.

### Trip Rows (radio)
64px rows, 2px stroke-row border, 20px/800 sentence-case text led by a 22px radio ring. Selected: lane-yellow fill, lane-ink text, thick ring; color change only. Forced-colors mode adds a Highlight outline.

### Inputs / Fields
Sign-white fill and stroke, field-ink 19px text, 12px radius, 58px tall, sign-green caret; labels 20px/800, the "optional" hint 600 in ink-soft. Error: warning-peach stroke and an 18px/700 sentence in Ed's voice below.

### FAQ (always open, on a sign)
"Straight answers" on the third sign: headline left, answers right from 1024px. Each 22px/800 white question has its 19px ink-soft answer directly beneath, separated by 2px rule-sign lines (the first has none from 1024px). Nothing collapses.

### Header
No nav bar. The brand (shamrock sign tile plus two-line uppercase wordmark) links to top; the full phone number with a yellow phone icon sits top-right as a `tel:` link. It scrolls away with the hero.

### Footer (the close)
Solid Night Verge ground that ends the road, centered: 64px white shamrock, the close headline, the Ed line, one Shamrock Green call button, the italic tagline, then fine print under a rule-footer hairline.

## Do's and Don'ts

### Do:
- **Do** let only the reader's scroll move the road and the signs; keep it a still frame under reduced motion.
- **Do** keep the hero to the two-line uppercase headline, the promise, and one yellow button to the form; the call lives in the header.
- **Do** hang every section after the hero on a real structure (cantilever or span truss), alternating sides down the page, never floating on bare posts.
- **Do** use the 3px focus-sky outline for every hover and focus.
- **Do** keep controls 58px or taller, links 48px, answer choices as large rows, text at 17px or larger.
- **Do** show answers in full; a question and its answer sit together.

### Don't:
- **Don't** animate anything on its own: no drive loop, autoplay, timed reveals or entrance effects; no zoom on scroll.
- **Don't** use accordions, tabs, carousels or other hide-and-reveal patterns.
- **Don't** use black or neutral charcoal as any ground; the darkest is ground-deep.
- **Don't** add a sticky header or sticky call bar, or email links.
- **Don't** add a second hero action; the call is the header number.
- **Don't** put yellow fills on interface non-controls.
- **Don't** use hard offset shadows; depth is soft.
