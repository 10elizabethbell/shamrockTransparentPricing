---
name: Shamrock Transportation
description: A still first-person view down I-95 at dusk, with a plain promise, a yellow call button and the rate request on a guide sign.
colors:
  lane-yellow: "#f5c242"
  lane-ink: "#132a1f"
  focus-sky: "#8fd6ff"
  sign-green: "#0d6a43"
  sign-white: "#f7fbf8"
  dusk-top: "#132849"
  dusk-mid: "#2c4770"
  dusk-veil: "rgba(19,40,73,.22)"
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
  concrete: "#e4e9e6"
  concrete-ink: "#0c3a2a"
  concrete-soft: "#33584a"
  field-ink: "#10261c"
  field-placeholder: "#6f897d"
  error-stroke: "#ffb199"
  error-text: "#ffd0c2"
  stroke-row: "rgba(247,251,248,.7)"
  rule-footer: "rgba(247,251,248,.15)"
  rule-concrete: "rgba(12,58,42,.18)"
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
  section-phone: "60px"
  section-desk: "88px"
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
  button-line:
    backgroundColor: "{colors.dusk-veil}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.button}"
    padding: "14px 30px"
    height: "76px"
    typography: "{typography.control}"
  header-call:
    textColor: "{colors.sign-white}"
    height: "48px"
    typography: "{typography.control}"
  step-number:
    backgroundColor: "{colors.lane-yellow}"
    textColor: "{colors.lane-ink}"
    rounded: "{rounded.dot}"
    size: "48px"
    typography: "{typography.title}"
  sign-panel:
    backgroundColor: "{colors.sign-green}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.sign}"
    padding: "38px 36px"
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
    backgroundColor: "{colors.concrete}"
    textColor: "{colors.concrete-ink}"
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

**Creative North Star: "One Still Frame of I-95 at Dusk"**

The page opens from the driver's seat: a dusk sky going peach at the horizon, a pine treeline, a two-lane road with a yellow left edge and white dashes bending gently right, reflector posts on both shoulders and a green guide sign ahead. Over it, in huge uppercase white, "One rate. / No surprises.", the second line in lane yellow. It is one still picture, not a scene that plays. Below the hero the interstate's own grammar carries on: the rate form on a guide-sign panel, answers on highway concrete, a dark footer that closes with the call.

Density is low and type is big for a 40-to-70 reader on a phone. The ground is deep roadside green, never black; the one light section is concrete. Lane yellow is the action color; a sky-blue outline is the one hover/focus voice. Nothing moves.

**Key Characteristics:**
- A still canvas road at dusk behind an uppercase two-line headline and two buttons (yellow call, white outline).
- One sign panel (green, inset white rule, 16px corners) holds the rate form; the road's own sign repeats that grammar.
- One yellow for action; one sky-blue outline for hover and focus.
- One system font stack worked by weight: 900 headings, 800 controls, 400 talk.
- Phone-first, big targets (48px links, 58 to 76px controls), 17px text floor.

## Colors

Roadside green and concrete for the page, guide-sign green for the panel, lane yellow for action, and a dusk palette that lives only in the hero picture.

### Primary
- **Lane-Line Yellow** (lane-yellow): call buttons, the selected trip row, step-number discs, "No surprises.", the "Call 732-300-3835" link beside the form, the header phone icon, text selection. In the road picture it is the left edge line and the left posts' reflectors. Never on concrete.
- **Lane Ink** (lane-ink): text and icons on yellow.
- **Focus Sky** (focus-sky): the hover and focus outline, nothing else.

### Secondary
- **Guide-Sign Green** (sign-green): the form's sign panel and its 7px inset margin, the brand tile, the distant road sign, the input caret.
- **Retroreflective White** (sign-white): text on green and dusk, the sign's inset rule, the outline button's border, field fill, the right edge line and lane dashes. At reduced alpha: unselected trip-row stroke (stroke-row) and the footer hairline (rule-footer).

### Tertiary (hero only)
- **Dusk** (dusk-top, dusk-mid, dusk-mauve, verge-far, verge-near): the hero's CSS gradient behind the canvas, navy to dusk blue at 40%, mauve at 56%, then a hard step into verge green; a 56px fade at the bottom lands it on the ground.
- **Canvas sky** (dusk-top, dusk-mid, dusk-rose, horizon-peach, sun-glow): the painted sky, navy through dusk blue at 62% and rose at 90% to peach on the horizon, with a flattened sun glow.
- **Pines, verge, road** (pine-far, pine-near, verge-far, verge-near, road-asphalt, road-haze): back and front pine rows, mown verge bands, asphalt; everything fades toward road-haze with distance.
- **Dusk Veil** (dusk-veil): the outline button's translucent fill.

