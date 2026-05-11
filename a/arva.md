# Arva — Style Reference
> rolling green landscape

**Theme:** light

Arva employs an earthy, modern aesthetic with a focus on natural greens and a light, open feel. Typography is grounded yet contemporary, using a mix of classic serif for emphasis and clean sans-serif for readability. Components feature soft, rounded corners and a preference for contained elements, creating a sense of natural organization. The overall visual tone is approachable and professional, echoing the brand's connection to agriculture and sustainability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Arva Forest | `#07503f` | `--color-arva-forest` | Primary action backgrounds, footer background, primary brand color for various UI elements. This deep green evokes nature and growth, aligning with the brand's agricultural focus |
| Garden Dew | `#b2cee7` | `--color-garden-dew` | Card backgrounds, secondary interactive states. A soft, cool gray-blue that acts as a complementary calming neutral |
| Harvest Gold | `#fceace` | `--color-harvest-gold` | Card backgrounds. A warm, muted yellow-orange evoking natural hues and sunlight |
| Sprout Green | `#e6ecd5` | `--color-sprout-green` | Card backgrounds. A very light, desaturated green that contributes to the natural, earthy palette |
| Spring Bud | `#e8fe85` | `--color-spring-bud` | Link backgrounds, informational highlights. A vivid green that provides a vibrant pop against the more muted palette, signifying attention |
| Sage Mist | `#c3cda7` | `--color-sage-mist` | Text color for certain inputs and subtle details. A desaturated green that harmonizes with the brand's core palette |
| Warning Red | `#e51520` | `--color-warning-red` | Red outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Ebony | `#212529` | `--color-ebony` | Primary text, headings, icons, strong borders. This near-black provides strong contrast for readability against light backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, button backgrounds, element borders, prominent surfaces. The dominant light background color |
| Graphite | `#353535` | `--color-graphite` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Parchment | `#f1efdf` | `--color-parchment` | Secondary card backgrounds, subtle background texture. A warm, almost white neutral that provides subtle variation from pure white |
| Silver Clay | `#efefef` | `--color-silver-clay` | Card backgrounds. A light gray for subtle surface differentiation |
| Ash Gray | `#6d6d6d` | `--color-ash-gray` | Muted text, button borders and text for ghost buttons. A mid-tone gray for less prominent information and inactive states |

## Tokens — Typography

### Inter — Primary sans-serif for body text, navigation, buttons, and larger display headlines. Its range of weights and optical adjustments ensure readability across various contexts, from small utility text to prominent calls to action. The tighter letter spacing on larger sizes adds a modern, impactful feel. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 100, 200, 300, 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 17px, 18px, 80px, 90px
- **Line height:** 0.97, 1.00, 1.10, 1.20, 1.24, 1.50, 1.52, 1.78, 1.88, 2.20
- **Letter spacing:** -0.0370em at larger sizes, 0.0250em for body text
- **Role:** Primary sans-serif for body text, navigation, buttons, and larger display headlines. Its range of weights and optical adjustments ensure readability across various contexts, from small utility text to prominent calls to action. The tighter letter spacing on larger sizes adds a modern, impactful feel.

### RecklessLight — Decorative serif for section headings and select display text. Its light weights give a refined, airy feel, contrasting the more structured sans-serif, and adding a touch of classic elegance. · `--font-recklesslight`
- **Substitute:** serif
- **Weights:** 100, 300
- **Sizes:** 16px, 24px, 25px, 28px, 37px, 45px, 49px, 57px
- **Line height:** 1.00, 1.06, 1.22, 1.24
- **Letter spacing:** normal
- **Role:** Decorative serif for section headings and select display text. Its light weights give a refined, airy feel, contrasting the more structured sans-serif, and adding a touch of classic elegance.

### Reckless — Stronger serif variant for headings. Used for prominence and impact, maintaining the elegant feel of RecklessLight but with more visual weight and slightly tighter tracking for better grouping. · `--font-reckless`
- **Substitute:** serif
- **Weights:** 300, 500, 600
- **Sizes:** 16px, 24px, 28px, 37px, 43px, 45px, 57px
- **Line height:** 1.00, 1.06, 1.22, 1.24
- **Letter spacing:** -0.0120em
- **Role:** Stronger serif variant for headings. Used for prominence and impact, maintaining the elegant feel of RecklessLight but with more visual weight and slightly tighter tracking for better grouping.

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 300, 400, 500
- **Sizes:** 17px
- **Line height:** 1.1, 1.35
- **Role:** sans-serif — detected in extracted data but not described by AI

### Helvetica — Helvetica — detected in extracted data but not described by AI · `--font-helvetica`
- **Weights:** 300, 400
- **Sizes:** 12px, 17px
- **Line height:** 1.35, 1.92
- **Role:** Helvetica — detected in extracted data but not described by AI

