# Apollo — Style Reference
> Warm professional sanctuary

**Theme:** light

Apollo Workspace projects an atmosphere of understated luxury and grounded professionalism. Its visual system favors rich, natural-toned neutrals creating a warm and inviting backdrop for focused work. Typography uses a mix of subtle tracking and generous line spacing to present content clearly, while a singular vibrant orange serves as a confident accent for calls to action, standing out against the otherwise restrained palette. Components are lightweight with minimal border radius, contributing to a sense of openness and modern simplicity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Earth Umber | `#3c261c` | `--color-earth-umber` | Primary text, dark surface backgrounds, button borders, subtle icon fills – grounds the palette with a deep, earthy tone |
| Terracotta Flame | `#e97451` | `--color-terracotta-flame` | CTA button backgrounds, primary navigation accents, link borders – provides a distinct, warm pop for interactive elements |
| Deep Violet | `#4a43dd` | `--color-deep-violet` | Decorative highlights, emphasized headings, specialized link text – a distinct, vivid accent used sparingly for visual interest |
| Pale Ochre | `#f7efc5` | `--color-pale-ochre` | Secondary text and link support, subtle background accents – a muted, warm yellow tint that adds a touch of natural softness |
| Platinum Frost | `#dddedf` | `--color-platinum-frost` | Hairline borders, subtle dividers, inactive states – a cool, light neutral defining structural elements without visual weight |
| Jet Black | `#000000` | `--color-jet-black` | Crisp text for maximum contrast where needed, subtle UI iconography – for pure, uncompromising readability against light backgrounds |
| Warm Linen | `#f9f8f0` | `--color-warm-linen` | Page backgrounds, card surfaces, default UI elements – soft, off-white canvas for the majority of content |
| Peach Cream | `#fcede8` | `--color-peach-cream` | Button text on Terracotta Flame buttons, subtle highlights – a very light, warm neutral used for contrast |

## Tokens — Typography

### MonaSans — General UI text, body copy, navigation, buttons, and most headings — provides a modern, readable foundation with various weights for hierarchy. · `--font-monasans`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 12px, 14px, 18px, 20px, 32px, 36px
- **Line height:** 1.00, 1.16, 1.17, 1.27, 1.35, 1.38, 1.42, 1.49, 1.50, 1.53, 1.55, 1.84
- **Letter spacing:** 0.36, 0.42, 0.54, 0.6, 0.96, 1.08
- **Role:** General UI text, body copy, navigation, buttons, and most headings — provides a modern, readable foundation with various weights for hierarchy.

### paradigm-pro — Distinctive hero and section headlines — its light weight and generous letter-spacing create a high-end, artistic feel, emphasizing space and clarity over density. · `--font-paradigm-pro`
- **Substitute:** serif
- **Weights:** 300
- **Sizes:** 36px, 47px
- **Line height:** 0.95, 0.97
- **Letter spacing:** 2.88, 3.76
- **Role:** Distinctive hero and section headlines — its light weight and generous letter-spacing create a high-end, artistic feel, emphasizing space and clarity over density.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.36px | `--text-caption` |
| body-sm | 14px | 1.5 | 0.42px | `--text-body-sm` |
| body | 18px | 1.49 | 0.54px | `--text-body` |
| subheading | 20px | 1.42 | 0.6px | `--text-subheading` |
| heading-sm | 32px | 1.35 | 0.96px | `--text-heading-sm` |
| heading | 36px | 1.17 | 1.08px | `--text-heading` |
| display | 47px | 0.97 | 3.76px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 17 | 17px | `--spacing-17` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 23 | 23px | `--spacing-23` |
| 30 | 30px | `--spacing-30` |
| 34 | 34px | `--spacing-34` |
| 40 | 40px | `--spacing-40` |
| 45 | 45px | `--spacing-45` |
| 60 | 60px | `--spacing-60` |
| 68 | 68px | `--spacing-68` |
| 90 | 90px | `--spacing-90` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 3px |
| images | 3px |
| buttons | 3px |
| navItems | 3px |

### Layout

- **Section gap:** 68px
- **Card padding:** 45px
- **Element gap:** 20px

## Components

### Primary Action Button
**Role:** Call to action button for reserving space or primary interactions.

