# Ortto — Style Reference
> Shifting canvases, vivid blue accent

**Theme:** mixed

Ortto employs a dynamic contrast design language, shifting between crisp dark canvases for heroic statements and pristine white surfaces for detailed content. A single vivid blue serves as the core brand accent, appearing in call-to-actions and key interactive elements. Typography mixes substantial, commanding sans-serifs for headlines with highly readable body text, maintaining legibility across diverse backgrounds. Component weighting is light, with soft borders and minimal elevation, allowing content and functionality to lead.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Canvas | `#14171f` | `--color-midnight-canvas` | Dark page sections and background for hero elements |
| Aura Gray | `#f9f8f7` | `--color-aura-gray` | Subtle background for UI elements, cards, and secondary surfaces |
| Snowdrift | `#ffffff` | `--color-snowdrift` | Primary page background, card surfaces, and active element backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, strong headings, and structural borders |
| Gunmetal | `#252525` | `--color-gunmetal` | Secondary text, subheadings, and muted borders |
| Deep Gray | `#0d0d0d` | `--color-deep-gray` | Tertiary text and subtle borders for content separation |
| Muted Stone | `#6d6b70` | `--color-muted-stone` | Muted helper text, secondary navigation links, and light borders |
| Porcelain | `#e9e5e2` | `--color-porcelain` | Subtle dividers and faint background washes |
| Ortto Blue | `#1070ff` | `--color-ortto-blue` | Primary call-to-action fills, interactive elements, and brand accents |
| Vivid Violet | `#0066ff` | `--color-vivid-violet` | Decorative fills primarily for iconography and illustrations |

## Tokens — Typography

### sans-serif — System default for utilitarian and fallback text like helper messages and default links. · `--font-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.20
- **Role:** System default for utilitarian and fallback text like helper messages and default links.

### Haas Grot Text R Web — Primary marketing and informational body text, maintaining clarity and consistency across various marketing materials. This font is also used for nav and link text for high legibility. · `--font-haas-grot-text-r-web`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 19px
- **Line height:** 1.20
- **Letter spacing:** -0.021em at 12px, 0.009em at 13px, 0.011em at 14px, 0.015em at 16px, 0.021em at 24px
- **Role:** Primary marketing and informational body text, maintaining clarity and consistency across various marketing materials. This font is also used for nav and link text for high legibility.

### Haas Grot Text R Web — Medium weight text for emphasis within copy and for sub-headings. · `--font-haas-grot-text-r-web`
- **Substitute:** Inter Medium
- **Weights:** 400
- **Sizes:** 14px, 16px, 24px
- **Line height:** 1.20, 1.38, 1.43
- **Letter spacing:** 0.009em at 14px, 0.011em at 16px
- **Role:** Medium weight text for emphasis within copy and for sub-headings.

### Ivar Text — A distinctive serif font used for impactful headings and pull quotes, providing a mature and authoritative vocal tone. · `--font-ivar-text`
- **Substitute:** Source Serif Pro
- **Weights:** 400
- **Sizes:** 24px
- **Line height:** 1.33
- **Letter spacing:** -0.010em at 20px, -0.004em at 24px, 0.003em at 48px, 0.003em at 64px, 0.003em at 72px
- **Role:** A distinctive serif font used for impactful headings and pull quotes, providing a mature and authoritative vocal tone.

### Haas Grot Text R Web — Bold weight text for strong emphasis in body copy and key UI elements, ensuring critical information stands out. · `--font-haas-grot-text-r-web`
- **Substitute:** Inter Bold
- **Weights:** 400
- **Sizes:** 12px, 13px, 14px, 16px, 24px
- **Line height:** 1.20, 1.33, 1.38, 1.40, 1.43
- **Letter spacing:** -0.021em at 14px, 0.009em at 16px, 0.011em at 24px
- **Role:** Bold weight text for strong emphasis in body copy and key UI elements, ensuring critical information stands out.

### Haas Grot Disp R Web — Display headings, used for very large, prominent titles where impact and presence are key. The negative letter spacing enhances conciseness. · `--font-haas-grot-disp-r-web`
- **Substitute:** Inter ExtraBold
- **Weights:** 400
- **Sizes:** 48px, 64px
- **Line height:** 1.00
- **Letter spacing:** -0.010em at 48px, -0.004em at 64px
- **Role:** Display headings, used for very large, prominent titles where impact and presence are key. The negative letter spacing enhances conciseness.

### Haas Grot Text R — General text for various purposes, often acting as a bridge between larger headings and smaller body copy. · `--font-haas-grot-text-r`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 19px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** General text for various purposes, often acting as a bridge between larger headings and smaller body copy.

