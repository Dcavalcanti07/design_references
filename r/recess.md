# Recess — Style Reference
> Pastel Cloud Dreamscape — like sipping an airy drink while floating amongst sweet-colored clouds on a clear day.

**Theme:** light

Recess evokes a playful and ephemeral calm, like floating candy clouds in a pastel sky. The visual language balances approachable softness with crisp technical legibility through the Sharp Grotesk typeface. Large, airy sections of pastel gradients and product photography create a relaxed, uncluttered feel, while the consistent use of a muted violet-blue for text and primary elements anchors the whimsical palette in a clear, trustworthy brand identity. The design uses rounded forms and soft shadows to maintain a friendly and light atmosphere.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sky Violet | `#25385b` | `--color-sky-violet` | Primary text, navigation links, button text, input text — a grounding, muted violet-blue that reads as sophisticated neutral rather than cold. |
| Cloud Indigo | `#0a0a3a` | `--color-cloud-indigo` | Footer background, secondary text — a deeper, more saturated violet-blue providing contrast and depth for structural elements. |
| Lavender Mist | `#a2b0ff` | `--color-lavender-mist` | Primary button backgrounds, highlight elements, subtle graphic accents — a moderate violet with a soft, inviting energy. |
| Vivid Cobalt | `#3252f4` | `--color-vivid-cobalt` | Secondary brand accent, used for prominent headlines — a brighter, vivid violet that draws attention without being aggressive. |
| Candy Apple | `#ff5a5a` | `--color-candy-apple` | Alerts, special promotions — a vivid red used sparingly for high-emphasis elements. |
| Vanilla Cream | `#fffcef` | `--color-vanilla-cream` | Button backgrounds, subtle surface highlights — a very light, warm off-white adding a soft glow. |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, text elements on dark backgrounds, icons — the primary achromatic background. |
| Jet Black | `#000000` | `--color-jet-black` | Icons, subtle graphic elements, some borders — used minimally for sharp definition. |
| Starlight Gray | `#84849c` | `--color-starlight-gray` | Secondary text, subtle borders, list item separators — a soft, almost lavender-tinted gray for understated detail. |
| Gradient Sky Glow A | `linear-gradient(rgb(236, 245, 246), rgb(235, 235, 253), rgb(251, 206, 205))` | `--color-gradient-sky-glow-a` | Background gradient for hero sections and key content blocks — transitioning from a cool cyan to a soft violet and then a warm rose. |
| Gradient Sky Glow B | `linear-gradient(rgba(162, 176, 255, 0), rgb(236, 245, 246))` | `--color-gradient-sky-glow-b` | Transitional and softer gradients, often used for masks or subtle background variations. |
| Gradient Sky Glow C | `linear-gradient(rgb(251, 206, 205), rgba(162, 176, 255, 0))` | `--color-gradient-sky-glow-c` | Transitional and softer gradients, often used for masks or subtle background variations. |

## Tokens — Typography

### Sharp Grotesk Web — Body text, navigation items, button text, input text — the primary typeface providing a clean, contemporary feel with good legibility. · `--font-sharp-grotesk-web`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 14px, 15px, 16px, 18px
- **Line height:** 1.33, 1.38, 1.40, 1.63
- **Role:** Body text, navigation items, button text, input text — the primary typeface providing a clean, contemporary feel with good legibility.

### Sharp Grotesk Web — Subheadings, prominent links, product titles — providing emphasis without being overly bold, maintaining the brand's light touch. · `--font-sharp-grotesk-web`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 20px, 24px, 60px
- **Line height:** 1.00, 1.10, 1.13, 1.20, 1.25
- **Role:** Subheadings, prominent links, product titles — providing emphasis without being overly bold, maintaining the brand's light touch.

### Sharp Grotesk Web — Main headlines, hero text — used for maximum impact, but still feels approachable due to the rounded letterforms and generous spacing. · `--font-sharp-grotesk-web`
- **Substitute:** Montserrat
- **Weights:** 700
- **Sizes:** 60px, 24px
- **Line height:** 1.00, 1.10
- **Role:** Main headlines, hero text — used for maximum impact, but still feels approachable due to the rounded letterforms and generous spacing.

### Adobe Blank — Likely a placeholder or fallback font, not intended for primary display. Should not be used in design. · `--font-adobe-blank`
- **Substitute:** None - placeholder/fallback
- **Weights:** 400
- **Sizes:** 14px, 24px
- **Line height:** 1.38, 1.63
- **Role:** Likely a placeholder or fallback font, not intended for primary display. Should not be used in design.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.63 | — | `--text-caption` |
| body | 16px | 1.38 | — | `--text-body` |
| subheading | 18px | 1.33 | — | `--text-subheading` |
| heading-sm | 20px | 1.25 | — | `--text-heading-sm` |
| heading | 24px | 1.2 | — | `--text-heading` |
| display | 60px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

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
| 84 | 84px | `--spacing-84` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 50% |
| cards | 0px |
| buttons | 0px |