Background: Terracotta Flame (#e97451). Text: Peach Cream (#fcede8), MonaSans weight 400. Padding: 22.5px vertical, 45px horizontal. Border radius: 3px.

### Ghost Navigation Link
**Role:** Standard navigation items and subtle interactive links.

Background: transparent. Text: Earth Umber (#3c261c), MonaSans weight 500. Padding: 17px vertical, 34px horizontal. No border or radius by default, but a 1px Earth Umber border on hover/active.

### Text Link - Earth Umber
**Role:** Standard inline links and secondary informational links.

Text: Earth Umber (#3c261c), MonaSans weight 400. No underline by default; underline appears on hover.

### Text Link - Pale Ochre
**Role:** Links with a muted, subtle appearance, potentially when against darker backgrounds.

Text: Pale Ochre (#f7efc5), MonaSans weight 400. No underline by default; underline appears on hover.

### Section Separator
**Role:** Visual division between content blocks.

1px solid border in Platinum Frost (#dddedf).

### Hero Headline
**Role:** Primary headline for hero sections, setting the page's tone.

Text: Warm Linen (#f9f8f0), paradigm-pro weight 300, size 47px, lineHeight 0.97, letterSpacing 3.76px.

### Sub-Navigation Item
**Role:** Secondary navigation for internal sections, like in Workspaces.

Text: Earth Umber (#3c261c), MonaSans weight 500, size 18px. Minimal padding, appears as a list item.

## Do's and Don'ts

### Do
- Prioritize Earth Umber (#3c261c) for most body text and secondary interactive elements to maintain a grounded, professional feel.
- Use Terracotta Flame (#e97451) exclusively for primary calls to action and critical active states to ensure high visibility.
- Apply the paradigm-pro typeface with its specific light weight and generous letter-spacing for large, impactful headlines only, not for body copy or small text.
- Maintain a conservative border-radius of 3px for all interactive elements and contained components like buttons, cards, and images.
- Ensure generous vertical spacing between sections (68px) and a consistent element gap (20px) to enhance readability and a sense of calm density.
- Utilize Warm Linen (#f9f8f0) as the dominant background color for most page content, reserving Earth Umber (#3c261c) only for distinct, immersive full-bleed sections.
- Use Platinum Frost (#dddedf) sparingly for subtle lines and borders, creating a delicate visual structure without heavy dividers.

### Don't
- Do not introduce new vibrant colors other than Terracotta Flame (#e97451) and Deep Violet (#4a43dd) for brand accents; maintain the natural, muted palette.
- Avoid using paradigm-pro for any text below 36px or in situations requiring dense readability; its expansive letter-spacing makes it unsuitable for paragraph text.
- Do not apply excessive shadow or elevation effects to elements; the system favors a flatter design with subtle borders and color shifts for depth.
- Resist using bold weights for all headlines; reserve MonaSans weight 300 for a more refined, authoritative whisper-like presence when appropriate.
- Do not vary border radii wildly; adhere to the consistent 3px radius for a cohesive, understated component aesthetic.
- Avoid tight letter-spacing for any text element, especially larger headlines, as the system emphasizes openness and clarity.
- Do not use Terracotta Flame (#e97451) for passive elements or general decorative purposes; it is reserved for action and emphasis related to primary interactions.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Warm Linen Canvas | `#f9f8f0` | Primary page background and default card surfaces, providing a clean, warm base. |
| 2 | Earth Umber Panel | `#3c261c` | Distinct, full-bleed sections, such as the hero background, creating a moodier, immersive boundary. |

## Imagery

The imagery features professional photography with a slightly warm, desaturated cast, focusing on individuals in dynamic, yet composed, work-related scenarios. People are often shown interacting with coffee or in well-lit, minimal environments. Product-focused elements (like offices or architecture) are presented with an overall light, airy feel, emphasizing natural light and materials. There are also hand-drawn, architectural illustrations with a warm, muted color palette that blend seamlessly with the overall sophisticated aesthetic. Icons, when present, are simple, outlined, and monochromatic, aligning with the clean UI. Imagery serves both decorative and explanatory roles, highlighting the aspirational quality of the workspace.

## Layout

The page primarily uses a max-width contained layout, centered on a Warm Linen (#f9f8f0) background, with ample white space. The hero section is full-bleed with a prominent, centered headline in paradigm-pro, layered over a darkened image background. Sections maintain consistent vertical spacing (68px) and often employ a two-column arrangement, alternating between text on one side and an image or illustration on the other. Navigation is a sticky top bar with text links and a distinguishing Terracotta Flame (#e97451) bordered button for primary action. Content blocks are generally spacious rather than compact, creating a deliberate pacing and an unhurried, thoughtful rhythm.

## Agent Prompt Guide

Quick Color Reference: 
text: #3c261c
background: #f9f8f0
border: #dddedf
accent: #e97451
primary action: #e97451 (filled action)

Example Component Prompts:
Create a standard navigation item: Text 'Workspaces' in Earth Umber (#3c261c), MonaSans weight 500, with 17px vertical and 34px horizontal padding. On hover, apply a 1px solid Earth Umber border.
Create a Primary Action Button: #e97451 background, #3c261c text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a Section Heading: Text 'When Your Space Works, So You Do.' in Earth Umber (#3c261c), MonaSans weight 600, size 36px, lineHeight 1.17, letterSpacing 1.08px.
Create an architectural illustration card: Use an image with 3px border-radius, background Warm Linen (#f9f8f0), and a 1px Platinum Frost (#dddedf) border. Ensure 45px padding if text content is present within the card.

## Similar Brands

- **WeWork** — Focus on high-end, inspiring workspace environments with clean layouts and a premium feel.
- **The Wing** — Elegant, understated aesthetics with subtle color accents and inviting, professional imagery.
- **Industrious** — Professional service-based design, using sophisticated typography and a light, spacious feel for office spaces.
- **Equinox** — Luxury brand aesthetic with a focus on elevated experiences, using refined typography and a restrained color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-earth-umber: #3c261c;
  --color-terracotta-flame: #e97451;
  --color-deep-violet: #4a43dd;
  --color-pale-ochre: #f7efc5;
  --color-platinum-frost: #dddedf;
  --color-jet-black: #000000;
  --color-warm-linen: #f9f8f0;
  --color-peach-cream: #fcede8;

  /* Typography — Font Families */
  --font-monasans: 'MonaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-paradigm-pro: 'paradigm-pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.36px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.42px;
  --text-body: 18px;
  --leading-body: 1.49;
  --tracking-body: 0.54px;
  --text-subheading: 20px;
  --leading-subheading: 1.42;
  --tracking-subheading: 0.6px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.35;
  --tracking-heading-sm: 0.96px;
  --text-heading: 36px;
  --leading-heading: 1.17;
  --tracking-heading: 1.08px;
  --text-display: 47px;
  --leading-display: 0.97;
  --tracking-display: 3.76px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-23: 23px;
  --spacing-30: 30px;
  --spacing-34: 34px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-90: 90px;

  /* Layout */
  --section-gap: 68px;
  --card-padding: 45px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-sm: 3px;

  /* Named Radii */
  --radius-cards: 3px;
  --radius-images: 3px;
  --radius-buttons: 3px;
  --radius-navitems: 3px;

  /* Surfaces */
  --surface-warm-linen-canvas: #f9f8f0;
  --surface-earth-umber-panel: #3c261c;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-earth-umber: #3c261c;
  --color-terracotta-flame: #e97451;
  --color-deep-violet: #4a43dd;
  --color-pale-ochre: #f7efc5;
  --color-platinum-frost: #dddedf;
  --color-jet-black: #000000;
  --color-warm-linen: #f9f8f0;
  --color-peach-cream: #fcede8;

  /* Typography */
  --font-monasans: 'MonaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-paradigm-pro: 'paradigm-pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.36px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.42px;
  --text-body: 18px;
  --leading-body: 1.49;
  --tracking-body: 0.54px;
  --text-subheading: 20px;
  --leading-subheading: 1.42;
  --tracking-subheading: 0.6px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.35;
  --tracking-heading-sm: 0.96px;
  --text-heading: 36px;
  --leading-heading: 1.17;
  --tracking-heading: 1.08px;
  --text-display: 47px;
  --leading-display: 0.97;
  --tracking-display: 3.76px;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-23: 23px;
  --spacing-30: 30px;
  --spacing-34: 34px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-90: 90px;

  /* Border Radius */
  --radius-sm: 3px;
}
```
