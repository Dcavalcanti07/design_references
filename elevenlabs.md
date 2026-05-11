# ElevenLabs — Style Reference
> Architect's blueprint on warm vellum — Waldenburg weight-300 headlines at 48px with -0.02em tracking anchored against an eggshell ground, pure black pill buttons as the only punctuation.

**Theme:** light

ElevenLabs feels like a museum label next to a working instrument — type-first, almost severe, yet alive with subtle warmth in the off-white surfaces. The page background #fdfcfc (named 'Eggshell' in the CSS tokens) is barely-not-white, giving the layout a slight papery warmth that black text lands on with extraordinary weight. Headlines use Waldenburg at weight 300 with -0.02em tracking, a custom serif that whispers where competitors shout — the counter-intuitive choice of a light-weight, slightly classical typeface for an AI voice platform creates authority through restraint. The entire chromatic palette is suppressed to near-zero saturation: #e5e5e5 borders, #777169 secondary text (a warm stone gray), and #fdfcfc surfaces — the only true color breaks come from pill-shaped black CTA buttons and the small colored avatar dots on voice profiles. The product UI card floats on a hairline shadow (0px 0px 1px rgba(0,0,0,0.4)) rather than elevation depth, keeping everything in the same visual plane.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Eggshell | `#fdfcfc` | `--color-eggshell` | Page background and primary surface — the near-white warmth distinguishes this from pure #ffffff, landing type with extra weight |
| Powder | `#f5f3f1` | `--color-powder` | Secondary surface, hover states, subtle section backgrounds |
| Chalk | `#e5e5e5` | `--color-chalk` | All borders, dividers, card outlines, button outlines — the single border color used universally |
| Fog | `#b1b0b0` | `--color-fog` | Disabled states, placeholder elements, logo grid grayscale treatment |
| Gravel | `#777169` | `--color-gravel` | Secondary body text, nav items, subheadings, captions — warm stone undertone separates it from a cold gray |
| Slate | `#a59f97` | `--color-slate` | Tertiary text, icon strokes, deemphasized labels |
| Cinder | `#57534` | `--color-cinder` | Mid-tone text, secondary headings on light surfaces |
| Obsidian | `#000000` | `--color-obsidian` | Primary text, filled CTA buttons (background), logo mark — the absolute black against eggshell creates 20.5:1 contrast |
| Signal Blue | `#0447ff` | `--color-signal-blue` | ElevenAgents product dot / brand avatar accent — appears only in small circular UI elements, not in text or buttons |
| Ember | `#ff4704` | `--color-ember` | ElevenCreative product dot / brand avatar accent — small circular UI indicator only |
| Voice Spectrum | `conic-gradient(from 180deg, rgb(61, 117, 216) 11.5931deg, rgb(42, 104, 210) 26.317deg, rgb(117, 190, 229) 32.3924deg, rgb(82, 208, 233) 38.9146deg, rgb(33, 89, 186) 75.3508deg, rgb(58, 116, 218) 85.0388deg, rgb(108, 215, 236) 94.5293deg, rgb(90, 185, 241) 122.11deg, rgb(51, 161, 229) 129.967deg, rgb(31, 95, 207) 136.719deg, rgb(44, 84, 202) 144.313deg, rgb(58, 158, 207) 175.985deg, rgb(49, 103, 197) 183.869deg, rgb(173, 232, 243) 201.635deg, rgb(216, 241, 245) 224.865deg, rgb(165, 219, 230) 239.729deg, rgb(43, 157, 214) 268.165deg, rgb(174, 224, 233) 286.211deg, rgb(32, 186, 208) 329.654deg, rgb(30, 83, 176) 343.551deg, rgb(47, 64, 210) 359.255deg)` | `--color-voice-spectrum` | Logo mark conic gradient — the spinning blue-cyan wheel that is the ElevenLabs logomark |

## Tokens — Typography

