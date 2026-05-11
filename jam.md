# Jam — Style Reference
> Midnight command center, softly glowing

**Theme:** dark

Jam's aesthetic is a 'developer's command center' — a dark, subdued interface with cool gray and violet tones providing a focused workspace. Typography is compact and precise, minimizing visual noise. A vibrant green accent color serves as a functional 'on' switch, highlighting critical actions and active states. Surfaces are subtly layered with soft, rounded corners, creating a sense of approachability within the dark theme.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#130f18` | `--color-midnight-ink` | Page background, primary text (dark theme), form field borders, subtle card borders |
| Deep Plum | `#21192a` | `--color-deep-plum` | Card backgrounds, secondary surface elevation, primary navigation background |
| Moonless Slate | `#25292e` | `--color-moonless-slate` | Subtle decorative fills, minor navigation elements |
| Cloud Gray | `#e5e7eb` | `--color-cloud-gray` | Light text on dark backgrounds, primary borders, input field borders |
| Fog Whisper | `#8b94a3` | `--color-fog-whisper` | Secondary text, link text, icon fills |
| Pure White | `#ffffff` | `--color-pure-white` | Strong contrasting text on dark backgrounds, section titles, icon fills |
| Electric Green | `linear-gradient(90deg, rgb(255, 255, 255) 0px, rgb(115, 229, 191) 30%)` | `--color-electric-green` | Green text accent for links, tags, and emphasized short phrases; Subtle background gradient for hero elements or special features; Vibrant secondary gradient for decorative backgrounds or graphical elements |
| Royal Violet | `#744ec2` | `--color-royal-violet` | Decorative card backgrounds, accent fills |
| Soft Amethyst | `#947fac` | `--color-soft-amethyst` | Muted icon details, subtle text accents |
| Lavender Mist | `#b89fd4` | `--color-lavender-mist` | Heading accents on dark backgrounds, specific body text highlights |
| Deep Aubergine | `#252542` | `--color-deep-aubergine` | Muted text, subtle decorative borders, code block text |
| Vivid Grape | `#a37af5` | `--color-vivid-grape` | Icon strokes and fills, emphasized body text for key features |
| Glowing Mint | `#c5ffe7` | `--color-glowing-mint` | Green supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Crimson Beam | `#ff4070` | `--color-crimson-beam` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Purple to Pink Gradient | `linear-gradient(to right, rgb(164, 123, 244), rgb(237, 78, 140))` | `--color-purple-to-pink-gradient` | Tertiary decorative gradient, often used for subtle shifts |

## Tokens — Typography

### SF Pro Text — Primary UI font for body text, navigation, buttons, and form elements. Its compact nature supports the focused, information-dense dark theme. · `--font-sf-pro-text`
- **Substitute:** Segoe UI, Arial, sans-serif
- **Weights:** 400, 500, 600, 700, 900
- **Sizes:** 11px, 12px, 13px, 14px, 15px, 16px, 24px
- **Line height:** 1.00, 1.25, 1.33, 1.43, 1.50
- **Letter spacing:** -0.025
- **Role:** Primary UI font for body text, navigation, buttons, and form elements. Its compact nature supports the focused, information-dense dark theme.

### Oldschool Grotesk — Display font used for large, impactful headlines and key branding text. Its heavy weight and large scale create immediate visual presence against the dark background. · `--font-oldschool-grotesk`
- **Substitute:** Impact, sans-serif
- **Weights:** 400, 900
- **Sizes:** 8px, 12px, 16px, 66px, 88px, 116px
- **Line height:** 1.00, 1.10, 1.50
- **Letter spacing:** 0
- **Role:** Display font used for large, impactful headlines and key branding text. Its heavy weight and large scale create immediate visual presence against the dark background.

