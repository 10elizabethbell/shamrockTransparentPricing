---
name: Shamrock Transportation
description: One flat rate, posted like an interstate guide sign, for a one-man NJ to Florida driveaway service.
colors:
  ground: "#0c3a2a"
  ground-deep: "#082a1e"
  sign-green: "#0d6a43"
  sign-deep: "#0a5637"
  sign-white: "#f7fbf8"
  ink-soft: "#cfe5d9"
  lane-yellow: "#f5c242"
  lane-ink: "#132a1f"
  concrete: "#e4e9e6"
  concrete-ink: "#0c3a2a"
  concrete-soft: "#33584a"
  focus-sky: "#8fd6ff"
  field-ink: "#10261c"
  field-placeholder: "#6f897d"
  error-stroke: "#ffb199"
  error-text: "#ffd0c2"
  dusk-top: "#132849"
  dusk-mid: "#2c4770"
  dusk-mauve: "#5d4f63"
  dusk-mauve-canvas: "#8d6c72"
  dusk-glow: "#e99f63"
  horizon-peach: "#eaa064"
  sun-glow: "rgba(255,190,120,.6)"
  sun-glow-clear: "rgba(255,190,120,0)"
  pine-verge: "#284638"
  pine-verge-deep: "#1a3d2c"
  treeline-far: "#2f4a5c"
  treeline-near: "#1d3445"
  asphalt: "#2b333c"
  road-asphalt: "#2e363f"
  road-shoulder: "#545a60"
  road-paint: "#f0f2ee"
  ground-fade: "rgba(12,58,42,0)"
  rule-concrete: "rgba(12,58,42,.18)"
  rule-footer: "rgba(247,251,248,.15)"
  stroke-row: "rgba(247,251,248,.7)"
  tint-outline: "rgba(19,40,73,.22)"
  tint-sent: "rgba(8,42,30,.55)"
  shade-28: "rgba(0,0,0,.28)"
  shade-40: "rgba(0,0,0,.4)"
  shade-45: "rgba(0,0,0,.45)"
  shade-55: "rgba(0,0,0,.55)"
  shade-60: "rgba(0,0,0,.6)"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(3rem,14.5vw,6rem)"
    fontWeight: 900
    lineHeight: 0.94
    letterSpacing: "-0.025em"
  display-desk:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(4.4rem,8.4vw,6rem)"
    fontWeight: 900
    lineHeight: 0.94
    letterSpacing: "-0.025em"
  display-wide:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "6rem"
    fontWeight: 900
    lineHeight: 0.94
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2rem,8.4vw,3.6rem)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  headline-close:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.7rem,7.6vw,2.8rem)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(19px,5.2vw,20px)"
    fontWeight: 400
    lineHeight: 1.4
  call-line:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 800
    lineHeight: 1.55
  question:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 800
    lineHeight: 1.3
  control:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 800
    lineHeight: 1.15
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.55
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
  button-outline:
    backgroundColor: "{colors.tint-outline}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.button}"
    padding: "14px 30px"
    height: "76px"
    typography: "{typography.control}"
  sign-panel:
    backgroundColor: "{colors.sign-green}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.sign}"
    padding: "30px 22px 28px"
  trip-row:
    backgroundColor: "transparent"
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
    typography: "{typography.question}"
  footer-close:
    backgroundColor: "{colors.ground-deep}"
    textColor: "{colors.ink-soft}"
    padding: "56px 0 44px"
    typography: "{typography.small}"
---

# Design System: Shamrock Transportation

## Overview

**Creative North Star: "The Posted Rate on I-95"**

The page is the interstate at dusk, posted the way a highway posts things: a guide-sign green panel with an inset white rule, heavy retroreflective-white uppercase, readable at 65 mph and therefore readable by a 40-to-70 reader on a phone. It is short and calm on purpose: a hero with a self-driving road, one rate form on a sign panel, four always-open answers on concrete, and a dark footer that carries the close.

Density is low and the type is big. The ground is deep roadside green, never black; the one light section is highway concrete. Lane-line yellow is the one action color; a sky-blue outline is the one hover/focus voice. The hero road is the only thing on the page that moves.

Rejected by the build and the owner: stock truck photos, a quote-form wall, fine print, black grounds, webfonts, sticky bars, email links, accordions, anything a reader has to figure out.

**Key Characteristics:**
- One sign panel (green, inset white rule, 16px corners) holds the rate form.
- One yellow for action; one sky-blue outline for hover and focus.
- System font stack only, 800 to 900 and uppercase for headings; questions and controls in sentence case.
- One moving element: the hero road, driving itself slowly with gentle bends.
- Phone-first, big targets (58 to 76px controls), 17px text floor.

## Colors

A two-ground highway palette: roadside green and pale concrete, a sign-green panel, lane yellow as the single action color, and a dusk sky kept inside the hero.

### Primary
- **Lane-Line Yellow** (lane-yellow): call buttons, the selected trip row, "No surprises." in the headline, the "Call 732-300-3835" link beside the form, text selection. Never on concrete.
- **Lane Ink** (lane-ink): text and icons on yellow.

