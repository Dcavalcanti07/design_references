# Harness.io — Style Reference
> Midnight Command Console. A digital workspace with data streams under soft, diffused light against a dark, technical expanse.

**Theme:** dark

Harness.io employs a dark, technical aesthetic with luminous accents. The UI features stark black canvases contrasted by subtle cool-toned gradients, creating a sense of depth and focus. Typography is dense and purposeful, using strong sans-serifs for headings and information hierarchy. Components are lightweight with rounded edges, emphasizing clear interactive states and data visualization within a controlled, high-contrast environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#070707` | `--color-absolute-zero` | Primary background for pages and sections, foundational dark surface |
| Deep Space | `#0d0e12` | `--color-deep-space` | Elevated card and subtle background surfaces, providing subtle layering against the darkest canvas |
| Ash Grey | `#141418` | `--color-ash-grey` | Tertiary card backgrounds and elevated components |
| Graphite | `#2e3038` | `--color-graphite` | Subtle borders and muted text on dark backgrounds |
| Light Ghost | `#ffffff` | `--color-light-ghost` | Primary text, critical UI elements, and filled button backgrounds |
| Cool Mist | `#f0f0f0` | `--color-cool-mist` | Secondary text and borders on dark backgrounds, slightly softer than pure white |
| Smokey Quartz | `#d9dae5` | `--color-smokey-quartz` | Desaturated accent for subtle borders and informational text |
| Storm Cloud | `#aeaeb7` | `--color-storm-cloud` | Body text and less prominent UI elements, providing contrast without harshness |
| Slate | `#22222a` | `--color-slate` | Text and borders on slightly lighter dark surfaces, providing differentiation |
| Ice Blue Highlight | `#effbff` | `--color-ice-blue-highlight` | Subtle surface highlights and active states, creating a luminous edge |
| Cyan Sparkle | `#70dcd3` | `--color-cyan-sparkle` | Distinct card backgrounds for featured content, creating visual interest |
| Electric Blue | `#0092e4` | `--color-electric-blue` | Accent for links, active navigation items, and highlighted borders for interactive elements |
| Skybound Blue | `#00ade4` | `--color-skybound-blue` | Navigation text and subtle accent borders, reinforcing brand identity |
| Interface Blue | `radial-gradient(circle at 26% 0px, rgba(178, 198, 255, 0.35), rgba(243, 243, 244, 0.06) 33%, rgba(255, 255, 255, 0) 56%, rgba(57, 59, 76, 0.15))` | `--color-interface-blue` | Input focus rings and small informational indicators |
| Forest Green | `#75ae4c` | `--color-forest-green` | Green accent for outlined action borders, linked labels, and lightweight interactive emphasis. Use as a supporting accent, not as a status color |
| Glassy Blue Gradient | `radial-gradient(circle at 26% 0px, rgba(178, 198, 255, 0.35), rgba(243, 243, 244, 0.06) 33%, rgba(255, 255, 255, 0) 56%, rgba(57, 59, 76, 0.15))` | `--color-glassy-blue-gradient` | Subtle radial gradient for UI elements, creating a luminous, holographic effect |
| Deep Sea Gradient | `linear-gradient(140deg, rgb(130, 187, 206), rgb(90, 109, 131) 50%, rgb(83, 104, 128) 70%, rgb(97, 128, 140))` | `--color-deep-sea-gradient` | Subtle background gradient for dark sections, adding depth and a cool tone |

## Tokens — Typography

### Geist — Primary UI font for body text, navigation, buttons, and detailed informational content. Highly versatile, supporting a wide range of weights and sizes for dense information display with tight tracking. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 8px, 10px, 12px, 14px, 15px, 16px, 18px, 20px, 22px, 24px, 40px
- **Line height:** 0.88, 1.00, 1.13, 1.20, 1.22, 1.37, 1.38, 1.44, 1.50, 1.57
- **Letter spacing:** -0.0200em, -0.0170em, 0.0160em, 0.0180em, 0.0420em, 0.0940em
- **OpenType features:** `'liga'`
- **Role:** Primary UI font for body text, navigation, buttons, and detailed informational content. Highly versatile, supporting a wide range of weights and sizes for dense information display with tight tracking.

