# Ballpark — Style Reference
> High-contrast research tool; like a scientific dashboard with a single, urgent indicator light.

**Theme:** light

Ballpark's design conveys a sense of confident authority through its stark visual contrasts and structured layout. The interplay of deep, near-black text and crisp white backgrounds, punctuated by a single vibrant "Rocket Red" accent, creates a focused, high-contrast experience, much like an advanced research instrument. The generous use of space, especially around core content and within card structures, emphasizes clarity and reduces cognitive load, allowing complex information to be easily digestible. Distinctive rounded forms—from the extra-large button radii to the subtle card curves—soften the otherwise sharp edges, balancing precision with approachability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Primary text, critical headings, icons, borders on dark elements. Establishes a bold and clear informational hierarchy. |
| Ghost White | `#ffffff` | `--color-ghost-white` | Page backgrounds, card surfaces, secondary button backgrounds. Provides clean canvas for content and negative space. |
| Ash Gray | `#f9fafb` | `--color-ash-gray` | Subtle section backgrounds, light borders, subtle hover states. Offers a barely-there differentiation from Ghost White. |
| Graphite | `#111827` | `--color-graphite` | Heading text, primary UI element text where Pitch Black might be too intense. Provides significant contrast without being absolute black. |
| Slate Blue | `#4b5563` | `--color-slate-blue` | Body copy, secondary text, iconography. Softens text impact for longer reads while maintaining readability. |
| Medium Gray | `#374151` | `--color-medium-gray` | Slightly darker body copy and secondary text for deeper contrast on lighter backgrounds. |
| Light Gray | `#6b7280` | `--color-light-gray` | Tertiary text, subtle borders, inactive states. Used for less prominent information. |
| Border Gray | `#e5e7eb` | `--color-border-gray` | Default boundary for containers and cards, hint for input fields, offering subtle structure without being visually heavy. |
| Rocket Red | `#fc4a2b` | `--color-rocket-red` | Primary Call-to-Action buttons, active indicators, highlights. Its vivid saturation against the largely achromatic palette ensures immediate attention. |
| Passion Red | `#e11d48` | `--color-passion-red` | Secondary brand accent for more intense calls to action or error states, providing a deeper red alternative to Rocket Red. |
| Sunset Orange | `#f97316` | `--color-sunset-orange` | Subtle stroke accents and decorative elements. A warmer, slightly more muted accent. |
| Coral Glow | `#ffac9` | `--color-coral-glow` | Highlight backgrounds, soft decorative elements. A light and airy accent derived from the brand red, used for subtle visual uplift. |
| Pale Peach | `#ffe5e0` | `--color-pale-peach` | Very light accent background, almost neutral, for soft visual differentiation. |
| Success Green | `#15803d` | `--color-success-green` | Subtle semantic indicator for success messages or positive states. |
| Warning Yellow | `#f59e0b` | `--color-warning-yellow` | Subtle semantic indicator for warnings or informational alerts. |
| Pill Button Gradient | `linear-gradient(268.33deg, rgb(248, 113, 113), rgb(254, 202, 202), rgb(254, 226, 226), rgb(254, 242, 242))` | `--color-pill-button-gradient` | Background for secondary action pills, offering a soft visual texture. |

## Tokens — Typography

### Inter Display — Display headlines and hero text. The tight line height and negative letter-spacing give it a commanding, engineered feel. The specific font features 'cv06', 'cv13', 'zero' are critical for its distinctive look. · `--font-inter-display`
- **Substitute:** system-ui, sans-serif
- **Weights:** 700, 800
- **Sizes:** 42px, 60px, 96px
- **Line height:** 1.00
- **Letter spacing:** -0.035em, -0.030em
- **OpenType features:** `"cv06", "cv13", "zero", "cv06", "cv13"`
- **Role:** Display headlines and hero text. The tight line height and negative letter-spacing give it a commanding, engineered feel. The specific font features 'cv06', 'cv13', 'zero' are critical for its distinctive look.

