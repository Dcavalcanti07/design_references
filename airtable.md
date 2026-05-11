# Airtable — Style Reference
> Polished Workflow, Vibrant Efficiency — like a perfectly organized, brightly lit command center.

**Theme:** light

The Airtable design system conveys an approachable enterprise workflow platform. Its light theme and ample spacing provide a sense of clarity, grounded by a distinctive dark blue (#181D26) for strong text elements and primary actions. Functional interactivity is highlighted by a bright blue (#1B61C9) while a palette of vivid, multi-colored accents introduces a playful, almost illustrative quality, suggesting flexibility and creativity within a structured environment. Rounded corners and subtle shadows soften the experience, making complex AI tools feel less intimidating.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Canvas | `#ffffff` | `--color-white-canvas` | Page background, primary surface color for cards and major sections. |
| Cloud Whisper | `#f8fafc` | `--color-cloud-whisper` | Secondary background, subtle visual break for content cards and sections. |
| Warm Parchment | `#faf5e8` | `--color-warm-parchment` | Dominant canvas color, offers a slight warmth compared to pure white, establishing the overall page tone. |
| Slate Ink | `#181d26` | `--color-slate-ink` | Primary heading color, strong body text, and background for primary action buttons. The core dark neutral. |
| Deep Graphite | `#333333` | `--color-deep-graphite` | General text color, provides strong contrast against light backgrounds. |
| Soft Steel | `#333840` | `--color-soft-steel` | Default body text, slightly softer than Deep Graphite for secondary text information. |
| Silver Mist | `#e0e2e6` | `--color-silver-mist` | Subtle borders, dividers, and disabled button backgrounds. |
| Muted Stone | `#41454d` | `--color-muted-stone` | Less prominent body text, link text in paragraphs. |
| Cool Gray | `#9297a0` | `--color-cool-gray` | Navigation text, inactive icons, subtle borders. |
| Frost | `#c7e5f2` | `--color-frost` | Light background shade, used on some interactive elements when hovered. |
| Dark Shadow | `#040e20` | `--color-dark-shadow` | Very dark text color, appears for headings and body text, a deeper contrast option. |
| Ocean Accent | `#1b61c9` | `--color-ocean-accent` | Call-to-action buttons, active navigation links, and interactive elements. Stands out clearly. |
| Sky Veil | `#c4dbfd` | `--color-sky-veil` | Subtle accent, often appears as a box shadow for active elements or focus states. |
| Amethyst | `#254fad` | `--color-amethyst` | Brand accent, used for specific interactive elements and highlighting key information, hinting at information or success. |
| Burnt Sienna | `#aa2d00` | `--color-burnt-sienna` | Brand accent, used in specific illustrative contexts and text highlighting, indicates urgency or warning. |
| Forest Nudge | `#0a2e00` | `--color-forest-nudge` | Brand accent, used for success indications and positive feedback, often in illustrative elements. |
| Sweet Pink | `#fa91e0` | `--color-sweet-pink` | Brand accent, used decoratively in illustrations and data visualizations for visual separation. |
| Sunburst | `#fcb42a` | `--color-sunburst` | Brand accent, used for highlighting and decorative elements, adds a vibrant pop. |
| Mars Red | `#912e1f` | `--color-mars-red` | Background for specific card variations, provides a strong, warm contrast. |
| Tropical Orange | `#fcab79` | `--color-tropical-orange` | Background for specific interactive elements or badges, a softer version of the orange accent. |
| Dark Forrest | `#214224` | `--color-dark-forrest` | Darker shade of green, for text against lighter green backgrounds or specific brand elements. |
| Warm Gold | `#423719` | `--color-warm-gold` | Darker shade of yellow-brown, primarily for headings in certain branded contexts. |

## Tokens — Typography

### Haas Groot Disp — Headline font. Used for prominent headings and titles like 'All your teams, all their workflows'. The thick weight at 48px creates a bold, authoritative statement without being overly aggressive due to the spacious line height. · `--font-haas-groot-disp`
- **Substitute:** IBM Plex Sans
- **Weights:** 400, 900
- **Sizes:** 20px, 48px
- **Line height:** 1.50
- **Letter spacing:** 0
- **Role:** Headline font. Used for prominent headings and titles like 'All your teams, all their workflows'. The thick weight at 48px creates a bold, authoritative statement without being overly aggressive due to the spacious line height.

### Haas — Primary UI font for body text, navigation, and most interactive elements. Weight 400 maintains approachability. Sizes range from small captions to larger subheadings, ensuring versatility. Letter spacing is slightly positive on smaller text to enhance legibility, tightening to normal at larger sizes. · `--font-haas`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 32px, 40px
- **Line height:** 1.15, 1.20, 1.25, 1.30, 1.35, 1.50
- **Letter spacing:** 0.007
- **Role:** Primary UI font for body text, navigation, and most interactive elements. Weight 400 maintains approachability. Sizes range from small captions to larger subheadings, ensuring versatility. Letter spacing is slightly positive on smaller text to enhance legibility, tightening to normal at larger sizes.

### Haas — Medium weight for secondary interactive elements, button text, and emphasized body copy. Provides a subtle distinction from regular body text without becoming too heavy. · `--font-haas`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 32px, 40px
- **Line height:** 1.15, 1.20, 1.25, 1.30, 1.35, 1.50
- **Letter spacing:** 0.006
- **Role:** Medium weight for secondary interactive elements, button text, and emphasized body copy. Provides a subtle distinction from regular body text without becoming too heavy.

### Haas — Semibold weight used for navigation headings, strong labels, and section titles where additional emphasis is paramount. It provides hierarchy and readability against lighter backgrounds. · `--font-haas`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 32px, 40px
- **Line height:** 1.15, 1.20, 1.25, 1.30, 1.35, 1.50
- **Letter spacing:** 0.005
- **Role:** Semibold weight used for navigation headings, strong labels, and section titles where additional emphasis is paramount. It provides hierarchy and readability against lighter backgrounds.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.35 | 0.007px | `--text-caption` |
| body | 16px | 1.3 | 0.007px | `--text-body` |
| subheading | 18px | 1.25 | 0.007px | `--text-subheading` |
| heading-sm | 20px | 1.2 | 0.006px | `--text-heading-sm` |
| heading | 24px | 1.2 | 0.006px | `--text-heading` |
| heading-lg | 32px | 1.15 | 0.005px | `--text-heading-lg` |
| display | 48px | 1.5 | — | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| nav | 12px |
| cards | 16px |
| links | 12px |
| buttons | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.32) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) ...` | `--shadow-subtle` |
| lg | `rgba(15, 48, 106, 0.05) 0px 0px 20px 0px` | `--shadow-lg` |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 40-80px
- **Card padding:** 24-48px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call to Action

Solid background in Slate Ink (#181D26), text in White Canvas (#FFFFFF). Rounded with 12px border-radius. Padding 16px vertical, 24px horizontal. Used for primary actions like 'Get started for free'.

### Secondary Outline Button
**Role:** Secondary Action

Transparent background, text and border in Slate Ink (#181D26), no border-radius. Padding 0px. Used for navigation items or subtle secondary actions like 'Book demo'.

### White Filled Button
**Role:** Tertiary/Alternate Action

Solid background in White Canvas (#FFFFFF), text in Slate Ink (#181D26). Rounded with 12px border-radius. Padding 16px vertical, 24px horizontal. Used when a light background is needed against a dark section.

### Compact Nav Link
**Role:** In-line Navigation Link/Tag

Transparent background, text color in Muted Stone (rgba(7, 12, 20, 0.82)), no border-radius. Minimal padding 1px vertical, 6px horizontal. Used for compact links within text or less prominent actions.

### Base Card
**Role:** Content container

Transparent background, no border-radius, no shadow. Padding 0px vertical, 48px horizontal. Used for content sections where the background provides the visual separation.

### Subtle Card
**Role:** Content container

Background in Cloud Whisper (#F8FAFC), 16px border-radius, no shadow. Padding 0px. Used for grouping related content with a soft visual lift.

### Accent Card - Mars Red
**Role:** Highlighted Content Container

Background in Mars Red (#912E1F), 24px border-radius, no shadow. Padding 0px. Used for prominent, branded content blocks.

### White Elevated Card
**Role:** Prominent Content Container

Background in White Canvas (#ffffff), 24px border-radius, no shadow. Padding 0px. Used for main content sections that stand out.

### Input / Search Bar
**Role:** Data Entry Field

Background in White Canvas (#ffffff), text in Slate Ink (#181D26). Border is implied or very subtle. Active state likely shows a subtle blue shadow (#C4DBFD) with `rgba(0, 0, 0, 0.32) 0px 0px 1px 0px` for depth. Rounded corners with a 12px radius.

### Navigation Bar
**Role:** Site Navigation

White Canvas (#ffffff) background, with a subtle shadow (`rgba(15, 48, 106, 0.05) 0px 0px 20px 0px`) for elevation. Contains various links and buttons. Height is around 90-120px.

## Do's and Don'ts

### Do
- Prioritize Slate Ink (#181D26) for headlines and primary actions against light backgrounds for strong contrast.
- Use Ocean Accent (#1B61C9) exclusively for interactive elements like primary CTAs and active navigation links.
- Apply 12px border-radius consistently to all buttons and similar interactive elements for a softened feel.
- Maintain comfortable spacing with 16px for elementGap and 24-48px for cardPadding to ensure visual breathing room.
- Utilize Haas Groot Disp (or IBM Plex Sans fallback) at its 900 weight for eye-catching, high-impact headlines.
- Employ the full palette of vivid brand accents (Amethyst, Burnt Sienna, Forest Nudge, Sweet Pink, Sunburst) for illustrative elements, badges, or specific content blocks, not for core UI text or backgrounds.
- Elevate primary navigation and critical interactive buttons with subtle box shadows to indicate hierarchy and interactivity.

### Don't
- Do not use Gray Mist (#E0E2E6) for primary text or backgrounds that require strong contrast.
- Avoid using the vivid brand accent colors for standard text or backgrounds; reserve them for highlighting and illustration.
- Do not introduce sharp corners on interactive components; maintain the established 12px or 16px radius for buttons and cards.
- Avoid excessive use of shadows; most elevation is achieved through color contrast and subtle background shades.
- Do not use letter-spacing on display-sized text; keep it normal for Haas Groot Disp at 48px.
- Do not condense spacing beyond 16px for element gaps; preserve the comfortable density.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Warm Parchment | `#faf5e8` | Dominant page canvas, providing a slightly off-white, warm base. |
| 1 | White Canvas | `#ffffff` | Primary content surface, used for main sections, navigation, and primary cards, sitting directly on the canvas. |
| 2 | Cloud Whisper | `#f8fafc` | Secondary, slightly elevated content surface, for cards or content blocks that need a subtle visual separation or grouping. |

