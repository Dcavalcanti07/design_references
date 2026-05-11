# Loops — Style Reference
> Architectural blueprint on white marble. Sharp, clean, and formally structured.

**Theme:** light

Loops presents a precise, document-like interface with stark black typography on crisp white and soft gray backgrounds. A distinctive, serif-led typographic voice for headlines creates an established feel, contrasting with system sans-serifs for body text and interactive elements. Interaction is direct and functional, guided by subtle borders, soft shadows, and a singular, vibrant orange accent for specific highlights and calls to attention, rather than primary actions. The overall impression is one of clarity, focused content, and understated authority.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, strong headings, critical UI elements, default icon color |
| Greige Canvas | `#faf9f7` | `--color-greige-canvas` | Page background, primary canvas |
| Whisper White | `#ffffff` | `--color-whisper-white` | Card backgrounds, elevated surfaces |
| Slate Gray | `#1c1917` | `--color-slate-gray` | Secondary text, subheadings, some button backgrounds, code backgrounds, dark borders. Provides depth without pure black |
| Fog | `#d6d3d1` | `--color-fog` | Subtle borders, inactive elements, visual dividers. Establishes UI structure |
| Ash | `#e7e5e4` | `--color-ash` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Stone | `#44403c` | `--color-stone` | Body text for extended reading |
| Pewter | `#a8a29e` | `--color-pewter` | Muted text, helper text, less prominent icons, secondary borders |
| Warm Gray | `#292524` | `--color-warm-gray` | Body text in specific content blocks, slightly softer than Midnight Ink |
| Steel | `#57534e` | `--color-steel` | Link color, prominent muted text |
| Silver | `#78716c` | `--color-silver` | Tertiary text, less important UI information |
| Porcelain | `#f1efef` | `--color-porcelain` | Subtle button backgrounds, very light surface differentiation |
| Flame Orange | `#f97316` | `--color-flame-orange` | Highlight accent for specific words, icons, and informational elements. Demands attention without being a primary interaction color |

## Tokens — Typography

### Newsreader — Headlines and prominent display text. The single bold weight and tightly tracked serif create a commanding, editorial presence with a classic feel, establishing authority without shouting. · `--font-newsreader`
- **Weights:** 600
- **Sizes:** 28px, 34px, 80px
- **Line height:** 1.00, 1.20, 1.25
- **Letter spacing:** -0.04em at 80px, -0.03em at 34px, -0.02em at 28px
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Headlines and prominent display text. The single bold weight and tightly tracked serif create a commanding, editorial presence with a classic feel, establishing authority without shouting.

### sans-serif — General body text, navigation elements, and some button labels. Its neutral presence provides clarity and balance to the more opinionated headline font. · `--font-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400, 600
- **Sizes:** 12px, 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** General body text, navigation elements, and some button labels. Its neutral presence provides clarity and balance to the more opinionated headline font.

### ui-sans-serif — Detailed UI text, small labels, and interactive components. The varied weights and slight letter-spacing adjustments support hierarchy and legibility in compact spaces. · `--font-ui-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 17px
- **Line height:** 1.00, 1.20, 1.25, 1.30, 1.35
- **Letter spacing:** -0.02em, -0.015em, 0.01em
- **Role:** Detailed UI text, small labels, and interactive components. The varied weights and slight letter-spacing adjustments support hierarchy and legibility in compact spaces.

### Inter — Contextual body text, links, and specific button text within components. Offers a slightly wider range of weights for granular control over emphasis. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 450, 500, 600
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 17px, 19px
- **Line height:** 0.75, 1.00, 1.20, 1.33, 1.40, 1.43, 1.50, 1.60, 1.65, 1.80
- **Letter spacing:** -0.02em, -0.01em, 0.08em
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Contextual body text, links, and specific button text within components. Offers a slightly wider range of weights for granular control over emphasis.

