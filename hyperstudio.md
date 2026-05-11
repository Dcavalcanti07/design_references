# Hyperstudio — Style Reference
> Monochrome terminal with amber accents. The design feels like a precisely coded interface, where every element serves a distinct, functional purpose against a dark, featureless backdrop.

**Theme:** dark

This design system evokes a sparse, high-contrast digital workspace, reminiscent of a command line interface or early internet text modes but with a refined typographic sensibility. The stark black backgrounds (#101010, #080808) are punctuated by crisp white text (#F3F3F3, #FFFFFF), creating a sense of technical precision and directness. Minimal chromatic accents (#E7C59A, #00AC5C) are used sparingly, like status lights, ensuring they immediately draw the eye and signify interactive elements or states without overwhelming the monochrome base. Custom Aeonik and Input fonts lend a distinctive, somewhat retro-futuristic feel, reinforcing the tech-focused brand identity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#101010` | `--color-midnight-void` | Primary page background, deepest dark surface. |
| Deep Space | `#080808` | `--color-deep-space` | Secondary background, slightly darker than Midnight Void, used for subtle depth. |
| Polar White | `#F3F3F3` | `--color-polar-white` | Primary text color, hero headlines, clear contrast against dark backgrounds. |
| Absolute Zero | `#FFFFFF` | `--color-absolute-zero` | Accent text and background for interactive elements like buttons, header text. |
| Ash Gray | `#949494` | `--color-ash-gray` | Secondary text, subtle borders, slightly toned down from main text. |
| Dark Carbon | `#333333` | `--color-dark-carbon` | Border colors, muted backgrounds for secondary elements. |
| Slate | `#C1C1C1` | `--color-slate` | Subtle borders, outlines, dividers. |
| Light Gradients | `linear-gradient(rgb(181, 181, 181), rgb(228, 228, 228))` | `--color-light-gradients` | Subtle background gradient for UI elements, providing a soft, almost imperceptible texture. |
| Amber Glow | `#E7C59A` | `--color-amber-glow` | Key accent color for interactive elements, 'NEW' tags, drawing attention in a restrained way appropriate for a tech brand. |
| Neon Green | `#00AC5C` | `--color-neon-green` | Small status indicators, 'spots left' tags, indicating positive status or availability. |

## Tokens — Typography

### Aeonik — Primary typeface for all headlines, body text, and UI elements. Its confident, geometric forms convey technical modernity and clarity consistently across sizes. · `--font-aeonik`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 13px, 14px, 16px, 17px, 18px, 21px, 23px, 34px, 44px, 63px
- **Line height:** 0.95, 1.03, 1.05, 1.07, 1.11, 1.22, 1.28, 1.29, 1.34, 1.35, 1.38, 1.43, 2.69
- **Letter spacing:** -0.011, -0.007
- **Role:** Primary typeface for all headlines, body text, and UI elements. Its confident, geometric forms convey technical modernity and clarity consistently across sizes.

### Input — Secondary typeface used for specific data points and code-like elements, adding a monospaced, technical contrast to Aeonik for specialized information. The tighter letter spacing enhances its code-like appearance. · `--font-input`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 13px, 14px, 16px, 17px, 18px
- **Line height:** 1.20, 1.21, 1.25, 1.31, 1.48, 1.50, 1.54
- **Letter spacing:** -0.037, -0.022
- **Role:** Secondary typeface used for specific data points and code-like elements, adding a monospaced, technical contrast to Aeonik for specialized information. The tighter letter spacing enhances its code-like appearance.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.43 | -0.007px | `--text-caption` |
| subheading | 18px | 1.28 | — | `--text-subheading` |
| heading-sm | 21px | 1.22 | — | `--text-heading-sm` |
| heading | 23px | 1.11 | — | `--text-heading` |
| heading-lg | 34px | 1.07 | — | `--text-heading-lg` |
| display | 44px | 1.03 | — | `--text-display` |
| display-lg | 63px | 0.95 | -0.011px | `--text-display-lg` |

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
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 20px |
| buttons | 8px |
| default | 8px |
| statusIcons | 99px |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Primary Ghost Button
**Role:** Call to action button for primary actions

Transparent background, Polar White text (#F3F3F3), no visible border, 8px radius. Text uses Aeonik, weight 400, size 16px. Example: 'START NOW'.

### Secondary Ghost Button
**Role:** Call to action button for secondary actions

Transparent background, Ash Gray text (#949494), no visible border, 8px radius. Text uses Aeonik, weight 400, size 16px. Example: 'VIEW WORK'.

### Small Status Pill Tag
**Role:** Indicates status or limited availability

Pill-shaped (99px radius) background in Neon Green (#00AC5C) with Polar White (#F3F3F3) text. Text uses Aeonik, weight 400, size 13px. Example: '2/5 SPOTS LEFT FOR APRIL'.

### Header Navigation Link
**Role:** Navigation items in the primary header

Polar White text (#F3F3F3), Aeonik, weight 400, size 16px. Underline on hover. Example: 'SERVICES'.

### Header Navigation Tag
**Role:** Highlighted new navigation items

Navigation link with an Amber Glow (#E7C59A) 'NEW' tag appended. Text uses Aeonik, weight 400, size 13px. Example: 'PORTFOLIO NEW'.

### Chat Button
**Role:** Persistent contact CTA in the header

Black button with Absolute Zero (#FFFFFF) text (Aeonik, weight 400, size 14px), 8px radius, with small icon. No border. Example: 'LET'S CHAT'.

### Service Feature Card
**Role:** Used to highlight key service offerings

Implied dark background on Deep Space (#080808), with Polar White (#F3F3F3) headline (Aeonik, weight 700, size 23px) and Ash Gray (#949494) body text (Aeonik, weight 400, size 16px). No explicit border or shadow, but clear visual separation through composition.

### Manifesto Button
**Role:** Secondary call to action button, typically for more information.

Dark Carbon (#333333) background, Absolute Zero (#FFFFFF) text (Aeonik, weight 400), with a 4.5px radius. Subtle light gradient suggests a slight emboss. Example: 'READ MANIFESTO'.

## Do's and Don'ts

### Do
- Prioritize high contrast between text and background, typically Polar White (#F3F3F3) on Midnight Void (#101010) or Absolute Zero (#FFFFFF) on Dark Carbon (#333333).
- Use Aeonik at size 63px, weight 700, and lineHeight 0.95 for primary display headlines to maintain a commanding yet compact presence.
- Employ Amber Glow (#E7C59A) exclusively for key attention-grabbing elements, such as 'NEW' labels or critical status indicators.
- Maintain a default border radius of 8px for most interactive elements and cards, using 99px only for circular or pill-shaped tags.
- Utilize Input font for any content that benefits from a monospace, data-like presentation, especially at -0.037em letter spacing for specific technical details.
- Structure layouts with ample section-gap (64px) to create a spacious, breathable feel between content blocks despite the dark theme.
- Employ Neon Green (#00AC5C) to denote positive status, availability, or success, ensuring it stands out as an unambiguous indicator.

### Don't
- Do not introduce additional vibrant colors; stick to Amber Glow (#E7C59A) and Neon Green (#00AC5C) as the only chromatic accents.
- Avoid using drop shadows for elevation; rely on varied shades of dark neutrals like Midnight Void (#101010) and Deep Space (#080808) for depth perception.
- Do not deviate from the specified tight line-heights for headlines, as they are crucial for the dense, impactful typographic style.
- Do not use generic system fonts; Aeonik and Input are essential to the brand's distinctive technical aesthetic.
- Avoid excessive rounding; maintain sharp or subtly rounded corners (8px) for most UI elements, reserving pill shapes for specific tags.
- Do not use full-width background images that break the defined dark background color palette; visual interest comes from typographic treatment and data visualization.

## Imagery

The visual language is characterized by abstract, pixelated graphics, specifically 'hands' composed of stark white dots on a black background, which adds a digitized, almost retro-tech aesthetic. There are no traditional photographs or realistic illustrations. Icons are simple, outlined, and monochromatic, matching the overall dark theme's precision. These graphics appear to be decorative, creating atmosphere and visual interest without being literal product showcases. The density of imagery is low; large areas of the screen are dominated by text and UI elements, with graphics serving as large-scale background motifs. Treatment is full-bleed for the abstract graphics, often low-opacity or subtle, allowing them to complement rather than compete with text.

## Layout

The page primarily uses a full-bleed, dark-themed model with content centered within an implied maximum width, though no explicit max-width is strictly enforced visually. The hero section is full-viewport, featuring a prominent centered headline over an abstract pixelated graphic on a deep black background. Sections are delineated by consistent vertical spacing of approximately 64px, with subtle shifts in background darkness creating a sense of depth rather than sharp dividers. Content arrangement leans towards centered stacks or clear two-column grid layouts for textual features and service descriptions. The density is comfortable, with generous breathing room around content blocks. Navigation is a sticky top bar with a left-aligned logo and right-aligned links and a prominent 'LET'S CHAT' button.

## Agent Prompt Guide

### Quick Color Reference
- Text: #F3F3F3
- Background: #101010
- CTA: #333333 (background), #FFFFFF (text)
- Border: #333333
- Accent: #E7C59A

### 3-5 Example Component Prompts
1. **Create a hero section:** background #101010. Headline 'World-class branding and websites for startups.' using Aeonik, size 63px, weight 700, #F3F3F3, letterSpacing -0.011em, lineHeight 0.95. Below, add a 'START NOW' button: transparent background, Aeonik, size 16px, weight 400, #F3F3F3, 8px border-radius. Next to it, a 'VIEW WORK' button: transparent background, Aeonik, size 16px, weight 400, #949494, 8px border-radius.
2. **Generate a service feature block:** background #080808. Title 'AWARD-WINNING LOGOS' using Aeonik, size 23px, weight 700, #F3F3F3. Body text 'Easy to remember and distinctive logos, giving your brand a unique identity.' using Aeonik, size 16px, weight 400, #949494. Ensure consistent 24px padding within the block, and the block is visually separated by 64px from other content.
3. **Design a persistent header bar:** background #101010. Logo 'Hyperstudio' using Aeonik, size 18px, weight 700, #F3F3F3. Navigation links 'SERVICES', 'PROCESS' using Aeonik, size 16px, weight 400, #F3F3F3. Add a 'PORTFOLIO NEW' link: 'PORTFOLIO' using Aeonik, size 16px, weight 400, #F3F3F3; 'NEW' tag appending it with background #E7C59A, text #F3F3F3, Aeonik, size 13px, weight 400. Include a 'LET'S CHAT' button on the right: background #000000, text #FFFFFF, Aeonik, size 14px, weight 400, 8px border-radius, with an icon.
4. **Create a 'Why Hyperstudio?' section:** background #101010. Main heading 'Why Hyperstudio?' using Aeonik, size 44px, weight 700, #F3F3F3. Body text paragraph using Aeonik, size 18px, weight 400, #F3F3F3, with lineHeight 1.31. Below, add a 'READ MANIFESTO' button: background #333333, text #FFFFFF, Aeonik, size 16px, weight 400, 4.5px border-radius.

## Similar Brands

- **Vercel** — Shares a strong monochrome dark theme combined with minimal, deliberate accent colors for interactive elements and status indicators.
- **Linear** — Features a similar crisp, high-contrast dark UI, heavy reliance on sophisticated typography (including custom fonts), and subtle use of color for functional cues rather than decoration.
- **Framer** — Employs a precise, minimalist aesthetic with a focus on clear hierarchy, dark backgrounds, and subtle grays, paired with a distinct, confident typeface.
- **Stripe** — Exhibits clean, geometric typography and a high-fidelity, high-contrast interface, although often in a lighter theme, the precision and controlled use of color are comparable.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #101010;
  --color-deep-space: #080808;
  --color-polar-white: #F3F3F3;
  --color-absolute-zero: #FFFFFF;
  --color-ash-gray: #949494;
  --color-dark-carbon: #333333;
  --color-slate: #C1C1C1;
  --color-light-gradients: #B5B5B5;
  --gradient-light-gradients: linear-gradient(rgb(181, 181, 181), rgb(228, 228, 228));
  --color-amber-glow: #E7C59A;
  --color-neon-green: #00AC5C;

  /* Typography — Font Families */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-input: 'Input', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.43;
  --tracking-caption: -0.007px;
  --text-subheading: 18px;
  --leading-subheading: 1.28;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.22;
  --text-heading: 23px;
  --leading-heading: 1.11;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.07;
  --text-display: 44px;
  --leading-display: 1.03;
  --text-display-lg: 63px;
  --leading-display-lg: 0.95;
  --tracking-display-lg: -0.011px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4.5px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-full: 99px;

  /* Named Radii */
  --radius-tags: 20px;
  --radius-buttons: 8px;
  --radius-default: 8px;
  --radius-statusicons: 99px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #101010;
  --color-deep-space: #080808;
  --color-polar-white: #F3F3F3;
  --color-absolute-zero: #FFFFFF;
  --color-ash-gray: #949494;
  --color-dark-carbon: #333333;
  --color-slate: #C1C1C1;
  --color-light-gradients: #B5B5B5;
  --color-amber-glow: #E7C59A;
  --color-neon-green: #00AC5C;

  /* Typography */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-input: 'Input', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.43;
  --tracking-caption: -0.007px;
  --text-subheading: 18px;
  --leading-subheading: 1.28;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.22;
  --text-heading: 23px;
  --leading-heading: 1.11;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.07;
  --text-display: 44px;
  --leading-display: 1.03;
  --text-display-lg: 63px;
  --leading-display-lg: 0.95;
  --tracking-display-lg: -0.011px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-md: 4.5px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-full: 99px;
}
```
