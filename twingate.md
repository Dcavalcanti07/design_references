# Twingate — Style Reference
> Midnight Terminal, Pulsing Neon. A dark, digital interface illuminated by precise, electric glows.

**Theme:** dark

This system projects an image of controlled innovation, like a high-tech console in a dimly lit server room. Dark, near-black surfaces create a sophisticated backdrop for critical information, highlighted by precise, vibrant accents. The interplay between the whispering 'TT Hoves Light' headlines and the sharp, functional 'TT Hoves Medium' body copy establishes a tone of serious capability. Strategic splashes of saturated violet and vivid green draw attention to key interactive elements and provide a subtle, energetic flicker against the subdued palette.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon | `#0e0f11` | `--color-carbon` | Primary background for pages and main content areas, providing a deep, consistent canvas for the UI. |
| Basalt | `#141617` | `--color-basalt` | Background for certain elevated components and sections, creating subtle depth against the Carbon base. |
| Obsidian | `#1d2023` | `--color-obsidian` | Background for secondary elements and interactive components, offering a slightly lighter dark tone. |
| Platinum | `#ffffff` | `--color-platinum` | Primary text color for headings and key information against dark backgrounds, ensuring high contrast and immediate legibility. |
| Graphite | `#a1a1aa` | `--color-graphite` | Secondary text color, subtle links, and supporting descriptive text, providing contrast without visual dominance. |
| Ash | `#cfcfd3` | `--color-ash` | Tertiary text and subtle distinctions, used for less prominent information or disabled states. |
| Spectral Violet | `#b6abff` | `--color-spectral-violet` | Primary interactive accent color for CTA buttons, active states, and highlighted elements — adding an authoritative yet inviting feel. |
| Electric Lime | `#eef35f` | `--color-electric-lime` | Secondary accent color for spotlighting headlines, badges, or specific product features, signaling innovation and freshness. |
| System Teal | `#00cbaa` | `--color-system-teal` | Used for specific body text elements and borders, offering a cool, technical highlight. |
| Deep Violet | `#6350dd` | `--color-deep-violet` | Background for certain decorative elements or internal blocks. |

## Tokens — Typography

### TT Hoves Light — Headlines and display text. The distinctive light weights at large sizes create an impression of quiet authority and modern elegance, contrasting with the often bolder choices of competitors. This 'whisper, don't shout' approach is a core brand identifier. · `--font-tt-hoves-light`
- **Substitute:** Open Sans Light
- **Weights:** 300, 400
- **Sizes:** 22px, 24px, 48px, 54px, 55px, 62px, 68px
- **Line height:** 1.10, 1.20, 1.30, 1.50
- **Letter spacing:** -0.018em at 68px, -0.016em at 62px, -0.010em at 54px/55px, -0.009em at 48px, -0.007em at 22px/24px
- **Role:** Headlines and display text. The distinctive light weights at large sizes create an impression of quiet authority and modern elegance, contrasting with the often bolder choices of competitors. This 'whisper, don't shout' approach is a core brand identifier.

### TT Hoves Medium — Sub-headings, prominent body text, and key UI labels. Provides legibility and clear hierarchy due to its moderate weight, supporting the whisper-weight headlines without competing with them. · `--font-tt-hoves-medium`
- **Substitute:** Open Sans Medium
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 13px, 14px, 15px, 16px, 17px, 20px, 32px
- **Line height:** 1.04, 1.12, 1.13, 1.14, 1.20, 1.27, 1.29, 1.50
- **Letter spacing:** -0.020em at 12px, -0.010em at 14px, 0.012em at 11, 0.023em at 13px
- **Role:** Sub-headings, prominent body text, and key UI labels. Provides legibility and clear hierarchy due to its moderate weight, supporting the whisper-weight headlines without competing with them.

### TT Hoves Regular — Standard body text, descriptive copy, and general UI elements. Its neutrality ensures readability for extended passages. · `--font-tt-hoves-regular`
- **Substitute:** Open Sans Regular
- **Weights:** 400
- **Sizes:** 11px, 12px, 14px, 15px, 16px, 17px
- **Line height:** 1.14, 1.20, 1.31, 1.50, 1.70
- **Letter spacing:** -0.010em at 16px, 0.014em at 12px
- **Role:** Standard body text, descriptive copy, and general UI elements. Its neutrality ensures readability for extended passages.

