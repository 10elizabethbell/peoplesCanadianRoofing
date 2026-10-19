---
name: People's Canadian Roofing
description: A one-page site for a Windsor roofer, set in a fall storm at dusk; the live shingle roof is the hero.
colors:
  sky-0: "#0c1a33"
  sky-1: "#172b50"
  sky-2: "#29436e"
  navy: "#13254a"
  navy-deep: "#0d1b38"
  paper: "#f4f5f7"
  ink: "#13213d"
  ink-2: "#46526b"
  red: "#d52b1e"
  red-deep: "#b0211a"
  gold: "#f4bf1a"
  gold-2: "#ffd44f"
  cream: "#f5f1e8"
  cream-2: "#c9d2e3"
typography:
  display:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(44px, 12.4vw, 96px)"
    fontWeight: 900
    lineHeight: 0.93
    letterSpacing: "-0.015em"
  headline:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(34px, 9vw, 60px)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.01em"
  title:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(21px, 5.6vw, 28px)"
    fontWeight: 850
    lineHeight: 1.15
  lead:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(20px, 5.2vw, 26px)"
    fontWeight: 650
    lineHeight: 1.35
  body:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 800
    lineHeight: 1.15
  small:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.55
rounded:
  control: "10px"
  focus: "6px"
  round: "50%"
spacing:
  gutter-phone: "16px"
  gutter-desktop: "32px"
  stack-sm: "12px"
  stack-md: "20px"
  column-gap: "72px"
  section: "76px"
  section-lg: "96px"
  container: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 24px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.gold-2}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 24px"
    height: "56px"
  button-ghost-hover:
    textColor: "{colors.gold}"
  input:
    backgroundColor: "#ffffff"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "13px 14px"
    height: "54px"
  chip:
    backgroundColor: "#ffffff"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0 18px"
    height: "50px"
  chip-selected:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.cream}"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    height: "76px"
  service-row-arrow:
    textColor: "{colors.ink}"
    rounded: "{rounded.round}"
    size: "46px"
  service-row-arrow-hover:
    backgroundColor: "{colors.red}"
    textColor: "#ffffff"
---

# Design System: People's Canadian Roofing

## Overview

**Creative North Star: "Fall Storm Over Essex County"**

Navy storm sky at dusk, an old mossy roof getting rained on, maple leaves blowing across it, a white aluminum eavestrough dripping at the edge. The visitor drags a finger across the roof and new shingles go down. The page is the flyer's palette (flag red, flyer gold, deep navy, flag-white paper) moved outdoors into the weather the business protects people from. It doesn't use stock house photos, blue quote banners or an icon-card services grid.

Type is heavy, uppercase and in the system stack, like a hand-set flyer: big, plain, confident. Away from the hero, the page settles into flat bands of colour (paper, navy, paper, red, deep navy). Rooflines and gutters are painted on canvas and join the bands, so the whole page reads as one house from ridge to eave. The density is low: one idea per band, large tap targets, and nothing a homeowner on a phone has to work for.

Motion belongs to the world and never to the interface. Rain, leaves, drips and the re-shingling roof all run on canvas. They stay out of the words, and they come to rest as a finished still frame when the visitor asks for less motion.

**Key Characteristics:**
- Navy storm-sky hero with a live, painted shingle roof filling the bottom of the first screen
- Uppercase 900-weight system type for display and section heads
- Flat colour bands below the hero, joined by painted eavestroughs
- Gold is the one action colour; red is the flag, the leaf and the hover/focus signal
- Maple leaf is the only mark and the only list bullet

## Colors

The flyer's flag palette under a storm sky: a navy ramp carries the weather, paper carries the reading, gold marks the action, and red marks the country and the touch.

### Primary
- **Flyer Gold** (gold): Primary buttons, the gold word in the hero headline, step numerals, the bars either side of ROOFING in the wordmark, the phone icon, the keyboard focus ring and text selection. Gold means "do this".
- **Bright Flyer Gold** (gold-2): Hover state of gold buttons only.

### Secondary
- **Canadian Flag Red** (red): The maple-leaf mark, list bullets, the arrow fill on service-row hover, hover/focus outlines on form controls, and the full-bleed closing band behind the big phone number.
- **Deep Flag Red** (red-deep): Form error text and invalid-field borders. Error copy needs the darker red to stay legible on paper.