### Ivar Text — Italicized text specifically for quotes and stylistic emphasis, offering expressive variation from standard body text. · `--font-ivar-text`
- **Substitute:** Source Serif Pro Italic
- **Weights:** 400
- **Sizes:** 20px, 24px, 48px, 64px, 72px
- **Line height:** 1.00, 1.33, 1.40
- **Letter spacing:** 0.003em
- **Role:** Italicized text specifically for quotes and stylistic emphasis, offering expressive variation from standard body text.

### Haas Grot Text R Web 65 Medium — Haas Grot Text R Web 65 Medium — detected in extracted data but not described by AI · `--font-haas-grot-text-r-web-65-medium`
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.25, 1.38, 1.43
- **Letter spacing:** 0.009, 0.011, 0.013
- **Role:** Haas Grot Text R Web 65 Medium — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | -0.252px | `--text-caption` |
| body | 14px | 1.38 | 0.154px | `--text-body` |
| heading-sm | 20px | 1 | -0.2px | `--text-heading-sm` |
| heading | 24px | 1.33 | -0.096px | `--text-heading` |
| heading-lg | 48px | 1 | -0.48px | `--text-heading-lg` |
| display | 64px | 1 | -0.256px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 50px |
| buttons | 40px |
| default | 4px |
| sections | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.04) 0px 4px 4px 0px, rgba(0, 0, 0, 0.05) ...` | `--shadow-sm` |

### Layout

- **Section gap:** 40px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Filled button for main calls-to-action.

Background: Ortto Blue (#1070ff), Text: Snowdrift (#ffffff), Border: none, Radius: 40px, Padding: 10px vertical, 24px horizontal, Font: Haas Grot Text R Web 400 at 16px.

### Ghost Button
**Role:** Outline button for secondary actions.

Background: Snowdrift (#ffffff), Text: Ink Black (#000000) (Browser default #0000ee observed), Border: 1px Ink Black (#000000), Radius: 0px, Padding: 32px vertical, 32px horizontal, Font: Haas Grot Text R Web 400 at 16px.

### Subtle Ghost Button
**Role:** Outline button with a soft background for less prominent secondary actions.

Background: Aura Gray (#f9f8f7), Text: Ink Black (#000000) (Browser default #0000ee observed), Border: 1px Ink Black (#000000), Radius: 0px, Padding: 32px vertical, 32px horizontal, Font: Haas Grot Text R Web 400 at 16px.

### Navigation Link
**Role:** Interactive elements in the header navigation.

Text: Ink Black (#000000), Active Border: Ortto Blue (#1070ff) at 4px. Uses Haas Grot Text R Web 400 at 16px.

### Feature Card
**Role:** Container for showcasing features or testimonials.

Background: Snowdrift (#ffffff), Radius: 16px, Shadow: rgba(0, 0, 0, 0.04) 0px 4px 4px..., Padding: 32px.

### Badge/Tag
**Role:** Small informational labels.

Background: varies, Text: varies, Radius: 50px (full pill shape), Padding: small implicit using elementGap.

## Do's and Don'ts

### Do
- Use Ortto Blue (#1070ff) exclusively for primary action backgrounds and brand highlights.
- Maintain high contrast text: Ink Black (#000000) or Gunmetal (#252525) on Snowdrift (#ffffff) backgrounds, and Snowdrift (#ffffff) on Midnight Canvas (#14171f) backgrounds.
- Apply 40px border-radius to all main action buttons for a consistent soft pill shape.
- Reserve Ivar Text for all high-impact headings (48px, 64px) and pull quotes.
- Utilize Haas Grot Text R Web for all body text, navigation, and secondary UI elements, adjusting weight for emphasis.
- Employ the 8px elementGap for consistent spacing between inline elements and compact UI components.
- Ensure section transitions maintain visual distinction either through alternating background colors (Midnight Canvas / Snowdrift) or clear dividing lines.

### Don't
- Do not introduce new saturated primary colors; Ortto Blue (#1070ff) is the singular brand accent.
- Avoid heavy drop shadows; use the predefined subtle multi-layer shadow for minimal elevation.
- Do not use generic sans-serif for headings; Ivar Text provides a distinct brand voice.
- Do not use sharp 0px corners except for specific ghost buttons variant shown in the UI.
- Avoid dense, unbroken text blocks; use a varied type scale and element gaps to break up content.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Snowdrift | `#ffffff` | Base page background and primary content surfaces. |
| 1 | Aura Gray | `#f9f8f7` | Secondary content containers, subtle background differentiation. |
| 2 | Porcelain | `#e9e5e2` | Tertiary backgrounds and dividers, light visual separation. |
| 3 | Midnight Canvas | `#14171f` | Dark section backgrounds, hero areas, and elements requiring strong contrast. |

## Elevation

- **Feature Card:** `rgba(0, 0, 0, 0.04) 0px 4px 4px 0px, rgba(0, 0, 0, 0.05) 0px 12px 12px 0px, rgba(0, 0, 0, 0.06) 0px 24px 24px 0px, rgba(0, 0, 0, 0.07) 0px 50px 50px 0px, rgba(0, 0, 0, 0.08) 0px 136px 136px 0px, rgba(0, 0, 0, 0.08) 0px 0px 0px 1px`