### Inter — All body copy, subheadings, navigation, and button text. Its versatility across weights and sizes, combined with careful letter-spacing adjustments, maintains readability and a precise tone. Features 'cv01', 'cv02', 'cv04', 'cv09' ensure consistent character design. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 13px, 14px, 16px, 18px, 20px, 24px
- **Line height:** 1.20, 1.33, 1.38, 1.40, 1.43, 1.46, 1.50, 1.60, 1.65
- **Letter spacing:** -0.03em, -0.02em, -0.014em, -0.01em, 0.05em
- **OpenType features:** `"cv01", "cv02", "cv04", "cv09", "cv01", "cv02", "cv03", "cv04", "cv09"`
- **Role:** All body copy, subheadings, navigation, and button text. Its versatility across weights and sizes, combined with careful letter-spacing adjustments, maintains readability and a precise tone. Features 'cv01', 'cv02', 'cv04', 'cv09' ensure consistent character design.

### sans-serif — Fallback and utilitarian text where a system font provides sufficient clarity, often for labels or minor UI elements. · `--font-sans-serif`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Fallback and utilitarian text where a system font provides sufficient clarity, often for labels or minor UI elements.

### IBM Plex Mono — Monospaced text for code snippets or specific data representations. The expanded letter spacing gives it a technical, distinct feel. · `--font-ibm-plex-mono`
- **Substitute:** monospace
- **Weights:** 600
- **Sizes:** 11px
- **Line height:** 1.50
- **Letter spacing:** 0.15em
- **Role:** Monospaced text for code snippets or specific data representations. The expanded letter spacing gives it a technical, distinct feel.