### FKGrotesk — FKGrotesk — detected in extracted data but not described by AI · `--font-fkgrotesk`
- **Weights:** 300
- **Sizes:** 12px, 16px
- **Line height:** 1.24
- **Role:** FKGrotesk — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.52 | 0.025px | `--text-body` |
| subheading | 24px | 1.24 | -0.012px | `--text-subheading` |
| heading | 37px | 1.24 | -0.012px | `--text-heading` |
| heading-lg | 49px | 1.24 | -0.037px | `--text-heading-lg` |
| display | 80px | 0.97 | -0.037px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 27 | 27px | `--spacing-27` |
| 30 | 30px | `--spacing-30` |
| 38 | 38px | `--spacing-38` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 64 | 64px | `--spacing-64` |
| 193 | 193px | `--spacing-193` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 33px |
| buttons | 100px |
| default | 20px |

### Layout

- **Page max-width:** 1350px
- **Section gap:** 50px
- **Card padding:** 50px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call-to-action button, filled style

Background: Arva Forest (#07503f); Text: Canvas White (#ffffff); Border Radius: 110px; Padding: 6px vertical, 30px horizontal. Used for primary actions and conversions.

### Ghost Button - Secondary
**Role:** Secondary action button, outlined style

Background: Canvas White (#ffffff); Text: Graphite (#353535); Border: 1px solid Graphite (#353535); Border Radius: 60px; Padding: 8px vertical, 27px horizontal. Used for less prominent actions.

### Ghost Button - Tertiary
**Role:** Tertiary action button, outlined style

Background: Canvas White (#ffffff); Text: Ash Gray (#6d6d6d); Border: 1px solid Ash Gray (#6d6d6d); Border Radius: 100px; Padding: 10px vertical, 30px horizontal. Used for subtle actions or filters.

### Farmer Type Card - Harvest Gold
**Role:** Informational card, warm background

Background: Harvest Gold (#fceace); Border Radius: 20px; Padding: 50px all sides. Used for distinguishing content blocks with a warm, inviting tone.

### Company Type Card - Garden Dew
**Role:** Informational card, cool background

Background: Garden Dew (#b2cee7); Border Radius: 20px; Padding: 50px all sides. Used for distinguishing content blocks with a fresh, cool tone.

### Subtle Card - Parchment
**Role:** Informational card, neutral background

Background: Parchment (#f1efdf); Border Radius: 20px; Padding: 50px all sides. Used for general content blocks with a soft, warm neutral background.

### Search Input - Dark
**Role:** Form input field, dark theme

Background: Arva Forest (#07503f); Text: Sage Mist (#c3cda7); Border: 1px solid Canvas White (#ffffff); Border Radius: 33px; Padding: 12px vertical, 10px horizontal. For inputs integrated into darker sections.

### Input - Dark Default
**Role:** Form input field, dark theme

Background: Arva Forest (#07503f); Text: Ebony (#212529); Border: 1px solid Canvas White (#ffffff); Border Radius: 2px; Padding: 8px all sides. For inputs integrated into darker sections.

### Dark Overlay Text Badge
**Role:** Informational badge typically over an image or dark background

Background: transparent; Text: Canvas White (#ffffff); Border Radius: 0px; Padding: 0px. Used for contextual labels without a distinct background.

## Do's and Don'ts

### Do
- Use Arva Forest (#07503f) for primary actions and significant brand elements to maintain an earthy and established feel.
- Apply a default border-radius of 20px for cards and section containers to maintain the soft, approachable aesthetic.
- Prioritize Inter for all body text, navigation, and button labels, utilizing its varying weights for hierarchy while ensuring consistent letter spacing for various sizes as defined in the type system.
- Employ RecklessLight and Reckless for headlines and display text, leveraging their distinct serif character to add a touch of refined elegance.
- Maintain a clear visual hierarchy by using Ebony (#212529) for primary text and headings, and Graphite (#353535) or Ash Gray (#6d6d6d) for secondary or supporting text.
- Utilize the comfortable spacing values (elementGap: 8px, cardPadding: 50px, sectionGap: 50px) to create an open and readable layout.
- Ensure interactive elements have clear visual states; primary buttons should use Arva Forest (#07503f) as background.

### Don't
- Avoid sharp corners; all significant UI elements like cards and buttons should have a radius of at least 20px.
- Do not introduce new primary brand colors beyond the established green, blue, and yellow accents.
- Refrain from using heavily saturated colors for backgrounds; surface colors should remain muted or neutral.
- Do not use dark backgrounds for entire sections unless specified by full-bleed imagery; the default page theme is light.
- Avoid dense, overcrowded layouts; respect the established element and section gaps to maintain comfort and scannability.
- Do not deviate from the specified font families; avoid system defaults or highly decorative fonts not in the system.
- Do not use box shadows for elevation; rely on background color variations and borders for surface differentiation.

## Elevation

The design intentionally avoids complex box-shadows. Surface differentiation is achieved primarily through distinct background colors (like Parchment, Garden Dew, Harvest Gold) and subtle borders on interactive elements. This approach contributes to the clean, flat, and grounded aesthetic, keeping the focus on content and imagery rather than layered UI.

## Imagery

The visual language relies heavily on photographic imagery, primarily focused on landscapes (lush green fields) and people in agricultural settings. Product-focused photography is clean, showcasing elements like tractors or crops in a natural environment without heavy styling. Imagery is typically full-bleed in hero sections or contained within cards, often featuring natural light and a slightly desaturated, yet rich, color palette that harmonizes with the brand's greens and earth tones. Icons are minimal, typically outlined and monochrome, serving a purely functional, explanatory role.

## Layout

The page adheres to a max-width contained model of 1350px after the initial full-bleed hero. The hero section features a full-viewport background image with centered, large-scale typography and prominent call-to-action buttons. Subsequent sections alternate between light backgrounds and the occasional soft neutral (like Parchment or Garden Dew) with consistent vertical section gaps of 50px. Content is often arranged in symmetrical 2-column or 3-column grids for features and partner logos, with a clear left-aligned bias for text blocks paired with right-aligned visuals. Navigation is a sticky top bar with a brand logo and clear menu items.

## Agent Prompt Guide

Quick Color Reference: 
text: #212529
background: #ffffff
border: #212529
accent: #b2cee7
primary action: #07503f (filled action)

Example Component Prompts:
Create a Primary Action Button: #07503f background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create an informational card: Background Harvest Gold (#fceace), radius 20px, 50px padding. Inside, a subheading in RecklessLight, 24px, #212529, normal letter-spacing, followed by body text in Inter, 16px, #353535, 0.0250em letter-spacing.

Create a navigation bar: Background Arva Forest (#07503f). Logo in Canvas White (#ffffff). Navigation links in Inter, 16px, Canvas White (#ffffff), 0.0250em letter-spacing. Include a primary action button as described above, but with 110px border radius and 6px vertical and 30px horizontal padding.

## Similar Brands

- **Indigo Ag** — Uses a similar blend of earthy tones and greens with a focus on agriculture technology and a clean, spacious layout.
- **FBN (Farmers Business Network)** — Employs a white and green dominant palette with clear, structured information and professional imagery.
- **Carbon Robotics** — Combines natural aesthetics with clear UX for agricultural software, featuring rounded elements and accessible typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-arva-forest: #07503f;
  --color-garden-dew: #b2cee7;
  --color-harvest-gold: #fceace;
  --color-sprout-green: #e6ecd5;
  --color-spring-bud: #e8fe85;
  --color-sage-mist: #c3cda7;
  --color-warning-red: #e51520;
  --color-ebony: #212529;
  --color-canvas-white: #ffffff;
  --color-graphite: #353535;
  --color-parchment: #f1efdf;
  --color-silver-clay: #efefef;
  --color-ash-gray: #6d6d6d;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-recklesslight: 'RecklessLight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-reckless: 'Reckless', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fkgrotesk: 'FKGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.52;
  --tracking-body: 0.025px;
  --text-subheading: 24px;
  --leading-subheading: 1.24;
  --tracking-subheading: -0.012px;
  --text-heading: 37px;
  --leading-heading: 1.24;
  --tracking-heading: -0.012px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.24;
  --tracking-heading-lg: -0.037px;
  --text-display: 80px;
  --leading-display: 0.97;
  --tracking-display: -0.037px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-extralight: 200;
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-27: 27px;
  --spacing-30: 30px;
  --spacing-38: 38px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-64: 64px;
  --spacing-193: 193px;

  /* Layout */
  --page-max-width: 1350px;
  --section-gap: 50px;
  --card-padding: 50px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-2xl: 20px;
  --radius-3xl: 26px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 33px;
  --radius-3xl-4: 45px;
  --radius-full: 60px;
  --radius-full-2: 100px;
  --radius-full-3: 110px;
  --radius-full-4: 9999px;

  /* Named Radii */
  --radius-inputs: 33px;
  --radius-buttons: 100px;
  --radius-default: 20px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-arva-forest: #07503f;
  --color-garden-dew: #b2cee7;
  --color-harvest-gold: #fceace;
  --color-sprout-green: #e6ecd5;
  --color-spring-bud: #e8fe85;
  --color-sage-mist: #c3cda7;
  --color-warning-red: #e51520;
  --color-ebony: #212529;
  --color-canvas-white: #ffffff;
  --color-graphite: #353535;
  --color-parchment: #f1efdf;
  --color-silver-clay: #efefef;
  --color-ash-gray: #6d6d6d;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-recklesslight: 'RecklessLight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-reckless: 'Reckless', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fkgrotesk: 'FKGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.52;
  --tracking-body: 0.025px;
  --text-subheading: 24px;
  --leading-subheading: 1.24;
  --tracking-subheading: -0.012px;
  --text-heading: 37px;
  --leading-heading: 1.24;
  --tracking-heading: -0.012px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.24;
  --tracking-heading-lg: -0.037px;
  --text-display: 80px;
  --leading-display: 0.97;
  --tracking-display: -0.037px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-27: 27px;
  --spacing-30: 30px;
  --spacing-38: 38px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-64: 64px;
  --spacing-193: 193px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-2xl: 20px;
  --radius-3xl: 26px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 33px;
  --radius-3xl-4: 45px;
  --radius-full: 60px;
  --radius-full-2: 100px;
  --radius-full-3: 110px;
  --radius-full-4: 9999px;
}
```