### Waldenburg — All display and section headlines. Weight 300 is the signature move — a light-weight custom serif for an AI platform inverts every SaaS convention of bold grotesque headlines. At 48px with -0.02em tracking the letters breathe and lean slightly classical. No substitute fully captures it. · `--font-waldenburg`
- **Substitute:** Cormorant Garamond 300, or Libre Baskerville 300
- **Weights:** 300
- **Sizes:** 32px, 36px, 48px
- **Line height:** 1.08–1.17
- **Letter spacing:** -0.64px at 32px, -0.72px at 36px, -0.96px at 48px
- **Role:** All display and section headlines. Weight 300 is the signature move — a light-weight custom serif for an AI platform inverts every SaaS convention of bold grotesque headlines. At 48px with -0.02em tracking the letters breathe and lean slightly classical. No substitute fully captures it.

### WaldenburgFH — Navigation product labels (ElevenCreative, ElevenAgents, ElevenAPI) and icon badges. The 0.05em wide tracking at weight 700 creates a compressed, stamp-like label style — tight caps energy in a small footprint. · `--font-waldenburgfh`
- **Substitute:** Inter 700 with letter-spacing 0.7px
- **Weights:** 700
- **Sizes:** 14px
- **Line height:** 1.10
- **Letter spacing:** 0.7px at 14px
- **Role:** Navigation product labels (ElevenCreative, ElevenAgents, ElevenAPI) and icon badges. The 0.05em wide tracking at weight 700 creates a compressed, stamp-like label style — tight caps energy in a small footprint.

### Inter — All body copy, UI labels, navigation, buttons, captions, footer. Weight 400 for body and descriptive text; weight 500 for interactive labels and emphasis. The 0.01em letter-spacing is a subtle open tracking that keeps small sizes legible on eggshell. · `--font-inter`
- **Substitute:** Inter (Google Fonts)
- **Weights:** 400, 500
- **Sizes:** 10px, 12px, 13px, 14px, 15px, 16px, 18px, 20px
- **Line height:** 1.0–2.06
- **Letter spacing:** 0.1px–0.2px across all sizes
- **OpenType features:** `"kern" 1`
- **Role:** All body copy, UI labels, navigation, buttons, captions, footer. Weight 400 for body and descriptive text; weight 500 for interactive labels and emphasis. The 0.01em letter-spacing is a subtle open tracking that keeps small sizes legible on eggshell.