### Neutral
- **Roadside Green** (ground): page ground. **Night Verge** (ground-deep): footer; at 55% the "Messages didn't open?" box (tint-sent).
- **Soft Sign Ink** (ink-soft): secondary text on green.
- **Highway Concrete** (concrete) with **Concrete Ink / Soft** (concrete-ink, concrete-soft): the FAQ; rule-concrete divides answers.
- **Field Ink / Placeholder** (field-ink, field-placeholder): inside white fields.
- **Warning Peach** (error-stroke, error-text): invalid stroke and the error sentence beneath it.

### Named Rules
**The Never-Black Rule.** The darkest surface is ground-deep. Black appears only inside soft shadows, never as a ground.

**The One Yellow Rule.** In the interface, a yellow rectangle is always a control; the only non-control yellow fills are the round step-number discs. Yellow type is reserved for the headline's second line, links and icons. The road picture paints yellow where a real road has it (edge line, reflectors).

**The One Outline Rule.** Hover and focus on every control is a 3px focus-sky outline (offset 2 to 3px; 6px radius on text links). No other hover color, fill change or glow.

## Typography

**Display Font:** System UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** Same stack (the PRODUCT.md stack constraint: system fonts only)

**Character:** One family worked by weight like highway lettering: 900 for what a driver reads off a sign, 800 for anything the reader taps, 400 for Ed talking.

### Hierarchy
- **Display** (900, 3rem to 6rem; 4.4rem to 6rem from 760px; 6rem from 1100px; 0.94, uppercase, -0.025em): the hero h1 only, two block lines, second line lane yellow, with a soft dark text-shadow.
- **Headline** (900, 2rem to 3rem, 1.1, sentence case): section h2, held to 14ch on the form. The footer's "You fly. I'll drive." uses **Headline Close** (1.7rem to 2.8rem).
- **Promise** (400, 19px to 20px, 1.4, max 32ch on phones): the white line under the h1, with a soft text-shadow.
- **Title** (800, 22px, 1.3): step titles, FAQ questions, the "Rather talk?" line; the step digit is 22px at 900.
- **Control** (800, 20px): button text, form legends, labels, trip rows. The header phone link is 800 at 18px (17px under 480px, 22px from 760px).
- **Answer** (400, 19px): FAQ answers (60ch), step lines, the footer Ed line, field text.
- **Body** (400, 18px, 1.55): running copy, notes, error sentences (700).
- **Small** (17px): a button's second line (700, centered under the first line), footer text.
- **Brand** (900, 17px, uppercase two-line wordmark; 20px from 760px). Under 480px it drops to 14px with no tracking so the full header number fits; that is the one recorded exception to the floor. Under 340px the words go visually hidden and the tile remains.

The road sign's lettering is drawn in the same stack at 800 (route) and 900 (destination), sized to the sign.

### Named Rules
**The 65 MPH Rule.** No text under 17px (the narrow-phone wordmark is the single exception), and nothing a reader acts on is lighter than 700.

## Layout

Phone-first single column, 20px gutters in a 1160px container (40px from 760px; 14px in the header under 480px). Sections run 56 to 64px vertical padding on phones, 88px on desktop.

The hero is a tall stage, `max(640px, min(100svh, 1000px))` (560px in short landscape), left-aligned at every width. Copy starts 96px down (132px from 760px, 84px in short landscape): h1, promise 18px below, actions 24px below. On phones the two buttons stack full width at 76px with a 12px gap; from 760px they sit side by side at their own width with a 16px gap. The canvas fills the hero; its horizon sits 48px below the copy or at 42% of the height, whichever is lower, so the road always shows under the buttons.

The header is absolutely placed over the hero, not sticky: brand top-left, full phone number top-right, 72px tall (88px from 760px). From 760px trip rows pair into two columns. Only from 1024px do the form and FAQ split 5fr / 7fr with a 56px gap and When / Your car share a row (landscape phones and small tablets stay single-column, so the form never squeezes). The footer is centered with one call button (max 420px). Breakpoints: 760px, 1024px, 1100px; max-width 479px, 379px (header phone icon hides), 339px; max-height 500px landscape.

## Elevation & Depth

Flat, with one mounted sign and a lifted yellow button. Depth in the hero comes from the picture itself: perspective, haze toward the horizon, a darker front pine row. Shadows are soft with negative spread, never hard offsets; text over the dusk carries soft dark halos.

### Shadow Vocabulary
- **Sign Mount** (`box-shadow: inset 0 0 0 7px #0d6a43, inset 0 0 0 10px #f7fbf8, 0 18px 40px -18px rgba(0,0,0,.6)`): the form's sign panel.
- **Button Lift** (`box-shadow: 0 8px 22px -8px rgba(0,0,0,.55)`): yellow call buttons.
- **Headline Halo** (`text-shadow: 0 2px 18px rgba(0,0,0,.28)`): the hero h1.
- **Promise Halo** (`text-shadow: 0 1px 10px rgba(0,0,0,.4)`): the promise line.
- **Dusk Legibility** (`text-shadow: 0 1px 8px rgba(0,0,0,.45)`): the header phone link and the outline button's label.

