# Ori — Style Reference
> Dark Command Center

**Theme:** dark

Radiant utilizes a dark command-center aesthetic, combining deep achromatic backgrounds with a single vivid orange accent. Typography is key, featuring a blend of precise monospaced and clean sans-serif fonts, often with subtle negative letter-spacing for a technical feel. Design elements are sharp and angular, with zero border-radius throughout, projecting an image of serious, unyielding infrastructure. Elevation is minimal, relying on strong color contrast rather than shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Core | `#000000` | `--color-midnight-core` | Page backgrounds, primary surface color, text on accent blocks, and dark contrast elements |
| Ghost Canvas | `#f5f5f5` | `--color-ghost-canvas` | Primary text on dark backgrounds, ghost button outlines, inactive navigation items, and very light surface accents |
| Deep Gray | `#1a1a1a` | `--color-deep-gray` | Input backgrounds, subtly elevated card surfaces, and borders for ghost elements that aren't pure black |
| Subtle Ash | `#3c3c3c` | `--color-subtle-ash` | Divider lines, secondary borders, and subtle text elements for minor contrast on dark backgrounds |
| Faded Silver | `#bfbfbf` | `--color-faded-silver` | Muted body text, card content text, and secondary icon colors, providing a softer contrast against dark surfaces |
| Shadow Tone | `#737373` | `--color-shadow-tone` | Tertiary text, copyright information, and subtle link lines |
| Radiant Orange | `#ff4f2b` | `--color-radiant-orange` | Primary action backgrounds, key headlines, active navigation states, and brand highlights. This vivid color provides critical contrast and directs attention |

## Tokens — Typography

### TWK Everett — Headlines, section titles, and any text requiring a bold, impactful presence. The consistent negative letter-spacing creates a dense, modern feel. · `--font-twk-everett`
- **Substitute:** Inter
- **Weights:** 300, 400, 700
- **Sizes:** 24px, 36px, 48px, 60px, 72px, 96px
- **Line height:** 0.95, 1.00, 1.10, 1.20, 1.30
- **Letter spacing:** -0.0110em
- **Role:** Headlines, section titles, and any text requiring a bold, impactful presence. The consistent negative letter-spacing creates a dense, modern feel.

### Switzer — General body text, subheadings, and UI elements. Used for legibility in product descriptions and standard content blocks. · `--font-switzer`
- **Substitute:** Poppins
- **Weights:** 400
- **Sizes:** 16px, 18px
- **Line height:** 1.40
- **Letter spacing:** normal
- **Role:** General body text, subheadings, and UI elements. Used for legibility in product descriptions and standard content blocks.

### Chivo Mono — Used for code snippets, metadata, navigation items, and input text, conveying a technical and precise tone. · `--font-chivo-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.00, 1.20, 1.40
- **Letter spacing:** normal
- **Role:** Used for code snippets, metadata, navigation items, and input text, conveying a technical and precise tone.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1 | — | `--text-caption` |
| body-sm | 16px | 1.4 | — | `--text-body-sm` |
| body | 18px | 1.4 | — | `--text-body` |
| subheading | 24px | 1.2 | -0.264px | `--text-subheading` |
| heading | 36px | 1.1 | -0.396px | `--text-heading` |
| heading-lg | 48px | 1.1 | -0.528px | `--text-heading-lg` |
| display | 96px | 0.95 | -1.056px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 92 | 92px | `--spacing-92` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 48px
- **Card padding:** 20px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Filled button