### Basis Grotesque Mono Pro Medium — Used for code snippets, technical details, or unique data representations, leveraging a mono typeface for clarity and distinction. · `--font-basis-grotesque-mono-pro-medium`
- **Substitute:** IBM Plex Mono Medium
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.50
- **Role:** Used for code snippets, technical details, or unique data representations, leveraging a mono typeface for clarity and distinction.

### Basis Grotesque Mono Pro Regular — Complementary to the Medium weight mono font, used for inline code or smaller technical annotations. · `--font-basis-grotesque-mono-pro-regular`
- **Substitute:** IBM Plex Mono Regular
- **Weights:** 400
- **Sizes:** 13px, 21px
- **Line height:** 1.20, 1.60
- **Role:** Complementary to the Medium weight mono font, used for inline code or smaller technical annotations.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.14 | — | `--text-caption` |
| body | 16px | 1.7 | -0.16px | `--text-body` |
| subheading | 22px | 1.3 | -0.154px | `--text-subheading` |
| heading-sm | 32px | 1.27 | — | `--text-heading-sm` |
| heading | 48px | 1.2 | -0.432px | `--text-heading` |
| heading-lg | 54px | 1.1 | -0.54px | `--text-heading-lg` |
| display | 68px | 1.1 | -1.224px | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 20px |
| cards | 12px |
| buttons | 50px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.1) 0px 0px 0px 0.5px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(255, 255, 255, 0.1) 0px 2.5px 0px -2px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgb(58, 61, 64) 0px 0px 0px 0.5px` | `--shadow-subtle-3` |
| subtle-4 | `rgb(48, 52, 56) 0px 0px 0px 0.5px` | `--shadow-subtle-4` |
| subtle-5 | `rgba(255, 255, 255, 0.15) 0px 2.5px 0px -2px inset, rgba(...` | `--shadow-subtle-5` |

### Layout

- **Section gap:** 80px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Primary CTA Button
**Role:** Key interaction for conversions

Background: Spectral Violet (#b6abff), Text: Platinum (#ffffff), Padding: 0px vertical, 14px horizontal. Border Radius: 50px. Subtle inset shadow rgba(255, 255, 255, 0.1) 0px 2.5px 0px -2px.

### Secondary CTA Button (Outlined)
**Role:** Alternative call to action, less prominent than primary

Background: Carbon Light (rgba(245, 245, 255, 0.1)), Text: Platinum (#ffffff), Border color: Spectral Violet (#b6abff), Border Radius: 50px, Padding: 0px vertical, 14px horizontal.

### Tertiary CTA Button (Ghost)
**Role:** Further action, or navigation, minimal visual weight

Background: Transparent, Text: Platinum (#ffffff), Border color: Transparent, Border Radius: 50px, Padding: 0px vertical, 14px horizontal. Text has an underline effect that appears on hover/active state (implied by `color=rgb(0,0,238)` in data).

### Feature Tag Button
**Role:** Small, informative labels or interactive filters

Background: Obsidian (#1d2023), Text: Platinum (#ffffff). Border Radius: 20px, Padding: 4px vertical, 14px horizontal.

### Hero Headline
**Role:** Primary page title

Font: TT Hoves Light, Weight: 300, Size: 68px, Line-height: 1.1, Letter-spacing: -0.018em. Color: Electric Lime (#eef35f) or Platinum (#ffffff) for emphasis.

### Body Text
**Role:** Standard paragraph text

Font: TT Hoves Regular, Weight: 400, Size: 16px, Line-height: 1.7. Color: Graphite (#a1a1aa).

### Navigation Link
**Role:** Primary site navigation items

Font: TT Hoves Regular, Weight: 400, Size: 14px, Line-height: 1.5. Color: Platinum (#ffffff). Hover/active state involves a subtle text color change or underline.

## Do's and Don'ts

### Do
- Prioritize the TT Hoves Light font (weights 300, 400) for all major headlines (48px and above) to maintain the signature 'whisper-weight' aesthetic.
- Use a color palette anchored in Carbon (#0e0f11) for backgrounds and Platinum (#ffffff) for primary text to ensure consistent dark-mode visuals.
- Apply Spectral Violet (#b6abff) as the primary accent for all interactive elements and high-priority CTAs.
- Employ Electric Lime (#eef35f) specifically for highlighting key words within headlines or for secondary feature spotlighting to create focused impact.
- Round all primary buttons to 50px radius and information tags to 20px radius to maintain a distinctive soft yet technical feel.
- Utilize a baseline of 4px for all spacing units, scaling up in multiples to ensure a comfortable but structured density.
- Implement the subtle inset shadow rgba(255, 255, 255, 0.1) 0px 2.5px 0px -2px for buttons to provide depth without heavy drop shadows.

### Don't
- Avoid using heavy font weights (e.g., 600+) for headlines; the system's identity relies on the lightness of TT Hoves Light.
- Do not introduce new primary accent colors outside of Spectral Violet (#b6abff) and Electric Lime (#eef35f) to prevent diluting brand recognition.
- Refrain from using hard, sharp corners unless explicitly part of a visual component (e.g., specific data visualizations), defaulting to 8px or 12px where appropriate.
- Do not deviate from the established 'Carbon' (#0e0f11) to 'Basalt' (#141617) to 'Obsidian' (#1d2023) dark surface progression for background depth.
- Avoid generic blue for links or interactive elements; all interactive text and borders should default to Spectral Violet (#b6abff) or Platinum (#ffffff).
- Do not use box-shadows that create strong, external elevation; prefer subtle inset shadows or shifts in background color for layering.
- Do not mix 'sans-serif' fonts with 'TT Hoves' for primary content; stick to the specified font system to maintain visual coherence.

## Elevation

- **Card/Container Border:** `rgb(58, 61, 64) 0px 0px 0px 0.5px`
- **Button Inset Shadow:** `rgba(255, 255, 255, 0.1) 0px 2.5px 0px -2px inset`

## Imagery

The visual language focuses on abstract, geometric diagrams and stylized product screenshots, rather than photography. These graphics often feature a monochrome (Carbon/Platinum) base with glowing highlights in System Teal (#00cbaa) or Spectral Violet (#b6abff), emphasizing connectivity, security, and data flow. Icons are outlined, with a moderate stroke weight, and monochromatic or tinted to match the accent colors. Full-bleed backgrounds carry abstract patterns subtly. Imagery functions primarily to explain complex concepts and to visually reinforce the brand's technical and secure identity, rather than decorative purposes. There's a minimal use of real-world imagery, prioritizing UI and conceptual diagrams.

## Layout

The layout is primarily centered and contained, with a clear max-width for content blocks, creating a structured and information-focused presentation. The hero section is full-bleed, featuring a dark background with a prominent, left-aligned headline and a stylized product graphic on the right. Content sections generally alternate between text-heavy and visual-heavy arrangements, often with two-column split layouts (text left, image right, or vice-versa). Vertical spacing between sections is generous and consistent, creating clear breaks. A sticky top navigation bar provides constant access to primary links and CTAs. Feature sections often employ multi-column grids (e.g., 3-column cards for benefits or testimonials) within the contained width.

## Agent Prompt Guide

### Quick Color Reference
- Text: #ffffff
- Background: #0e0f11
- CTA: #b6abff
- Border: #a1a1aa
- Accent: #eef35f

### 3-5 Example Component Prompts
1. Create a hero section: background #0e0f11. Left side has a headline 'Security, Performance, Simplicity. Pick Three.' using TT Hoves Light weight 300, size 68px, #eef35f, letter-spacing -1.224px. Below is body text 'Identity-based access for users...' using TT Hoves Regular, weight 400, size 16px, #a1a1aa, line-height 1.7. Below are two buttons: 'Try Twingate' (#b6abff background, #ffffff text, 50px radius, 0px 14px padding) and 'Request a Demo' (transparent background, #b6abff text, 50px radius, 0px 14px padding, border #b6abff).
2. Generate a feature card: background #141617, 12px border radius. Title 'Zero Trust Network Access' using TT Hoves Medium, weight 500, size 22px, #ffffff. Body text 'Remote access built...' using TT Hoves Regular, weight 400, size 16px, #a1a1aa.
3. Design a header navigation bar: background solid #0e0f11. Logo 'Twingate' is #ffffff. Nav links 'Product', 'Docs', 'Customers' use TT Hoves Regular, weight 400, size 14px, #ffffff. Right side has a 'Request Demo' button (transparent background, #b6abff text, 50px radius, 0px 14px padding, border #b6abff) and 'Try for Free' button (#b6abff background, #ffffff text, 50px radius, 0px 14px padding).
4. Create a small informational badge: background #1d2023, 20px border-radius. Text 'New Twingate MSP Portal' using TT Hoves Medium, weight 500, size 13px, #ffffff. Padding 4px vertical, 14px horizontal.

## Similar Brands

- **Linear** — Uses dark surfaces with vibrant single-color accents for interactivity and status, coupled with light, airy typography for headlines.
- **Vercel** — Employs a sophisticated dark theme with subtle elevation via background shifts, geometric graphics, and a functional, modern sans-serif font system.
- **Netlify** — Features a dark UI with clear information hierarchy, high-contrast text, and strategic use of bright accent colors to guide users.
- **Auth0** — Combines a dark background, sparse layout, and a focus on clean typography with technical diagrams to convey complex security concepts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon: #0e0f11;
  --color-basalt: #141617;
  --color-obsidian: #1d2023;
  --color-platinum: #ffffff;
  --color-graphite: #a1a1aa;
  --color-ash: #cfcfd3;
  --color-spectral-violet: #b6abff;
  --color-electric-lime: #eef35f;
  --color-system-teal: #00cbaa;
  --color-deep-violet: #6350dd;

  /* Typography — Font Families */
  --font-tt-hoves-light: 'TT Hoves Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tt-hoves-medium: 'TT Hoves Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tt-hoves-regular: 'TT Hoves Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basis-grotesque-mono-pro-medium: 'Basis Grotesque Mono Pro Medium', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-basis-grotesque-mono-pro-regular: 'Basis Grotesque Mono Pro Regular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.14;
  --text-body: 16px;
  --leading-body: 1.7;
  --tracking-body: -0.16px;
  --text-subheading: 22px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.154px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.27;
  --text-heading: 48px;
  --leading-heading: 1.2;
  --tracking-heading: -0.432px;
  --text-heading-lg: 54px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.54px;
  --text-display: 68px;
  --leading-display: 1.1;
  --tracking-display: -1.224px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

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
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-full: 50px;
  --radius-full-2: 91.06px;
  --radius-full-3: 100px;
  --radius-full-4: 133.33px;
  --radius-full-5: 136.27px;
  --radius-full-6: 500px;
  --radius-full-7: 1000px;

  /* Named Radii */
  --radius-tags: 20px;
  --radius-cards: 12px;
  --radius-buttons: 50px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.1) 0px 0px 0px 0.5px inset;
  --shadow-subtle-2: rgba(255, 255, 255, 0.1) 0px 2.5px 0px -2px inset;
  --shadow-subtle-3: rgb(58, 61, 64) 0px 0px 0px 0.5px;
  --shadow-subtle-4: rgb(48, 52, 56) 0px 0px 0px 0.5px;
  --shadow-subtle-5: rgba(255, 255, 255, 0.15) 0px 2.5px 0px -2px inset, rgba(255, 255, 255, 0.15) 0px 0px 0px 0.5px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon: #0e0f11;
  --color-basalt: #141617;
  --color-obsidian: #1d2023;
  --color-platinum: #ffffff;
  --color-graphite: #a1a1aa;
  --color-ash: #cfcfd3;
  --color-spectral-violet: #b6abff;
  --color-electric-lime: #eef35f;
  --color-system-teal: #00cbaa;
  --color-deep-violet: #6350dd;

  /* Typography */
  --font-tt-hoves-light: 'TT Hoves Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tt-hoves-medium: 'TT Hoves Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tt-hoves-regular: 'TT Hoves Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basis-grotesque-mono-pro-medium: 'Basis Grotesque Mono Pro Medium', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-basis-grotesque-mono-pro-regular: 'Basis Grotesque Mono Pro Regular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.14;
  --text-body: 16px;
  --leading-body: 1.7;
  --tracking-body: -0.16px;
  --text-subheading: 22px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.154px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.27;
  --text-heading: 48px;
  --leading-heading: 1.2;
  --tracking-heading: -0.432px;
  --text-heading-lg: 54px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.54px;
  --text-display: 68px;
  --leading-display: 1.1;
  --tracking-display: -1.224px;

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
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-full: 50px;
  --radius-full-2: 91.06px;
  --radius-full-3: 100px;
  --radius-full-4: 133.33px;
  --radius-full-5: 136.27px;
  --radius-full-6: 500px;
  --radius-full-7: 1000px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.1) 0px 0px 0px 0.5px inset;
  --shadow-subtle-2: rgba(255, 255, 255, 0.1) 0px 2.5px 0px -2px inset;
  --shadow-subtle-3: rgb(58, 61, 64) 0px 0px 0px 0.5px;
  --shadow-subtle-4: rgb(48, 52, 56) 0px 0px 0px 0.5px;
  --shadow-subtle-5: rgba(255, 255, 255, 0.15) 0px 2.5px 0px -2px inset, rgba(255, 255, 255, 0.15) 0px 0px 0px 0.5px inset;
}
```