### Calsans — Used for prominent headlines and calls to action. The lighter weight 300 for large display text is an intentional choice, creating a sophisticated feel through restraint rather than bombast. Wide letter spacing at large sizes enhances legibility against dark backgrounds. · `--font-calsans`
- **Substitute:** Montserrat
- **Weights:** 300, 600
- **Sizes:** 18px, 24px, 32px, 34px, 56px, 64px, 72px, 88px
- **Line height:** 0.96, 1.00, 1.10, 1.15, 1.20, 1.37
- **Letter spacing:** 0.0560em
- **OpenType features:** `'liga'`
- **Role:** Used for prominent headlines and calls to action. The lighter weight 300 for large display text is an intentional choice, creating a sophisticated feel through restraint rather than bombast. Wide letter spacing at large sizes enhances legibility against dark backgrounds.

### Helvetica — Fallback font for small print, legal text, and secondary information where system font robustness is prioritized. · `--font-helvetica`
- **Substitute:** Arial
- **Weights:** 400, 600
- **Sizes:** 13px
- **Line height:** 1.69
- **Letter spacing:** normal
- **OpenType features:** `'liga'`
- **Role:** Fallback font for small print, legal text, and secondary information where system font robustness is prioritized.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.37 | — | `--text-body` |
| subheading | 24px | 1.2 | — | `--text-subheading` |
| heading-sm | 32px | 1.15 | — | `--text-heading-sm` |
| heading | 40px | 1.13 | -0.017px | `--text-heading` |
| heading-lg | 56px | 1.1 | 0.056px | `--text-heading-lg` |
| display | 88px | 0.96 | 0.056px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| base | 20px |
| tags | 40px |
| cards | 20px |
| input | 5px |
| buttons | 800px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 2px 2px 0px 0px` | `--shadow-subtle` |
| subtle-2 | `rgb(255, 255, 255) 0px -1px 0px 0px inset, rgb(255, 255, ...` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Ghost Navigation Link
**Role:** Main navigation items and secondary actions.

Transparent background, 'Light Ghost' text color, 0px border radius, 2px padding. Emphasizes text hierarchy without visual weight.

### Primary Pill Button
**Role:** Prominent calls to action.

Background 'Light Ghost', text 'Absolute Zero', border 'Absolute Zero'. Padded 12px vertical, 24px horizontal, with 800px border radius creating a pill shape. High contrast against dark backgrounds.

### Subtle Tag Button
**Role:** Informational tags or small interactive elements.

Background 'Cool Mist', text 'Slate'. Padded 8px vertical, 12px horizontal, with 40px border radius creating a soft pill shape.

### Transparent Card
**Role:** Container for content with no distinct background.

Transparent background, 0px border radius, no shadow. Padding 0px top/bottom, 32px left/right for content flush to edges but respecting horizontal rhythm.

### Elevated Dark Card
**Role:** Content container with subtle elevation from the background.

Background 'Deep Space', 20px border radius, no shadow. Padding 0px top/bottom, 56px left for asymmetrical content alignment.

### Bordered Dark Card
**Role:** Container with a fine border for structured content.

Background 'Ash Grey', 20px border radius, no shadow. 1px padding on all sides, acting as a thin visual border.

### Outlined Input Field
**Role:** Standard user input element.

Background 'Light Ghost', text 'Absolute Zero'. Border color 'Interface Blue' on focus. 5px border radius. Padding 12px top, 13px left, 12.453px right, 14px bottom.

### Feature Highlight Card
**Role:** Card for showcasing key features or information with a distinct background.

Background 'Cyan Sparkle', 20px border radius. Used to break up monochromatic sections with a vibrant tone.

## Do's and Don'ts

### Do
- Prioritize 'Absolute Zero' (#070707) as the primary page and section background.
- Use 'Light Ghost' (#ffffff) for primary text and critical interactive button backgrounds.
- Apply Geist font for all UI text, navigation, and body content, utilizing its diverse weights and tight letter spacing for information density.
- Reserve Calsans font for significant headlines and display text, employing its lighter weights (300, 600) with wide letter spacing (0.0560em) for authority through clarity.
- Utilize 20px border radius for most cards and elements to maintain a consistent soft-edged aesthetic.
- Create visual hierarchy using 'Deep Space' (#0d0e12) and 'Ash Grey' (#141418) for layered card surfaces against the main background.
- Employ 'Electric Blue' (#0092e4) for all link states, active navigation elements, and primary accent borders.

### Don't
- Avoid harsh shadows; opt for subtle inset or diffuse shadows (e.g., rgba(0, 0, 0, 0.05) 2px 2px 0px 0px) only when elevation is necessary for interaction.
- Do not introduce bright, unsubstantiated colors; all accents should be derived from the 'Electric Blue', 'Cyan Sparkle', or muted green semantic palette.
- Do not use generic square buttons; always apply at least a 5px radius for inputs and 800px for pill-shaped buttons and tags.
- Avoid cluttering the dark background with too many competing colors; most of the UI should remain high-contrast monochrome with specific accent points.
- Do not use letter spacing smaller than -0.0200em or larger than 0.0940em, as seen in the Geist font family, to maintain typographic rhythm.
- Avoid dense sections without adequate spacing; ensure a minimum element gap of 16px and card padding of 16px for readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Absolute Zero Canvas | `#070707` | Dominant background for the entire application and main content areas. |
| 1 | Deep Space Card | `#0d0e12` | First layer of elevated surfaces, typically for cards or content blocks. |
| 2 | Ash Grey Elevated | `#141418` | Secondary elevated surfaces, often for nested cards or modals, providing further visual separation. |
| 3 | Cyan Sparkle Feature | `#70dcd3` | Specialized elevated surfaces for highlighted features or informational blocks, introducing a distinct color accent. |

## Elevation

- **Input Field:** `rgba(0, 0, 0, 0.05) 2px 2px 0px 0px`
- **Interactive Buttons:** `rgba(0, 0, 0, 0.05) 2px 2px 0px 0px`
- **Link with Inset Border:** `rgb(255, 255, 255) 0px -1px 0px 0px inset, rgb(255, 255, 255) 1px 0px 0px 0px inset, rgb(255, 255, 255) -1px 0px 0px 0px inset, rgb(255, 255, 255) 0px 1px 0px 0px inset`

## Imagery

This system features a mix of conceptual illustrations and product UI diagrams. Illustrations are highly stylized with gradients that suggest depth and luminosity, often featuring circuit-like pathways or flowing elements in cool-toned blues and grays (e.g., Glassy Blue Gradient). Product UI is presented as abstracted diagrams, showcasing code snippets or data flow, set against dark, transparent, or softly glowing backgrounds. Icons are minimalist, outlined, and monochromatic, used functionally rather than decoratively to support technical concepts. Imagery serves to explain and contextualize complex technical processes, acting as atmospheric content rather than raw product showcases, often integrated into the composition with blur effects and soft glow.

## Layout

The page maintains a centered, max-width layout within a full-bleed dark background. The hero section is full-bleed with a large, centered headline and descriptive text, featuring dynamically rendered UI elements integrated into a 3D-effect background illustration. Sections alternate between full-width immersive experiences with integrated visuals and contained content blocks. Content arrangement often uses two-column structures for text and associated visuals or code examples. A compact card grid illustrates features. Vertical rhythm is established by consistent section gaps, creating breathing room within the dark canvas. The navigation is a sticky top bar with left-aligned branding and right-aligned actions, featuring subtle ghost links and a primary pill button.

## Agent Prompt Guide

### Quick Color Reference
text: #ffffff
background: #070707
border: #2e3038
accent: #0092e4
primary action: #ffffff (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: 'Absolute Zero' (#070707) background. Headline 'The End-To-End Open Source Software Delivery Platform' using Calsans weight 600 at 72px (lineHeight 0.96, letterSpacing 0.056em), color 'Light Ghost' (#ffffff). Subtext 'Configure hosted development environments...' using Geist weight 400 at 18px (lineHeight 1.38), color 'Storm Cloud' (#aeaeb7). Include a 'Get started' button: 'Light Ghost' (#ffffff) background, 'Absolute Zero' (#070707) text, 800px radius, 12px vertical padding, 24px horizontal padding, Geist weight 500 at 16px. Followed by a ghost button 'Read the announcement blog' with 'Light Ghost' (#ffffff) text and border, Geist weight 500 at 16px, 2px padding, 0px radius.
2. Design an 'Elevated Dark Card' with title 'Familiar Git Experience.' using Calsans weight 600 at 56px (lineHeight 1.1, letterSpacing 0.056em), color 'Light Ghost' (#ffffff). Card background is 'Deep Space' (#0d0e12) with a 20px border radius, 0px vertical padding, 56px left padding.
3. Create a Primary Action Button: #ffffff background, #070707 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
4. Design an outlined input field: Background 'Light Ghost' (#ffffff), text 'Absolute Zero' (#070707), border color 'Interface Blue' (#0677d4) on focus, 5px border radius, 12px top padding, 13px left padding, 12.453px right padding, 14px bottom padding, Geist weight 400 at 16px for placeholder text 'Enter your email'.

## Gradient System

The system features subtle, predominantly cool-toned gradients to add depth and luminescence to dark surfaces. Radial gradients (e.g., 'Glassy Blue Gradient' #b2c6ff) are used to create soft, glowing focal points within UI elements. Linear gradients (e.g., 'Deep Sea Gradient' #82bbe2) are typically applied to large background sections to create a sense of expansive depth, shifting from deeper to lighter blues/grays. Gradients are strategically placed to highlight elements or add atmospheric qualities rather than for bold decoration, creating a tech-centric, almost holographic feel.

## Similar Brands

- **GitHub** — Similar dark-mode UI with technical illustrations and a focus on developer tools and code.
- **Vercel** — Emphasizes sleek dark UI, subtle gradients, and concise typography for developer-focused platforms.
- **Linear** — Strong commitment to dark mode, clean typography, and functional interactive elements.
- **Supabase** — Uses dark themes with contrasting accent colors and code-focused visual elements in their web presence.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #070707;
  --color-deep-space: #0d0e12;
  --color-ash-grey: #141418;
  --color-graphite: #2e3038;
  --color-light-ghost: #ffffff;
  --color-cool-mist: #f0f0f0;
  --color-smokey-quartz: #d9dae5;
  --color-storm-cloud: #aeaeb7;
  --color-slate: #22222a;
  --color-ice-blue-highlight: #effbff;
  --color-cyan-sparkle: #70dcd3;
  --color-electric-blue: #0092e4;
  --color-skybound-blue: #00ade4;
  --color-interface-blue: #0677d4;
  --gradient-interface-blue: radial-gradient(circle at 26% 0px, rgba(178, 198, 255, 0.35), rgba(243, 243, 244, 0.06) 33%, rgba(255, 255, 255, 0) 56%, rgba(57, 59, 76, 0.15));
  --color-forest-green: #75ae4c;
  --color-glassy-blue-gradient: #b2c6ff;
  --gradient-glassy-blue-gradient: radial-gradient(circle at 26% 0px, rgba(178, 198, 255, 0.35), rgba(243, 243, 244, 0.06) 33%, rgba(255, 255, 255, 0) 56%, rgba(57, 59, 76, 0.15));
  --color-deep-sea-gradient: #82bbe2;
  --gradient-deep-sea-gradient: linear-gradient(140deg, rgb(130, 187, 206), rgb(90, 109, 131) 50%, rgb(83, 104, 128) 70%, rgb(97, 128, 140));

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-calsans: 'Calsans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.37;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.15;
  --text-heading: 40px;
  --leading-heading: 1.13;
  --tracking-heading: -0.017px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.056px;
  --text-display: 88px;
  --leading-display: 0.96;
  --tracking-display: 0.056px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 5px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;
  --radius-full-2: 800px;

  /* Named Radii */
  --radius-base: 20px;
  --radius-tags: 40px;
  --radius-cards: 20px;
  --radius-input: 5px;
  --radius-buttons: 800px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 2px 2px 0px 0px;
  --shadow-subtle-2: rgb(255, 255, 255) 0px -1px 0px 0px inset, rgb(255, 255, 255) 1px 0px 0px 0px inset, rgb(255, 255, 255) -1px 0px 0px 0px inset, rgb(255, 255, 255) 0px 1px 0px 0px inset;

  /* Surfaces */
  --surface-absolute-zero-canvas: #070707;
  --surface-deep-space-card: #0d0e12;
  --surface-ash-grey-elevated: #141418;
  --surface-cyan-sparkle-feature: #70dcd3;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #070707;
  --color-deep-space: #0d0e12;
  --color-ash-grey: #141418;
  --color-graphite: #2e3038;
  --color-light-ghost: #ffffff;
  --color-cool-mist: #f0f0f0;
  --color-smokey-quartz: #d9dae5;
  --color-storm-cloud: #aeaeb7;
  --color-slate: #22222a;
  --color-ice-blue-highlight: #effbff;
  --color-cyan-sparkle: #70dcd3;
  --color-electric-blue: #0092e4;
  --color-skybound-blue: #00ade4;
  --color-interface-blue: #0677d4;
  --color-forest-green: #75ae4c;
  --color-glassy-blue-gradient: #b2c6ff;
  --color-deep-sea-gradient: #82bbe2;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-calsans: 'Calsans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.37;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.15;
  --text-heading: 40px;
  --leading-heading: 1.13;
  --tracking-heading: -0.017px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.056px;
  --text-display: 88px;
  --leading-display: 0.96;
  --tracking-display: 0.056px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 5px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;
  --radius-full-2: 800px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 2px 2px 0px 0px;
  --shadow-subtle-2: rgb(255, 255, 255) 0px -1px 0px 0px inset, rgb(255, 255, 255) 1px 0px 0px 0px inset, rgb(255, 255, 255) -1px 0px 0px 0px inset, rgb(255, 255, 255) 0px 1px 0px 0px inset;
}
```
