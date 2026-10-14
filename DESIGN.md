---
name: Shamrock Transportation
description: A still interstate guide sign at dusk that says what Ed does, where, and how to call him.
colors:
  lane-yellow: "#f5c242"
  lane-ink: "#132a1f"
  focus-sky: "#8fd6ff"
  sign-green: "#0d6a43"
  sign-white: "#f7fbf8"
  dusk-top: "#132849"
  dusk-mid: "#2c4770"
  strip-paint: "#eef1ed"
  strip-asphalt: "#2e3740"
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
  rule-route: "rgba(247,251,248,.5)"
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
    route-max: "24px"
    close-min: "1.7rem"
    headline-min: "2rem"
    display-min: "2.3rem"
    close-max: "2.8rem"
    headline-max: "3rem"
    display-max: "3.6rem"
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2.3rem,10vw,3.6rem)"
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: "-0.02em"
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
  route:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(19px,5.4vw,24px)"
    fontWeight: 900
    lineHeight: 1.3
    letterSpacing: "0.03em"
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
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.5
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
    padding: "14px 34px"
    height: "76px"
    typography: "{typography.control}"
  text-link:
    textColor: "{colors.lane-yellow}"
    height: "48px"
    typography: "{typography.control}"
  header-call:
    textColor: "{colors.sign-white}"
    height: "48px"
    typography: "{typography.control}"
  hero-sign:
    backgroundColor: "{colors.sign-green}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.sign}"
    padding: "40px 52px 36px"
    width: "760px"
    typography: "{typography.display}"
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

**Creative North Star: "The Posted Sign on I-95"**

The page is the interstate at dusk, posted the way a highway posts things: one guide-sign green panel with an inset white rule, heavy retroreflective-white lettering, plain enough to read at 65 mph and therefore easy for a 40-to-70 reader on a phone. It is short, still and calm: a dusk hero with one sign, three numbered steps, a rate form on a second sign panel, five always-open answers on concrete, and a dark footer that carries the close.

Density is low and the type is big. The ground is deep roadside green, never black; the one light section is highway concrete. Lane-line yellow is the action color; a sky-blue outline is the one hover/focus voice. Nothing on the page moves.

Rejected by the build and the owner: stock truck photos, a quote-form wall, fine print, black grounds, webfonts, sticky bars, email links, accordions, animation, anything a reader has to figure out.

**Key Characteristics:**
- Two sign panels (green, inset white rule, 16px corners): the hero sign and the rate form.
- One yellow for action; one sky-blue outline for hover and focus.
- System font stack only, 800 to 900 for headings, sentence case everywhere except the route line and the wordmark.
- No animation, no canvas; only brief color and press transitions on controls.
- Phone-first, big targets (48px links, 58 to 76px controls), 17px text floor.

## Colors

A two-ground highway palette: roadside green and pale concrete, sign-green panels, lane yellow for action, and a dusk sky kept inside the hero.

### Primary
- **Lane-Line Yellow** (lane-yellow): call buttons, the selected trip row, the hero's "or text me for a rate" link, the "Call 732-300-3835" link beside the form, the route-line arrow, the header phone icon, the step-number discs, the highway strip's edge line, text selection. Never on concrete.
- **Lane Ink** (lane-ink): text and icons on yellow.
- **Focus Sky** (focus-sky): the hover and focus outline, nothing else.

### Secondary
- **Guide-Sign Green** (sign-green): both sign panels and their 7px inset margin, the brand tile, the input caret.
- **Retroreflective White** (sign-white): primary text on green and dusk, the signs' inset rule, text-field fill, footer headline and Ed line. At reduced alpha it is the route line's rule (rule-route), the unselected trip-row stroke (stroke-row) and the footer hairline (rule-footer).

### Tertiary (hero only)
- **Dusk** (dusk-top, dusk-mid): the hero's still vertical gradient, navy at the top to dusk blue at 55%, landing on the ground green at the bottom edge.
- **Highway strip** (strip-asphalt, strip-paint, lane-yellow): a 22px still strip along the hero's bottom edge: yellow top edge, asphalt band, white bottom edge, 34px white dashes every 80px down the middle.

### Neutral
- **Roadside Green** (ground): page ground and the end of the hero gradient.
- **Night Verge** (ground-deep): footer; at 55% it tints the "Messages didn't open?" box (tint-sent).
- **Soft Sign Ink** (ink-soft): secondary text on green (lead, step lines, notes, optional-field hint, footer).
- **Highway Concrete** (concrete) with **Concrete Ink / Soft** (concrete-ink, concrete-soft): the FAQ section; rule-concrete divides answers.
- **Field Ink / Placeholder** (field-ink, field-placeholder): inside white fields.
- **Warning Peach** (error-stroke, error-text): invalid stroke and the error sentence beneath it, on green.