### Neutral
- **Storm Sky Ramp** (sky-0, sky-1, sky-2): The hero's vertical gradient, darkest at the top, lightening toward the ridge. sky-0 is also the browser theme colour.
- **Flyer Navy** (navy): The "How it works" band and the selected chip.
- **Night Navy** (navy-deep): Footer ground.
- **Flag-White Paper** (paper): Cool, slightly blue-grey page ground for every reading band. Not warm cream, and never black.
- **Storm Ink** (ink): All text on paper, and text on gold buttons.
- **Slate Ink** (ink-2): Secondary text on paper (town list, form notes, "(optional)").
- **Lamplight Cream** (cream): Primary text and ghost-button stroke on navy.
- **Overcast Blue-Grey** (cream-2): Secondary text on navy (promise line, step copy, hint, footer).

### Named Rules
**The Gold Means Go Rule.** Gold is for the action and nothing else: buttons, the focus ring, and a single emphasised word in the hero. If gold is decorating rather than pointing, it doesn't belong there.

**The Flag Ground Rule.** The page ground is paper, navy or red, never black. Dark surfaces are always navy from the sky ramp.

## Typography

**Display Font:** system-ui (with -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif)
**Body Font:** the same system stack

**Character:** A single native sans in two voices. Display and section heads are 900-weight uppercase with slightly tight tracking, as loud as a printed flyer. Body copy is plain 17px sentence case at a relaxed 1.55 line height.

### Hierarchy
- **Display** (900, clamp(44px, 12.4vw, 96px), 0.93, uppercase): The hero headline only. One word may switch to gold.
- **Headline** (900, clamp(34px, 9vw, 60px), 1, uppercase): One per section head, balanced wrapping.
- **Title** (850, clamp(21px, 5.6vw, 28px), 1.15): Service rows. Step titles use 900 at 22px.
- **Lead** (650, clamp(20px, 5.2vw, 26px), 1.35, max 24 to 26ch): The single statement paragraph in a band (care line, service area).
- **Body** (400, 17px, 1.55, max 34 to 46ch): The promise, step copy and town list. The promise line sits at clamp(17px, 4.6vw, 20px) and is coloured cream-2.
- **Label** (800, 16px): Form labels, legends, button text (17px), header phone number, fact list (18px).
- **Small** (15px): Footer, form note and error text.

### Named Rules
**The House Stack Rule.** Use only the system font stack. No web fonts are loaded and none should be added.

**The Shout Only At Heads Rule.** Uppercase is reserved for the display line, section heads and the wordmark. Everything a visitor reads at length stays in sentence case.

**The Tabular Phone Rule.** Every rendering of the phone number uses tabular numerals.

## Layout

Single column on phones with a 16px gutter. At 760px the gutter becomes 32px. Content sits in a centred container of up to 1180px. Section bands run full-bleed, with vertical padding of 72 to 96px.

- **Hero (first screen).** The wordmark is top-left and the phone number top-right. Below them sit the display line, promise, actions and drag hint. The live roof fills the rest of the screen down to a dripping eavestrough (phone: clamp(190px, 32svh, 280px); desktop: at least 34 to 36vh, with the hero capped at min(100svh, 1040px)).
- **Actions.** On phones the buttons stack full width with a 12px gap. From 760px they sit in a row, each at least 250px wide.
- **From 1024px.** Services and estimate become two columns (1.1fr / 0.9fr and 1fr / 1fr) with a 72px gap. Steps become three columns from 760px.
- **Rhythm.** Form stacks use a 20px gap, field stacks 7px, and lists 12 to 14px. Measure is capped in ch on every text block.

### Named Rules
**The One Phone Up Top Rule.** On the first screen, the phone number appears once, top-right in the header. The next large phone number is the closing red band.

**The Two Buttons Rule.** The hero carries at most two buttons: gold primary and outlined ghost.

**The No Sticky Bar Rule.** There is no sticky or fixed bottom bar. Calling is already one tap away in the header, and the bottom of the phone screen belongs to the roof.

## Elevation & Depth

The interface is flat. Depth lives in the painted world: shingle courses with granule noise, shaded butt edges, curled corners, a gradient sky with cloud masses, and the eavestrough's metal gradient. The UI has exactly one shadow, under the hero's gold button, to lift it off the moving roof and sky. The same button inside the form drops it.

### Shadow Vocabulary
- **Sky lift** (`box-shadow: 0 6px 18px rgba(5,10,22,.28)`): Gold primary button over the hero canvas only.

### Named Rules
**The Paint Not Plastic Rule.** Depth comes from the painted roof, sky and gutter, not from UI shadows. Cards don't float, and shadows don't appear in the paper bands.

## Shapes

Controls are softly rounded at 10px (buttons, inputs, chips). The service-row arrow is the only circle (46px). The focus ring follows a 6px radius. Section bands are square, full-bleed rectangles, and their edges become rooflines: an eavestrough (16px, or 64px with two shingle courses above it) sits between the hero and services and between "How it works" and the estimate. The maple leaf is the one organic silhouette, used as mark, bullet and closing emblem. Hairlines are 1px ink at 16% opacity. Control strokes are 2px ink at 24% opacity.

