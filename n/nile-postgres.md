# Nile Postgres — Style Reference
> Midnight console, glowing accents

**Theme:** dark

Nile uses a 'command center cool' dark theme, presenting information on deep black canvases with contrasting crisp white text. Interactive elements are marked by a singular, vivid cyan accent, drawing the eye and signaling functionality. The system balances highly contained information blocks with spacious navigation, emphasizing clarity and quick comprehension.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0e0e0e` | `--color-midnight-ink` | Primary background for pages and default surfaces |
| Carbon Panel | `#1c1c1c` | `--color-carbon-panel` | Secondary surface for cards and elevated components, providing subtle depth against the main background |
| Ash Gray | `#3f3f3f` | `--color-ash-gray` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Steel Gray | `#2f3336` | `--color-steel-gray` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Smoke | `#2b2b2b` | `--color-smoke` | Subtle background for UI elements, slightly lighter than Carbon Panel |
| Ghost White | `#ffffff` | `--color-ghost-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Silver Muted | `#d3d3d3` | `--color-silver-muted` | Secondary text for body copy, icons, and less prominent information |
| Slate Text | `#a1a1aa` | `--color-slate-text` | Muted helper text, captions, and copyright information |
| Cyber Cyan | `#6fe2ff` | `--color-cyber-cyan` | Primary action background, indicator for active states, link highlights, and brand accents |
| Amber Glow | `#ffba6a` | `--color-amber-glow` | Decorative card background for illustrative content sections |
| Violet Haze | `#d8d3ff` | `--color-violet-haze` | Decorative card background for illustrative content sections, providing visual variety |
| Gradient Wash | `linear-gradient(170deg, rgb(244, 197, 135) 7.25%, rgb(214, 211, 233) 50.26%, rgb(153, 210, 236) 93.27%)` | `--color-gradient-wash` | Decorative background for attention-grabbing sections, combining warm and cool tones for a soft, tech-infused glow |

## Tokens — Typography

### aeonik — Primary typeface for all headings and body text, providing a technical yet friendly feel. Varied weights and sizes structure information hierarchy. · `--font-aeonik`
- **Substitute:** system-ui
- **Weights:** 400, 600, 700
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 24px, 32px, 40px, 42px, 48px, 64px, 96px
- **Line height:** 1.00, 1.08, 1.10, 1.18, 1.20, 1.25, 1.43, 1.50, 1.56, 1.60
- **Letter spacing:** -0.0100em at 40px and higher, 0.0100em at 12-16px, normal at other sizes
- **Role:** Primary typeface for all headings and body text, providing a technical yet friendly feel. Varied weights and sizes structure information hierarchy.

### aeonik — Medium weight for specific navigation elements, subheadings, and emphasized text segments. · `--font-aeonik`
- **Substitute:** system-ui
- **Weights:** 500
- **Sizes:** 16px, 20px, 24px, 96px
- **Line height:** 1.00, 1.20, 1.25, 1.50
- **Letter spacing:** normal
- **Role:** Medium weight for specific navigation elements, subheadings, and emphasized text segments.

### ui-monospace — Monospace typeface exclusively for code blocks and technical content, maintaining readability for developers. · `--font-ui-monospace`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.14, 1.18, 1.50
- **Letter spacing:** 0.0100em
- **Role:** Monospace typeface exclusively for code blocks and technical content, maintaining readability for developers.

### Inter — Minimal usage for small print or meta information, offering high legibility at small sizes. · `--font-inter`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.33
- **Letter spacing:** normal
- **Role:** Minimal usage for small print or meta information, offering high legibility at small sizes.

### aeonikMedium — aeonikMedium — detected in extracted data but not described by AI · `--font-aeonikmedium`
- **Weights:** 500
- **Sizes:** 16px, 20px, 24px, 96px
- **Line height:** 1, 1.2, 1.25, 1.5
- **Role:** aeonikMedium — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.33 | 0.12px | `--text-caption` |
| body-sm | 14px | 1.25 | 0.14px | `--text-body-sm` |
| body | 16px | 1.5 | 0.16px | `--text-body` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading | 32px | 1.18 | — | `--text-heading` |
| heading-lg | 48px | 1.08 | -0.48px | `--text-heading-lg` |
| display | 96px | 1 | -0.96px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 10px |
| cards | 16px |
| buttons | 9999px |
| hero-cards | 20px |
| large-elements | 100px |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call-to-action button for initiating key actions.

