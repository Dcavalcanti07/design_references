# Dezeen — Style Reference
> Architectural Blueprint on Crisp White. This metaphor evokes the precision and clarity of architectural drawings and the pristine nature of a fresh page.

**Theme:** light

The Dezeen design system presents an editorial aesthetic, blending classic serif typography with a modern sans-serif for a distinctive voice. Dominant black text on bright white surfaces creates crisp readability, while the signature 'Indigo Accent' (#556e9b) injects a cool, authoritative hue across key interactive elements and titles. The layout emphasizes content separation and clear hierarchy, utilizing subtle borders and generous vertical spacing to frame articles and navigation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Primary text, core UI elements, bold borders — forms the backbone of the typographic hierarchy and defines structure. |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, input fields — provides expansive canvas for content and ensures high contrast. |
| Fog Gray | `#f0f0f0` | `--color-fog-gray` | Subtle background for UI sections, list backgrounds — offers a soft visual break from pure white without introducing chromatic noise. |
| Silver Ash | `#d8d8d8` | `--color-silver-ash` | Secondary backgrounds, subtle borders, inactive link states — provides subdued contrast for secondary content. |
| Concrete Gray | `#757575` | `--color-concrete-gray` | Subtle text, secondary links — used for less prominent textual information, such as timestamps or meta-information. |
| Soft Stone | `#eaeaea` | `--color-soft-stone` | Navigation backgrounds, dividers — a slightly darker off-white for structural elements. |
| Indigo Accent | `#556e9b` | `--color-indigo-accent` | Key headings, interactive links, active navigation, subtle button borders — establishes brand identity and guides user attention. |
| Sunset Orange | `#ff7617` | `--color-sunset-orange` | Accent for certain links, potentially call-to-action highlights — adds a vibrant, warm contrast. |

## Tokens — Typography

### StandardCT — Display and primary headings. The bold, all-caps presentation at larger sizes commands attention, while the specific font-feature-settings ensure stylistic consistency with the brand's custom type, providing a strong, editorial presence. · `--font-standardct`
- **Substitute:** Open Sans, Montserrat
- **Weights:** 700
- **Sizes:** 19px, 27px, 40px
- **Line height:** 0.95, 1.00, 1.10, 1.20, 1.25, 1.37, 1.38
- **OpenType features:** `"calt" 0, "kern", "liga" 0`
- **Role:** Display and primary headings. The bold, all-caps presentation at larger sizes commands attention, while the specific font-feature-settings ensure stylistic consistency with the brand's custom type, providing a strong, editorial presence.

### Chronicle Text G1 A — Body copy, article content, secondary headings, and general UI text. This serif font provides a classic, readable foundation for lengthy editorial content, distinguishing it from the sans-serif headings. · `--font-chronicle-text-g1-a`
- **Substitute:** Georgia, Merriweather
- **Weights:** 400, 700
- **Sizes:** 14px, 16px
- **Line height:** 1.23, 1.25, 1.29, 1.50
- **Role:** Body copy, article content, secondary headings, and general UI text. This serif font provides a classic, readable foundation for lengthy editorial content, distinguishing it from the sans-serif headings.

### Arial — System fallback for UI elements, labels, and minor interactive components where a clean, straightforward sans-serif is required. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 700
- **Sizes:** 13px, 14px, 16px
- **Line height:** 1.00, 1.20, 1.29
- **Role:** System fallback for UI elements, labels, and minor interactive components where a clean, straightforward sans-serif is required.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.29 | — | `--text-body` |
| body-lg | 16px | 1.25 | — | `--text-body-lg` |
| subheading | 19px | 1.38 | — | `--text-subheading` |
| heading | 27px | 1.2 | — | `--text-heading` |
| display | 40px | 1.1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 26 | 26px | `--spacing-26` |
| 30 | 30px | `--spacing-30` |
| 35 | 35px | `--spacing-35` |
| 50 | 50px | `--spacing-50` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| inputs | 0px |
| buttons | 0px |
| accentCircular | 100% |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(101, 122, 183, 0.6) 10px 0px 0px 0px, rgba(101, 122,...` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1212px
- **Section gap:** 48px
- **Card padding:** 0px
- **Element gap:** 9px

## Components

### Circular Play Button
**Role:** Interaction

Small, circular button with a black background (#000000) and an 'Indigo Accent' (#556e9b) border and text. Fully rounded (borderRadius: 50%) with no padding specified, implying a contained icon. This button is used for media playback, distinguished by its unique circular shape against a predominantly angular UI.

### Underlined Text Button
**Role:** Navigation/Action

Transparent background (rgba(0,0,0,0)) with 'Pitch Black' (#000000) text and border color. No border-radius. Minimal vertical padding (1px top/bottom, 6px sides). Used for text-based actions or links within content, maintaining a subtle presence.

### Circular Highlight Button
**Role:** Accent/Icon

Small, circular button with 'Silver Ash' (#dddddd) background and 'Pure White' (#ffffff) text. Fully rounded (borderRadius: 100%) with 5px padding on all sides. Used for prominent, small interactive elements or icons.

### Article Card
**Role:** Content Display

Transparent background with no border-radius or box-shadow, relying on text and image content for definition. No padding, implying content extends to edges. Used for displaying articles in lists or grids, maintaining a clean, unadorned presentation.

### Newsletter Input Field
**Role:** Form Input

Pure White (#ffffff) background with 'Pitch Black' (#000000) text and border. No border-radius, presenting a sharp, functional appearance. Features 0px top/bottom padding and 5px horizontal padding. Used for email subscription forms.

## Do's and Don'ts

### Do
- Use 'Pitch Black' (#000000) for all primary body text and 'Pure White' (#ffffff) for all main backgrounds to ensure high contrast and readability.
- Apply 'Indigo Accent' (#556e9b) exclusively to key interactive elements like links, active navigation items, and prominent headings to guide user focus.
- Reserve the 'Circular Play Button' style for media controls, emphasizing its unique shape against the otherwise angular design.
- Maintain 0px border-radius for all cards and input fields to uphold the sharp, architectural aesthetic.
- Utilize 'Chronicle Text G1 A' for all long-form editorial content at 14px or 16px with appropriate line heights (1.23-1.50) for optimal legibility.
- Employ 'StandardCT' (weight 700) for all main headings and titles, leveraging its strong editorial presence.
- Ensure generous vertical spacing, typically in multiples of 9px or 11px, between content blocks to create a comfortable density and clear content hierarchy.

### Don't
- Do not use shadow for card elevation; rely on clear borders or background color shifts where visible.
- Avoid decorative rounded corners on any elements other than specific circular buttons, as it contradicts the sharp, precise aesthetic.
- Do not introduce new chromatic colors unless explicitly defined as an accent; the palette is tightly controlled.
- Never use 'Arial' for main headings or body text; reserve it for minor UI elements or as a system fallback.
- Do not use excessive letter-spacing; all specified fonts use 'normal' letter-spacing to maintain typographic integrity.

## Elevation

- **Highlight Heading Borders:** `rgba(101, 122, 183, 0.6) 10px 0px 0px 0px, rgba(101, 122, 183, 0.6) -10px 0px 0px 0px`

## Imagery

This site prominently features photography within article cards and hero sections, often displayed full-bleed within its content blocks (0px padding, no radius). The photography style is varied, encompassing product shots, architectural exteriors and interiors, and landscape vistas, but generally leans towards high-quality, professional imagery that serves to illustrate content more than set a specific mood. Photos are contained, not overlapping, and appear without masks or special treatments. Density is moderate, balancing visual interest with text-dominant article layouts. Icons are minimal, typically monochrome, and integrated subtly for navigation or interaction.

## Layout

The page maintains a centered max-width of 1212px for its core content, providing a contained reading experience. The hero section often presents a split layout, with a prominent image juxtaposed against a large headline. Content sections follow a vertical rhythm, with consistent spacing of 9px to 11px between elements and an implied 48px between major sections. Articles typically arrange text and images in alternating left-right or stacked configurations. Navigation consists of a sticky top bar with a search utility and prominent category links, supplemented by a left sidebar for 'Highlights' and 'Most Popular' sections creating a multi-column editorial structure. The layout prioritizes clear content separation and readability.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000
- Background: #ffffff
- CTA: #556e9b
- Border: #000000 (primary), #556e9b (accent)
- Accent: #ff7617

### 3-5 Example Component Prompts
1. Create a primary headline: Text 'Milan design week must-sees', font 'StandardCT', weight 700, size 40px, lineHeight 1.1, color #000000, fontFeatureSettings '"calt" 0, "kern", "liga" 0'.
2. Design an article body paragraph: Text 'London studio about DSDHA prioritises "elegant frugality" in Henry Moore Studios gallery revamp', font 'Chronicle Text G1 A', weight 400, size 16px, lineHeight 1.25, color #000000.
3. Make an interactive text link: Text 'Highlights', font 'Chronicle Text G1 A', weight 400, size 14px, color #556e9b, with a subtle 1px #556e9b border on hover.
4. Build a newsletter input field: 'Pure White' (#ffffff) background, 'Pitch Black' (#000000) text and 1px border. No border-radius. Padding 0px top/bottom, 5px left/right. Placeholder text 'Email' in #000000 color.
5. Assemble an Article Card: Transparent background, no border-radius. Contains an image at the top (no corner radius), followed by a 'subheading' in 'StandardCT' and a 'body' text in 'Chronicle Text G1 A'. No internal padding for the card container.

## Similar Brands

- **ArchDaily** — Both are architectural editorial sites with a focus on clean, content-first layouts and sophisticated typography.
- **Wallpaper*** — Shares a high-contrast, editorial aesthetic with strong typographic hierarchy and a refined visual language.
- **The New York Times** — Employs a similar classic serif font for body text paired with a strong sans-serif for headlines, creating a timeless editorial feel.
- **Monocle** — Known for a structured, content-rich layout that blends clean typography with carefully curated imagery, similar to Dezeen's approach.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-pure-white: #ffffff;
  --color-fog-gray: #f0f0f0;
  --color-silver-ash: #d8d8d8;
  --color-concrete-gray: #757575;
  --color-soft-stone: #eaeaea;
  --color-indigo-accent: #556e9b;
  --color-sunset-orange: #ff7617;

  /* Typography — Font Families */
  --font-standardct: 'StandardCT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chronicle-text-g1-a: 'Chronicle Text G1 A', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.29;
  --text-body-lg: 16px;
  --leading-body-lg: 1.25;
  --text-subheading: 19px;
  --leading-subheading: 1.38;
  --text-heading: 27px;
  --leading-heading: 1.2;
  --text-display: 40px;
  --leading-display: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-50: 50px;

  /* Layout */
  --page-max-width: 1212px;
  --section-gap: 48px;
  --card-padding: 0px;
  --element-gap: 9px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-inputs: 0px;
  --radius-buttons: 0px;
  --radius-accentcircular: 100%;

  /* Shadows */
  --shadow-subtle: rgba(101, 122, 183, 0.6) 10px 0px 0px 0px, rgba(101, 122, 183, 0.6) -10px 0px 0px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-pure-white: #ffffff;
  --color-fog-gray: #f0f0f0;
  --color-silver-ash: #d8d8d8;
  --color-concrete-gray: #757575;
  --color-soft-stone: #eaeaea;
  --color-indigo-accent: #556e9b;
  --color-sunset-orange: #ff7617;

  /* Typography */
  --font-standardct: 'StandardCT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chronicle-text-g1-a: 'Chronicle Text G1 A', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.29;
  --text-body-lg: 16px;
  --leading-body-lg: 1.25;
  --text-subheading: 19px;
  --leading-subheading: 1.38;
  --text-heading: 27px;
  --leading-heading: 1.2;
  --text-display: 40px;
  --leading-display: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-50: 50px;

  /* Shadows */
  --shadow-subtle: rgba(101, 122, 183, 0.6) 10px 0px 0px 0px, rgba(101, 122, 183, 0.6) -10px 0px 0px 0px;
}
```