### Layout

- **Section gap:** 48-80px
- **Element gap:** 8px

## Components

### Ghost Icon Button
**Role:** Icon-only interactive elements in headers/navigation

backgroundColor: rgba(0, 0, 0, 0), color: #25385b, border: none, borderRadius: 50%, padding: 0px.

### Outlined Text Button
**Role:** Secondary action buttons, navigation items that appear button-like

backgroundColor: rgba(0, 0, 0, 0), color: #25385b, borderColor: #25385b, border: 1px solid, borderRadius: 0px, padding: 12px 12px.

### Primary Accent Button
**Role:** Prominent calls to action

backgroundColor: #a2b0ff, color: #25385b, border: 1px solid #25385b, borderRadius: 0px, padding: 24px 36px.

### Text Input Light
**Role:** Form inputs on light backgrounds

backgroundColor: rgba(0, 0, 0, 0), color: #25385b, borderBottom: 1px solid #25385b, borderRadius: 0px, paddingTop: 12px, paddingBottom: 12px, paddingLeft: 0px.

### Text Input Dark
**Role:** Form inputs on dark backgrounds

backgroundColor: rgba(0, 0, 0, 0), color: #ffffff, borderBottom: 1px solid #ffffff, borderRadius: 0px, paddingTop: 9px, paddingBottom: 9px, paddingLeft: 0px.

## Do's and Don'ts