### Named Rules
**The Still Page Rule.** Nothing animates. The road is drawn once as a still picture and redrawn only when the hero's size changes; no loop, no parallax, no scroll or entrance effects. The only transitions are on controls: button press (translateY 1px, scale .99 over .2s cubic-bezier(.2,.8,.2,1)), outline color (.15s), trip-row color (.15s). The jump to the form scrolls smoothly; under prefers-reduced-motion it jumps and transitions are off.

**The Mounted Sign Rule.** The only raised surfaces are the sign panel and the yellow call button. Steps, answers and footer content stay flat, divided by space or rules, never cards.

## Shapes

Softly rounded rectangles stepping down with size: sign panel 16px, buttons 14px, trip rows, fields and the sent box 12px, text-link outlines 6px. Circles only for the 48px step discs and each trip row's 22px radio ring (7px stroke when selected). Icons are inline stroked SVG (2.4 to 2.6 stroke, round caps): 24px in buttons, 20px in the header. The shamrock sits in a 44 to 52px rounded sign tile in the header and alone at 64px in the footer. In the picture, the guide sign is a rounded green panel with an inset white rule on two posts; the reflector posts are thin white bars with a colored reflector near the top.

## Components

### Call Button
Heavy, wide, unmistakable. Lane-yellow fill and 3px border, lane-ink text, 14px radius, Button Lift, a leading 24px phone or SMS icon, the number as a second 17px line. 60px tall; 76px in the hero. Used in the hero, as "Text this to Ed" on the form, and in the footer.

### Line Button (hero only)
The second path: "Get a rate by text" with a trailing 24px down arrow, jumping to the form. 3px white border, white text with Dusk Legibility, dusk-veil fill, 14px radius, no lift. Same height and padding as the hero call button beside it.

### Hero Road (signature)
A full-bleed canvas behind the copy, decorative and hidden from assistive tech: the dusk sky and sun glow, two rows of pines, mown verge bands, a two-lane road bending right with a yellow left edge, white right edge and white dashes, reflector posts (white-reflector right, yellow-reflector left) and one green guide sign on the right shoulder. The sign reads I-95 NORTH / NEW JERSEY from April through August and I-95 SOUTH / FLORIDA the rest of the year.

### Sign Panel (the rate form)
Sign-green, Sign Mount, 30px 22px 28px padding (38px 36px from 760px, max 680px wide until 1024px). Holds the trip rows, When / Your car / Your name fields, the yellow "Text this to Ed" button and a soft-white note.

### Trip Rows (radio)
64px rows, 2px stroke-row border, 20px/800 sentence-case text led by a 22px radio ring. Selected: lane-yellow fill, lane-ink text, thick ring; color change only. Forced-colors mode adds a Highlight outline.

### Inputs / Fields
Sign-white fill and stroke, field-ink 19px text, 12px radius, 58px tall, sign-green caret; labels 20px/800, the "optional" hint 600 in ink-soft. Error: warning-peach stroke and an 18px/700 sentence in Ed's voice below.

### FAQ (always open)
On concrete: headline left, answers right from 1024px. Each 22px/800 question has its 19px concrete-soft answer directly beneath, separated by 2px rule-concrete lines. Nothing collapses.

### Header
No nav bar. The brand (shamrock sign tile plus two-line uppercase wordmark) links to top; the full phone number with a yellow phone icon sits top-right as a `tel:` link. It scrolls away with the hero.

### Footer (the close)
Night Verge ground, centered: 64px white shamrock, the close headline, the Ed line, one call button, the italic tagline, then fine print under a rule-footer hairline.

## Do's and Don'ts

### Do:
- **Do** keep the page still: draw the road once, redraw only on resize, transitions only on controls.
- **Do** keep the hero to the two-line uppercase headline, the promise, and two buttons: yellow call first, white outline second.
- **Do** put the rate form on the sign panel with the Sign Mount.
- **Do** use the 3px focus-sky outline for every hover and focus.
- **Do** keep controls 58px or taller, links 48px, answer choices as large rows, text at 17px or larger.
- **Do** show answers in full; a question and its answer sit together.

### Don't:
- **Don't** animate anything: no drive loop, moving road, parallax, scroll reveals or entrance effects.
- **Don't** use accordions, tabs, carousels or other hide-and-reveal patterns.
- **Don't** use black or neutral charcoal as any ground; the darkest is ground-deep.
- **Don't** add a sticky header or sticky call bar, or email links.
- **Don't** add a third hero action or a second yellow button in the hero.
- **Don't** put yellow fills on interface non-controls beyond the step discs.
- **Don't** place lane-yellow on concrete.
- **Don't** use hard offset shadows; depth is soft.
