---
name: Shamrock Transportation
description: One flat rate, posted like an interstate guide sign, for a one-man NJ to Florida driveaway service.
colors:
  ground: "#0c3a2a"
  ground-deep: "#082a1e"
  sign-green: "#0d6a43"
  sign-white: "#f7fbf8"
  ink-soft: "#cfe5d9"
  lane-yellow: "#f5c242"
  lane-ink: "#132a1f"
  concrete: "#e4e9e6"
  concrete-ink: "#0c3a2a"
  concrete-soft: "#33584a"
  focus-sky: "#8fd6ff"
  dusk-top: "#132849"
  dusk-mid: "#2c4770"
  road-asphalt: "#2e3740"
  road-shoulder: "#59626b"
  road-paint: "#eef1ed"
  field-ink: "#10261c"
  field-placeholder: "#6f897d"
  error-stroke: "#ffb199"
  error-text: "#ffd0c2"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(3rem, 14.5vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.94
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2rem, 8.4vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 900
    lineHeight: 1.08
    letterSpacing: "-0.01em"
  sign-line:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "23px"
    fontWeight: 800
    lineHeight: 1.3
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "0.04em"
  exit-tab:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: "0.06em"
rounded:
  tab: "9px 9px 0 0"
  row: "10px"
  field: "12px"
  button: "14px"
  sign: "16px"
  pill: "50%"
spacing:
  gutter-phone: "20px"
  gutter-desk: "40px"
  stack: "22px"
  section-phone: "60px"
  section-desk: "96px"
  column-gap: "56px"
  container: "1160px"
components:
  button-call:
    backgroundColor: "{colors.lane-yellow}"
    textColor: "{colors.lane-ink}"
    rounded: "{rounded.button}"
    padding: "14px 26px"
    height: "60px"
    typography: "{typography.label}"
  button-call-hero:
    backgroundColor: "{colors.lane-yellow}"
    textColor: "{colors.lane-ink}"
    rounded: "{rounded.button}"
    padding: "14px 30px"
    height: "76px"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.button}"
    padding: "14px 26px"
    height: "76px"
  sign-panel:
    backgroundColor: "{colors.sign-green}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.sign}"
    padding: "26px 22px"
  exit-tab:
    backgroundColor: "{colors.sign-green}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.tab}"
    padding: "5px 12px 6px"
    typography: "{typography.exit-tab}"
  route-row:
    textColor: "{colors.sign-white}"
    rounded: "{rounded.row}"
    padding: "18px 16px"
    height: "76px"
    typography: "{typography.sign-line}"
  chip:
    backgroundColor: "transparent"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.field}"
    padding: "10px 14px"
    height: "58px"
  chip-selected:
    backgroundColor: "{colors.lane-yellow}"
    textColor: "{colors.lane-ink}"
    rounded: "{rounded.field}"
  text-field:
    backgroundColor: "{colors.sign-white}"
    textColor: "{colors.field-ink}"
    rounded: "{rounded.field}"
    padding: "14px 16px"
    height: "58px"
---

# Design System: Shamrock Transportation

## Overview

**Creative North Star: "The Posted Rate on I-95"**

The whole page is the interstate at dusk. Information is posted the way a highway posts it: on guide-sign green panels with an inset white border, in heavy retroreflective-white uppercase, readable at 65 mph and therefore readable by a 60-plus reader on a phone. The road itself is the page's one unbroken line. It starts as a steerable first-person drive into a pine horizon in the hero, then returns between sections as top-down asphalt ribbons with a yellow left edge and white dashes, and runs as a live lane under the four exit-numbered steps.

Density is low and the type is big. Every section is one claim plus one proof, never a wall. The ground is deep roadside green, never black; light sections are highway concrete, so the page alternates green and concrete like driving from asphalt onto a bridge deck. Lane-line yellow is the one action color. A sky-blue outline is the one hover/focus voice.

Rejected by the build and the owner: stock truck photos, a quote-form wall, fine print, black grounds, webfonts, sticky bottom bars, email links.

**Key Characteristics:**
- Guide-sign panels (green, inset white rule, rounded 16px corners) carry every structured list: rates, steps, the form, the close.
- One yellow for action; one sky-blue outline for hover and focus.
- System font stack only, set heavy (800 to 900) and uppercase for headings.
- The road recurs as the connective tissue: hero canvas, section dividers, step lane.
- Phone-first, big targets (60px controls, 76px hero buttons and route rows), 17px text floor.

## Colors

A two-ground highway palette: deep roadside green and pale concrete, posted on sign green, with lane yellow as the single action color and a dusk sky reserved for the hero.

### Primary
- **Lane-Line Yellow** (lane-yellow): the call button, the selected chip, the "No surprises." half of the headline, the active route arrow, inline phone links on green, list dashes on green, text selection. It always sits on green or dusk, never on concrete.
- **Lane Ink** (lane-ink): text and icons on yellow.

### Secondary
- **Guide-Sign Green** (sign-green): every sign panel and exit tab, the brand tile, the list dashes on concrete.
- **Retroreflective White** (sign-white): primary text on green, the sign's inset border, the outlined button stroke, text-field fill.