### Geist Mono — Code snippets, technical annotations, voice-text preview inline markers like [sarcastic] and [whispers]. Monospace signals machine-generated or technical content within prose. · `--font-geist-mono`
- **Substitute:** JetBrains Mono 400, or IBM Plex Mono 400
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.69
- **Role:** Code snippets, technical annotations, voice-text preview inline markers like [sarcastic] and [whispers]. Monospace signals machine-generated or technical content within prose.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | — | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.44 | — | `--text-subheading` |
| heading-sm | 20px | 1.4 | — | `--text-heading-sm` |
| heading | 32px | 1.17 | -0.64px | `--text-heading` |
| heading-lg | 36px | 1.13 | -0.72px | `--text-heading-lg` |
| display | 48px | 1.08 | -0.96px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 16px |
| badges | 12px |
| inputs | 4px |
| modals | 24px |
| panels | 20px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.075) 0px 0px 0px 0.5px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) ...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px inset` | `--shadow-subtle-3` |
| subtle-4 | `rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0...` | `--shadow-subtle-4` |
| subtle-5 | `rgba(0, 0, 0, 0.1) 0px 0px 0px 1px inset` | `--shadow-subtle-5` |
| subtle-6 | `rgb(235, 232, 228) 0px 0px 0px 0.5px inset` | `--shadow-subtle-6` |
| subtle-7 | `rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0...` | `--shadow-subtle-7` |
| subtle-8 | `rgba(255, 255, 255, 0.6) 0px 0px 0px 1px inset` | `--shadow-subtle-8` |
| subtle-9 | `rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0...` | `--shadow-subtle-9` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 80-120px
- **Card padding:** 16-24px
- **Element gap:** 8-12px

## Components

### Primary Pill Button (Filled)
**Role:** Primary CTA — Sign up, Play, Submit

Background #000000, text #fdfcfc, border-radius 9999px, padding 0px 16px (height driven by line-height), border 1px solid #e5e5e5. Shadow: rgba(0,0,0,0.06) 0px 0px 0px 1px, rgba(0,0,0,0.04) 0px 1px 2px, rgba(0,0,0,0.04) 0px 2px 4px. WaldenburgFH 700 14px 0.05em tracking for product-label buttons; Inter 500 14px for general CTAs.

### Ghost Pill Button (Outline)
**Role:** Secondary actions — Contact sales, Log in, Read all stories

Background #ffffff, text #000000, border-radius 9999px, padding 0px 12px, border 1px solid #e5e5e5. Same shadow system as filled button. The white fill over eggshell background gives a subtle float-off-page effect.

### Rounded Outline Button (Tab/Toggle)
**Role:** Segmented control tabs — ElevenCreative, ElevenAgents, ElevenAPI selector

Background transparent, text #000000, border-radius 18px, padding 8px 12px, border 1px solid #e5e5e5. WaldenburgFH 700 14px for product name labels. Active state upgrades to filled pill.

### Compact Action Button
**Role:** Inline UI actions — pagination arrows, expand/collapse controls

Background transparent, text #000000, border-radius 12px, padding 0px 8px left / 12px right, border 1px solid #e5e5e5. Smaller footprint for secondary UI controls inside cards.

### Product Demo Card
**Role:** Interactive voice-player UI card embedded in hero section

Background #ffffff, border-radius 16px, box-shadow rgba(0,0,0,0.4) 0px 0px 1.143px 0px, rgba(0,0,0,0.04) 0px 2px 4px. Contains a voice list (Inter 14px #000000 names, Inter 13px #777169 descriptors), a text input area, and a Play pill button. Inner elements use 4px and 12px radii for sub-controls.

### Voice List Item
**Role:** Individual voice selection row inside demo card

Full-width row with 32px circular avatar (colored gradient or flat color), voice name in Inter 500 14px #000000, voice descriptor in Inter 400 13px #777169. Active/selected row gets background #f5f3f1 with 4px radius highlight. Row height ~40px, horizontal padding 12px.

### Navigation Bar
**Role:** Top global navigation

Background #fdfcfc, height 36px, max-width 1200px centered. Logo left-aligned. Nav links in Inter 400 14px #000000. Product sub-items in WaldenburgFH 700 14px 0.05em tracking. 'Log in' as Ghost Pill, 'Sign up' as Filled Pill. Border-bottom 1px solid #e5e5e5 on scroll.

### Section Divider Label
**Role:** Eyebrow text above section headings

Inter 400 14px #777169 (Gravel), no background, no border. Placed 8-12px above the Waldenburg heading. Communicates category without visual decoration.

### Text Input (Transparent)
**Role:** Inline text editors and search fields

Background transparent, border-radius 0px, border-bottom 1px solid #000000, padding 12px 20px, text Inter 400 14px #000000, placeholder Inter 400 14px #a59f97. No box shadow. Stripped-back, editorial-form input style.

### Text Input (Contained)
**Role:** Form inputs with white background

Background #ffffff, border 1px solid #e5e5e5, border-radius 0px, padding 12px 20px, text Inter 400 14px #000000. Inner shadow rgba(0,0,0,0.075) 0px 0px 0px 0.5px inset for depth on white surface.

### Feature Platform Card (Ghost)
**Role:** Two-column product description cards — ElevenCreative / ElevenAgents

Background transparent, border 0, radius 0px, padding 0. Heading in Inter 500 16px #000000, body in Inter 400 14px #777169. No elevation — these are pure typographic blocks on the eggshell ground, differentiated only by the colored dot prefix (Ember #ff4704 or Signal Blue #0447ff).

## Do's and Don'ts

### Do
- Use Waldenburg 300 with -0.02em letter-spacing for all headings at 32px and above — never substitute a heavier weight.
- Apply 9999px border-radius to every button and pill tag; use 16-20px for cards and panels; use 0px for bare input fields.
- Keep the entire color palette at near-zero saturation: #000000 text, #fdfcfc background, #e5e5e5 borders, #777169 secondary text. Reserve #ff4704 and #0447ff for product avatar dots only.
- Use the inset shadow rgba(0,0,0,0.075) 0px 0px 0px 0.5px inset on white UI surfaces that sit on eggshell — it replaces border outlines on cards without adding visual weight.
- Use Geist Mono 400 13px only for machine-generated or technical inline annotations (e.g. [whispers], [sarcastic]) and code snippets.
- Render all third-party logos in the social proof grid at #b1b0b0 (Fog) with no hover color change — chromatic logos break the achromatic discipline.
- Size section gaps at 80-120px vertical spacing between major content blocks; use 8-12px for element-level gaps within components.

### Don't
- Never use a weight above 300 for Waldenburg display headlines — weight 700 belongs only to WaldenburgFH product-label contexts at 14px.
- Never introduce saturated color for text, background fills, or buttons — the Signal Blue #0447ff and Ember #ff4704 are reserved exclusively for 8-16px avatar/dot indicators.
- Never apply box-shadow elevation larger than rgba(0,0,0,0.4) 0px 0px 1.143px — ElevenLabs cards float by 1px shadow, not by depth layering.
- Never use a pure white #ffffff background for page surfaces — use #fdfcfc (Eggshell) for all base surfaces to preserve the warm papery ground.
- Never place Inter body text below 13px in product UI contexts or below 14px in marketing prose — the 0.01em tracking needs minimum size to work.
- Never use more than two button variants in the same visual cluster — one filled black pill (primary) + one white ghost pill (secondary) is the maximum combination.
- Never apply border-radius to input fields — inputs use 0px radius, creating an editorial underline-or-box distinction from the rounded interactive elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Ground | `#fdfcfc` | Base page background — all page-level content sits here |
| 1 | Powder Surface | `#f5f3f1` | Section highlights, active row states, nav hover backgrounds |
| 2 | Card White | `#ffffff` | Interactive demo cards and form inputs that need to pop off the eggshell ground |
| 3 | Obsidian | `#000000` | Primary CTA fill, logo mark, full-bleed dark sections |