### Named Rules
**The Never-Black Rule.** The darkest surface is ground-deep. Black appears only inside soft shadows, never as a ground.

**The One Yellow Rule.** Lane yellow marks action. A yellow rectangle is always a control (call button, selected trip row); the only non-control yellow fills are the round step-number discs and the painted edge line of the highway strip. Yellow on green is a link, the route arrow, or a step number; headlines, instructions and body copy stay white or soft white.

**The One Outline Rule.** Hover and focus on every control is a 3px focus-sky outline (offset 2 to 3px; 6px radius on text links). No other hover color, fill change or glow.

## Typography

**Display Font:** System UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** Same stack

**Character:** One family worked by weight like highway lettering: 900 for what a driver reads off a sign, 800 for anything the reader taps or answers, 400 for Ed talking.

### Hierarchy
- **Display** (900, 1.1, sentence case): the hero h1 only, "I'll drive your car. You fly.", inside the hero sign.
- **Route** (900, 1.3, uppercase, 0.03em): "New Jersey ⇄ Florida" under the h1, set off by a 2px rule-route line, with a 30px yellow two-way arrow between the places.
- **Headline** (900, 1.1, sentence case): section h2, held to about 14ch on the form. The footer's "You fly. I'll drive." uses **Headline Close**.
- **Title** (800, 22px, 1.3): step titles, FAQ questions, the "Rather talk?" line; the step-number digit is the same size at 900.
- **Lead** (400, 20px; 22px from 760px for the hero promise): the hero promise in white, the sentence under an h2 in ink-soft.
- **Control** (800, 20px): button text, the hero text link, form legends, labels and trip rows. The header phone link is 800 at 18px (17px under 430px, 22px from 760px).
- **Answer** (400, 19px): FAQ answers (60ch), step lines, the footer Ed line, field text.
- **Body** (400, 18px, 1.55): running copy, notes, error sentences (700).
- **Small** (17px): the number on a button's second line (700), footer text.
- **Brand** (900, 17px, uppercase two-line wordmark; 20px from 760px). Under 430px wide it drops to 14px with no tracking so the full header number fits; this is the page's one recorded exception to the text floor, not a size for anything else. Under 340px the words go visually hidden and the tile remains.

### Named Rules
**The 65 MPH Rule.** No text is under 17px (the narrow-phone wordmark is the single recorded exception), and nothing a reader acts on is lighter than 700.

**The No Webfont Rule.** The system stack is mandatory.

## Layout

Phone-first single column, 20px gutters in a 1160px container (40px from 760px; 14px in the header under 430px). Sections run 56 to 64px vertical padding on phones and 88px on desktop.

The hero is a still, padded block (104px top / 76px bottom on phones, 140 / 104px from 760px, 88px top in short landscape), not a full-screen stage. On phones everything is left-aligned: sign (26px side padding), promise, then a full-width 76px Call Ed button with the text link beneath. From 760px the hero centers: sign up to 760px wide (40px 52px 36px padding), route line centered, promise on one line at 22px, the button and link side by side with a 32px gap.

The header is absolutely placed over the hero, not sticky: brand top-left, full phone number top-right, 72px tall (88px from 760px). How it works is a 48px number column beside title and line, stacked at 22px on phones and three across with 32px gaps from 760px. From 760px the form and FAQ split 5fr / 7fr with a 56px gap; trip rows pair into two columns and When / Your car share a row. The footer is centered and narrow with one call button (max 420px). Breakpoints: 760px; max-width 429px, 379px (header phone icon hides) and 339px; max-height 500px landscape.

## Elevation & Depth

Flat, with mounted signs. Each sign panel reads as mounted metal: a 7px green inset margin, a 3px white rule, then a soft downward drop. Call buttons carry a smaller soft drop. The header phone number carries a soft dark text-shadow for legibility over the dusk. Shadows are diffuse with negative spread, never hard offsets.

### Shadow Vocabulary
- **Sign Mount** (`box-shadow: inset 0 0 0 7px #0d6a43, inset 0 0 0 10px #f7fbf8, 0 18px 40px -18px rgba(0,0,0,.6)`): both sign panels.
- **Button Lift** (`box-shadow: 0 8px 22px -8px rgba(0,0,0,.55)`): yellow call buttons.
- **Dusk Legibility** (`text-shadow: 0 1px 8px rgba(0,0,0,.45)`): the header phone link.

