# Evergreen — Style Reference
> Warm parchment, dark ink, verdant accent

**Theme:** light

Evergreen's visual system evokes a natural, grounded feel with a dominant warm, off-white canvas and dark, authoritative text. The interface maintains a spacious rhythm, using broad sections of soft background colors, rather than strong dividers. Typography is confident and editorial, with a custom headline font providing gravitas, while interactions are punctuates by a subtle, verdant green.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Rich Earth | `#000000` | `--color-rich-earth` | Primary text, headline text, action buttons — a deep, grounding black that provides strong contrast |
| Parchment | `#edede2` | `--color-parchment` | Page background, main canvas |
| Cloud Whisper | `#ffffff` | `--color-cloud-whisper` | Input backgrounds, button text on dark backgrounds, subtle highlights |
| Forest Fern | `#beedc0` | `--color-forest-fern` | Decorative background elements, subtle card surfaces, active states — a muted green that connects to the brand's ecological mission |
| Deep Slate | `#333333` | `--color-deep-slate` | Secondary text, muted links, borders, icon fills — a softer alternative to Rich Earth for less prominent elements |
| Soft Vanilla | `#fffff3` | `--color-soft-vanilla` | Card backgrounds, elevated container surfaces — a warm, creamy off-white |

## Tokens — Typography

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.6
- **Role:** Arial — detected in extracted data but not described by AI

### ivypresto-headline — Main headlines and prominent display text: the weight 600 combined with generous line height creates an editorial, luxurious feel, drawing immediate attention with a classic serif presence. · `--font-ivypresto-headline`
- **Substitute:** Playfair Display
- **Weights:** 600
- **Sizes:** 54px, 74px
- **Line height:** 1.40, 1.48, 1.49
- **Role:** Main headlines and prominent display text: the weight 600 combined with generous line height creates an editorial, luxurious feel, drawing immediate attention with a classic serif presence.

### Rubik — Body text, subheadings, interface labels, and buttons: a highly legible sans-serif for functional elements, balancing legibility with a modern, approachable feel at various sizes. · `--font-rubik`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 17px, 18px, 19px, 20px, 21px, 23px, 28px, 30px
- **Line height:** 1.00, 1.41, 1.54, 1.70, 1.90
- **Role:** Body text, subheadings, interface labels, and buttons: a highly legible sans-serif for functional elements, balancing legibility with a modern, approachable feel at various sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.6 | — | `--text-caption` |
| body | 18px | 1.54 | — | `--text-body` |
| subheading | 28px | 1 | — | `--text-subheading` |
| heading | 54px | 1.48 | — | `--text-heading` |
| display | 74px | 1.49 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 24 | 24px | `--spacing-24` |
| 29 | 29px | `--spacing-29` |
| 30 | 30px | `--spacing-30` |
| 36 | 36px | `--spacing-36` |
| 42 | 42px | `--spacing-42` |
| 48 | 48px | `--spacing-48` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| input | 7px |
| links | 30px |
| other | 46px |
| buttons | 40.5px |

### Layout

- **Section gap:** 165px
- **Card padding:** 17px
- **Element gap:** 14px

## Components

### Filled Primary Button
**Role:** Primary calls to action