### Do
- Use Sharp Grotesk Web for all text elements, prioritizing weights 400 for body, 500 for subheadings, and 700 for headlines.
- Implement the Sky Violet (#25385b) for all primary text and calls to action when on a light background.
- Apply Lavender Mist (#a2b0ff) for primary button backgrounds and interactive highlights, paired with Sky Violet text.
- Maintain the strict use of 0px border-radius for all primary buttons and cards, creating a crisp, intentional contrast with organic product forms.
- Employ the linear-gradient(rgb(236, 245, 246), rgb(235, 235, 253), rgb(251, 206, 205)) for large background sections to establish the 'cloud dreamscape' atmosphere.
- Utilize 24px 36px padding for prominent CTA buttons to emphasize their importance and provide visual spaciousness.
- Separate interactive elements (buttons, links) with an `elementGap` of 8px for clear distinction.

### Don't
- Avoid using Adobe Blank for any display text; it's a structural element only.
- Do not introduce strong, dark shadows on cards or elevated components; the aesthetic is light and airy.
- Do not use highly saturated colors for large content blocks; reserve them for accents and interactive states.
- Do not deviate from the 0px border-radius unless explicitly for a circular icon or a small dot indicator (50%).
- Avoid tight spacing between sections; maintain generous vertical padding (sectionGap: 48-80px) to enhance the feeling of calm and spaciousness.
- Do not use dark backgrounds for body text; Sky Violet (#25385b) on light neutrals (#ffffff, #fffcef) is the standard.
- Refrain from introducing additional typefaces; Sharp Grotesk Web is the sole brand font.

## Imagery

The visual language is product-centric, featuring vibrant, color-rich photographs of Recess cans and powders, often with fresh fruits or natural elements. Products are typically arranged artfully, sometimes with soft, diffuse lighting or against gradient backgrounds that echo the site's pastel palette. Photography is contained within sections, not full-bleed, often complemented by abstract, soft, 3D cloud graphics that float around UI elements, adding a whimsical, dreamlike quality. Icons are minimal, either outline or filled in Sky Violet or Jet Black, maintaining a clean aesthetic. Visuals serve both decorative atmosphere and explicit product showcase functions, occupying significant visual space relative to text to convey an aspirational lifestyle.

## Layout

The page primarily uses a full-bleed structure, particularly in hero sections, with content centered. The hero pattern features a large, often gradient or photographic background with a bold, centered headline and a prominent CTA. Subsequent sections alternate between full-bleed backgrounds (gradients or solid pastel colors) and content-contained rows. Content arrangement frequently uses a centered stack for textual information, transitioning to two-column layouts for image-left/text-right feature presentations. There's a consistent, generous vertical spacing between sections, contributing to an open and spacious feel. Navigation is a sticky top bar, with prominent 'shop' and user login/cart icons.

## Agent Prompt Guide

### Quick Color Reference
- Text: #25385b (Sky Violet)
- Background: #ffffff (Pure White)
- CTA (Primary): #a2b0ff (Lavender Mist)
- Border (Primary): #25385b (Sky Violet)
- Accent (Headline): #3252f4 (Vivid Cobalt)

### Example Component Prompts
1. Create a hero section with the background gradient `linear-gradient(rgb(236, 245, 246), rgb(235, 235, 253), rgb(251, 206, 205))`. Headline text 'relax & unwind with Recess' at 60px, Sharp Grotesk Web weight 700, color #25385b. Subtext 'you won’t miss the booze when you have Recess on hand' at 18px, Sharp Grotesk Web weight 400, color #25385b. Include a 'shop now' button: background #fffcef, text color #25375a, border 1px solid #25375a, 0px border-radius, 24px 36px padding.

2. Generate a 'shop all products' button: background #a2b0ff, text color #25385b, border 1px solid #25385b, 0px border-radius, 24px 36px padding.

3. Design a testimonial card: #ffffff background, 0px border-radius, 28px padding. Text in Sharp Grotesk Web weight 400, 16px, color #25385b. Include two small, abstract, white 3D cloud graphics floating around it.

4. Create a text input: background rgba(0, 0, 0, 0), text color #25385b, 1px solid #25385b bottom border, 0px border-radius, 12px vertical padding, 0px horizontal padding.

## Similar Brands

- **Olipop** — Shares a playful, product-centric e-commerce UI with a bright, welcoming color palette and a focus on lifestyle branding without overt luxury cues.
- **Kin Euphorics** — Similar approach to botanical-infused beverages, reflected in a light, ethereal design that emphasizes calm and well-being through soft colors and modern typography.
- **Dirty Lemon** — Uses a clean, aspirational aesthetic for health drinks, often with stark product photography and a minimalist, almost architectural layout, though Recess is softer.
- **Moon Juice** — Employs a sophisticated yet whimsical aesthetic for wellness products, with a focus on natural ingredients, pastel palettes, and clean, legible typography.
- **Starface** — Shows how a playful, almost childlike aesthetic (through shapes and colors) can be applied to a commercial product effectively, echoing Recess's use of soft forms and inviting hues.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sky-violet: #25385b;
  --color-cloud-indigo: #0a0a3a;
  --color-lavender-mist: #a2b0ff;
  --color-vivid-cobalt: #3252f4;
  --color-candy-apple: #ff5a5a;
  --color-vanilla-cream: #fffcef;
  --color-pure-white: #ffffff;
  --color-jet-black: #000000;
  --color-starlight-gray: #84849c;
  --color-gradient-sky-glow-a: #ecf5f6;
  --gradient-gradient-sky-glow-a: linear-gradient(rgb(236, 245, 246), rgb(235, 235, 253), rgb(251, 206, 205));
  --color-gradient-sky-glow-b: #a2b0ff;
  --gradient-gradient-sky-glow-b: linear-gradient(rgba(162, 176, 255, 0), rgb(236, 245, 246));
  --color-gradient-sky-glow-c: #fbecdc;
  --gradient-gradient-sky-glow-c: linear-gradient(rgb(251, 206, 205), rgba(162, 176, 255, 0));

  /* Typography — Font Families */
  --font-sharp-grotesk-web: 'Sharp Grotesk Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-adobe-blank: 'Adobe Blank', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.63;
  --text-body: 16px;
  --leading-body: 1.38;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.25;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-display: 60px;
  --leading-display: 1;

  /* Typography — Weights */
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
  --spacing-84: 84px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 48-80px;
  --element-gap: 8px;

  /* Named Radii */
  --radius-tags: 50%;
  --radius-cards: 0px;
  --radius-buttons: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sky-violet: #25385b;
  --color-cloud-indigo: #0a0a3a;
  --color-lavender-mist: #a2b0ff;
  --color-vivid-cobalt: #3252f4;
  --color-candy-apple: #ff5a5a;
  --color-vanilla-cream: #fffcef;
  --color-pure-white: #ffffff;
  --color-jet-black: #000000;
  --color-starlight-gray: #84849c;
  --color-gradient-sky-glow-a: #ecf5f6;
  --color-gradient-sky-glow-b: #a2b0ff;
  --color-gradient-sky-glow-c: #fbecdc;

  /* Typography */
  --font-sharp-grotesk-web: 'Sharp Grotesk Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-adobe-blank: 'Adobe Blank', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.63;
  --text-body: 16px;
  --leading-body: 1.38;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.25;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-display: 60px;
  --leading-display: 1;

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
  --spacing-84: 84px;
  --spacing-144: 144px;
}
```