### Named Rules
**The Mounted Sign Rule.** The only raised surfaces are sign panels and the yellow button. Steps, FAQ answers and footer content stay flat, divided by space or rules, never cards.

**The Still Page Rule.** Nothing animates: no canvas, no scroll effects, no entrance motion. The only transitions are on controls: button press (translateY 1px, scale .99 over .2s cubic-bezier(.2,.8,.2,1)), outline color (.15s) and trip-row color change (.15s). The in-page jump to the form scrolls smoothly; under prefers-reduced-motion it jumps and the transitions are off.

## Shapes

Softly rounded, sign-like rectangles stepping down with size: sign panels 16px, buttons 14px, trip rows, fields and the sent box 12px, text-link focus outlines 6px. Circles are reserved for the 48px step-number discs and each trip row's 22px radio ring (stroke thickens to 7px when selected). Icons are inline stroked SVG (2.4 to 2.6 stroke, round caps): 24px in buttons, 30px route arrow, 22px on the text link, 20px in the header. The shamrock sits in a 44 to 52px rounded sign tile in the header and stands alone at 64px in the footer.

## Components

### Call Button
Heavy, wide, unmistakable. Lane-yellow fill and 3px border, lane-ink text, 14px radius, Button Lift, a leading 24px phone or SMS icon, the number as a second 17px line. 60px tall; 76px and full-width on phones in the hero. Appears in the hero, as "Text this to Ed" on the form, and in the footer. It is the only button style on the page.

### Text Link
Yellow 20px/800 text with a 2px underline and a trailing down-arrow icon, 48px tall: "or text me for a rate", jumping to the form. Beside the form, "Call 732-300-3835" is the same yellow without the underline.

### Hero Sign
Sign-green panel with the Sign Mount: the display h1, then the uppercase route line under a 2px rule-route line. The promise and actions sit below the sign on the dusk, not inside it.

### How It Works
Three static numbered steps: a 48px lane-yellow disc with a 22px/900 digit, a 22px step title, a 19px ink-soft line. No cards, no icons.

### Sign Panel (the rate form)
Sign-green, Sign Mount, 30px 22px 28px padding (38px 36px from 760px). Holds the trip rows, When / Your car / Your name fields, the yellow "Text this to Ed" button and a soft-white note.

### Trip Rows (radio)
64px rows with a 2px stroke-row border and 20px/800 sentence-case text led by a 22px radio ring. Selected: lane-yellow fill, lane-ink text, thick ring; color change only, no pop. Forced-colors mode adds a Highlight outline.

### Inputs / Fields
Sign-white fill and stroke, field-ink 19px text, 12px radius, 58px tall, sign-green caret; labels 20px/800 sentence case, the "optional" hint 600 in ink-soft. Hover and focus follow the One Outline Rule at 2px offset. Error: warning-peach stroke and an 18px/700 sentence in Ed's voice below.

### FAQ (always open)
On concrete: headline left, Q&A right from 760px. Each 22px/800 question has its 19px concrete-soft answer directly beneath, separated by 2px rule-concrete lines. Nothing collapses.

### Header
No nav bar. The brand (shamrock sign tile plus a two-line uppercase wordmark) links back to top; the full phone number with a yellow phone icon sits top-right as a `tel:` link. It scrolls away with the hero.

### Footer (the close)
Night Verge ground, centered: 64px white shamrock, the close headline, the Ed line in white, one call button, the italic tagline, then fine print under a rule-footer hairline.

## Do's and Don'ts

### Do:
- **Do** keep the page still; transitions only on controls, only color and press.
- **Do** put the headline and the rate form on sign panels with the Sign Mount.
- **Do** use the 3px focus-sky outline for every hover and focus.
- **Do** keep controls 58px or taller, links 48px, answer choices as large rows, and text at 17px or larger.
- **Do** show answers in full; a question and its answer sit together.
- **Do** center the hero from 760px and left-align it on phones.

### Don't:
- **Don't** animate anything: no canvas, moving road, parallax, scroll reveals or entrance effects.
- **Don't** use accordions, tabs, carousels or other hide-and-reveal patterns.
- **Don't** use black or neutral charcoal as any ground; the darkest is ground-deep.
- **Don't** load a webfont; the system stack is the brand type.
- **Don't** add a sticky header or sticky call bar, or email links.
- **Don't** put more than one button in the hero; the second path is a yellow text link, never a second button.
- **Don't** put yellow fills on non-controls beyond the round step-number discs and the strip's edge line, or yellow text on green beyond links, the route arrow and step numbers.
- **Don't** place lane-yellow on concrete.
- **Don't** use hard offset shadows; depth is the soft sign mount.