Filled button with a Cyber Cyan background (#6fe2ff), Midnight Ink text (#0e0e0e), 10px corner radius, and 20px horizontal padding.

### Ghost Action Button
**Role:** Secondary action or navigational button within the dark theme.

Ghost button with a Carbon Panel background (#1c1c1c), Ghost White text (#ffffff), a 1px solid Ash Gray border (#3f3f3f), and 9999px (pill-shaped) corner radius. Padding is 8px vertical, 16px horizontal.

### Tertiary Ghost Button
**Role:** Subtle interactive button, often for 'View on X' or less prominent actions.

Ghost button with Midnight Ink background (#0e0e0e), Ghost White text (#ffffff), a 1px solid Carbon Panel border (#1c1c1c), and 10px corner radius.

### Testimonial Card
**Role:** Displaying short quotes or testimonials.

Card with Carbon Panel background (#1c1c1c), 16px border radius, and 16px internal padding. No distinct shadow.

### Hero Feature Card
**Role:** Highlights key features with distinct background colors.

Card with varied accent background colors (Amber Glow #ffba6a or Violet Haze #d8d3ff), 20px border radius, and generous internal padding.

### Monospace Code Block
**Role:** Showcasing code snippets.

Card with a Carbon Panel background (#1c1c1c), 20px border radius, and featuring text in ui-monospace font, Silver Muted (#d3d3d3) color.

### Gradient Highlight Card
**Role:** Attention-grabbing information card with a unique background.

Card with a Gradient Wash linear-gradient background (utilizing rgb(244, 197, 135) to rgb(153, 210, 236) via rgb(214, 211, 233)), 20px border radius, and Ghost White text.

### Inline Notification Tag
**Role:** Small, informational tag.

Small dark tag with a Carbon Panel background (#1c1c1c), Ghost White text (#ffffff), and a 10px border radius. Padding is 8px vertical and 16px horizontal.

## Do's and Don'ts

### Do
- Use Midnight Ink (#0e0e0e) as the base background for all pages and sections, maintaining the dark theme.
- Apply Cyber Cyan (#6fe2ff) exclusively for primary calls to action, active states, and brand highlights, never for decorative elements.
- Structure information hierarchy using aeonik (weights 400, 600, 700) with Ghost White (#ffffff) for headings and Silver Muted (#d3d3d3) for body text.
- Ensure all interactive elements, including buttons and links, have a minimum contrast ratio of 14:1 (Ghost White on Midnight Ink) as seen in contrast pairs analysis.
- Utilize 9999px border-radius for all primary and ghost buttons to create a distinctive pill shape.
- Maintain consistent vertical spacing between sections using the sectionGap token of 40px.
- For code snippets, employ the ui-monospace font at 14px with Silver Muted (#d3d3d3) text color on a Carbon Panel (#1c1c1c) background.

### Don't
- Avoid using bright or overly saturated colors outside of the defined accent palette; maintain a subdued, dark aesthetic.
- Do not introduce shadows or elevation effects unless they explicitly use the blue-tinted drop-shadow style or are for decorative illustration purposes.
- Do not apply the general content letter-spacing of 0.0100em from aeonik to large headings; use normal letter-spacing unless specified.
- Never use achromatic colors for primary button backgrounds; always use Cyber Cyan (#6fe2ff) for filled primary actions.
- Do not deviate from the defined border radii; ensure cards use 16px or 20px and interactive elements use 10px or 9999px for consistency.
- Avoid using any gradients for interactive components; gradients are reserved for large decorative cards and background sections.
- Do not use generic system fonts for headings or main body text; all primary typography must adhere to the aeonik family.

## Imagery

This design system prioritizes a blend of abstract 3D renders for high-impact hero sections, often utilizing iridescent or glow effects within dark compositions. Product-focused graphics, such as stylized chip diagrams and code snippets, serve explanatory content. Photography is absent. Icons, where present, are outline-based with a slightly thicker stroke, often monochromatic or subtly tinted with brand colors, serving functional and decorative roles. The overall density of imagery is balanced, with visuals often contained within card-like structures or featuring negative space to allow the UI to breathe.

## Layout

The page primarily uses a max-width contained layout of 1280px, with content centered. The hero section is full-bleed, a deep black canvas with a centered headline and a call to action. Subsequent sections often feature alternating two-column layouts (text on left, visual on right, or vice-versa) or three-column card grids for features and testimonials. Vertical rhythm is established through consistent section gaps. Navigation is a sticky top bar with minimal links and prominent action buttons on the right.

## Agent Prompt Guide

primary action: #6fe2ff (filled action)
Create a Primary Action Button: #6fe2ff background, #0e0e0e text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:
1. Create a Hero Headline: 'Build Finance B2B apps fast' using aeonik, 96px, weight 700, #ffffff, letter-spacing -0.0100em. Below it, a subheading: 'PostgreSQL re-engineered for multi-tenant apps' using aeonik, 24px, weight 400, #d3d3d3, normal letter-spacing.
2. Design a Primary Action Button: Text 'Build with Nile →' (aeonik, 16px, weight 400), background #6fe2ff, text color #0e0e0e, border radius 10px, padding 0px for top/bottom, 20px for left/right.
3. Create a Testimonial Card: Carbon Panel background (#1c1c1c), 16px border radius, 16px padding on all sides. Text inside should be aeonik, 16px, weight 400, #d3d3d3, normal letter-spacing.
4. Produce a Code Block: Carbon Panel background (#1c1c1c), 20px border radius, showing code in ui-monospace, 14px, weight 400, #d3d3d3, letter-spacing 0.0100em.
5. Design a Ghost Navigation Button: Text 'Docs' (aeonik, 16px, weight 400), background #1c1c1c, text color #d3d3d3, 1px solid #3f3f3f border, 9999px border radius, 8px vertical padding, 16px horizontal padding.

## Similar Brands

- **Vercel** — Similar dark-mode aesthetic with strong typography and a focus on developer tools. Uses a single accent color for interaction.
- **Supabase** — Shared database/developer tool context, dark UI with clear information hierarchy and often vibrant accent colors for brand elements.
- **Linear** — Systematic dark UI, precise typography, and a command-center feel for productivity and dev tools.
- **Prisma** — Developer-focused brand with a clean dark interface, strong use of monospace fonts for code, and a refined brand color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0e0e0e;
  --color-carbon-panel: #1c1c1c;
  --color-ash-gray: #3f3f3f;
  --color-steel-gray: #2f3336;
  --color-smoke: #2b2b2b;
  --color-ghost-white: #ffffff;
  --color-silver-muted: #d3d3d3;
  --color-slate-text: #a1a1aa;
  --color-cyber-cyan: #6fe2ff;
  --color-amber-glow: #ffba6a;
  --color-violet-haze: #d8d3ff;
  --color-gradient-wash: #f4c587;
  --gradient-gradient-wash: linear-gradient(170deg, rgb(244, 197, 135) 7.25%, rgb(214, 211, 233) 50.26%, rgb(153, 210, 236) 93.27%);

  /* Typography — Font Families */
  --font-aeonik: 'aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonikmedium: 'aeonikMedium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.18;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.08;
  --tracking-heading-lg: -0.48px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -0.96px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-160: 160px;
  --spacing-192: 192px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 100px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-tags: 10px;
  --radius-cards: 16px;
  --radius-buttons: 9999px;
  --radius-hero-cards: 20px;
  --radius-large-elements: 100px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0e0e0e;
  --color-carbon-panel: #1c1c1c;
  --color-ash-gray: #3f3f3f;
  --color-steel-gray: #2f3336;
  --color-smoke: #2b2b2b;
  --color-ghost-white: #ffffff;
  --color-silver-muted: #d3d3d3;
  --color-slate-text: #a1a1aa;
  --color-cyber-cyan: #6fe2ff;
  --color-amber-glow: #ffba6a;
  --color-violet-haze: #d8d3ff;
  --color-gradient-wash: #f4c587;

  /* Typography */
  --font-aeonik: 'aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonikmedium: 'aeonikMedium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.18;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.08;
  --tracking-heading-lg: -0.48px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -0.96px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-160: 160px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 100px;
  --radius-full-2: 9999px;
}
```
