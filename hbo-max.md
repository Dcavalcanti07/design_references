# HBO Max — Style Reference
> Midnight movie theater

**Theme:** dark

HBO Max presents a cinematic dark mode experience. A deep black canvas provides a dramatic backdrop for content, punctuated by crisp white typography and a vibrant, authoritative blue that guides user actions. Components are minimal, focusing on content with subtle outlines and soft radii. The overall impression is one of sophistication and clarity, optimized for content absorption in a low-light setting.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Abyss | `#000000` | `--color-midnight-abyss` | Primary page background, text color for light surfaces, card backgrounds for content display |
| Silver Moonlight | `#ffffff` | `--color-silver-moonlight` | Primary text color, background for select interactive elements like buttons and cards, essential UI borders |
| Ghostly Gray | `#b8b6bb` | `--color-ghostly-gray` | Secondary text, muted helper text, inactive icon elements, subtle borders |
| Deep Shadow | `#050409` | `--color-deep-shadow` | Subtle elevated surface backgrounds within the dark theme, such as pricing plan cards |
| Steel Accent | `#89868e` | `--color-steel-accent` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Muted Ash | `#999999` | `--color-muted-ash` | Tertiary text for footnotes and legal disclaimers, subtle borders |
| Action Blue | `#3d6a99` | `--color-action-blue` | Primary action button backgrounds, interactive elements, significant borders — signals interactivity and confirmation |
| Link Sky | `#71b8f2` | `--color-link-sky` | Blue text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |
| Dark Overlay | `#0e0a17` | `--color-dark-overlay` | Subtle border for headings and section dividers, almost indistinguishable from the background but provides structure |

## Tokens — Typography

### Max Sans — The primary typeface for all text content. Its clean, modern character, especially at lighter weights like 300, contributes to a legible yet sophisticated aesthetic in a dark environment. The generous letter-spacing at smaller sizes ensures readability, while the tighter spacing at larger sizes maintains a polished feel. · `--font-max-sans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 100, 300, 400, 600, 700
- **Sizes:** 10px, 12px, 13px, 14px, 16px, 18px, 19px, 20px, 24px, 26px, 28px, 35px, 37px, 44px, 56px
- **Line height:** 0.80, 1.00, 1.10, 1.11, 1.20, 1.23, 1.25, 1.35, 1.60, 1.96
- **Letter spacing:** 0.083em for small text (10px, 12px), 0.100em for larger headings and buttons.
- **OpenType features:** `"locl" 0`
- **Role:** The primary typeface for all text content. Its clean, modern character, especially at lighter weights like 300, contributes to a legible yet sophisticated aesthetic in a dark environment. The generous letter-spacing at smaller sizes ensures readability, while the tighter spacing at larger sizes maintains a polished feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.6 | 0.83px | `--text-caption` |
| body | 14px | 1.6 | 0.83px | `--text-body` |
| subheading | 18px | 1.35 | 0.1px | `--text-subheading` |
| heading | 24px | 1.25 | 0.1px | `--text-heading` |
| heading-lg | 35px | 1.11 | 0.1px | `--text-heading-lg` |
| display | 56px | 0.8 | 0.1px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4.5px |
| pills | 100px |
| images | 8px |
| buttons | 8px |

### Layout

- **Page max-width:** 1140px
- **Section gap:** 24px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Filled button for primary calls to action.

