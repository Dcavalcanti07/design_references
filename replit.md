# replit — Style Reference
> Warm, creative studio. Like paper and clay in a sunlit workbench, punctuated by a streak of vibrant orange.

**Theme:** light

Replit's design system evokes a playful yet powerful creative studio, featuring a bright, almost tactile off-white canvas overlaid with soft, rounded forms. Vivid orange accents punctuate the UI, highlighting active states and key actions, suggesting energy and innovation. Typography balances modern geometric sans-serifs with classic readability, often employing tight tracking for headlines to convey a sense of precision and forward momentum. Components are distinctly shaped with generous radii, ranging from slight curves to full pills, giving the interface a friendly, approachable feel despite its technical focus.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#faf6f1` | `--color-canvas` | Primary background for pages and larger sections, giving a warm, paper-like foundation to the UI |
| Ghost | `#ffffff` | `--color-ghost` | Background for elevated cards, active elements, and distinct content blocks, providing a crisp contrast against the Canvas |
| Carbon | `#0e0e0f` | `--color-carbon` | Primary body text, main headings, and significant borders. Provides strong contrast and visual weight to core content |
| Lead | `#36373b` | `--color-lead` | Secondary text, subheadings, and contextual UI elements. Slightly softer than Carbon for less emphasis |
| Ash | `#898c94` | `--color-ash` | Muted text, helper labels, placeholder text, and subtle borders. Used for information of lower hierarchy |
| Stone | `#dfddd8` | `--color-stone` | Subtle borders, dividers, and ghost button outlines, providing gentle separation without harsh lines |
| Off-White Accent | `#cbc7c3` | `--color-off-white-accent` | Decorative backgrounds and subtle content dividers. Slightly darker than Canvas to provide minimal depth |
| Slate | `#52545a` | `--color-slate` | Caption text and tertiary information, a slightly darker gray for smaller text sizes |
| Black | `#000000` | `--color-black` | Strictly for contrast-critical borders and some iconic elements |
| Signal Orange | `#ff3c00` | `--color-signal-orange` | Primary call-to-action buttons, active navigation indicators, and key interactive elements – a potent focal point |
| Deep Orange | `#ec4e02` | `--color-deep-orange` | Accent for small icons, decorative fills, and specific text highlights that require a deeper orange hue |
| Soft Peach | `#ffb199` | `--color-soft-peach` | Large decorative card backgrounds and graphic elements, adding a warm, inviting tone |
| Vivid Coral | `#ff764c` | `--color-vivid-coral` | Large decorative card backgrounds, used for higher visual impact than Soft Peach |
| Accent Blue | `#2492ff` | `--color-accent-blue` | Blue outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |

## Tokens — Typography

### ABC Diatype — Body text and general UI elements. Its clean, geometric form ensures readability in diverse contexts. · `--font-abc-diatype`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 13px, 14px, 16px, 32px
- **Line height:** 1.20, 1.25, 1.38, 1.50, 1.60
- **Letter spacing:** normal
- **Role:** Body text and general UI elements. Its clean, geometric form ensures readability in diverse contexts.

### ABC Diatype Plus Variable — Headings, display text, and emphasized UI elements. Variable font provides precise control over weight and a distinct, slightly condensed feel, especially with tight letter-spacing. · `--font-abc-diatype-plus-variable`
- **Substitute:** Inter Variable
- **Weights:** 400, 500, 600, 700
- **Sizes:** 8px, 10px, 11px, 12px, 14px, 15px, 16px, 17px, 18px, 20px, 24px, 26px, 28px, 32px, 42px, 48px, 60px, 64px, 69px
- **Line height:** 0.80, 0.83, 0.89, 1.00, 1.05, 1.10, 1.20, 1.40, 1.60
- **Letter spacing:** -0.01em at 12px, -0.02em at 16px, -0.03em at 24px, -0.04em at 48px, etc.
- **Role:** Headings, display text, and emphasized UI elements. Variable font provides precise control over weight and a distinct, slightly condensed feel, especially with tight letter-spacing.