## Elevation

- **Navigation Bar:** `rgba(15, 48, 106, 0.05) 0px 0px 20px 0px`
- **Interactive Buttons/Focus States:** `rgba(0, 0, 0, 0.32) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px, rgba(45, 127, 249, 0.28) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 0px 0px 0.5px inset`

## Imagery

The visual language blends product screenshots with abstract, illustrative elements. Product screenshots are typically centered, slightly elevated as if floating, and feature an inner shadow suggesting depth and interaction. Illustrations are often in a flat, geometric style, using the full spectrum of brand accent colors (Amethyst, Burnt Sienna, Forest Nudge, Sweet Pink, Sunburst) to depict data flow, connections, or metaphorical concepts related to workflows and AI. Icons are minimal, either outlined or filled in a mono color (Slate Ink or a brand accent), used functionally rather than decoratively to guide UI. The density is image-moderate, with illustrations breaking up text-heavy sections and product shots showcasing key features directly.

## Layout

The page primarily follows a max-width contained layout, centering content within a flexible width, likely around 1280px. The hero section features a full-width background (often a solid color or subtle gradient) behind a centered headline and subtext, followed by a large product demonstration graphic that visually breaks the top fold. Sections below alternate between varying background shades (White Canvas, Cloud Whisper, Warm Parchment) and feature common patterns: centered content stacks, text-left/image-right (or vice-versa) modules, and multi-column grid layouts for features and testimonials. Vertical spacing between sections is generous (40-80px), creating a comfortable, open rhythm. The navigation is a sticky top bar, providing persistent access.

