# Cora — Style Reference
> Sky canvas, cloud cards

**Theme:** light

Cora employs a sky-blue canvas punctuated by crisp white cards, evoking a calm and expansive digital workspace. Typography is a blend of confident sans-serif for functional elements and an authoritative serif for headlines, creating a distinct voice. Interactive elements are minimal and feature rounded corners, favoring ghost buttons or subtle fills. The visual system balances a cloud-like softness with clear functional hierarchy, using blue as a primary accent for activation and brand recognition.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sky Canvas | `#117bc8` | `--color-sky-canvas` | Dominant page background, navigation bar fill — expansive and soft blue |
| Midnight Accent | `#09426c` | `--color-midnight-accent` | Primary action button background — a deep, authoritative blue that grounds interactive elements |
| Cloud White | `#ffffff` | `--color-cloud-white` | Card backgrounds, primary text on dark backgrounds, ghost button text and borders, page main content background |
| Ash Gray | `#dadada` | `--color-ash-gray` | Subtle borders for cards and visual dividers, background for input fields |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, prominent borders, icon fills |
| Text Gray | `#2b2b2b` | `--color-text-gray` | Body text, some heading text, detailed secondary text |
| Muted Silver | `#a1a1a1` | `--color-muted-silver` | Muted helper text, secondary information text, subtle UI elements |
| Blue Border | `#60a8dd` | `--color-blue-border` | Outlined button borders, card borders where distinction is needed |
| Carbon Shadow | `#0d5c96` | `--color-carbon-shadow` | Shadow tint for elevated elements — provides depth with a cool, subtle blue cast |
| Error Red | `#cf372d` | `--color-error-red` | Red outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Whisper Gray | `#ebebeb` | `--color-whisper-gray` | Subtly elevated card backgrounds, secondary surface |

## Tokens — Typography

### switzer — Versatile sans-serif for body text, navigation items, buttons, and functional UI; it provides a direct, modern voice. · `--font-switzer`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 15px, 16px, 17px, 18px, 20px, 22px
- **Line height:** 1.00, 1.02, 1.20, 1.24
- **Letter spacing:** normal
- **Role:** Versatile sans-serif for body text, navigation items, buttons, and functional UI; it provides a direct, modern voice.

### signifier — Distinctive serif for headings and display text; its lighter 300 weight for larger sizes creates an authoritative whisper rather than a shout, conveying gravitas without being heavy. · `--font-signifier`
- **Substitute:** serif
- **Weights:** 300, 400
- **Sizes:** 24px, 34px, 36px, 45px, 55px
- **Line height:** 1.02, 1.18, 1.20
- **Letter spacing:** normal
- **Role:** Distinctive serif for headings and display text; its lighter 300 weight for larger sizes creates an authoritative whisper rather than a shout, conveying gravitas without being heavy.