Solid Radiant Orange background (#ff4f2b) with black (#000000) text. Features 0px border-radius and 16px padding on all sides.

### Ghost Outline Button
**Role:** Secondary action button

Transparent background with a 1px Ghost Canvas (#f5f5f5) border and Ghost Canvas (#f5f5f5) text. Features 0px border-radius and 8px padding on all sides.

### Input Field
**Role:** Form control

Deep Gray (#1a1a1a) background with Ghost Canvas (#f5f5f5) text and 0px border-radius. Padding is 16px on all sides.

### Navigation Link
**Role:** Primary navigation item

Chivo Mono font, 16px, weight 400, Ghost Canvas (#f5f5f5) color. Includes 16px bottom padding, animating to Radiant Orange (#ff4f2b) on hover or active state with a 1px bottom border.

### Feature Card
**Role:** Content container for features or articles

Transparent background with 0px border-radius and no box-shadow. Content within has 20px vertical and 5px horizontal spacing. Text hierarchy uses Faded Silver (#bfbfbf) for body and Ghost Canvas (#f5f5f5) for titles.

### Hero Headline
**Role:** Main page title

TWK Everett, 96px, weight 700, Radiant Orange (#ff4f2b) for primary words, Ghost Canvas (#f5f5f5) for supporting words. Line height 0.95 and letter-spacing -0.011em.

## Do's and Don'ts

### Do
- Prioritize Midnight Core (#000000) as the dominant background for all primary content sections.
- Use Radiant Orange (#ff4f2b) exclusively for primary calls to action, key interactive states, and headline highlights to maintain its high impact.
- Apply 0px border-radius to all UI elements, including buttons, cards, and input fields, for a sharp, angular aesthetic.
- Ensure all body text uses Switzer 400 at 16px or 18px for optimal readability on dark backgrounds.
- Implement TWK Everett with a consistent -0.011em letter-spacing for all headlines and significant display text.
- Utilize Chivo Mono for navigation, labels, and input text to reinforce a technical, precise brand identity.
- Maintain a clear separation between content blocks using the sectionGap of '48px' to ensure comfortable density.

### Don't
- Do not introduce any rounded corners or soft edges on any UI elements; maintain the strict 0px border-radius throughout.
- Avoid using multiple accent colors; Radiant Orange (#ff4f2b) is the sole chromatic identifier.
- Do not apply drop shadows to UI elements; rely on color contrast and subtle borders for perceived depth.
- Do not use generic system fonts; stick to Switzer, TWK Everett, and Chivo Mono as defined.
- Avoid arbitrary letter-spacing changes for TWK Everett; the prescribed -0.011em is critical for its visual character.
- Do not use Ghost Canvas (#f5f5f5) as a background for large sections; reserve it for text and outlines on dark surfaces.
- Never use gradients as backgrounds; the visual system is based on flat, contrasting color blocks.

## Imagery

Imagery consists primarily of dark, mood-setting product photography or abstract visuals, often featuring glowing lines or detailed server racks, conveying a high-tech, infrastructure-focused environment. These visuals are typically full-bleed or large background elements, creating an immersive, dramatic atmosphere. Iconography, when present, is minimalist, outlined, and monochromatic, usually in Ghost Canvas, aligning with the clean, technical aesthetic. The visuals contribute to a text-dominant layout, acting as atmospheric backdrops rather than primary content.

## Layout

The page primarily uses a full-bleed layout with content often contained within implicit vertical guides. The hero section is full-bleed dark with a powerful, asymmetric headline pairing text in Radiant Orange and Ghost Canvas. Sections commonly alternate between solid Midnight Core backgrounds and occasional Radiant Orange highlight blocks. Content arrangement frequently features large centered headlines followed by centered body text, or text-left/image-right configurations. There's a clear vertical rhythm with a '48px' section gap, creating ample breathing room. The navigation is a sticky top bar, minimal and monochromatic with Chivo Mono links.

## Agent Prompt Guide

Quick Color Reference:
text: #f5f5f5
background: #000000
border: no distinct border color
accent: #ff4f2b
primary action: #ff4f2b (filled action)

Example Component Prompts:
1. Create a hero section: Midnight Core (#000000) background. Headline 'We Are Powered Intelligence.' in TWK Everett, 'We Are' in Ghost Canvas (#f5f5f5), 'Powered Intelligence.' in Radiant Orange (#ff4f2b), 96px, weight 700, line-height 0.95, letter-spacing -1.056px for the whole headline. Subtext 'Radiant is the first fully integrated AI infrastructure platform.' in Switzer 18px, weight 400, Ghost Canvas (#f5f5f5).
2. Create a primary action button: Radiant Orange (#ff4f2b) fill, Midnight Core (#000000) text, Chivo Mono 16px, weight 400, 0px radius, 16px padding on all sides, text 'TALK TO AN ARCHITECT'.
3. Create a navigation item: Chivo Mono 16px, weight 400, Ghost Canvas (#f5f5f5) text. On hover, text color changes to Radiant Orange (#ff4f2b) with a 1px Radiant Orange bottom border. Text 'AI Cloud'.
4. Create an input field: Deep Gray (#1a1a1a) background, Ghost Canvas (#f5f5f5) text (Chivo Mono 16px), 0px radius, 16px padding on all sides, 1px Ghost Canvas (#f5f5f5) border.

## Similar Brands

- **Anthropic** — Similar dark theme with a single prominent accent color for primary actions and headlines, conveying a strong, technical brand.
- **NVIDIA** — Employs a precise, almost angular visual language with a focus on high-performance technology, dark backgrounds, and strong typography.
- **Palantir** — Uses dark, technical interfaces with a focus on data and infrastructure, often with a stark contrast between background and informational text.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-core: #000000;
  --color-ghost-canvas: #f5f5f5;
  --color-deep-gray: #1a1a1a;
  --color-subtle-ash: #3c3c3c;
  --color-faded-silver: #bfbfbf;
  --color-shadow-tone: #737373;
  --color-radiant-orange: #ff4f2b;

  /* Typography — Font Families */
  --font-twk-everett: 'TWK Everett', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chivo-mono: 'Chivo Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --text-body: 18px;
  --leading-body: 1.4;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.264px;
  --text-heading: 36px;
  --leading-heading: 1.1;
  --tracking-heading: -0.396px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.528px;
  --text-display: 96px;
  --leading-display: 0.95;
  --tracking-display: -1.056px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-92: 92px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 20px;
  --element-gap: 16px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-core: #000000;
  --color-ghost-canvas: #f5f5f5;
  --color-deep-gray: #1a1a1a;
  --color-subtle-ash: #3c3c3c;
  --color-faded-silver: #bfbfbf;
  --color-shadow-tone: #737373;
  --color-radiant-orange: #ff4f2b;

  /* Typography */
  --font-twk-everett: 'TWK Everett', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chivo-mono: 'Chivo Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1;
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --text-body: 18px;
  --leading-body: 1.4;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.264px;
  --text-heading: 36px;
  --leading-heading: 1.1;
  --tracking-heading: -0.396px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.528px;
  --text-display: 96px;
  --leading-display: 0.95;
  --tracking-display: -1.056px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-92: 92px;
  --spacing-180: 180px;
}
```