Background: Action Blue (#3d6a99). Text: Silver Moonlight (#FFFFFF). Border radius: 8px. Padding: 13px vertical, 24px horizontal. Uses Max Sans 600 at 16px.

### Ghost Action Button
**Role:** Outline button for secondary or tertiary actions, often in areas with dark backgrounds.

Background: transparent. Text: Silver Moonlight (#FFFFFF). Border: 1px solid Silver Moonlight (#FFFFFF). Border radius: 8px. Padding: 10px vertical, 24px horizontal. Uses Max Sans 600 at 16px.

### Text Link Button
**Role:** Minimal interactive element, typically used for navigation or in-line actions within text.

Background: transparent. Text: Silver Moonlight (#FFFFFF). No border or padding beyond text content. Uses Max Sans 600 at 16px.

### White Surface Card
**Role:** Used for content blocks requiring a lighter surface for contrast, such as pricing plans.

Background: Silver Moonlight (#FFFFFF). Border radius: 4.5px. Box shadow: none. Padding: 22.5px vertical, 27px horizontal. Displays dark text.

### Dark Content Card
**Role:** Default card for content presentation, blending into the dark background.

Background: Midnight Abyss (#000000). Border radius: 0px. Box shadow: none. Minimal padding. Displays light text.

### Sign-Up Button (Header)
**Role:** Prominent sign-up call to action in the header.

Background: Silver Moonlight (#FFFFFF). Text: Midnight Abyss (#000000). Border radius: 8px. Padding: 10px vertical, 24px horizontal. Uses Max Sans 600 at 16px.

### Plan Toggle Button
**Role:** Segmented control for switching between monthly/yearly plans.

Background: Midnight Abyss (#000000). Active segment background: Silver Moonlight (#FFFFFF), with Midnight Abyss (#000000) text. Inactive segment text: Ghostly Gray (#b8b6bb). Border radius: 100px. Padding (segments): 10px vertical, 24px horizontal. Uses Max Sans 600 at 16px.

## Do's and Don'ts

### Do
- Prioritize Midnight Abyss (#000000) for all main page backgrounds, establishing a deep dark theme.
- Use Silver Moonlight (#FFFFFF) as the primary text color on dark backgrounds for optimal contrast and readability.
- Apply Action Blue (#3d6a99) for all primary interactive elements, including button backgrounds and significant active states.
- Employ Max Sans weight 300 for headlines to create an understated, refined authority, rather than shouting.
- Maintain an 8px border radius for all buttons and content images to ensure a consistent, softly rounded interaction.
- Use Max Sans with 0.083em letter-spacing for body text (10px, 12px) to enhance legibility on dark backgrounds.
- Structure pricing plan cards with a Silver Moonlight (#FFFFFF) background to visually separate them from the dark surroundings, using 4.5px border radius.

### Don't
- Avoid using bright, high-saturation colors for large background areas; limit chromatic colors to accents and interactive elements.
- Do not use generic system fonts; always specify Max Sans with its custom weights and letter-spacing for brand consistency.
- Never use dark text on dark backgrounds; ensure sufficient contrast with Silver Moonlight (#FFFFFF) on Midnight Abyss (#000000) or Deep Shadow (#050409).
- Avoid excessive use of outlines or borders on cards; prefer subtle background changes or elevation for visual hierarchy.
- Do not use letter-spacing: normal on smaller font sizes; apply the specified 0.083em for enhanced readability.
- Resist adding strong box shadows; the design relies on flat surfaces and minimal elevation for depth.
- Do not vary border radii arbitrarily; adhere strictly to 8px for buttons/images and 4.5px for cards.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Abyss | `#000000` | Base page canvas, content card background. |
| 1 | Deep Shadow | `#050409` | Slightly elevated surface, for contextual grouping like pricing plan containers or secondary content blocks. |
| 2 | Silver Moonlight | `#ffffff` | Prominent background for specific UI elements that require high contrast, such as pricing plan cards or primary sign-up buttons. |

## Imagery

The site heavily relies on product imagery in the form of movie and TV show posters. These are treated as full-bleed, almost wallpaper-like backgrounds in the hero section, creating an immersive, cinematic atmosphere. Elsewhere, they appear as contained, slightly rounded (8px radius) thumbnails within dark content cards. The visual style of these images is diverse, reflecting the content, but they are consistently presented against a dark backdrop to keep the UI from competing. Icons are minimal, monochromatic (usually white or light gray) and primarily functional, with an occasional accent blue.

## Layout

The page primarily uses a max-width 1140px centered layout for most content sections, ensuring readability and focus. The hero section is full-bleed, showcasing large-scale content posters as an immersive background for an impactful first impression. Sections often have a consistent vertical rhythm due to a 24px section gap. Content arrangement frequently features centered stacked blocks for headlines and calls to action, particularly in introductory or promotional areas. Pricing plans are presented in a 3-column card grid, which adapts to a single column on smaller viewports. Navigation is a sticky top bar with minimal links and prominent sign-in/sign-up buttons.

## Agent Prompt Guide

Quick Color Reference: 
- text: #FFFFFF
- background: #000000
- border: #B8B6BB
- accent: #3D6A99
- primary action: #3d6a99 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #3d6a99 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a pricing plan card: White Surface Card with 'Basic with Ads' as headline (Max Sans 19px weight 600, Midnight Abyss #000000). Body text in Midnight Abyss #000000, 14px Max Sans. Include a 'Select Plan' Primary Action Button at the bottom.
- Create a navigation bar: Dark background (#000000). 'Sign In' ghost action button (Silver Moonlight #FFFFFF text), and 'Sign Up Now' button (Silver Moonlight #FFFFFF background, Midnight Abyss #000000 text), both 8px radius. Text in Max Sans 16px weight 600.

## Similar Brands

- **Netflix** — Dark-mode UI with a focus on large content imagery, minimal text, and high-contrast calls to action.
- **Disney+** — Content-driven dark theme, emphasizing poster artwork as visual elements within a structured grid layout.
- **Apple TV+** — Uses a dark background to highlight visual content, with crisp white typography and subtle interactive elements.
- **Peacock** — Media streaming service with a dark interface, legible white text, and a distinct primary accent color for actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-abyss: #000000;
  --color-silver-moonlight: #ffffff;
  --color-ghostly-gray: #b8b6bb;
  --color-deep-shadow: #050409;
  --color-steel-accent: #89868e;
  --color-muted-ash: #999999;
  --color-action-blue: #3d6a99;
  --color-link-sky: #71b8f2;
  --color-dark-overlay: #0e0a17;

  /* Typography — Font Families */
  --font-max-sans: 'Max Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.6;
  --tracking-caption: 0.83px;
  --text-body: 14px;
  --leading-body: 1.6;
  --tracking-body: 0.83px;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --tracking-subheading: 0.1px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: 0.1px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: 0.1px;
  --text-display: 56px;
  --leading-display: 0.8;
  --tracking-display: 0.1px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
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
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-96: 96px;

  /* Layout */
  --page-max-width: 1140px;
  --section-gap: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4.5px;
  --radius-lg: 8px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 4.5px;
  --radius-pills: 100px;
  --radius-images: 8px;
  --radius-buttons: 8px;

  /* Surfaces */
  --surface-midnight-abyss: #000000;
  --surface-deep-shadow: #050409;
  --surface-silver-moonlight: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-abyss: #000000;
  --color-silver-moonlight: #ffffff;
  --color-ghostly-gray: #b8b6bb;
  --color-deep-shadow: #050409;
  --color-steel-accent: #89868e;
  --color-muted-ash: #999999;
  --color-action-blue: #3d6a99;
  --color-link-sky: #71b8f2;
  --color-dark-overlay: #0e0a17;

  /* Typography */
  --font-max-sans: 'Max Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.6;
  --tracking-caption: 0.83px;
  --text-body: 14px;
  --leading-body: 1.6;
  --tracking-body: 0.83px;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --tracking-subheading: 0.1px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: 0.1px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: 0.1px;
  --text-display: 56px;
  --leading-display: 0.8;
  --tracking-display: 0.1px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-md: 4.5px;
  --radius-lg: 8px;
  --radius-full: 100px;
}
```
