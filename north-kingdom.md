# North Kingdom — Style Reference
> Cinematic Night Canvas

**Theme:** dark

North Kingdom presents a dark, cinematic brand experience that marries deep, dark backgrounds with sharp, white typography. The design emphasizes content through dramatic scaling of text and minimal UI elements, creating a focused, immersive feel. Surface treatments are largely flat with subtle layering, relying on bold text and large visuals to convey impact rather than intricate component styling. Typography carries significant weight in establishing brand presence, particularly in prominent headlines.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#050311` | `--color-midnight-ink` | Page and section backgrounds, dark surface base, subtle border accents for text elements |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text, headers, interactive elements, navigation links, button outlines — serves as the dominant foreground color against dark backgrounds |
| Pitch Black | `#000000` | `--color-pitch-black` | Card backgrounds, secondary surface accents, contrast for specific button text |
| Dusty Slate | `#9b9aa0` | `--color-dusty-slate` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |

## Tokens — Typography

### FKGroteskNeue — General text, links, body copy, and navigation. Its slightly condensed and tabular figures give a precise, digital aesthetic. · `--font-fkgroteskneue`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 24px
- **Line height:** 1.15, 1.70
- **Letter spacing:** -0.0100em
- **OpenType features:** `"tnum"`
- **Role:** General text, links, body copy, and navigation. Its slightly condensed and tabular figures give a precise, digital aesthetic.

### Arial — Small functional text within buttons and icons, maintaining legibility at compact sizes. · `--font-arial`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Small functional text within buttons and icons, maintaining legibility at compact sizes.

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 10 | 10px | `--spacing-10` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 80 | 80px | `--spacing-80` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| input | 26px |
| buttons | 4px |
| general | 8px |

### Layout

- **Section gap:** 80px
- **Card padding:** 0px
- **Element gap:** 10px

## Components

### Ghost Border Button
**Role:** Interactive element (e.g. video controls)

Transparent background, Ghost White text, 1px Ghost White border, 4px border-radius. Padding is minimal at 7px all around. Used for secondary actions and video player controls.

### Circular Play Button
**Role:** Video player control

Circular button with 50% border-radius, Pitch Black text on a Ghost White background. Minimal padding 1px vertical, 6px horizontal. Primarily used for embedded media playback.

### Muted Ghost Button
**Role:** Tertiary interactive state

Transparent background, muted Ghost White text (60% opacity), minimal padding 1px vertical, 6px horizontal. Used for less prominent actions, like 'Unmute Mute' controls.

### Feature Card
**Role:** Content display

Pitch Black background, 8px border-radius, with no internal padding; content is expected to manage its own spacing. Used to frame large content blocks like project showcases.

### Text Input
**Role:** Form entry

Transparent background, Ghost White text, 1px Ghost White border with a generous 26px border-radius, indicating a pill-shaped input. No internal padding defined at the component level.

### Badge/Label
**Role:** Categorization or decorative text

Transparent background, Ghost White text, no border-radius defined at this level, but has a significant bottom padding of 62px, used possibly for vertically aligning text within a larger layout.

## Do's and Don'ts

### Do
- Use Midnight Ink (#050311) as the default background for most page sections.
- Prioritize Ghost White (#ffffff) for all primary text, headlines, and active interactive elements to ensure high contrast against dark backgrounds.
- Apply 8px border-radius consistently to all cards and significant image containers.
- Enclose all buttons with a 4px border-radius, even when the button implicitly forms a circle.
- Ensure large headlines leverage the FKGroteskNeue font to maintain the distinct heavy yet precise typographic style.
- Maintain a compact element spacing of 10px between minor UI elements to keep information dense.
- Outline all interactive buttons with a Ghost White (#ffffff) border if not using a solid fill.

### Don't
- Avoid using highly saturated accent colors that deviate from the dark, monochrome palette.
- Do not introduce strong shadows or excessive elevation; maintain a generally flat and layered UI aesthetic.
- Do not use generic system fonts for prominent headlines; utilize FKGroteskNeue for brand consistency.
- Avoid large gaps between closely related UI elements; maintain a compact, dense arrangement where appropriate.
- Do not use highly rounded corners for general elements; reserve 26px radius for specific inputs and 4-8px for cards/buttons.
- Do not use standard paragraph spacing for headlines; large headlines are expected to have tight line heights and letter-spacing.
- Avoid full-width content blocks without internal padding; use the specified 140px horizontal padding for content within major sections.

## Imagery

This design system primarily uses captivating, often game-related, conceptual 3D renders or stylized illustrations, frequently presented within hexagonal or irregularly masked cutouts. Images are typically large, serving as focal points rather than decorative backdrops. When photography is used, it often maintains a dark, moody atmosphere with a focus on product or conceptual scenes. Icons are simple, filled, and monochromatic (white against dark), embodying a functional, minimal style. The visual density heavily leans towards large imagery dominating sections, with text supporting the visual impact.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #050311
border: #ffffff
accent: no distinct accent color
primary action: #ffffff (filled action)

Example Component Prompts:
1. Create a Hero Headline: Ghost White (#ffffff) text, using FKGroteskNeue at large sizes (e.g., 96px, 1.15 line height, -0.0100em letter-spacing) against a Midnight Ink (#050311) background. Follow general element spacing guidelines if a visual element is present.
2. Create a Ghost Border Button: Ghost White (#ffffff) text, 1px Ghost White (#ffffff) border, 4px border-radius, with a transparent background. Padding 7px all sides, using FKGroteskNeue font.
3. Create a Feature Card: A Pitch Black (#000000) background, 8px border-radius, with no padding inside. This card should contain a large image or visual element that fills the card from edge to edge.
4. Create a Navigation Link: Ghost White (#ffffff) text, using FKGroteskNeue, letter-spacing -0.0100em, with 24px vertical and horizontal padding around the link if part of a list, against a Midnight Ink (#050311) header background.

## Similar Brands

- **Riot Games** — Uses dark themes with strong typographic branding and cinematic imagery to convey a gaming aesthetic.
- **Unity (website)** — Dark theme, prominent use of 3D renders and strong headlines, minimal UI elements to emphasize content.
- **Epic Games** — Employs dark backgrounds and large, impactful visuals with strong typography to market creative and gaming projects.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #050311;
  --color-ghost-white: #ffffff;
  --color-pitch-black: #000000;
  --color-dusty-slate: #9b9aa0;

  /* Typography — Font Families */
  --font-fkgroteskneue: 'FKGroteskNeue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-sm: 13px;
  --leading-sm: 1.2;
  --text-2xl: 24px;
  --leading-2xl: 1.15;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-80: 80px;
  --spacing-140: 140px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 0px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 26px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-input: 26px;
  --radius-buttons: 4px;
  --radius-general: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #050311;
  --color-ghost-white: #ffffff;
  --color-pitch-black: #000000;
  --color-dusty-slate: #9b9aa0;

  /* Typography */
  --font-fkgroteskneue: 'FKGroteskNeue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-sm: 13px;
  --leading-sm: 1.2;
  --text-2xl: 24px;
  --leading-2xl: 1.15;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-80: 80px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 26px;
  --radius-full: 100px;
}
```