Filled with Rich Earth (#000000) and Cloud Whisper (#ffffff) text, featuring generous 40.5px border-radius for a soft, approachable pill shape. Padding is 14.4px vertical, 26.4px horizontal.

### Navigation Link Button
**Role:** Secondary calls to action or navigation links within headers

Black text on Parchment (#edede2) background with a 30px border-radius or 10px borderRadius for rounded rectangular action. Padding is 9px vertical, 29.4px horizontal.

### Product Feature Card
**Role:** Highlighting features or testimonials effectively.

Background of Soft Vanilla (#fffff3) with a 10px border-radius. Features 17px padding on horizontal sides for content, and 72px top, 36px bottom.

### Circular Accent Card
**Role:** Decorative elements or image containers.

Forest Fern (#beedc0) background, 100% border-radius to create a perfect circle.

### Text Input Field
**Role:** Forms and data entry.

Cloud Whisper (#ffffff) background with a Rich Earth (#000000) border, 7px 0px 0px 7px border-radius, giving it a soft, slightly asymmetrical rounded left edge. Padding is 0 vertical, 18.9px horizontal.

### Top Banner Alert
**Role:** Important, non-dismissible site-wide messages.

Rich Earth (#000000) background with Cloud Whisper (#ffffff) text (Arial, 14px, 400 weight). Padding 10px vertical.

## Do's and Don'ts

### Do
- Use Parchment (#edede2) as the default page background to maintain the foundational warm, inviting canvas.
- Apply Rich Earth (#000000) for all primary body and headline text to ensure strong contrast and readability.
- Utilize ivypresto-headline (Playfair Display) 600 weight for all major headings to convey an editorial and weighty presence.
- Implement 40.5px border-radius for all primary action buttons for a distinctive pill-like shape.
- Use 'Rubik' (Inter) font for all functional UI elements, body text, and button labels, at various weights from 400 to 700 to provide consistent legibility.
- Incorporate Forest Fern (#beedc0) as a subtle background for decorative cards or callout sections, leveraging its muted green to reinforce brand values.
- Maintain generous vertical spacing (165px) between main content sections to create a spacious and unhurried reading experience.

### Don't
- Avoid harsh white backgrounds; always opt for Soft Vanilla (#fffff3) or Parchment (#edede2) for surfaces and canvas.
- Do not use highly saturated or bright colors for backgrounds or large areas; maintain a muted, natural palette.
- Do not use overly strong shadows; the design relies on subtle background shifts and borders for depth.
- Avoid tight layouts or compact spacing; prioritize breathing room between elements and sections.
- Do not introduce additional font families; adhere strictly to ivypresto-headline (Playfair Display) and Rubik (Inter).
- Never use square, sharp-cornered buttons or cards; maintain the system's characteristic soft, rounded edges.
- Do not use arbitrary padding values; stick to the established system of 14.4px or 9px vertical padding for buttons, and 17px horizontal for cards.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Parchment | `#edede2` | Dominant page background, main canvas. |
| 1 | Soft Vanilla | `#fffff3` | Card backgrounds, elevated content containers. |
| 2 | Cloud Whisper | `#ffffff` | Input fields, foreground elements against Soft Vanilla. |
| 3 | Forest Fern | `#beedc0` | Circular accent cards, decorative background areas for visual interest. |
| 4 | Rich Earth | `#000000` | Top banner background. |

## Imagery

The site uses a combination of subtle illustrations and candid, circular portrait photography. Illustrations appear in muted, natural tones with botanical leaf motifs, often as background elements or borders. Photography consists of single circular headshots, often with a subtle border, placed as decorative accents within text or as avatar representations, rather than full-bleed hero images. Icons are minimalist, monochrome (Deep Slate #333333 or Cloud Whisper #ffffff on Rich Earth #000000) and functional. The overall visual language is light with a focus on human connection and nature.

## Layout

The site uses a mostly full-bleed layout for background elements, but content is typically contained with a subtle max-width and centered alignment. The hero section features a centered headline over the Parchment (#edede2) background, complemented by circular portrait photography. Main content sections alternate between the primary Parchment background and sections with soft, decorative Forest Fern (#beedc0) accents or the richer purple of the integration sidebar. Vertical spacing between these sections is notably generous at 165px, creating a relaxed, spacious rhythm. Content often appears in single-column stacks or simple two-column layouts, with elements such as feature cards or user recognition flows, enhancing readability and minimizing visual clutter. Navigation is a standard top bar, with prominent branding and a rounded action button.

## Agent Prompt Guide

**Quick Color Reference**
text: #000000
background: #edede2
border: #333333
accent: #beedc0
primary action: #000000 (filled action)

**3-5 Example Component Prompts**
1. Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a feature card: Soft Vanilla (#fffff3) background, 10px radius, 17px horizontal padding (72px top, 36px bottom). Headline in Rich Earth (#000000) with Rubik 28px, 600 weight. Body text in Deep Slate (#333333) with Rubik 18px, 400 weight.
3. Design a navigation bar: Parchment (#edede2) background. Left aligned 'Evergreen' logo (Deep Slate #333333). Right aligned navigation links: Deep Slate (#333333) text (Rubik, 17px, 400 weight), element gap 14px. A 'Schedule a demo' Navigation Link Button: Rich Earth (#000000) text (Rubik, 17px, 400 weight), 30px radius, 9px vertical, 29.4px horizontal padding.

## Similar Brands

- **Calm** — Uses a muted, natural color palette dominated by soft greens and earthy tones, creating a tranquil atmosphere.
- **Headspace** — Employs a warm, friendly color scheme with rounded forms and inviting illustrations to convey a gentle, approachable feeling.
- **Mailchimp** — Features a strong, editorial serif font for headlines paired with a clean sans-serif for body text, and a distinctive background color (yellow) that grounds the brand. Also uses pill-shaped buttons.
- **Harvest** — Leverages a pale, almost off-white background and strong, simple typography to convey a sense of calm and focus.
- **Pleo** — Distinctive use of an off-white/light pastel background as canvas with limited, intentional accent colors and large, confident typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-rich-earth: #000000;
  --color-parchment: #edede2;
  --color-cloud-whisper: #ffffff;
  --color-forest-fern: #beedc0;
  --color-deep-slate: #333333;
  --color-soft-vanilla: #fffff3;

  /* Typography — Font Families */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ivypresto-headline: 'ivypresto-headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rubik: 'Rubik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --text-body: 18px;
  --leading-body: 1.54;
  --text-subheading: 28px;
  --leading-subheading: 1;
  --text-heading: 54px;
  --leading-heading: 1.48;
  --text-display: 74px;
  --leading-display: 1.49;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-42: 42px;
  --spacing-48: 48px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-72: 72px;

  /* Layout */
  --section-gap: 165px;
  --card-padding: 17px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-lg: 10px;
  --radius-3xl: 30px;
  --radius-3xl-2: 40.5px;
  --radius-3xl-3: 46px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-input: 7px;
  --radius-links: 30px;
  --radius-other: 46px;
  --radius-buttons: 40.5px;

  /* Surfaces */
  --surface-parchment: #edede2;
  --surface-soft-vanilla: #fffff3;
  --surface-cloud-whisper: #ffffff;
  --surface-forest-fern: #beedc0;
  --surface-rich-earth: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-rich-earth: #000000;
  --color-parchment: #edede2;
  --color-cloud-whisper: #ffffff;
  --color-forest-fern: #beedc0;
  --color-deep-slate: #333333;
  --color-soft-vanilla: #fffff3;

  /* Typography */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ivypresto-headline: 'ivypresto-headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rubik: 'Rubik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --text-body: 18px;
  --leading-body: 1.54;
  --text-subheading: 28px;
  --leading-subheading: 1;
  --text-heading: 54px;
  --leading-heading: 1.48;
  --text-display: 74px;
  --leading-display: 1.49;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-42: 42px;
  --spacing-48: 48px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-72: 72px;

  /* Border Radius */
  --radius-md: 7px;
  --radius-lg: 10px;
  --radius-3xl: 30px;
  --radius-3xl-2: 40.5px;
  --radius-3xl-3: 46px;
}
```
