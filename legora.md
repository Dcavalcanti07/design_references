# Legora — Style Reference
> Warm monochrome legal canvas

**Theme:** light

Legora employs a classic minimalist aesthetic with high contrast typography and subdued, often desaturated, color accents. The design emphasizes clear information hierarchy through sparse layouts and strong textual elements. Subtle background shifts and minimal interactive elements create an atmosphere of quiet professionalism, allowing content to take center stage.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell Black | `#000000` | `--color-inkwell-black` | Primary text, borders, dark background for hero section and certain UI elements |
| Canvas White | `#fefefc` | `--color-canvas-white` | Page background, primary light surface for cards and content sections |
| Text Gray | `#0a0a0a` | `--color-text-gray` | Content text, secondary dark borders, slightly softer than Inkwell Black for body copy |
| Pale Ash | `#ebf5ed` | `--color-pale-ash` | Subtle background for UI elements, input fields, and alternating section backgrounds |
| Shadowstone Gray | `#6b6b6b` | `--color-shadowstone-gray` | Muted helper text, secondary body copy |
| Whisper Gray | `#444444` | `--color-whisper-gray` | Tertiary text, even subtler than Shadowstone Gray, for very de-emphasized elements |
| Parchment Tan | `#e1d5b6` | `--color-parchment-tan` | Subtle background accent for specific sections, adding a warm, academic feel |
| Sky Tint | `#bdd4f0` | `--color-sky-tint` | Background for certain interactive link states or prominent data blocks |
| Steel Blue | `#98a7aa` | `--color-steel-blue` | Background for specific link states, a cool accent |

## Tokens — Typography

### sans-serif — System fallback for small UI elements and utility text. · `--font-sans-serif`
- **Substitute:** Arial, Helvetica
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** System fallback for small UI elements and utility text.

### Suisse Intl Book — Primary body text, labels, and paragraph content. The 'Book' weight at 450 provides a substantial yet refined feel. Its specific font features ('blwf', 'cv03', 'cv04', 'cv09', 'cv11') are critical for the brand's typographic identity. · `--font-suisse-intl-book`
- **Substitute:** Inter
- **Weights:** 450
- **Sizes:** 11px, 13px, 14px, 16px
- **Line height:** 0.80, 1.25, 1.30
- **Letter spacing:** -0.01em at 16px, 0.01em at 11px
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Primary body text, labels, and paragraph content. The 'Book' weight at 450 provides a substantial yet refined feel. Its specific font features ('blwf', 'cv03', 'cv04', 'cv09', 'cv11') are critical for the brand's typographic identity.

### Aktiv Grotesk VF Variable Regular — Subheadings and supporting headlines in product descriptions. The regular weight keeps it grounded. · `--font-aktiv-grotesk-vf-variable-regular`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 15px, 20px
- **Line height:** 1.30
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Subheadings and supporting headlines in product descriptions. The regular weight keeps it grounded.

### Rhymes Display Light — Emphasis headlines. The highly distinctive 'Light' weight (300) for large display sizes creates an unusually refined and open feel, conveying authority through restraint rather than boldness. · `--font-rhymes-display-light`
- **Substitute:** Lora
- **Weights:** 300
- **Sizes:** 24px, 32px, 88px
- **Line height:** 0.95, 1.10
- **Letter spacing:** -0.02em at 88px, -0.01em at 24px
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Emphasis headlines. The highly distinctive 'Light' weight (300) for large display sizes creates an unusually refined and open feel, conveying authority through restraint rather than boldness.

### Playfair Display — Prominent display headlines, particularly the main hero title. Its serif elegance adds a touch of classic sophistication. · `--font-playfair-display`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 80px
- **Line height:** 1.00
- **Letter spacing:** -0.02em
- **Role:** Prominent display headlines, particularly the main hero title. Its serif elegance adds a touch of classic sophistication.

### Inter — Secondary utility text and metadata, providing a clear sans-serif contrast. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Secondary utility text and metadata, providing a clear sans-serif contrast.