### Tertiary
- **Dusk Navy to Dusk Blue** (dusk-top, dusk-mid): the hero sky only, fading through a mauve band into the Florida-peach glow at the horizon and the pine verge below. Not a section ground.
- **Road Asphalt, Shoulder, Paint** (road-asphalt, road-shoulder, road-paint): the drawn road wherever it appears (hero canvas, dividers, step lane). The left edge line is always lane-yellow; the right edge and center dashes are road-paint.

### Neutral
- **Roadside Green** (ground): page ground, html background, the dark half of every divider, the 2px separation ring on focus rings over concrete.
- **Night Verge** (ground-deep): footer only.
- **Soft Sign Ink** (ink-soft): secondary text on green (leads, step copy, notes).
- **Highway Concrete** (concrete): light sections (Pack it, FAQ).
- **Concrete Ink / Concrete Soft** (concrete-ink, concrete-soft): headings and body on concrete.
- **Field Ink / Placeholder** (field-ink, field-placeholder): text and placeholder inside white fields.
- **Warning Peach** (error-stroke, error-text): invalid field stroke and the error sentence beneath it, on green.

### Named Rules
**The Never-Black Rule.** The darkest surface is ground-deep. No section, card or overlay uses black or near-neutral charcoal as a ground.

**The One Yellow Rule.** Lane yellow marks the action and the promise. A yellow surface is always a control (call button, selected chip). Yellow text on green is either a link or the headline promise; plain instructions (like the note under the rate board) stay in soft white.

**The One Outline Rule.** Hover and focus on every control is a 3px focus-sky outline (offset 2-3px). On concrete sections it gains a 2px ground ring between control and outline so the pale blue still reads. No other hover color or glow.

## Typography

**Display Font:** System UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** Same stack
**Label Font:** Same stack

**Character:** One family, worked by weight and case like highway lettering: 900 uppercase for anything a driver would read off a sign, regular sentence case for Ed talking.

### Hierarchy
- **Display** (900, clamp(3rem, 14.5vw, 6rem), 0.94): the hero headline only, uppercase, two stacked lines, second line in lane yellow. Soft text-shadow over the sky.
- **Headline** (900, clamp(2rem, 8.4vw, 3.6rem), 1.02): section h2, uppercase, balanced wrap, usually held to about 14ch. Concrete sections may push it to a poster size (up to 5.4rem, 0.95) when the section is a single claim.
- **Title** (900, 24px, 1.08): h3 inside sign panels; uppercase.
- **Sign Line** (800, 23px phone / 27px desktop, 1.3): destinations on the rate board, set like guide-sign legends with an inline arrow.
- **Lead** (400, 20px, 1.55): the sentence under an h2, ink-soft, 34 to 38ch.
- **Body** (400, 18px, 1.55): running copy; FAQ answers capped at 60ch.
- **Label** (800, 17px, 0.04em, uppercase): form legends and field labels; also the weight and size of button sub-lines.
- **Exit Tab** (900, 15px, 0.06em, uppercase): the only text below 17px, and only inside an exit tab.

### Named Rules
**The 65 MPH Rule.** Nothing a reader must act on is under 17px or lighter than 700. Body is 18px; buttons are 20px/800.