## Elevation

ElevenLabs uses only hairline elevation: rgba(0,0,0,0.4) 0px 0px 1.143px with a secondary rgba(0,0,0,0.04) 0px 2px 4px. Cards barely detach from the eggshell surface — they hover rather than float. This flatness keeps all UI elements in the same perceptual plane, matching the editorial, text-first design intention. The inset shadow rgba(0,0,0,0.075) 0px 0px 0px 0.5px is used instead of border-color on white-on-eggshell surfaces.

## Imagery

Product screenshots are the dominant visual — specifically, the interactive voice-player UI shown as a white card with structured list and text area. No lifestyle photography is present. Illustration is absent. The only 'graphic' element is the conic-gradient logomark, a spinning blue-to-cyan color wheel suggesting audio waveforms or voice spectra, contained within a ~24px icon footprint. Voice avatars use small 28-32px circular gradient fills (multicolor mini-spheres) as person-indicators — these are the only chromatic imagery in the UI. Social proof section uses SVG wordmark logos uniformly desaturated to #b1b0b0 Fog. The design is text-dominant: imagery occupies roughly 30% of visual space with the product card; 70% is typographic.

## Layout

Max-width ~1200px centered on eggshell ground. Hero is a two-column asymmetric split: large Waldenburg headline left (60% width) with body text right, followed by two pill buttons. Below the fold, a full-width white product card (border-radius 16px) acts as a live demo embed spanning the full content column. Logo grid is a 6-column × 3-row flat array on white, centered, with generous 24-32px row gaps. Feature descriptions use a 2-column text block layout (no images, purely typographic). Navigation is a slim 36px top bar, likely sticky on scroll, with logo left and auth CTAs right. Section rhythm is seamless — no alternating dark/light bands; the entire page is the same eggshell ground broken only by the white card surfaces and the #f5f3f1 subtle hover zones.

## Agent Prompt Guide