### IBM Plex Sans — Specific utility text or code snippets, chosen for its clear, monospace-like qualities and distinct character shapes at small sizes. · `--font-ibm-plex-sans`
- **Substitute:** IBM Plex Sans
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.00, 1.20, 1.57
- **Letter spacing:** normal
- **Role:** Specific utility text or code snippets, chosen for its clear, monospace-like qualities and distinct character shapes at small sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.5 | -0.14px | `--text-body` |
| body-lg | 16px | 1.4 | -0.32px | `--text-body-lg` |
| subheading | 24px | 1.2 | -0.72px | `--text-subheading` |
| heading | 32px | 1.1 | -0.96px | `--text-heading` |
| heading-lg | 48px | 1.05 | -1.92px | `--text-heading-lg` |
| display | 69px | 0.8 | -4.14px | `--text-display` |

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
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| lg | 20px |
| md | 16px |
| sm | 6px |
| xl | 40px |
| 2xl | 60px |
| none | 0px |
| pill | 90px |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with 'Signal Orange' (#ff3c00) background, 'Ghost' (#ffffff) text, and a generous 'pill' (90px) border-radius. Padding is 10px vertical, 40px horizontal.

### Ghost Border Button
**Role:** Secondary action

Transparent background with 'Carbon' (#0e0e0f) text and a 'Ghost' (#ffffff) border. Border-radius is 'sm' (6px) with an 8px horizontal padding, primarily used for internal navigation.

### Muted Border Button
**Role:** Tertiary action or filter tag

Background 'Ghost' (#ffffff) with 'Lead' (#36373b) text and 'Stone' (#dfddd8) border. 'Sm' (6px) border-radius, 8px horizontal padding, for less prominent interactions or categorization.

### Feature Card
**Role:** Product feature display

Background 'Ghost' (#ffffff) with '2xl' (60px) border-radius. Contains internal padding of 48px, used for presenting key functionalities.

### Decorative Section Card
**Role:** Visual content container

Background can be 'Soft Peach' (#ffb199) or 'Vivid Coral' (#ff764c) with a large 'xl' or '2xl' (40px or 70px) border-radius, often with no internal padding for full-bleed graphics.

### Text Input
**Role:** User entry field

Transparent background with 'Carbon' (#0e0e0f) or 'Lead' (#36373b) text. The border color matches the text color, and border-radius is 'sm' (6px). Input has 4px vertical, 8px horizontal padding.

## Do's and Don'ts

### Do
- Prioritize 'Canvas' (#faf6f1) as the primary page background to maintain the warm, receptive visual tone.
- Use 'Signal Orange' (#ff3c00) exclusively for primary calls-to-action to maximize impact and user focus.
- Apply generous border-radii: 'pill' (90px) for prominent buttons, '2xl' (60px) for key cards, and 'sm' (6px) for inputs and less prominent interactive elements.
- Employ ABC Diatype Plus Variable with tight letter-spacing (e.g., -1.92px at 48px) for all headings to create a modern, precise feel.
- Utilize 'Carbon' (#0e0e0f) for main body text and 'Ash' (#898c94) for secondary or descriptive text consistently for clear hierarchy.
- Maintain a comfortable density with an 'elementGap' of 8px and 'cardPadding' of 24px between internal block elements.

### Don't
- Avoid using multiple bright accent colors; 'Signal Orange' (#ff3c00) and 'Accent Blue' (#2492ff) should be used judiciously and functionally.
- Do not introduce sharp corners or minimal border-radii; rounded shapes are a core identifier of this system.
- Refrain from heavy shadows or complex gradients; the system prefers clean surfaces and minimal elevation.
- Do not use dark backgrounds for major content sections, as the system is anchored in a light mode aesthetic.
- Avoid generic system fonts when custom fonts are specified; the unique tracking and weights of ABC Diatype are crucial to the brand's typographic identity.
- Do not rely on subtle color differences for interactive states; ensure sufficient contrast and use 'Signal Orange' for clear feedback.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#faf6f1` | The foundational background for the entire page, providing a warm, slightly textured base. |
| 1 | Floating Card | `#ffffff` | Used for distinct content cards and interactive components, appearing crisp and elevated above the canvas. |
| 2 | Muted Content Card | `#faf6f1` | A surface that subtly blends with the page canvas but has distinct borders or is part of a different section. |

## Imagery

Imagery typically features a mix of conceptual illustrations and stylized product screenshots. Illustrations are characterized by strong, simplified shapes, often in brand colors like 'Soft Peach' or 'Vivid Coral', used as large, organic background elements or contained within similarly rounded cards. Product screenshots are clean, showcasing UI in context, often with a slight perspective. Icons are outlined, simple, and mono-color, usually in 'Carbon' or 'Ash'. Imagery plays a decorative and explanatory role, often full-bleed within sections or acting as large, background shapes that define content areas, creating a fluid, almost sculptural feel.

## Layout

The page primarily uses a contained layout with a flexible-width content area that appears centered. The hero section often features a prominent, centered headline with a large input field, setting an immediate interaction focus. Sections alternate between full-bleed background-colored blocks (often the 'Canvas' or brand orange/pink decorative shapes) and contained white content sections. Content arrangement frequently uses a centered stack for forms and calls-to-action, transitioning to alternating image-right/text-left or feature grid patterns in subsequent sections. Spacing between major sections is generous, contributing to a comfortable, uncrowded feel. A sticky top navigation bar provides consistent access to primary links and actions.

## Agent Prompt Guide

Quick Color Reference:
text: #0e0e0f
background: #faf6f1
border: #dfddd8
accent: #ff3c00
primary action: #ff3c00 (filled action)

Example Component Prompts:
1. Create a hero section with 'Canvas' (#faf6f1) background. The main heading should be 'What will you build?' using ABC Diatype Plus Variable at 69px, Carbon (#0e0e0f), with letter-spacing -4.14px. Below it, a subheading 'Turn ideas into apps in minutes' in ABC Diatype at 16px, Lead (#36373b), normal letter-spacing. Include a large 'Text Input' field with 'sm' (6px) radius.
2. Create a Primary Action Button: #ff3c00 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Implement a 'Feature Card' as a 'Floating Card' (#ffffff) with '2xl' (60px) border-radius and 48px padding. The heading inside should be ABC Diatype Plus Variable at 42px, Carbon (#0e0e0f), letter-spacing -1.26px. Below it, a paragraph in ABC Diatype at 14px, Carbon (#0e0e0f), normal letter-spacing. 

## Similar Brands

- **Figma** — Utilizes a bright, almost white canvas with distinct, generously rounded UI elements and functional accent colors to denote interactivity.
- **Webflow** — Combines soft, off-white backgrounds with highly rounded componentry and a focus on clean typography, creating an approachable yet powerful feel.
- **Notion** — Features a light, neutral base with minimal, functional accent colors and a strong emphasis on legible typography, conveying productivity and clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #faf6f1;
  --color-ghost: #ffffff;
  --color-carbon: #0e0e0f;
  --color-lead: #36373b;
  --color-ash: #898c94;
  --color-stone: #dfddd8;
  --color-off-white-accent: #cbc7c3;
  --color-slate: #52545a;
  --color-black: #000000;
  --color-signal-orange: #ff3c00;
  --color-deep-orange: #ec4e02;
  --color-soft-peach: #ffb199;
  --color-vivid-coral: #ff764c;
  --color-accent-blue: #2492ff;

  /* Typography — Font Families */
  --font-abc-diatype: 'ABC Diatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-diatype-plus-variable: 'ABC Diatype Plus Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.14px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.32px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.72px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -1.92px;
  --text-display: 69px;
  --leading-display: 0.8;
  --tracking-display: -4.14px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-3xl-3: 46px;
  --radius-full: 56px;
  --radius-full-2: 60px;
  --radius-full-3: 70px;
  --radius-full-4: 90px;
  --radius-full-5: 100px;
  --radius-full-6: 999px;
  --radius-full-7: 1028px;

  /* Named Radii */
  --radius-lg: 20px;
  --radius-md: 16px;
  --radius-sm: 6px;
  --radius-xl: 40px;
  --radius-2xl: 60px;
  --radius-none: 0px;
  --radius-pill: 90px;

  /* Surfaces */
  --surface-page-canvas: #faf6f1;
  --surface-floating-card: #ffffff;
  --surface-muted-content-card: #faf6f1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #faf6f1;
  --color-ghost: #ffffff;
  --color-carbon: #0e0e0f;
  --color-lead: #36373b;
  --color-ash: #898c94;
  --color-stone: #dfddd8;
  --color-off-white-accent: #cbc7c3;
  --color-slate: #52545a;
  --color-black: #000000;
  --color-signal-orange: #ff3c00;
  --color-deep-orange: #ec4e02;
  --color-soft-peach: #ffb199;
  --color-vivid-coral: #ff764c;
  --color-accent-blue: #2492ff;

  /* Typography */
  --font-abc-diatype: 'ABC Diatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-diatype-plus-variable: 'ABC Diatype Plus Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.14px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.32px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.72px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -1.92px;
  --text-display: 69px;
  --leading-display: 0.8;
  --tracking-display: -4.14px;

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
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-3xl-3: 46px;
  --radius-full: 56px;
  --radius-full-2: 60px;
  --radius-full-3: 70px;
  --radius-full-4: 90px;
  --radius-full-5: 100px;
  --radius-full-6: 999px;
  --radius-full-7: 1028px;
}
```