### SF Mono — Monospaced font for code snippets, technical details, and certain data displays, maintaining alignment and readability for developers. · `--font-sf-mono`
- **Substitute:** Courier New, monospace
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.50
- **Letter spacing:** 0
- **Role:** Monospaced font for code snippets, technical details, and certain data displays, maintaining alignment and readability for developers.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1 | — | `--text-caption` |
| body | 14px | 1.43 | -0.025px | `--text-body` |
| heading | 24px | 1 | -0.025px | `--text-heading` |
| heading-lg | 66px | 1.1 | — | `--text-heading-lg` |
| display | 116px | 1.1 | — | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 196 | 196px | `--spacing-196` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| pills | 9999px |
| buttons | 12px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(19, 15, 24, 0.1) 0px 0px 0px 2px, rgba(115, 229, 191...` | `--shadow-subtle` |
| subtle-2 | `rgb(197, 255, 231) 0px 1px 1px 0px inset` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 48px
- **Card padding:** 40px
- **Element gap:** 16px

## Components

### Ghost Navigation Button (Text)
**Role:** Navigation and secondary actions

Transparent background, text color is Fog Whisper (#8b94a3). No border, 8px vertical padding, 0px horizontal padding. Uses SF Pro Text, 14px, weight 400.

### Feature Tag Button (Outlined)
**Role:** Informational tags and selectable filters

Transparent background, text color is Deep Aubergine (#252542). Border color is Cloud Gray (#e5e7eb) and 12px border radius. No horizontal or vertical padding set on the button itself; internal padding will be nested. Uses SF Pro Text, 13px.

### Primary Action Button
**Role:** Main call-to-action

Background is Electric Green (#73e5bf) with white text Pure White (#ffffff). Has a subtle inset shadow (rgb(197, 255, 231) 0px 1px 1px 0px inset) and a prominent box shadow (rgba(19, 15, 24, 0.1) 0px 0px 0px 2px, rgba(115, 229, 191, 0.2) 0px 20px 25px -5px, rgba(115, 229, 191, 0.2) 0px 8px 10px -6px). Border radius 12px. Uses SF Pro Text, 16px.

### Customer Testimonial Card
**Role:** Displaying customer feedback

Background is Deep Plum (#21192a), with a 24px border radius. Padding is 40px on all sides. Uses SF Pro Text for body copy and Oldschool Grotesk for names.

### Highlight Feature Card
**Role:** Highlighting key features or product aspects

Background can be Royal Violet (#744ec2), with a 9999px border radius (pill shape). These are often tightly contained and used for visual emphasis without text content itself. Padding is 0px.

### UI Control Card
**Role:** Interactive panels within the application UI (e.g., bug reporting module)

Pure White (#ffffff) background with a 12px border radius. No box shadow, 0px padding. Content within defines its layout.

## Do's and Don'ts

### Do
- Use Midnight Ink (#130f18) for all page backgrounds to maintain the dominant dark theme.
- Apply Deep Plum (#21192a) for card and secondary surface backgrounds, establishing visual hierarchy.
- Highlight primary actions with Electric Green (#73e5bf) as a background, maintaining white text for contrast.
- Employ SF Pro Text for all body copy and most UI elements, reserving Oldschool Grotesk for large impact headlines.
- Use a specific letter-spacing of -0.025em for SF Pro Text sizes 12px, 13px, 14px, 15px, 16px, and 24px.
- Set the default border-radius to 8px, using 24px for larger cards and 9999px for pill-shaped elements.
- Utilize Cloud Gray (#e5e7eb) for primary borders and dividers to softly separate content.

### Don't
- Avoid using saturated colors for large background areas; they should appear as functional accents only.
- Do not deviate from the SF Pro Text and Oldschool Grotesk font combination; introduce no new sans-serif typefaces.
- Never use generic square corners; all interactive and surface elements should have at least an 8px border radius.
- Do not use dark text on dark backgrounds without sufficient contrast; ensure text colors like Fog Whisper (#8b94a3) are used on surfaces like Deep Plum (#21192a), or Pure White (#ffffff) on Midnight Ink (#130f18).
- Avoid using a hard drop shadow for elevation; instead, use the subtle green-tinted shadows or inset highlights provided.
- Do not overcrowd sections; maintain a comfortable density with a minimum element gap of 16px and card padding of 40px.
- Do not use standard blue for links; default to Fog Whisper (#8b94a3) for inactive links and potentially Electric Green (#73e5bf) for active or primary links.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas | `#130f18` | Primary page background |
| 2 | Card Base | `#21192a` | Card and secondary container backgrounds |
| 3 | Elevated UI | `#ffffff` | Interactive UI panels and complex components (e.g., bug report modal) |

## Elevation

- **Primary Action Button:** `rgba(19, 15, 24, 0.1) 0px 0px 0px 2px, rgba(115, 229, 191, 0.2) 0px 20px 25px -5px, rgba(115, 229, 191, 0.2) 0px 8px 10px -6px`
- **Active Input / Focus State:** `rgb(197, 255, 231) 0px 1px 1px 0px inset`

## Imagery

The visual language predominantly features clean, product-focused screenshots of the Jam UI, typically presented on a subtle dark background or within an elevated UI card. Imagery is highly functional, showcasing the product interface directly rather than abstract concepts. Icons are primarily outlined or ghosted in neutral tones (Fog Whisper) with occasional fills in accent colors like Vivid Grape or Electric Green for emphasis. Illustrations are minimal, with a few instances of abstract, colorful gradients or simple geometric shapes used decoratively, providing visual interest without distracting from the UI. The density is moderate, balancing text-heavy sections with contained product visuals.

## Layout

The page primarily uses a full-bleed dark background, with content centered within a logical maximum width. The hero section features a large, off-center product screenshot or GIF against the dark canvas, anchored by a prominent headline. Sections are defined by consistent vertical spacing (sectionGap 48px) rather than hard dividers, creating a seamless flow. Content frequently alternates between stacked centered elements and two-column layouts featuring text on one side and product visuals or abstract graphics on the other. A card grid is used for testimonials, employing 24px rounded cards with 40px internal padding. The navigation is a fixed top bar on the dark canvas, minimal and always visible. Overall, the layout prioritizes clarity and a focused presentation, avoiding unnecessary visual clutter.

## Agent Prompt Guide

Quick Color Reference:
text: #e5e7eb
background: #130f18
border: #e5e7eb
accent: #73e5bf
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section with a centered headline: 'One click bug reports devs love' in Oldschool Grotesk, 116px, weight 900, Pure White (#ffffff). Below it, a ghost button 'Try Jam MCP' using Fog Whisper (#8b94a3) text, transparent background, and 8px border radius, with 8px vertical padding. The button should have an arrow icon trailing the text.
2. Create a customer testimonial card: Deep Plum (#21192a) background, 24px border radius, 40px all-around padding. Inside, use SF Pro Text, 14px, weight 400, Pure White (#ffffff) for the testimonial text. Below the text, include a customer name in SF Pro Text, 16px, weight 700.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
4. Design a 'feature tag' button: Background transparent, Deep Aubergine (#252542) for text, and a Cloud Gray (#e5e7eb) 1px border with 12px border radius. Text should be SF Pro Text, 13px.

## Similar Brands

- **Linear** — Shares a sophisticated dark mode UI, precise typography with detailed letter-spacing, and a functional accent color to highlight interactive elements.
- **Raycast** — Employs a prominent dark interface, product-focused imagery, and uses a limited, high-contrast color palette, similar to Jam’s approach with Electric Green as an accent.
- **Figma (dark mode)** — Features a utilitarian dark environment, compact UI, and clear information hierarchy enabled by varied text weights and subtle surface elevation.
- **Vercel** — Utilizes a dark, developer-centric aesthetic with clear typography and a focus on product visuals for explanation, rather than decorative imagery.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #130f18;
  --color-deep-plum: #21192a;
  --color-moonless-slate: #25292e;
  --color-cloud-gray: #e5e7eb;
  --color-fog-whisper: #8b94a3;
  --color-pure-white: #ffffff;
  --color-electric-green: #73e5bf;
  --gradient-electric-green: linear-gradient(90deg, rgb(255, 255, 255) 0px, rgb(115, 229, 191) 30%);
  --color-royal-violet: #744ec2;
  --color-soft-amethyst: #947fac;
  --color-lavender-mist: #b89fd4;
  --color-deep-aubergine: #252542;
  --color-vivid-grape: #a37af5;
  --color-glowing-mint: #c5ffe7;
  --color-crimson-beam: #ff4070;
  --color-purple-to-pink-gradient: #a473f4;
  --gradient-purple-to-pink-gradient: linear-gradient(to right, rgb(164, 123, 244), rgb(237, 78, 140));

  /* Typography — Font Families */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-oldschool-grotesk: 'Oldschool Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-mono: 'SF Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.025px;
  --text-heading: 24px;
  --leading-heading: 1;
  --tracking-heading: -0.025px;
  --text-heading-lg: 66px;
  --leading-heading-lg: 1.1;
  --text-display: 116px;
  --leading-display: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-196: 196px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 40px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-pills: 9999px;
  --radius-buttons: 12px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-subtle: rgba(19, 15, 24, 0.1) 0px 0px 0px 2px, rgba(115, 229, 191, 0.2) 0px 20px 25px -5px, rgba(115, 229, 191, 0.2) 0px 8px 10px -6px;
  --shadow-subtle-2: rgb(197, 255, 231) 0px 1px 1px 0px inset;

  /* Surfaces */
  --surface-canvas: #130f18;
  --surface-card-base: #21192a;
  --surface-elevated-ui: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #130f18;
  --color-deep-plum: #21192a;
  --color-moonless-slate: #25292e;
  --color-cloud-gray: #e5e7eb;
  --color-fog-whisper: #8b94a3;
  --color-pure-white: #ffffff;
  --color-electric-green: #73e5bf;
  --color-royal-violet: #744ec2;
  --color-soft-amethyst: #947fac;
  --color-lavender-mist: #b89fd4;
  --color-deep-aubergine: #252542;
  --color-vivid-grape: #a37af5;
  --color-glowing-mint: #c5ffe7;
  --color-crimson-beam: #ff4070;
  --color-purple-to-pink-gradient: #a473f4;

  /* Typography */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-oldschool-grotesk: 'Oldschool Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-mono: 'SF Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.025px;
  --text-heading: 24px;
  --leading-heading: 1;
  --tracking-heading: -0.025px;
  --text-heading-lg: 66px;
  --leading-heading-lg: 1.1;
  --text-display: 116px;
  --leading-display: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-196: 196px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(19, 15, 24, 0.1) 0px 0px 0px 2px, rgba(115, 229, 191, 0.2) 0px 20px 25px -5px, rgba(115, 229, 191, 0.2) 0px 8px 10px -6px;
  --shadow-subtle-2: rgb(197, 255, 231) 0px 1px 1px 0px inset;
}
```