### Secondary
- **Guide-Sign Green** (sign-green): the form's sign panel and its 7px inset margin, the brand tile, the input caret.
- **Retroreflective White** (sign-white): primary text on green, the sign's inset rule, the outline button stroke, text-field fill, footer headline and Ed line.

### Tertiary (hero only)
- **Dusk sky** (dusk-top, dusk-mid, dusk-mauve, pine-verge, pine-verge-deep): the hero's CSS gradient behind the canvas, navy through a mauve band to the pine verge.
- **Canvas scene** (dusk-mauve-canvas, horizon-peach, sun-glow, treeline-far, treeline-near): the drawn sky, setting-sun glow and two treeline rows.
- **Road** (road-asphalt, road-shoulder, road-paint): the drawn two-lane road. The left edge line is lane-yellow; the right edge and center dashes are road-paint. The overhead sign is sign-green with a sign-white border.

### Neutral
- **Roadside Green** (ground): page and html ground; the hero's bottom fade runs from ground-fade into it.
- **Night Verge** (ground-deep): footer only.
- **Soft Sign Ink** (ink-soft): secondary text on green (lead, notes, optional-field hint, footer fine print).
- **Highway Concrete** (concrete) with **Concrete Ink / Soft** (concrete-ink, concrete-soft): the FAQ section, its questions and answers; rule-concrete divides the answers.
- **Field Ink / Placeholder** (field-ink, field-placeholder): inside white fields.
- **Warning Peach** (error-stroke, error-text): invalid stroke and the error sentence beneath, on green.
- **Strokes and tints** (stroke-row, rule-footer, tint-outline, tint-sent): unselected trip-row stroke, footer fine-print rule, outline-button wash over the sky, the "Messages didn't open?" box.
- **Shades** (shade-28 to shade-60): text-shadow and drop-shadow blacks only, never a surface.
- sign-deep, asphalt and dusk-glow are declared in `:root` but not referenced by any rule; the canvas draws its own road and glow values.

### Named Rules
**The Never-Black Rule.** The darkest surface is ground-deep. Black appears only inside soft shadows, never as a ground.

**The One Yellow Rule.** Lane yellow marks the action and the promise. A yellow surface is always a control (call button, selected trip row). Yellow text on green is either a link or the headline promise; plain instructions stay in white or soft white.

**The One Outline Rule.** Hover and focus on every control is a 3px focus-sky outline (offset 2 to 3px; 6px radius on text links). No other hover color, fill change or glow.

## Typography

**Display Font:** System UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** Same stack

**Character:** One family, worked by weight and case like highway lettering: 900 uppercase for what a driver reads off a sign, sentence case for Ed talking and for anything the reader answers or taps.

### Hierarchy
- **Display** (900, 0.94): the hero h1 only, two stacked uppercase lines, second in lane yellow. Phone clamp, desktop clamp from 760px, locked at 6rem from 1100px.
- **Headline** (900, 1.02, uppercase): section h2, held to about 14ch on the form. The footer's "You fly. I'll drive." uses the smaller close size.
- **Promise** (400, 1.4): the hero sentence under the h1, white with a soft shadow.
- **Question / Call Line** (800, 22px; 1.3 and 1.55): FAQ questions in sentence case; the "Rather talk?" line beside the form.
- **Control** (800, 20px): button text, form legends and labels, trip rows.
- **Lead** (400, 20px): the sentence under an h2, ink-soft, 36ch.
- **Answer** (400, 19px): FAQ answers (60ch), the footer Ed line, field text.
- **Body** (400, 18px, 1.55): running copy, notes, error sentences (700).
- **Small** (17px): the phone number on a button's second line (700), footer text; **Brand** (900, 17px, 20px from 760px, uppercase): the wordmark.

### Named Rules
**The 65 MPH Rule.** No text on the page is under 17px, and nothing a reader acts on is lighter than 700.

**The No Webfont Rule.** The system stack is mandatory. The canvas sign lettering reads the computed body font so drawn text matches the page.

## Layout

Phone-first single column, 20px gutters in a 1160px container (40px gutters from 760px). Sections sit at 60 to 64px vertical padding on phones and 88 to 96px on desktop. From 760px the form and FAQ sections split 5fr / 7fr (claim left, content right) with a 56px gap; the hero buttons sit side by side; the trip rows stay single column at every width; When and Your car pair into two columns. Form fields stack at 22px.

The hero fills the first screen (min 640px, up to 100svh, capped at 1000px; 560px in short landscape): copy on top, the canvas road behind and below, fading into the ground over its last 56px. The footer is centered and narrow: shamrock mark, close headline, Ed line, one call button (max 420px), italic tagline, then fine print under a hairline. Breakpoints: 760px, 1100px, max-height 500px landscape.

## Elevation & Depth

Flat, with one mounted sign. The form panel reads as mounted metal: a 7px green inset margin, a 3px white rule, then a soft downward drop. Call buttons carry a smaller soft drop. Text over the dusk sky carries soft dark text-shadows for legibility only. Shadows are diffuse with negative spread, never hard offsets.