## Components

### Buttons
Big and plain. Easy to hit with a thumb in a Facebook in-app browser.
- **Shape:** softly rounded (10px), at least 56px tall, 24px horizontal padding, 800-weight 17px label, 2px border slot.
- **Primary:** gold fill with ink text, plus the sky-lift shadow when it sits in the hero.
- **Hover / Focus:** the primary lightens to gold-2. Inside the form, hover and focus add a 2px red outline at 2px offset. Colour transitions take 0.15s.
- **Ghost:** transparent, with cream text and a cream stroke at 70% opacity. On hover the stroke and text turn gold. Used only as the hero's second action.

### Chips
- **Style:** a white field, 2px ink-24% stroke, 10px radius, 50px tall and 18px padding, 700-weight label. The radio input is visually hidden.
- **State:** selected chips fill navy with cream text. Hover and keyboard focus add a 2px red outline at 2px offset. On phones they stack, and from 520px they wrap inline.

### Inputs / Fields
- **Style:** a white field, 2px ink-24% stroke, 10px radius, at least 54px tall, 13px by 14px padding, 500-weight 17px text. The label above is 800-weight 16px. Placeholders are slate grey.
- **Hover / Focus:** the border turns red and a 2px red outline appears at 2px offset.
- **Error:** the border becomes red-deep, and a 15px, 700-weight red-deep message sits below the field. It is hidden when empty.

### Navigation
There is no nav menu. The header holds the wordmark (left: maple leaf, then "PEOPLE'S CANADIAN" over a gold "ROOFING" flanked by short gold bars) and the phone link (right: gold handset icon, cream 800-weight tabular number, turns gold on hover). Both are at least 44px tall.

### Service Rows
A full-width list of links with hairline rules above and below each. Title type on the left; a 46px circular outlined arrow on the right.
- **Hover / Focus:** only the arrow changes. It fills red with a white glyph, and keyboard focus adds a 3px red ring around it. The row itself gets no background, underline or shadow.

### Steps
A large gold tabular numeral (52px, 900) beside a 22px title and cream-2 body, on navy. On desktop the numeral sits above the title in three columns.

### Closing Band
A full-bleed red band, centred: white maple leaf (58px), uppercase headline, then the phone number at clamp(40px, 12vw, 88px), 900 weight, white with a 3px underline that thickens to 6px on hover.

### Live Roof (signature)
A canvas layer behind the hero. It paints sky, cloud, rain, blowing maple leaves and a weathered shingle roof (moss, streaks, missing and curled tabs) that the pointer re-shingles. When idle, it autoplays a roofer laying courses, holds the new roof, then lets it weather back. The eavestroughs between bands reuse the same shingle painter and add drips that respond to the pointer. Values live in the script's TUNE object, not in CSS.
- **Clear zones:** rain, leaves and drips are kept out of the header, the hero copy block (with 12px padding) and the hint text. Nothing in the motion layer crosses words.
- **Reduced motion:** a single still frame of the finished new roof, with a few leaves resting on it and the hint hidden. Drips are drawn once as static beads. All CSS transitions are switched off.
- **Performance:** one shared animation loop, paused off-screen via IntersectionObserver. Pointer listeners are passive and never block scroll. Painting starts after first paint so the buttons respond first.

## Do's and Don'ts

### Do:
- **Do** keep the page ground to paper, navy or red bands, and join bands with the painted eavestrough wherever a roofline makes sense.
- **Do** use gold for actions only: the primary button, the focus ring (3px gold outline, 3px offset) and one emphasised display word.
- **Do** use the 2px red outline at 2px offset as the hover/focus signal on form controls (inputs, chips and the form's submit button).
- **Do** use the maple leaf as the bullet and the mark, filled flag red on paper and white on red.
- **Do** keep every motion-layer element out of the clear zones around the header, the hero copy and the hint.
- **Do** give reduced-motion visitors a finished still frame, not a blank canvas or a half-weathered roof.
- **Do** keep tap targets at 44px or more, and buttons at 56px.

### Don't:
- **Don't** load web fonts or swap out the system stack.
- **Don't** add a sticky or fixed bottom bar.
- **Don't** repeat the phone number on the first screen beyond the top-right header link.
- **Don't** put more than two buttons in the hero.
- **Don't** change anything but the arrow on service-row hover. No row background, underline, shift or shadow.
- **Don't** replace the painted roof with a stock house photo, or the service rows with an icon-card grid.
- **Don't** use a black page ground. Dark means navy.
- **Don't** add UI shadows beyond the hero gold button's sky lift.