**Quick Color Reference**
- Text (primary): #000000
- Text (secondary): #777169
- Text (tertiary): #a59f97
- Background (page): #fdfcfc
- Background (surface): #f5f3f1
- Card background: #ffffff
- Border (universal): #e5e5e5
- CTA fill: #000000 with #fdfcfc text
- Product dot (Creative): #ff4704
- Product dot (Agents): #0447ff

**Example Component Prompts**

1. **Hero Section**: Eggshell (#fdfcfc) background, max-width 1200px centered, 120px top padding. Two-column layout: left 60% has Waldenburg 300 48px headline #000000 letter-spacing -0.96px line-height 1.08, then 16px gap, then Inter 400 16px #777169 body text, then 24px gap, then row of two buttons. Right 40% empty or decorative. First button: filled pill #000000 bg, #fdfcfc text, 9999px radius, 0px 16px padding, Inter 500 14px. Second button: ghost pill #ffffff bg, #000000 text, 9999px radius, 0px 12px padding, 1px solid #e5e5e5 border.

2. **Product Demo Card**: Background #ffffff, border-radius 16px, box-shadow rgba(0,0,0,0.4) 0px 0px 1.143px, rgba(0,0,0,0.04) 0px 2px 4px. Left panel: tab row of three ghost pills (18px radius, 8px 12px padding, WaldenburgFH 700 14px 0.05em tracking) for ElevenCreative/ElevenAgents/ElevenAPI. Below: voice list rows — 12px padding, 40px height each, circular 28px avatar + Inter 500 14px #000000 name + Inter 400 13px #777169 descriptor. Right panel: text area Inter 400 14px #000000 on white with transparent border, Geist Mono 400 13px for inline [direction] annotations in #777169.

3. **Social Proof Logo Band**: #fdfcfc or #ffffff background, 80px vertical padding. Header row: Inter 400 14px #777169 left label + Ghost Pill Button right ('Read all stories', 9999px, 0px 12px padding, 1px #e5e5e5 border). Logo grid: 6 columns, SVG logos all at #b1b0b0, no hover color, 24px row gap, 40px column gap, logos max-height 28px.

4. **Navigation Bar**: Height 36px, #fdfcfc background, border-bottom 1px solid #e5e5e5. Left: ElevenLabs logomark (conic gradient wheel icon + WaldenburgFH 700 14px wordmark). Center: Inter 400 14px #000000 nav links with 16px gap. Product labels (ElevenCreative, ElevenAgents, ElevenAPI) in WaldenburgFH 700 14px 0.05em tracking. Right: 'Log in' ghost pill (0px 12px padding) + 'Sign up' filled black pill (0px 16px padding).

5. **Two-Column Feature Block**: #fdfcfc background, 80px vertical padding, max-width 1200px. Waldenburg 300 36px headline #000000 letter-spacing -0.72px spanning full width. Below: 2-column equal grid, 32px gap. Each column: 8px colored dot (Ember #ff4704 or Signal Blue #0447ff) + Inter 500 16px #000000 product name + 8px gap + Inter 400 14px #777169 description body.

## WaldenburgFH Label System

WaldenburgFH 700 at 14px with 0.05em letter-spacing (0.7px) is used exclusively for product-family labels: ElevenCreative, ElevenAgents, ElevenAPI. This weight/tracking combination creates a compact stamp identity within navigation tabs and feature pills. Never use WaldenburgFH for body copy or large headings — it exists only at 14px as a labeling system. The 0.05em wide-tracking at a small size creates a monogram-like compressed authority that contrasts with the open, whisper-weight Waldenburg 300 headlines.

## Similar Brands

- **Linear** — Same achromatic palette discipline with a single accent-color confined to UI indicators only, custom-weight typography as brand signature
- **Notion** — Eggshell/near-white page ground with black pill CTAs and editorial type-first layout, serif headline weight against sans body
- **Vercel** — Pure black/white high-contrast CTA system with zero saturated brand color in the marketing UI
- **Anthropic** — Custom serif at light weight for AI product headlines, warm-toned off-white surfaces, deliberate restraint on color expression
- **Perplexity** — Monochrome pill-button system, Inter body at multiple weights, product demo card embedded in hero section

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-eggshell: #fdfcfc;
  --color-powder: #f5f3f1;
  --color-chalk: #e5e5e5;
  --color-fog: #b1b0b0;
  --color-gravel: #777169;
  --color-slate: #a59f97;
  --color-cinder: #57534;
  --color-obsidian: #000000;
  --color-signal-blue: #0447ff;
  --color-ember: #ff4704;
  --color-voice-spectrum: #3d75d8;
  --gradient-voice-spectrum: conic-gradient(from 180deg, rgb(61, 117, 216) 11.5931deg, rgb(42, 104, 210) 26.317deg, rgb(117, 190, 229) 32.3924deg, rgb(82, 208, 233) 38.9146deg, rgb(33, 89, 186) 75.3508deg, rgb(58, 116, 218) 85.0388deg, rgb(108, 215, 236) 94.5293deg, rgb(90, 185, 241) 122.11deg, rgb(51, 161, 229) 129.967deg, rgb(31, 95, 207) 136.719deg, rgb(44, 84, 202) 144.313deg, rgb(58, 158, 207) 175.985deg, rgb(49, 103, 197) 183.869deg, rgb(173, 232, 243) 201.635deg, rgb(216, 241, 245) 224.865deg, rgb(165, 219, 230) 239.729deg, rgb(43, 157, 214) 268.165deg, rgb(174, 224, 233) 286.211deg, rgb(32, 186, 208) 329.654deg, rgb(30, 83, 176) 343.551deg, rgb(47, 64, 210) 359.255deg);

  /* Typography — Font Families */
  --font-waldenburg: 'Waldenburg', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-waldenburgfh: 'WaldenburgFH', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 32px;
  --leading-heading: 1.17;
  --tracking-heading: -0.64px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.72px;
  --text-display: 48px;
  --leading-display: 1.08;
  --tracking-display: -0.96px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 80-120px;
  --card-padding: 16-24px;
  --element-gap: 8-12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 16px;
  --radius-badges: 12px;
  --radius-inputs: 4px;
  --radius-modals: 24px;
  --radius-panels: 20px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.075) 0px 0px 0px 0.5px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 0px 1px 2px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px inset;
  --shadow-subtle-4: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0px 4px 4px 0px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.1) 0px 0px 0px 1px inset;
  --shadow-subtle-6: rgb(235, 232, 228) 0px 0px 0px 0.5px inset;
  --shadow-subtle-7: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;
  --shadow-subtle-8: rgba(255, 255, 255, 0.6) 0px 0px 0px 1px inset;
  --shadow-subtle-9: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;

  /* Surfaces */
  --surface-page-ground: #fdfcfc;
  --surface-powder-surface: #f5f3f1;
  --surface-card-white: #ffffff;
  --surface-obsidian: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-eggshell: #fdfcfc;
  --color-powder: #f5f3f1;
  --color-chalk: #e5e5e5;
  --color-fog: #b1b0b0;
  --color-gravel: #777169;
  --color-slate: #a59f97;
  --color-cinder: #57534;
  --color-obsidian: #000000;
  --color-signal-blue: #0447ff;
  --color-ember: #ff4704;
  --color-voice-spectrum: #3d75d8;

  /* Typography */
  --font-waldenburg: 'Waldenburg', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-waldenburgfh: 'WaldenburgFH', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 32px;
  --leading-heading: 1.17;
  --tracking-heading: -0.64px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.72px;
  --text-display: 48px;
  --leading-display: 1.08;
  --tracking-display: -0.96px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.075) 0px 0px 0px 0.5px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 0px 1px 2px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px inset;
  --shadow-subtle-4: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0px 4px 4px 0px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.1) 0px 0px 0px 1px inset;
  --shadow-subtle-6: rgb(235, 232, 228) 0px 0px 0px 0.5px inset;
  --shadow-subtle-7: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;
  --shadow-subtle-8: rgba(255, 255, 255, 0.6) 0px 0px 0px 1px inset;
  --shadow-subtle-9: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;
}
```