### Source Serif 4 — Used for specific body text, possibly quotes or editorial content, offering a more traditional and softer reading experience with subtle tracking. · `--font-source-serif-4`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.60
- **Letter spacing:** -0.02em
- **Role:** Used for specific body text, possibly quotes or editorial content, offering a more traditional and softer reading experience with subtle tracking.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.5px | `--text-caption` |
| body | 14px | 1.6 | -0.14px | `--text-body` |
| subheading | 18px | 1.5 | -0.36px | `--text-subheading` |
| heading | 24px | 1.4 | -0.48px | `--text-heading` |
| heading-lg | 42px | 1 | -1.47px | `--text-heading-lg` |
| display | 96px | 1 | -3.36px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 104 | 104px | `--spacing-104` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| cards | 10px |
| images | 6px |
| inputs | 6px |
| buttons | 6px |
| interactive | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 6px 9px 0px` | `--shadow-md` |
| subtle | `rgba(75, 85, 99, 0.2) 0px 0px 0px 1px` | `--shadow-subtle` |
| xl | `rgba(50, 50, 92, 0.05) 0px 50px 100px -20px, rgba(0, 0, 0...` | `--shadow-xl` |
| subtle-2 | `rgb(252, 74, 43) 0px 0px 0px 2px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-3` |
| subtle-4 | `rgba(75, 85, 99, 0.2) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06...` | `--shadow-subtle-4` |
| subtle-5 | `rgb(17, 24, 39) 0px 0px 0px 1px` | `--shadow-subtle-5` |
| subtle-6 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px, rgba(75, 85, 99, 0.2...` | `--shadow-subtle-6` |
| subtle-7 | `rgba(0, 0, 0, 0.1) 0px 1px 2px 0px inset, rgb(249, 250, 2...` | `--shadow-subtle-7` |
| subtle-8 | `rgb(255, 255, 255) 0px 0px 0px 1px` | `--shadow-subtle-8` |

### Layout

- **Section gap:** 64-96px
- **Card padding:** 14-24px
- **Element gap:** 8px

## Components

### Navigation Link
**Role:** Primary navigation in header

Text: Inter, 16px, weight 500, Graphite (#111827). Hover state: Pitch Black (#000000). Active state: underline 2px Rocket Red (#fc4a2b). Generous padding: 8px vertical, 8-16px horizontal to ensure distinct hit areas.

### Secondary Ghost Button
**Role:** Tertiary actions, secondary calls to attention

Text: Pitch Black (#000000), 16px, weight 400. Background: transparent. Border: transparent. Active state: faint border or background color change. Used for subtle interactions like 'Sign In'.

### Feature Card
**Role:** Showcasing features or testimonials

Background: Ghost White (#ffffff). Border radius: 10px. Box shadow: rgba(0, 0, 0, 0.1) 0px 6px 9px 0px, subtle inner shadow rgba(75, 85, 99, 0.2) 0px 0px 0px 1px. Contains content with 16px padding on all sides. The prominent shadow lifts the card significantly.

### Header Brand Link
**Role:** Brand logo in header

Text: Pitch Black (#000000), 24px, Inter Display, weight 700. Features: 'cv06', 'cv13'. Minimal padding. Sets a bold brand identity at the top of every page.

### Tertiary Callout Button
**Role:** Informational or less prominent calls to action

Text: Pitch Black (#000000), 16px, weight 400. Background: Light Gray (#e6e8eb). Radius: 6px. Padding: 8px vertical, 14px horizontal. Serves as a neutral, accessible button for less critical actions.

## Do's and Don'ts

### Do
- Prioritize high contrast between text and background using Pitch Black (#000000) or Graphite (#111827) on Ghost White (#ffffff) or Ash Gray (#f9fafb).
- Use Rocket Red (#fc4a2b) exclusively for primary call-to-action buttons and essential active states to maintain its impact.
- Apply a 9999px radius for all pill-shaped elements (buttons, tags, filters) and use 6px for standard buttons and inputs.
- Employ the Inter Display font with specific font features ('cv06', 'cv13') for all display-level headlines (42px and above) to achieve its distinct character.
- Maintain generous padding around content blocks and within components, targeting 14-24px for card padding and 8px as a base element gap.
- Utilize the shadow `rgba(0, 0, 0, 0.1) 0px 6px 9px 0px, rgba(75, 85, 99, 0.2) 0px 0px 0px 1px` for all elevated cards and containers to create a consistent lifted appearance.
- Ensure letter-spacing is applied as specified in the typography for Inter and Inter Display, especially the negative values for larger headlines, to optimize visual density.

### Don't
- Do not introduce new primary accent colors; restrict vibrant accents to Rocket Red (#fc4a2b) and its derivatives.
- Avoid using multiple shadows on a single element; stick to the defined shadow styles for cards to prevent visual clutter.
- Do not deviate from the specified font features for Inter and Inter Display, as they are integral to the brand's typographic identity.
- Refrain from using radii smaller than 6px or larger than 10px (except for 9999px pills) to maintain shape consistency.
- Do not use generic system sans-serif for body or heading text; always use 'Inter' for its consistent, readable structure.
- Avoid excessive use of bold text in body copy; reserve weights 600-700 for headings, subheadings, and key UI labels only.

## Elevation

- **Feature Card:** `rgba(0, 0, 0, 0.1) 0px 6px 9px 0px, rgba(75, 85, 99, 0.2) 0px 0px 0px 1px`
- **Hovered Button:** `rgba(0, 0, 0, 0.06) 0px 2px 2px 0px, rgba(75, 85, 99, 0.2) 0px 0px 0px 1px`
- **Callout / Modal:** `rgba(50, 50, 92, 0.05) 0px 50px 100px -20px, rgba(0, 0, 0, 0.15) 0px 30px 60px -30px`
- **Accent Ring:** `rgb(252, 74, 43) 0px 0px 0px 2px`

## Imagery

This design primarily uses product screenshots and abstract, organic vector graphics that appear to be illustrations. Photography, when present in testimonials, is framed within rounded containers (16px radius) and sometimes features a subtle, brand-colored overlay (like the red Vodafone graphic). Product screenshots are often contained within structured cards, emphasizing functionality over aesthetic appeal. Illustrations are generally flat, geometric, and either filled with muted, abstract colors or outlines in brand colors like Rocket Red. Iconography is primarily outline-based with a medium stroke weight. The overall role of imagery is explanatory and supportive rather than purely decorative, providing visual context to features and testimonials. Image density is moderate, balanced with significant textual content and whitespace.

## Layout

The page maintains a centered, max-width layout, effectively creating a content-focused experience within clear boundaries. The hero section is characterized by a centered, bold headline over a white background, occasionally featuring subtle background elements or abstract graphics. Sections generally alternate between centered text stacks and two-column layouts pairing text with images or product illustrations, creating a balanced rhythm. A prominent feature is the use of card grids (often 3-column) for displaying multiple features or testimonials, ensuring content is visually digestible. Navigation is a sticky top bar with a clear brand logo and primary actions. Generous vertical spacing between sections creates breathing room and allows each section to convey a distinct message without visual overlap.

## Agent Prompt Guide

### Quick Color Reference
- **Text:** Pitch Black (#000000)
- **Background:** Ghost White (#ffffff)
- **CTA:** Rocket Red (#fc4a2b)
- **Body Text:** Slate Blue (#4b5563)
- **Border:** Border Gray (#e5e7eb)

### 3-5 Example Component Prompts
1. **Create a Hero Section:** Set background to Ghost White (#ffffff). Headline text: "Your Research, Simplified" using Inter Display, 96px, weight 800, Pitch Black (#000000), letter-spacing -3.36px. Subheading: "A new way to get insights." using Inter, 24px, weight 400, Slate Blue (#4b5563), letter-spacing -0.48px. Add a Primary CTA Button (see below).
2. **Generate a Primary CTA Button:** Text: "Get Started Now" using Inter, 16px, weight 700, Pitch Black (#000000). Background: Rocket Red (#fc4a2b). Border radius: 6px. Padding: 8px vertical, 14px horizontal. Box shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px.
3. **Design a Feature Card:** Background: Ghost White (#ffffff). Border radius: 10px. Box shadow: rgba(0, 0, 0, 0.1) 0px 6px 9px 0px, rgba(75, 85, 99, 0.2) 0px 0px 0px 1px. Inside, add a heading: "Instant Insights" using Inter, 20px, weight 600, Graphite (#111827), letter-spacing -0.2px. Below, add body text: "Leverage AI to get data in minutes." using Inter, 14px, weight 400, Slate Blue (#4b5563), letter-spacing -0.14px. Inner padding should be 16px.
4. **Create a Pill Tag:** Text: "Surveys" using Inter, 14px, weight 400, Graphite (#111827). Background: Ash Gray (#f9fafb). Border radius: 9999px. Padding: 7px horizontal, 0px vertical.
5. **Compose a Navigation Link:** Text: "Solutions" using Inter, 16px, weight 500, Graphite (#111827). On hover, change text to Pitch Black (#000000). Active state adds a 2px underline in Rocket Red (#fc4a2b). Padding: 8px vertical, 12px horizontal.

## Similar Brands

- **Figma** — Clean, high-contrast UI with a single vibrant accent color and strong typography, prioritizing clarity in a complex tool.
- **Stripe** — Understated design with strategic use of negative space, crisp typography, and an emphasis on structure for technical products.
- **Linear** — Focus on high-contrast text and interactive elements, minimalist aesthetic, and custom typography to maintain readability and precision.
- **Notion** — Utilizes generous white space, a functional grey palette, and clear text hierarchy to present information dense content accessibly.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-ghost-white: #ffffff;
  --color-ash-gray: #f9fafb;
  --color-graphite: #111827;
  --color-slate-blue: #4b5563;
  --color-medium-gray: #374151;
  --color-light-gray: #6b7280;
  --color-border-gray: #e5e7eb;
  --color-rocket-red: #fc4a2b;
  --color-passion-red: #e11d48;
  --color-sunset-orange: #f97316;
  --color-coral-glow: #ffac9;
  --color-pale-peach: #ffe5e0;
  --color-success-green: #15803d;
  --color-warning-yellow: #f59e0b;
  --color-pill-button-gradient: #f87171;
  --gradient-pill-button-gradient: linear-gradient(268.33deg, rgb(248, 113, 113), rgb(254, 202, 202), rgb(254, 226, 226), rgb(254, 242, 242));

  /* Typography — Font Families */
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-source-serif-4: 'Source Serif 4', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.5px;
  --text-body: 14px;
  --leading-body: 1.6;
  --tracking-body: -0.14px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.36px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --tracking-heading: -0.48px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.47px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -3.36px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

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
  --spacing-56: 56px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 64-96px;
  --card-padding: 14-24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 1.5px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 36px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-cards: 10px;
  --radius-images: 6px;
  --radius-inputs: 6px;
  --radius-buttons: 6px;
  --radius-interactive: 100px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 6px 9px 0px;
  --shadow-subtle: rgba(75, 85, 99, 0.2) 0px 0px 0px 1px;
  --shadow-xl: rgba(50, 50, 92, 0.05) 0px 50px 100px -20px, rgba(0, 0, 0, 0.15) 0px 30px 60px -30px;
  --shadow-subtle-2: rgb(252, 74, 43) 0px 0px 0px 2px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-4: rgba(75, 85, 99, 0.2) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 2px 2px 0px;
  --shadow-subtle-5: rgb(17, 24, 39) 0px 0px 0px 1px;
  --shadow-subtle-6: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px, rgba(75, 85, 99, 0.2) 0px 0px 0px 1px;
  --shadow-subtle-7: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px inset, rgb(249, 250, 251) 0px 0px 0px 10px;
  --shadow-subtle-8: rgb(255, 255, 255) 0px 0px 0px 1px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-ghost-white: #ffffff;
  --color-ash-gray: #f9fafb;
  --color-graphite: #111827;
  --color-slate-blue: #4b5563;
  --color-medium-gray: #374151;
  --color-light-gray: #6b7280;
  --color-border-gray: #e5e7eb;
  --color-rocket-red: #fc4a2b;
  --color-passion-red: #e11d48;
  --color-sunset-orange: #f97316;
  --color-coral-glow: #ffac9;
  --color-pale-peach: #ffe5e0;
  --color-success-green: #15803d;
  --color-warning-yellow: #f59e0b;
  --color-pill-button-gradient: #f87171;

  /* Typography */
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-source-serif-4: 'Source Serif 4', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.5px;
  --text-body: 14px;
  --leading-body: 1.6;
  --tracking-body: -0.14px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.36px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --tracking-heading: -0.48px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.47px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -3.36px;

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
  --spacing-56: 56px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 1.5px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 36px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 6px 9px 0px;
  --shadow-subtle: rgba(75, 85, 99, 0.2) 0px 0px 0px 1px;
  --shadow-xl: rgba(50, 50, 92, 0.05) 0px 50px 100px -20px, rgba(0, 0, 0, 0.15) 0px 30px 60px -30px;
  --shadow-subtle-2: rgb(252, 74, 43) 0px 0px 0px 2px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-4: rgba(75, 85, 99, 0.2) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 2px 2px 0px;
  --shadow-subtle-5: rgb(17, 24, 39) 0px 0px 0px 1px;
  --shadow-subtle-6: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px, rgba(75, 85, 99, 0.2) 0px 0px 0px 1px;
  --shadow-subtle-7: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px inset, rgb(249, 250, 251) 0px 0px 0px 10px;
  --shadow-subtle-8: rgb(255, 255, 255) 0px 0px 0px 1px;
}
```