### Times — Fallback serif for legacy content or specific textual emphasis where a system default is sufficient, primarily at body size. · `--font-times`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback serif for legacy content or specific textual emphasis where a system default is sufficient, primarily at body size.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1.2 | — | `--text-body-sm` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 20px | 1 | — | `--text-subheading` |
| heading-sm | 24px | 1.02 | — | `--text-heading-sm` |
| heading | 36px | 1.18 | — | `--text-heading` |
| heading-lg | 45px | 1.02 | — | `--text-heading-lg` |
| display | 55px | 1.02 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 21 | 21px | `--spacing-21` |
| 22 | 22px | `--spacing-22` |
| 38 | 38px | `--spacing-38` |
| 108 | 108px | `--spacing-108` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| forms | 8px |
| avatars | 9999px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.25) 4px 6px 8px -2px, rgba(0, 0, 0, 0.2) ...` | `--shadow-sm` |
| sm-2 | `rgba(0, 0, 0, 0.1) 0px 4px 4px 0px` | `--shadow-sm-2` |
| sm-3 | `rgba(0, 0, 0, 0.25) 4px 6px 8px 0px, rgba(0, 0, 0, 0.25) ...` | `--shadow-sm-3` |

### Layout

- **Section gap:** 24px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Pill Button - Primary
**Role:** Main call to action button.

Filled with Midnight Accent (#09426c), Cloud White (#ffffff) text, 9999px border-radius, 12px vertical, 65px horizontal padding.

### Pill Button - Ghost
**Role:** Secondary action button, typically on dark backgrounds.

Transparent background, Cloud White (#ffffff) text, 9999px border-radius, 12px vertical, 38px horizontal padding, with a subtle border of rgba(255, 255, 255, 0.376).

### Pill Button - White
**Role:** Secondary action button, typically on light backgrounds.

Filled with Cloud White (#ffffff), Ink Black (#000000) text, 9999px border-radius, 10px vertical, 20px horizontal padding.

### Default Card
**Role:** Standard content container.

Cloud White (#ffffff) background, 12px border-radius, 12px vertical, 15px horizontal padding. Features a subtle shadow: rgba(0, 0, 0, 0.07) 0px 4px 9.99999px 0px.

### Cloud Card - Testimonial
**Role:** Elevated card for testimonials or featured content.

Cloud White (#ffffff) background, 25px border-radius, 15px padding. Elevated with a distinctive two-sided shadow: rgba(0, 0, 0, 0.25) 4px 6px 8px 0px, rgba(0, 0, 0, 0.25) -4px -6px 8px 0px. This asymmetry highlights the floating nature.

### Subtle Surface Card
**Role:** Secondary surface for internal content blocks.

Whisper Gray (#ebebeb) background, 12px border-radius without shadow. Used for less prominent content areas within a larger card context.

### Navigation Link
**Role:** Top-level navigation item.

switzer font, weight 400, 15px, Ink Black (#000000) color. Small 1px padding for click area.

## Do's and Don'ts

### Do
- Prioritize Sky Canvas (#117bc8) as the primary page background for the dominant open-sky aesthetic.
- Use Signifier font for all major headings (H1-H3) and display text, leveraging its light 300 weight for a refined, authoritative tone.
- Apply 9999px border-radius consistently to all interactive elements like buttons and tags to maintain a soft, approachable feel.
- Employ Cloud White (#ffffff) cards on the Sky Canvas (#117bc8) background, and ensure cards have a subtle elevation shadow (rgba(0, 0, 0, 0.07) 0px 4px 9.99999px 0px) for visual lift.
- Reserve Midnight Accent (#09426c) exclusively for primary call-to-action buttons, creating a clear focal point for user actions.
- Maintain an element gap of 8px between closely related UI elements within components or small collections.
- Use Text Gray (#2b2b2b) for standard body copy, providing contrast against white surfaces without the starkness of pure black.

### Don't
- Avoid using bright, saturated colors other than the defined brand / accent blues for primary UI elements, to maintain the calm aesthetic.
- Do not introduce sharp, angular corners; all interactive and content containers should adhere to the established border-radius values (9999px for interactive, 12px for cards).
- Refrain from using heavy, opaque shadows; instead, use the defined subtle shadows or the distinct two-sided testimonial shadow to create depth.
- Do not use type sizes below 12px switzer 400 for any functional text, as readability starts here.
- Do not use pure Ink Black (#000000) for body text; instead, use Text Gray (#2b2b2b) to soften the default text appearance on light backgrounds.
- Avoid decorative images with busy backgrounds; visual elements should either float with light shadows or blend into the blue canvas.
- Do not treat every visual border as a functional border; many subtle borders are purely decorative or serve as soft dividers, often using Ash Gray (#dadada).

## Elevation

- **Default Card:** `rgba(0, 0, 0, 0.07) 0px 4px 9.99999px 0px`
- **Cloud Card - Testimonial:** `rgba(0, 0, 0, 0.25) 4px 6px 8px 0px, rgba(0, 0, 0, 0.25) -4px -6px 8px 0px`
- **Overlay / Modal:** `rgba(0, 0, 0, 0.25) 4px 6px 8px -2px, rgba(0, 0, 0, 0.2) -4px -1px 8px -2px`

## Imagery

The site primarily uses expressive, stylized illustrations of clouds and skies as background elements, creating an atmospheric, expansive feel. Product screenshots are typically inset into these cloudscapes, appearing within a white-framed device resembling a tablet or laptop. When product UI is shown, it features a clean, white internal interface. There is also use of small, outlined, monochrome icons for UI elements and decorative purposes. Imagery is decorative and sets a mood rather than directly explaining features, with a focus on a 'head in the clouds' but 'work done' feeling.

## Layout

The page model is full-bleed for the background imagery, primarily an expansive blue sky with clouds. Content is generally centered and constrained within a comfortable reading width, but the background extends to the viewport edges. The hero section features a large, centered headline over the Sky Canvas, with a product screenshot strategically placed in the lower-middle, appearing to float within the cloud imagery. Sections alternate between full-bleed illustrative backgrounds and white card-like blocks containing text and UI, maintaining a consistent vertical rhythm. Content arrangements often involve centered stacks or simple text-right/image-left type patterns. Navigation is a minimalist top bar with a logo and two ghost/filled pill buttons.

## Agent Prompt Guide

**Quick Color Reference**
text: #000000
background: #117bc8
border: #dadada
accent: #60a8dd
primary action: #09426c (filled action)

**3-5 Example Component Prompts**
1. Create a Primary Action Button: #09426c background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a Default Card: Cloud White (#ffffff) background, 12px radius, 12px vertical, 15px horizontal padding, with rgba(0, 0, 0, 0.07) 0px 4px 9.99999px 0px shadow. Inside, add body text "Cora reads your email patterns to discover who you are..." using switzer weight 400, 16px, Text Gray (#2b2b2b).
4. Create a Cloud Card - Testimonial: Cloud White (#ffffff) background, 25px radius, 15px padding. Add a shadow of rgba(0, 0, 0, 0.25) 4px 6px 8px 0px, rgba(0, 0, 0, 0.25) -4px -6px 8px 0px.
5. Implement a footer section: Cloud White (#ffffff) background. Headline "Free Yourself from Email" using signifier weight 400, 36px, Ink Black (#000000). Body text "Join the waitlist" using switzer weight 400, 16px, Text Gray (#2b2b2b).

## Similar Brands

- **Superhuman** — Polished, productivity-focused app with a strong emphasis on clean UI and distinct, yet minimal, color accents.
- **Linear** — Clean, card-based UI with subtle shadows and a precise typographic hierarchy, often using a limited color palette.
- **Dropbox (new branding)** — Mix of sans-serif and serif typography for distinct brand voice, with playful illustrations and soft, rounded elements.
- **Notion** — Focus on white, card-like surfaces and functional typography, with a reliance on subtle shadows and borders for structure.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sky-canvas: #117bc8;
  --color-midnight-accent: #09426c;
  --color-cloud-white: #ffffff;
  --color-ash-gray: #dadada;
  --color-ink-black: #000000;
  --color-text-gray: #2b2b2b;
  --color-muted-silver: #a1a1a1;
  --color-blue-border: #60a8dd;
  --color-carbon-shadow: #0d5c96;
  --color-error-red: #cf372d;
  --color-whisper-gray: #ebebeb;

  /* Typography — Font Families */
  --font-switzer: 'switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-signifier: 'signifier', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 20px;
  --leading-subheading: 1;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.02;
  --text-heading: 36px;
  --leading-heading: 1.18;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.02;
  --text-display: 55px;
  --leading-display: 1.02;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-22: 22px;
  --spacing-38: 38px;
  --spacing-108: 108px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 35px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-forms: 8px;
  --radius-avatars: 9999px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.25) 4px 6px 8px -2px, rgba(0, 0, 0, 0.2) -4px -1px 8px -2px;
  --shadow-sm-2: rgba(0, 0, 0, 0.1) 0px 4px 4px 0px;
  --shadow-sm-3: rgba(0, 0, 0, 0.25) 4px 6px 8px 0px, rgba(0, 0, 0, 0.25) -4px -6px 8px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sky-canvas: #117bc8;
  --color-midnight-accent: #09426c;
  --color-cloud-white: #ffffff;
  --color-ash-gray: #dadada;
  --color-ink-black: #000000;
  --color-text-gray: #2b2b2b;
  --color-muted-silver: #a1a1a1;
  --color-blue-border: #60a8dd;
  --color-carbon-shadow: #0d5c96;
  --color-error-red: #cf372d;
  --color-whisper-gray: #ebebeb;

  /* Typography */
  --font-switzer: 'switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-signifier: 'signifier', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 20px;
  --leading-subheading: 1;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.02;
  --text-heading: 36px;
  --leading-heading: 1.18;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.02;
  --text-display: 55px;
  --leading-display: 1.02;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-22: 22px;
  --spacing-38: 38px;
  --spacing-108: 108px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 35px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.25) 4px 6px 8px -2px, rgba(0, 0, 0, 0.2) -4px -1px 8px -2px;
  --shadow-sm-2: rgba(0, 0, 0, 0.1) 0px 4px 4px 0px;
  --shadow-sm-3: rgba(0, 0, 0, 0.25) 4px 6px 8px 0px, rgba(0, 0, 0, 0.25) -4px -6px 8px 0px;
}
```