## Imagery

Imagery primarily utilizes product screenshots that are contained and often cropped to showcase UI elements clearly. These are typically presented with a soft 16px border-radius, fitting into the minimal elevation. Iconography is clean and functional, often using Ortto Blue for accents. When photographs are present, they lean towards professional and conceptual rather than lifestyle. The overall imagery density is moderate; product UI serves to explain, while minimal photography adds atmosphere.

## Layout

The page primarily uses a max-width contained layout, with significant sections centered. The hero section prominently features a split composition: a dark full-bleed background on the left containing the main headline and calls to action, paired with a product UI screenshot on a lighter background on the right. Content sections alternate between these dark and light canvases. Internal content often employs a two-column text-left/image-right pattern or centered stacks. Card grids are used for features, adhering to the 16px border-radius. Navigation is a sticky top bar.

## Agent Prompt Guide

primary action: #1070ff (filled action)
Create a Primary Action Button: #1070ff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:
2. Create a Feature Card: Snowdrift (#ffffff) background, 16px border-radius, default elevation shadow. Heading 'MARKETING AUTOMATION' using Gunmetal (#252525) Haas Grot Text R Web 400 (medium) at 16px. Subheading 'A complete platform for powerful marketing automation' using Ivar Text 48px, Ink Black (#000000) text.
3. Create a Navigation Bar: Snowdrift (#ffffff) background, top of page. Links 'Product', 'Solutions', 'Resources' with Ink Black (#000000) Haas Grot Text R Web 400 at 16px. Active link 'Templates' with a 4px Ortto Blue (#1070ff) border-bottom.

## Similar Brands

- **Segment** — Monolithic dark hero, clean product UI inside, focus on a single dominant brand accent color.
- **Mailchimp** — Clear distinction between brand-focused landing pages and clean SaaS product interfaces, with a vibrant accent color for interaction.
- **Customer.io** — Emphasis on marketing automation and customer data platforms, using professional but not overly stiff sans-serifs and a structured layout.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-canvas: #14171f;
  --color-aura-gray: #f9f8f7;
  --color-snowdrift: #ffffff;
  --color-ink-black: #000000;
  --color-gunmetal: #252525;
  --color-deep-gray: #0d0d0d;
  --color-muted-stone: #6d6b70;
  --color-porcelain: #e9e5e2;
  --color-ortto-blue: #1070ff;
  --color-vivid-violet: #0066ff;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-text-r-web: 'Haas Grot Text R Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ivar-text: 'Ivar Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-disp-r-web: 'Haas Grot Disp R Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-text-r: 'Haas Grot Text R', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-text-r-web-65-medium: 'Haas Grot Text R Web 65 Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.252px;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: 0.154px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.2px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.096px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.256px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-tags: 50px;
  --radius-buttons: 40px;
  --radius-default: 4px;
  --radius-sections: 16px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 4px 4px 0px, rgba(0, 0, 0, 0.05) 0px 12px 12px 0px, rgba(0, 0, 0, 0.06) 0px 24px 24px 0px, rgba(0, 0, 0, 0.07) 0px 50px 50px 0px, rgba(0, 0, 0, 0.08) 0px 136px 136px 0px, rgba(0, 0, 0, 0.08) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-snowdrift: #ffffff;
  --surface-aura-gray: #f9f8f7;
  --surface-porcelain: #e9e5e2;
  --surface-midnight-canvas: #14171f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-canvas: #14171f;
  --color-aura-gray: #f9f8f7;
  --color-snowdrift: #ffffff;
  --color-ink-black: #000000;
  --color-gunmetal: #252525;
  --color-deep-gray: #0d0d0d;
  --color-muted-stone: #6d6b70;
  --color-porcelain: #e9e5e2;
  --color-ortto-blue: #1070ff;
  --color-vivid-violet: #0066ff;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-text-r-web: 'Haas Grot Text R Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ivar-text: 'Ivar Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-disp-r-web: 'Haas Grot Disp R Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-text-r: 'Haas Grot Text R', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-text-r-web-65-medium: 'Haas Grot Text R Web 65 Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.252px;
  --text-body: 14px;
  --leading-body: 1.38;
  --tracking-body: 0.154px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.2px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.096px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.256px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 4px 4px 0px, rgba(0, 0, 0, 0.05) 0px 12px 12px 0px, rgba(0, 0, 0, 0.06) 0px 24px 24px 0px, rgba(0, 0, 0, 0.07) 0px 50px 50px 0px, rgba(0, 0, 0, 0.08) 0px 136px 136px 0px, rgba(0, 0, 0, 0.08) 0px 0px 0px 1px;
}
```