### Suisse Intl Medium — Input labels and placeholder text, providing clear readability. · `--font-suisse-intl-medium`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 13px
- **Line height:** 1.00
- **Role:** Input labels and placeholder text, providing clear readability.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 0.8 | — | `--text-caption` |
| body | 14px | 1.25 | — | `--text-body` |
| heading-sm | 20px | 1.3 | — | `--text-heading-sm` |
| heading | 24px | 1.1 | -0.24px | `--text-heading` |
| heading-lg | 32px | 0.95 | -0.32px | `--text-heading-lg` |
| display | 88px | 0.95 | -1.76px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| images | 8px |
| inputs | 8px |
| buttons | 2px |
| cookieConsent | 4px |

### Layout

- **Section gap:** 80px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Ghost Navigation Link
**Role:** Primary navigation item

Text in Inkwell Black. No background, no border. Used for top navigation menu items. Font: Suisse Intl Book at 16px, weight 450.

### Filled Action Button
**Role:** Call to action button

Background: rgba(255, 255, 255, 0.12) - a translucent white over dark backgrounds. Text color: rgba(0, 0, 238) (browser default link blue, implying it's not a brand-specific button color). Border-radius: 4px. Padding: 10px vertical, 16px horizontal. Used for primary interactive buttons.

### Outlined Cookie Consent Button
**Role:** Secondary action in cookie consent

Background: Canvas White (#fefefc). Text color: rgb(0, 0, 238) (browser default link blue). Border-radius: 4px. Padding: 10px vertical, 16px horizontal.

### Text Input Field
**Role:** User input control

Background: Pale Ash (#ebf5ed). Text color: Text Gray (#0a0a0a). Border-radius: 8px. Padding: 10px all sides. Uses Suisse Intl Medium at 13px, weight 500.

### Cookie Consent Banner
**Role:** Legal disclosure pop-up

Background: Canvas White (#fefefc). Text: Whisper Gray (#444444). Rounded corners at 4px. Contains a filled and an outlined button.

## Do's and Don'ts

### Do
- Prioritize high visual contrast between text (#000000, #0a0a0a) and background (#fefefc, #ebf5ed), maintaining AAA accessibility standards.
- Use Rhymes Display Light (weight 300) for large headlines (32px and up) with a tight line height and negative letter-spacing for a refined, spacious feel.
- Apply Suisse Intl Book (weight 450) consistently for all body text, maintaining its specific font feature settings for brand consistency.
- Utilize Pale Ash (#ebf5ed) as a subtle alternating background color for content sections, providing visual rhythm without strong division.
- Employ a radius of 8px for cards, images, and input fields to convey a soft, modern touch.
- Ensure interactive elements like buttons and links maintain a clear visual distinction, even if the primary action color is derived from a browser default.
- Use Inkwell Black (#000000) for hero section text and prominent borders to create a strong initial impression against dark backgrounds.

### Don't
- Avoid using highly saturated colors for large UI elements; accents should be subtle and functional.
- Do not introduce strong drop shadows; rely on background color changes or minimal borders for surface differentiation.
- Do not deviate from the specified font families and weights, especially for Rhymes Display Light, as its unique weight defines the brand's headline style.
- Avoid over-clustering content; embrace white space and the specified elementGap (10px) to maintain a compact yet uncrowded appearance.
- Do not use generic system borders for inputs; always apply Pale Ash (#ebf5ed) background and 8px border-radius.
- Do not use multiple button styles for primary actions; stick to the translucent white filled button on dark backgrounds and the outlined white button on light backgrounds.
- Avoid full-bleed imagery that competes with text; imagery should be contained or used as a subtle background element as seen in the hero.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fefefc` | Primary page background and default light surface. |
| 1 | Pale Ash | `#ebf5ed` | Subtle elevated surface for input fields and alternating content blocks. |
| 2 | Parchment Tan | `#e1d5b6` | Accent background for specific content sections, providing a warm, slightly higher-level background. |

## Imagery

The site uses a mix of high-quality, professional photography and subtle, abstract visual elements, with a distinct absence of illustrative graphics. Photography is often dark and moody, featuring professional individuals in a corporate or office setting, sometimes blurred or used as a background layer, such as in the hero section. Product screenshots are clean, functional, and presented flat within UI frames, sometimes with a slight backdrop filter blur. Icons are minimal, outlined, and monochromatic, typically in Inkwell Black. The imagery serves both decorative atmospheric purposes (hero) and explanatory content (product screenshots), maintaining a refined and serious tone. Image density is moderate, used strategically to break up text-heavy sections or to establish a mood, rather than overwhelming the page.

## Layout

The page primarily employs a contained layout with a maximum content width, centered on a light canvas. The hero section is a full-bleed application of the Inkwell Black background with a foreground image, displaying a centered, large-format serif headline and supportive text. Subsequent sections alternate between the Canvas White and Pale Ash backgrounds, providing clear visual breaks. Content within these sections often uses a two-column layout, featuring text on one side and a product screenshot or abstract visual on the other, occasionally reversing the arrangement for rhythm (z-pattern). Vertical spacing is consistent with a section gap of 80px, contributing to a spacious feel. Navigation is handled by a sticky top bar with minimal ghost links and a single primary action button (Book a demo).

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #fefefc
border: #000000
accent: #e1d5b6
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create an Input Field: background Pale Ash (#ebf5ed), text Text Gray (#0a0a0a), border-radius 8px, padding 10px. Placeholder text in Suisse Intl Medium 13px weight 500, #6b6b6b.
3. Create a Feature Block: background Canvas White (#fefefc), heading 'Review faster' using Aktiv Grotesk VF Variable Regular 20px weight 400, #0a0a0a. Body text using Suisse Intl Book 14px weight 450, #0a0a0a. Card padding 16px, element gap 10px.

## Similar Brands

- **Axiom** — Legal tech with a professional, conservative aesthetic, minimalist UI, and emphasis on clear communication.
- **Clerk AI** — AI for legal professionals, featuring dark mode sections, sharp typography, and clean layouts.
- **LexisNexis** — Enterprise legal solutions often use classic serif typography for gravitas and a subdued color palette.
- **Palantir** — Complex data-heavy platforms often prioritize high contrast, crisp typography, and functional gray palettes.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell-black: #000000;
  --color-canvas-white: #fefefc;
  --color-text-gray: #0a0a0a;
  --color-pale-ash: #ebf5ed;
  --color-shadowstone-gray: #6b6b6b;
  --color-whisper-gray: #444444;
  --color-parchment-tan: #e1d5b6;
  --color-sky-tint: #bdd4f0;
  --color-steel-blue: #98a7aa;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl-book: 'Suisse Intl Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aktiv-grotesk-vf-variable-regular: 'Aktiv Grotesk VF Variable Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rhymes-display-light: 'Rhymes Display Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-playfair-display: 'Playfair Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl-medium: 'Suisse Intl Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 0.8;
  --text-body: 14px;
  --leading-body: 1.25;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --text-heading: 24px;
  --leading-heading: 1.1;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.32px;
  --text-display: 88px;
  --leading-display: 0.95;
  --tracking-display: -1.76px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-3xl: 40px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-images: 8px;
  --radius-inputs: 8px;
  --radius-buttons: 2px;
  --radius-cookieconsent: 4px;

  /* Surfaces */
  --surface-canvas-white: #fefefc;
  --surface-pale-ash: #ebf5ed;
  --surface-parchment-tan: #e1d5b6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell-black: #000000;
  --color-canvas-white: #fefefc;
  --color-text-gray: #0a0a0a;
  --color-pale-ash: #ebf5ed;
  --color-shadowstone-gray: #6b6b6b;
  --color-whisper-gray: #444444;
  --color-parchment-tan: #e1d5b6;
  --color-sky-tint: #bdd4f0;
  --color-steel-blue: #98a7aa;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl-book: 'Suisse Intl Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aktiv-grotesk-vf-variable-regular: 'Aktiv Grotesk VF Variable Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rhymes-display-light: 'Rhymes Display Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-playfair-display: 'Playfair Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl-medium: 'Suisse Intl Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 0.8;
  --text-body: 14px;
  --leading-body: 1.25;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --text-heading: 24px;
  --leading-heading: 1.1;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.32px;
  --text-display: 88px;
  --leading-display: 0.95;
  --tracking-display: -1.76px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-3xl: 40px;
}
```