## Agent Prompt Guide

**Quick Color Reference:**
- Text (Strong): `#181D26` (Slate Ink)
- Text (Body): `#333840` (Soft Steel)
- Background (Canvas): `#faf5e8` (Warm Parchment)
- Background (Surface 1): `#ffffff` (White Canvas)
- CTA Button (Background): `#181D26` (Slate Ink)
- Accent (Interactive): `#1b61c9` (Ocean Accent)
- Border (Subtle): `#e0e2e6` (Silver Mist)

**3-5 Example Component Prompts:**
1. **Create a hero section:** Background is Warm Parchment (#faf5e8). Centered headline: 'All your teams, all their workflows—connected in one workspace' using Haas Groot Disp, 48px, weight 900, Slate Ink (#181D26). Subtext: 'Build AI-powered workflows...' using Haas, 18px, weight 400, Soft Steel (#333840). Follow with a Primary Filled Button: 'Get started for free' (Slate Ink background, White Canvas text, 12px radius, 16px/24px padding). Below this, an image of the product UI, featuring a search bar component (White Canvas background, 12px radius, subtle shadow, containing an input with Slate Ink text).
2. **Generate a feature card:** Background Cloud Whisper (#f8fafc), 16px border-radius, 24px internal padding. Title: 'Production apps at prototype speed' using Haas, 24px, weight 600, Slate Ink (#181D26). Body text 'Streamline your team’s critical data...' using Haas, 16px, weight 400, Soft Steel (#333840). Include a 'Learn more' Primary Filled Button (Ocean Accent background, White Canvas text, 12px radius, 16px/24px padding) aligned right.
3. **Design a customer logo band:** White Canvas (#ffffff) background, with a top border of Silver Mist (#E0E2E6). Section padding 40px top/bottom. Centered heading 'Trusted by 500,000 leading teams' using Haas, 20px, weight 600, Dark Shadow (#040e20). Display 5-6 customer logos, each treated as a transparent image against the white background, with 32px column and row gaps between them.

## Similar Brands

- **monday.com** — Shares a light, spacious layout with rounded UI elements and a playful, multi-colored accent palette to convey approachability for workflow management.
- **asana** — Utilizes a clean, light base with a strong primary font and a subtle, functional highlight color, focusing on clarity in a task management interface.
- **notion** — Employs a minimalist, clean aesthetic with effective use of white space and a slightly muted text hierarchy, making complex information feel manageable.
- **Linear** — Features a similar combination of strong text (dark gray / black) on light backgrounds, with specific interactive elements highlighted by a clear, consistent accent color, prioritizing clear functionality for dev tools.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-cloud-whisper: #f8fafc;
  --color-warm-parchment: #faf5e8;
  --color-slate-ink: #181d26;
  --color-deep-graphite: #333333;
  --color-soft-steel: #333840;
  --color-silver-mist: #e0e2e6;
  --color-muted-stone: #41454d;
  --color-cool-gray: #9297a0;
  --color-frost: #c7e5f2;
  --color-dark-shadow: #040e20;
  --color-ocean-accent: #1b61c9;
  --color-sky-veil: #c4dbfd;
  --color-amethyst: #254fad;
  --color-burnt-sienna: #aa2d00;
  --color-forest-nudge: #0a2e00;
  --color-sweet-pink: #fa91e0;
  --color-sunburst: #fcb42a;
  --color-mars-red: #912e1f;
  --color-tropical-orange: #fcab79;
  --color-dark-forrest: #214224;
  --color-warm-gold: #423719;

  /* Typography — Font Families */
  --font-haas-groot-disp: 'Haas Groot Disp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas: 'Haas', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.35;
  --tracking-caption: 0.007px;
  --text-body: 16px;
  --leading-body: 1.3;
  --tracking-body: 0.007px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.007px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.006px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: 0.006px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: 0.005px;
  --text-display: 48px;
  --leading-display: 1.5;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 40-80px;
  --card-padding: 24-48px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Named Radii */
  --radius-nav: 12px;
  --radius-cards: 16px;
  --radius-links: 12px;
  --radius-buttons: 12px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.32) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px, rgba(45, 127, 249, 0.28) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 0px 0px 0.5px inset;
  --shadow-lg: rgba(15, 48, 106, 0.05) 0px 0px 20px 0px;

  /* Surfaces */
  --surface-warm-parchment: #faf5e8;
  --surface-white-canvas: #ffffff;
  --surface-cloud-whisper: #f8fafc;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-cloud-whisper: #f8fafc;
  --color-warm-parchment: #faf5e8;
  --color-slate-ink: #181d26;
  --color-deep-graphite: #333333;
  --color-soft-steel: #333840;
  --color-silver-mist: #e0e2e6;
  --color-muted-stone: #41454d;
  --color-cool-gray: #9297a0;
  --color-frost: #c7e5f2;
  --color-dark-shadow: #040e20;
  --color-ocean-accent: #1b61c9;
  --color-sky-veil: #c4dbfd;
  --color-amethyst: #254fad;
  --color-burnt-sienna: #aa2d00;
  --color-forest-nudge: #0a2e00;
  --color-sweet-pink: #fa91e0;
  --color-sunburst: #fcb42a;
  --color-mars-red: #912e1f;
  --color-tropical-orange: #fcab79;
  --color-dark-forrest: #214224;
  --color-warm-gold: #423719;

  /* Typography */
  --font-haas-groot-disp: 'Haas Groot Disp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas: 'Haas', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.35;
  --tracking-caption: 0.007px;
  --text-body: 16px;
  --leading-body: 1.3;
  --tracking-body: 0.007px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.007px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.006px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: 0.006px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: 0.005px;
  --text-display: 48px;
  --leading-display: 1.5;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.32) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px, rgba(45, 127, 249, 0.28) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 0px 0px 0.5px inset;
  --shadow-lg: rgba(15, 48, 106, 0.05) 0px 0px 20px 0px;
}
```