**The No Webfont Rule.** The system stack is mandatory. Canvas lettering (the hero's overhead sign) reads the computed body font so drawn text matches the page.

## Layout

Phone-first single column at 20px gutters inside a 1160px container (40px gutters from 760px). Sections breathe at about 60px vertical padding on phones and 88 to 100px on desktop. At 760px, two-column sections split asymmetrically, claim on the left (5fr) and sign panel on the right (7fr), with a 56px gap; the Pack section reverses the weight (7fr / 5fr) with the manifest aligned to the bottom. The four steps go from a vertical stack with the road lane running down the left edge to a four-across row with the lane running beneath. Form fields stack at 22px and pair into two columns on desktop.

Section transitions between green and concrete are always a road divider (76px phone, 96px desktop) whose top and bottom halves match the neighbouring grounds. The hero fills the first screen (min 640px, up to 100svh, capped at 1000px); the copy sits on top and the road takes the lower part, with the horizon computed to stay below the buttons. Breakpoints: 760px (layout), 1100px (display size lock), and a short-landscape case (max-height 500px).

## Elevation & Depth

Mostly flat, with physical sign depth. Sign panels read as mounted metal: an inset 7px green margin, a 3px white rule, then a soft downward drop. The call button has a smaller soft drop. Shadows are diffuse and negative-spread, never hard offsets. Text over the dusk sky carries a soft dark text-shadow for legibility only.

### Shadow Vocabulary
- **Sign Mount** (`box-shadow: inset 0 0 0 7px #0d6a43, inset 0 0 0 10px #f7fbf8, 0 18px 40px -18px rgba(0,0,0,.6)`): every sign panel.
- **Button Lift** (`box-shadow: 0 8px 22px -8px rgba(0,0,0,.55)`): the yellow call button.
- **Sky Legibility** (`text-shadow: 0 2px 18px rgba(0,0,0,.28)`): hero headline and promise over the gradient.

### Named Rules
**The Mounted Sign Rule.** The only raised object is a sign panel (or the yellow button on it). Lists on the open ground stay flat and use rules or dashes, not cards.

## Shapes

Softly rounded, sign-like rectangles. Radii step down with size: sign panels 16px, buttons 14px, chips and fields 12px, route rows 10px, exit tabs 9px on the top corners only with no bottom border so they sit on the panel like a real exit tab. The route arrow sits in a 40px circle. List markers are short rounded bars (18-22px by 6px, 2px radius), lane-dash shaped, yellow on green and sign-green on concrete. Icons are inline stroked SVG at 2.4 to 2.6 stroke width with round caps.

## Components

### Buttons
Heavy, wide, unmistakable.
- **Shape:** gently rounded (14px), 3px border, 60px minimum height; 76px in the hero.
- **Primary (Call):** lane-yellow fill and border, lane-ink text, 20px/800, phone or SMS icon leading at 24px. The phone number rides as a 17px second line.
- **Secondary (Outline):** sign-white 3px stroke, white text, a faint dusk-navy tint (rgba(19,40,73,.22)) so it holds over the sky. Only in the hero, beside the call button.
- **Hover / Focus:** 3px focus-sky outline at 3px offset; press nudges down 1px and scales to 0.99 on cubic-bezier(.2,.8,.2,1).
- **Limit:** at most two buttons in the hero; the secondary is always the outline.

### Chips
- **Style:** two-column grid of radio labels, 58px tall, 2px white stroke at 70% opacity, 17px/800 text.
- **State:** selected fills lane-yellow with lane-ink text and pops once (scale 1.04 over .25s). Forced-colors mode gets a Highlight outline.

### Cards / Containers (Sign Panel)
- **Corner Style:** 16px.
- **Background:** sign-green.
- **Shadow Strategy:** Sign Mount (see Elevation).
- **Border:** the inset white rule from the shadow; no CSS border.
- **Internal Padding:** 26px 22px phone; up to 38px 36px (form) or 56px 48px (close) on desktop.

### Inputs / Fields
- **Style:** sign-white fill and 2px stroke, field-ink 19px text, 12px radius, 58px tall, sign-green caret.
- **Focus:** 3px focus-sky outline at 2px offset (also on hover with a mouse).
- **Error:** warning-peach stroke, and an 18px/700 error-text sentence in Ed's voice below the field.

### Navigation
No nav bar. The brand (shamrock in a guide-sign tile plus a two-line uppercase wordmark) sits top-left over the hero, absolutely positioned, scrolls away, and links back to top. No sticky header, no sticky bottom bar.

### Rate Board (signature)
A sign panel holding route rows split by 2px white rules at 22%. Each row is a full link (76px tall) with a sign-line destination, inline arrow between places, and a circled arrow on the right that fills yellow on hover or focus. When rates are confirmed, a yellow 19px/800 "$___ flat" line sits under each destination.

### Exit Tab
A small green tab with a white border on three sides, set above a sign panel's top edge, carrying a sequence number ("Exit 1" to "Exit 4"). It numbers steps on the route; it is not a section label.

### The Road (signature)
Canvas-drawn and steerable. Hero: first-person two-lane I-95 at dusk, overhead sign reading I-95 SOUTH / FLORIDA (or NORTH / NEW JERSEY in April to August), drag or pointer bends the road and grade, springing back (spring 38, damping 6.5) and resuming autopilot after 2.2s. Dividers: top-down asphalt ribbons whose control points bow away from the finger and spring back, dashes flowing at 70px/s. The step lane is a CSS-drawn lane with dashes advancing 46px per 1.4s. All animation ticks only while on screen, and prefers-reduced-motion freezes every road to a still frame.

## Do's and Don'ts

### Do:
- **Do** put every structured list (rates, steps, the estimate form, the closing card) on a sign panel with the Sign Mount treatment.
- **Do** keep one yellow action per view; the call button is yellow, with the phone number on its second line.
- **Do** use the 3px #8fd6ff outline for every hover and focus, adding the 2px ground ring on concrete.
- **Do** join a green section to a concrete section with a road divider whose halves match both grounds.
- **Do** keep controls at 58px or taller and interactive text at 17px/700 or heavier.
- **Do** honor prefers-reduced-motion by freezing the road, the lane and the chip pop.

### Don't:
- **Don't** use black or neutral charcoal as any ground; the darkest is ground-deep.
- **Don't** load a webfont; the system stack is the brand type.
- **Don't** add a sticky header or sticky bottom call bar.
- **Don't** put more than two contact buttons in the hero, or make the second anything but the outline.
- **Don't** add email links or mailto actions.
- **Don't** style non-clickable things as clickable: no yellow fills, circled arrows or bordered pills on anything that isn't a control.
- **Don't** use exit tabs as section eyebrows above headings; they only number steps on a sign panel.
- **Don't** place lane-yellow on concrete; on light sections the accent is sign-green.
- **Don't** use hard offset shadows; depth is the soft sign mount.