### ui-monospace — Code snippets and developer-focused content. Maintains consistent character width for readability in technical displays. · `--font-ui-monospace`
- **Substitute:** monospace
- **Weights:** 400, 500
- **Sizes:** 14px, 16px
- **Line height:** 1.16, 1.20, 1.29, 1.78
- **Letter spacing:** normal
- **Role:** Code snippets and developer-focused content. Maintains consistent character width for readability in technical displays.

### Iowan Old Style — Specific body text in short, descriptive paragraphs. Its serif nature provides a softer, more traditional voice compared to the sans-serif body. · `--font-iowan-old-style`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.45
- **Letter spacing:** normal
- **Role:** Specific body text in short, descriptive paragraphs. Its serif nature provides a softer, more traditional voice compared to the sans-serif body.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1.29 | — | `--text-body-sm` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 20px | 1.45 | — | `--text-subheading` |
| heading | 28px | 1.25 | -0.56px | `--text-heading` |
| heading-lg | 34px | 1.2 | -1.02px | `--text-heading-lg` |
| display | 80px | 1 | -3.2px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 108 | 108px | `--spacing-108` |
| 140 | 140px | `--spacing-140` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 999px |
| cards | 8px |
| buttons | 8px |
| default | 8px |
| elevatedCards | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.05) 0px 1px 4px 0px, rgba(0, 0, 0, 0.03) ...` | `--shadow-sm` |
| subtle | `rgba(255, 255, 255, 0.07) 0px 1px 0px 0px inset, rgba(255...` | `--shadow-subtle` |
| subtle-2 | `rgb(214, 211, 209) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgb(231, 229, 228) 0px 0px 0px 1px inset` | `--shadow-subtle-3` |
| subtle-4 | `rgba(0, 0, 0, 0.04) 0px 1px 2px 0px, rgba(0, 0, 0, 0.03) ...` | `--shadow-subtle-4` |

### Layout

- **Section gap:** 40px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Pill Ghost Button
**Role:** Secondary action or tag within content.

Background: Ash (#e7e5e4), Text: Stone (#44403c), Border: Ash (#e7e5e4) 1px, Radius: 999px, Padding: 7px vertical, 13px horizontal. This button offers a soft visual presence as a non-primary interaction.

### Standard Ghost Button
**Role:** Informational or subtle action within the UI.

Background: Porcelain (#f1efef), Text: Warm Gray (#292524), Border: none, Radius: 8px, Padding: 0px. Used for tab-like controls or category filters.

### Outlined Card
**Role:** Content container with an emphasis on its contained nature.

Background: Whisper White (#ffffff), Border: Fog (#d6d3d1) 1px, Radius: 8px, Padding: 14px vertical, 18px horizontal. A clear boundary for grouped information.

### Navigation Link
**Role:** Primary navigation item.

Text: Midnight Ink (#000000), Weight: 400, Size: 16px, Line height: 1.2. No explicit background or border, relies on text for presence.

### Hero Action Button
**Role:** Primary Call to Action.

Background: Slate Gray (#1c1917), Text: Whisper White (#ffffff), Border: none, Radius: 8px, Padding: ~14-18px horizontal, flexible vertical. The solid fill and dark color make it stand out as the main action, contrasting with lighter secondary ghost buttons.

### Elevated Content Card
**Role:** Highlighting key information or interactive blocks.

Background: Whisper White (#ffffff), Border: none, Radius: 12px, Shadow: rgba(0, 0, 0, 0.05) 0px 1px 4px 0px, rgba(0, 0, 0, 0.03) 0px 0px 0px 0.5px. The soft shadow provides a subtle lift from the background.

### Code Block Card
**Role:** Showcasing code snippets or API examples.

Background: Greige Canvas (#faf9f7), Border: none, Radius: 14px, Padding: 12px vertical, 10px horizontal. A slightly darker background visually separates code from standard content. Text uses ui-monospace.

### Monochrome Tab Button
**Role:** Switching between content views.

Background: transparent, Text: Slate Gray (#1c1917), Border: none, Radius: 0px, flexible padding. Underlined on active state with a solid color from the main text palette.

## Do's and Don'ts

### Do
- Use Newsreader 600 with tight letter-spacing for all primary headings (display, heading-lg, heading).
- Employ Greige Canvas (#faf9f7) as the default page background to maintain a light, expansive feel.
- Accentuate specific terms using Flame Orange (#f97316) for keywords in body text or small decorative icons.
- Structure interactive elements and content cards with a default border-radius of 8px, defaulting to 12px for elevated cards.
- Utilize Slate Gray (#1c1917) as the background for primary action buttons to create visual weight and clear calls to action.
- Apply Soft Shadows (rgba(0, 0, 0, 0.05) 0px 1px 4px 0px, rgba(0, 0, 0, 0.03) 0px 0px 0px 0.5px) sparingly for only truly elevated components like cards or modals.
- Implement the 12px unit as the primary elementGap for vertical and horizontal spacing between content blocks.

### Don't
- Do not use saturated colors other than Flame Orange (#f97316) unless for semantic success/error states.
- Avoid heavy drop shadows; elevation should be subtle, usually a single soft shadow layer.
- Do not deviate from the specified serif for headlines; maintain its distinct, opinionated character.
- Refrain from using complex background gradients; surfaces should remain flat or subtly shaded neutrals.
- Do not use pure white for large content blocks unless it's a card on a Greige Canvas (#faf9f7) background.
- Avoid excessive spacing or overly large typography for body text; prioritize compact and dense readability.
- Do not introduce new typefaces; rely on the established system sans-serifs, Newsreader, and ui-monospace.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Greige Canvas | `#faf9f7` | Dominant page background, a subtle off-white base. |
| 1 | Whisper White | `#ffffff` | Primary surface for cards, content blocks, and interactive components. Appears brighter against the canvas. |
| 2 | Elevated Card | `#ffffff` | Key information cards, subtly lifted using a soft shadow, maintaining Whisper White as the background. |

## Imagery

The site largely avoids decorative imagery beyond simple, functional icons and product screenshots. Photography is absent. Icons are typically solid black or Slate Gray (#1c1917), exhibiting a filled style with clean lines, conveying functionality. Product screenshots are contained within cards or code-like blocks, serving an explanatory and demonstrative role rather than aesthetic adornment. The density is text-dominant, with visuals acting as clear, explanatory anchors.

## Layout

The page uses a maximum-width contained layout, likely around 1200px, centered on the screen. The hero section features a large, centered headline and subtext, followed by a dark, filled button and a ghost button. Content sections alternate between centered text blocks and multi-column layouts, often featuring a 2-column arrangement with text on one side and a content card (like a code block or screenshot) on the other. Vertical spacing between logical sections is consistent and comfortable. The navigation is a minimalist top bar with log-in/start buttons and a left-aligned sidebar for secondary navigation, maintaining a clean, focused presentation.

## Agent Prompt Guide

**Quick Color Reference:** 
- text: #000000
- background: #faf9f7
- border: #d6d3d1
- accent: #f97316
- primary action: no distinct CTA color

**3-5 Example Component Prompts:**
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2.  Create an elevated content card: Whisper White (#ffffff) background, 12px radius, Shadow: rgba(0, 0, 0, 0.05) 0px 1px 4px 0px, rgba(0, 0, 0, 0.03) 0px 0px 0px 0.5px. Inside, a heading (heading role, Newsreader 600, Midnight Ink #000000) 'Email design from first principles'. Body text (body role, Stone #44403c). A soft ghost tab button 'Human' (Standard Ghost Button, Porcelain #f1efef background, Warm Gray #292524 text) and 'Agent Alpha' (Standard Ghost Button, Porcelain #f1efef background, Warm Gray #292524 text). 
3.  Create a code block card: Greige Canvas (#f1efef) background, 14px radius, no shadow. Content uses ui-monospace 14px, Midnight Ink (#000000). A muted link within the text uses Flame Orange (#f97316).
4.  Create a navigation bar: Greige Canvas (#faf9f7) background. Left logo. Right buttons: 'Log In' (Whisper White #ffffff text, no button style, regular sans-serif), 'Start' (Hero Action Button, Slate Gray #1c1917 background, Whisper White #ffffff text, 8px radius).

## Similar Brands

- **Vercel** — Similar stark black/white monochrome palette, focus on developer tools and content, and minimalist UI emphasizing functionality.
- **Stripe** — Uses large, impactful serif headlines for brand presence alongside system sans-serifs for UI, combined with a clean, mostly achromatic interface and subtle card-based layouts.
- **Linear** — Shares the use of system fonts, a strong dark-on-light theme, and subtle elevation for cards and components, creating a highly functional and fast interface feel.
- **Supabase** — Features strong, clear typography on clean backgrounds, with code snippets as a prominent content type, and minimal use of bright accent colors. 
- **Resend** — Specific focus on transactional email like Loops, and similar aesthetic principles of clean, minimalist design with clear typography and functional UI rather than heavy branding.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-greige-canvas: #faf9f7;
  --color-whisper-white: #ffffff;
  --color-slate-gray: #1c1917;
  --color-fog: #d6d3d1;
  --color-ash: #e7e5e4;
  --color-stone: #44403c;
  --color-pewter: #a8a29e;
  --color-warm-gray: #292524;
  --color-steel: #57534e;
  --color-silver: #78716c;
  --color-porcelain: #f1efef;
  --color-flame-orange: #f97316;

  /* Typography — Font Families */
  --font-newsreader: 'Newsreader', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-iowan-old-style: 'Iowan Old Style', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.29;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 20px;
  --leading-subheading: 1.45;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.56px;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.02px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -3.2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-108: 108px;
  --spacing-140: 140px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-pill: 999px;
  --radius-cards: 8px;
  --radius-buttons: 8px;
  --radius-default: 8px;
  --radius-elevatedcards: 12px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 1px 4px 0px, rgba(0, 0, 0, 0.03) 0px 0px 0px 0.5px;
  --shadow-subtle: rgba(255, 255, 255, 0.07) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.06) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.25) 0px 1px 2px 0px, rgba(0, 0, 0, 0.15) 0px 2px 6px 0px;
  --shadow-subtle-2: rgb(214, 211, 209) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgb(231, 229, 228) 0px 0px 0px 1px inset;
  --shadow-subtle-4: rgba(0, 0, 0, 0.04) 0px 1px 2px 0px, rgba(0, 0, 0, 0.03) 0px 1px 4px 0px;

  /* Surfaces */
  --surface-greige-canvas: #faf9f7;
  --surface-whisper-white: #ffffff;
  --surface-elevated-card: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-greige-canvas: #faf9f7;
  --color-whisper-white: #ffffff;
  --color-slate-gray: #1c1917;
  --color-fog: #d6d3d1;
  --color-ash: #e7e5e4;
  --color-stone: #44403c;
  --color-pewter: #a8a29e;
  --color-warm-gray: #292524;
  --color-steel: #57534e;
  --color-silver: #78716c;
  --color-porcelain: #f1efef;
  --color-flame-orange: #f97316;

  /* Typography */
  --font-newsreader: 'Newsreader', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-iowan-old-style: 'Iowan Old Style', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.29;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 20px;
  --leading-subheading: 1.45;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.56px;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.02px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -3.2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-108: 108px;
  --spacing-140: 140px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 1px 4px 0px, rgba(0, 0, 0, 0.03) 0px 0px 0px 0.5px;
  --shadow-subtle: rgba(255, 255, 255, 0.07) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.06) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.25) 0px 1px 2px 0px, rgba(0, 0, 0, 0.15) 0px 2px 6px 0px;
  --shadow-subtle-2: rgb(214, 211, 209) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgb(231, 229, 228) 0px 0px 0px 1px inset;
  --shadow-subtle-4: rgba(0, 0, 0, 0.04) 0px 1px 2px 0px, rgba(0, 0, 0, 0.03) 0px 1px 4px 0px;
}
```
