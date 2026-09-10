# omomo Design Tokens

Machine-readable design rules for omomo. Use this when generating marketing materials, UI, or documentation with AI.

## Colors

```
Primary Brand Color
  name: beige-red
  hex: #C2685C
  ral: RAL 3012
  usage: Main enclosure, hero backgrounds, primary accents
  mood: warm, aged, approachable

Secondary Colors
  name: matte-black
  hex: #1A1A1A
  usage: Hardware, text, high contrast
  mood: technical, neutral

  name: warm-gray
  hex: #8B8680
  usage: Secondary surfaces, labels, borders
  mood: practical, subtle

  name: gold-brass
  hex: #D4AF37
  usage: Accents only (handles, connectors, minimal details)
  mood: premium, intentional

Neutral
  name: off-white
  hex: #F5F1ED
  usage: Backgrounds, documentation, digital spaces

  name: deep-charcoal
  hex: #2C2C2C
  usage: Primary text, high contrast
  mood: readable, professional
```

## Typography

```
Headers & Marketing
  family: Geometric sans-serif (Aktiv Grotesk, Neue Haas Grotesk, or similar)
  weight: 600–700 (semibold to bold)
  size: 32px–56px (marketing), 20px–24px (section headers)
  line-height: 1.2
  character: Modern, slightly geometric, not trendy

Body & Documentation
  family: Humanist sans-serif (Inter, IBM Plex Sans)
  weight: 400 (regular)
  size: 14px–16px (body), 12px (small)
  line-height: 1.6 (relaxed)
  character: High legibility, warm, readable

Technical & Labels
  family: Monospace (JetBrains Mono, IBM Plex Mono)
  weight: 400–500
  size: 11px–13px
  character: Precision, specs, serial numbers
```

## Spacing & Layout

```
Base unit: 8px

Spacing scale:
  xs:  4px
  sm:  8px
  md:  16px
  lg:  24px
  xl:  32px
  xxl: 48px

Container width: 1200px (marketing site), full-bleed (product images)
Padding: 24px–32px (desktop), 16px–20px (mobile)
Gap between elements: 16px–24px
```

## Imagery & Photography

```
Lighting
  style: Warm, natural daylight (golden hour preferred)
  temperature: 3500K–4500K color temp
  contrast: Medium—avoid blown highlights or muddy shadows
  mood: Approachable, not sterile

Composition
  focus: Product (enclosure, driver, handle detail)
  context: Pedalboard, guitar, cables (secondary)
  scale: Show size relationship (hand, pedalboard context)
  depth: Shallow depth of field ok; keep product sharp

Materials
  showcase: Powder coat texture, speaker cone, connectors
  weathering: Clean, not pristine; aged OK
  background: Neutral or complementary (warm, not white)

Color Treatment
  saturation: Slight desaturation on backgrounds; product primary
  tone: Warm. Avoid cool blue tints.
  consistency: Match beige-red across photos (color-correct if needed)
```

## Product Specs Format

```
Specs should be presented as:
  • Clear, bulleted list (not prose)
  • Technical but concise
  • Include dimensions, weight, power specs
  • Monospace font for values

Example:
  Enclosure: Hammond 1590DE
  Driver: Visaton FR10
  Amplifier: TPA3116 Class-D
  Power: 50W @ 4Ω
  Frequency Response: 60Hz–20kHz
  Dimensions: 230 × 155 × 65mm
  Weight: 2.8kg
```

## Tone Rules for Copy

```
✓ Do
  • Be specific: "50W amplifier with full-range speaker"
  • Be direct: "Made in Hamburg"
  • Be technical: Include specs, not fluff
  • Be warm: "Designed for musicians"

✗ Don't
  • Flowery metaphors: Avoid "sonic poetry," "liquid highs"
  • Vague claims: Avoid "premium" without context
  • Passive voice: Say "We use RAL 3012" not "RAL 3012 is utilized"
  • Corporate speak: Avoid jargon, say "amplifier" not "sonic transduction device"
```

## Digital Applications

```
Button
  primary: beige-red background, deep-charcoal text, 6px radius
  secondary: deep-charcoal border (2px), off-white background
  hover: darken beige-red by 10%, add subtle shadow
  size: 44px height minimum (touch-friendly)

Links
  color: beige-red, underline on hover
  weight: regular (inherit from body)

Dividers
  color: warm-gray at 40% opacity
  weight: 1px
  margin: 24px top/bottom

Backgrounds
  primary: off-white
  secondary: beige-red at 8% opacity (very light tint)
  dark mode: deep-charcoal with beige-red accents
```

---

**Last updated:** September 2026  
**Format:** Markdown for human readability + AI parsing  
**Version:** 1.0 (baseline)