### Shadow Vocabulary
- **Sign Mount** (`box-shadow: inset 0 0 0 7px #0d6a43, inset 0 0 0 10px #f7fbf8, 0 18px 40px -18px rgba(0,0,0,.6)`): the sign panel.
- **Button Lift** (`box-shadow: 0 8px 22px -8px rgba(0,0,0,.55)`): yellow call buttons.
- **Sky Legibility** (`text-shadow: 0 2px 18px rgba(0,0,0,.28)` headline; `0 1px 10px rgba(0,0,0,.4)` promise; `0 1px 8px rgba(0,0,0,.45)` outline button): hero text only.

### Named Rules
**The Mounted Sign Rule.** The only raised surface is a sign panel (and the yellow button). FAQ answers and footer content stay flat, divided by rules, not cards.

## Shapes

Softly rounded, sign-like rectangles stepping down with size: sign panel 16px, buttons 14px, trip rows, fields and the sent box 12px, text-link focus outlines 6px. The only circle is the radio dot in each trip row (22px ring; the stroke thickens to 7px when selected). Icons are inline stroked SVG (2.4 to 2.6 stroke, round caps) at 24px in buttons; the shamrock mark is 44 to 52px in the brand tile and 64px in the footer.

## Components

### Buttons
Heavy, wide, unmistakable.
- **Shape:** 14px radius, 3px border, 60px minimum height; 76px in the hero.
- **Call (primary):** lane-yellow fill and border, lane-ink text, leading 24px phone or SMS icon; the number rides as a second line. Appears in the hero, as "Text this to Ed" on the form, and in the footer.
- **Outline (secondary):** 3px sign-white stroke over a faint dusk wash; hero only, beside the call button.
- **Hover / Focus:** The One Outline Rule at 3px offset. Press nudges down 1px and scales to 0.99 over .2s cubic-bezier(.2,.8,.2,1).

### Trip Rows (radio)
- **Style:** full-width single-column rows inside the sign panel, 64px tall, 2px stroke-row border, 20px/800 sentence-case text led by a 22px radio ring.
- **Selected:** lane-yellow fill, lane-ink text, solid-looking dot. Color change only (.15s), no pop. Forced-colors mode gets a Highlight outline.

### Sign Panel (the rate form)
16px corners, sign-green, Sign Mount, 30px 22px 28px padding (38px 36px from 760px). Holds the trip rows, When / Your car / Your name fields, the yellow "Text this to Ed" button and a soft-white note.

### Inputs / Fields
- **Style:** sign-white fill and 2px stroke, field-ink 19px text, 12px radius, 58px tall, sign-green caret; labels are 20px/800 sentence case, the "optional" hint 600 in ink-soft.
- **Focus / Hover:** The One Outline Rule at 2px offset.
- **Error:** warning-peach stroke and a 18px/700 sentence in Ed's voice below.

### FAQ (always open)
On concrete: uppercase headline left, Q&A list right. Each item is a 22px/800 sentence-case question with its 19px concrete-soft answer directly beneath, separated by 2px rule-concrete lines. Nothing collapses; nothing is clickable.

### Footer (the close)
Night Verge ground, centered: 64px white shamrock, "You fly. I'll drive." in the close headline size, the Ed line in white, one call button, the card tagline in italic, then fine print in ink-soft.

### Navigation
No nav bar. The brand (shamrock in a guide-sign tile plus a two-line uppercase wordmark) sits top-left over the hero, scrolls away, and links back to top.

### The Road (signature)
A canvas first-person two-lane I-95 at dusk, the only moving element. It drives itself at an easy pace (8 units/s) along slow, layered, gentle bends (max 0.7), flat with no hills, under an overhead sign reading I-95 SOUTH / FLORIDA (I-95 NORTH / NEW JERSEY April to August). It ignores touch and pointer, ticks only while the hero is on screen, and shows one still frame under prefers-reduced-motion.

## Do's and Don'ts

### Do:
- **Do** keep the hero road as the page's only moving element; everything else is still apart from short color and press transitions.
- **Do** put the rate form on a sign panel with the Sign Mount treatment.
- **Do** use the 3px #8fd6ff outline for every hover and focus.
- **Do** keep controls 58px or taller, answer choices as large single-column rows, and all text at 17px or larger.
- **Do** show answers in full; a question and its answer sit together on the page.
- **Do** keep yellow text on green to links and the headline promise.

### Don't:
- **Don't** make the road (or anything) react to touch, drag or pointer, and don't add a second animation.
- **Don't** use accordions, tabs, carousels or other hide-and-reveal patterns.
- **Don't** use black or neutral charcoal as any ground; the darkest is ground-deep.
- **Don't** load a webfont; the system stack is the brand type.
- **Don't** add a sticky header or sticky bottom call bar, or email links.
- **Don't** put more than two buttons in the hero, or make the second anything but the outline.
- **Don't** style non-clickable things as clickable: no yellow fills or bordered rows on anything that isn't a control.
- **Don't** place lane-yellow on concrete.
- **Don't** use hard offset shadows; depth is the soft sign mount.
