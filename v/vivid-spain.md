# Vivid Spain — Style Reference
> diffused lavender light

**Theme:** light

Vivid Spain's design system feels like a digital canvas touched by soft, diffused light, giving financial services an approachable, almost ethereal quality. The pervasive use of very subtle, near-gray lavenders and clear white creates a clean, expansive backdrop. Pops of vivid violet on interactive elements act as gentle guiding lights, preventing the light palette from feeling sterile and instead imbuing it with a sense of calm innovation. The subtle use of gradients adds a painterly depth, making backgrounds feel less like solid blocks and more like atmospheric washes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#24282d` | `--color-midnight-ink` | Primary text for headlines and body copy, providing high contrast against light backgrounds. Also used for borders and icons, establishing a consistent dark tone for important elements. |
| Snowdrift | `#ffffff` | `--color-snowdrift` | Dominant page and card backgrounds, ensuring a clean and spacious feel. Used for high-contrast text on accent buttons. |
| Graphite | `#333333` | `--color-graphite` | Secondary text color for body copy and button labels, offering slightly softer contrast than Midnight Ink. Also used for icons and borders. |
| Ash Gray | `#79797f` | `--color-ash-gray` | Subtle text for secondary information, metadata, and inactive states. Used for icons and borders in less prominent areas, contributing to clarity without boldness. |
| Pale Lavender | `#f4edff` | `--color-pale-lavender` | Subtle background for card surfaces and interactive elements like navigation items, adding a brand-specific soft hue without overwhelming the layout. |
| Cloud Gray | `#eceef2` | `--color-cloud-gray` | Borders and subtle background fills for components, providing structure with minimal visual weight. Used for dividers and secondary interaction states. |
| Desert Sand | `#f5f5f4` | `--color-desert-sand` | Subtle background for certain informational blocks, offering a slight textural variation from pure white. |
| Frosty Pearl | `#bbbbc1` | `--color-frosty-pearl` | Less prominent borders and icon fills, hinting at interactive or secondary elements without drawing primary attention. |
| Vivid Violet | `#7d33f6` | `--color-vivid-violet` | Primary brand accent, used for prominent CTA buttons, active navigation states, and key links. This color makes interactive elements unmistakable and injects brand energy. |
| Hero Gradient | `linear-gradient(251deg, rgb(248, 240, 237) -9.1%, rgb(242, 228, 240) 36.43%, rgb(170, 147, 234) 105.93%)` | `--color-hero-gradient` | Background gradient for hero sections and illustrative elements, creating a soft, ethereal visual entry point. |
| Pricing Card Gradient | `radial-gradient(circle at 0px 100%, rgb(247, 236, 238) 0px, rgb(231, 215, 239) 60%, rgb(199, 164, 230) 68%, rgb(159, 127, 225) 100%)` | `--color-pricing-card-gradient` | Background gradient within pricing cards, adding a subtle depth and visual interest to structured content. |
| Success Green | `#00b67a` | `--color-success-green` | Signifier for positive states and success indicators, maintaining a clear semantic role. |
| Light Success | `#daf7db` | `--color-light-success` | Subtle background for success messages or elements, providing a soft backdrop to the main green. |

## Tokens — Typography

### Satoshi — The primary typeface for all content, from headlines to body text. Its subtle variance in letter-spacing across sizes, from slightly expanded at small text (10px) to slightly condensed at display sizes (60px), creates a cohesive visual flow where headlines feel expansive and body text remains clear. The use of weights 400 and 500 for body copy ensures high readability without being overly heavy, while 600 and 700 are reserved for emphasized elements and larger headings. · `--font-satoshi`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 13px, 14px, 15px, 16px, 20px, 24px, 36px, 40px, 52px, 56px, 60px
- **Line height:** 1.00, 1.10, 1.14, 1.17, 1.20, 1.25, 1.29, 1.30, 1.33, 1.38, 1.50, 1.57, 1.60, 2.00
- **Letter spacing:** 0.3, 0.12, 0.1, 0.08, 0.05, -0.05, -0.09, -0.1, -0.11, -0.15, -0.2, -0.2, -0.21
- **Role:** The primary typeface for all content, from headlines to body text. Its subtle variance in letter-spacing across sizes, from slightly expanded at small text (10px) to slightly condensed at display sizes (60px), creates a cohesive visual flow where headlines feel expansive and body text remains clear. The use of weights 400 and 500 for body copy ensures high readability without being overly heavy, while 600 and 700 are reserved for emphasized elements and larger headings.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.3px | `--text-caption` |
| body | 15px | 1.6 | 0.05px | `--text-body` |
| subheading | 20px | 1.3 | -0.09px | `--text-subheading` |
| heading | 36px | 1.17 | -0.11px | `--text-heading` |
| display | 52px | 1.1 | -0.2px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

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
| 80 | 80px | `--spacing-80` |
| 176 | 176px | `--spacing-176` |

### Border Radius

| Element | Value |
|---------|-------|
| full | 48px |
| cards | 24px |
| buttons | 100px |
| elements | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.08) 0px 8px 32px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 72px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Navigation Link
**Role:** Interactive element

Text only, no background, color Graphite (#333333), 0px rounded corners. Used in main navigation.

### Nav Pill Button
**Role:** Secondary action / Navigation

Background Snowdrift (#ffffff), text Graphite (#000000), border Cloud Gray (#eceef2), 100px border-radius, 1px vertical padding, 6px horizontal padding. Used for 'Login' style buttons in header.

### Secondary Pill Button (Pale)
**Role:** Secondary action / Tag

Background Desert Sand (#f5f5f4), text Graphite (#333333), border Graphite (#333333), 48px border-radius, 12px vertical padding, 36px horizontal padding. Used for subtly emphasized actions or tags.

### Subtle Card
**Role:** Content container

Transparent background, 24px border-radius, no box-shadow, 24px padding.

### Input Field
**Role:** User input

Transparent background, text Midnight Ink (#000000), border Midnight Ink (#000000), 0px border-radius, no padding specified.

### Pricing Tier Card (Primary)
**Role:** Call to action variant

Background using Pricing Card Gradient, 24px border-radius, 24px padding, no explicit shadow. Used for emphasized pricing tiers like 'Pro'.

## Do's and Don'ts

### Do
- Prioritize Satoshi for all text elements; ensure correct weight and letter-spacing for each size to maintain the brand's typographic tone.
- Use Vivid Violet (#7d33f6) exclusively for primary calls to action and active interactive states, reserving its prominence.
- Apply Pale Lavender (#f4edff) or Snowdrift (#ffffff) for card backgrounds and content sections to maintain a bright, spacious feel.
- Utilize 24px border-radius for all content cards and larger photographic elements, establishing a consistent soft geometry.
- Embed the Hero Gradient on primary hero sections to create a distinct, atmospheric entry point.
- Employ Midnight Ink (#24282d) and Graphite (#333333) for all primary text, ensuring high contrast and readability on light backgrounds.
- Maintain a uniform elementGap of 8px for consistent internal spacing between smaller elements.

### Don't
- Avoid introducing new primary colors; maintain the dominance of violet and the neutral palette to prevent visual clutter.
- Do not use box-shadows for elevation; instead, rely on background color variations and subtle background gradients to imply depth.
- Do not use sharp corners; ensure all significant interactive elements and containers adhere to the 24px or 100px border-radius system.
- Limit the use of bold (weight 700) to critical headlines or emphasized words; primarily use 400 and 500 for body text.
- Avoid generic button styles; stick to the defined pill-shaped buttons with 100px or 48px border-radius.
- Do not vary letter-spacing for different custom weights of the same font size; follow the defined letter-spacing rules per size.
- Do not add additional padding to components unless specifically defined, especially for buttons which rely on internal content for their perceived size.

## Imagery

The visual language of imagery is a mix of abstract 3D renders, illustrative product screenshots on devices, and stylized headshot photography. Product screenshots are clean, showcasing the UI on tablets and phones against a soft, gradient background. Abstract 3D elements, like floating coins or stylized objects (e.g., a briefcase), complement the clean UI, often rendered in muted tones or with soft light. Photography features diverse, professional-looking individuals, often in natural light, in a lifestyle context, but integrated into UI cards rather than full-bleed. Icons are primarily filled or subtly outlined, monochrome in Graphite (#333333) or Vivid Violet (#7d33f6), maintaining a sleek, minimal aesthetic. The overall density of imagery is balanced, with visuals serving an explanatory or brand-reinforcing role rather than purely decorative, providing clear context for banking solutions.

## Layout

The page model is primarily full-bleed with a centered content area that is not strictly constrained by a max-width, allowing sections to breathe. The hero section is a full-bleed gradient background with a prominent, left-aligned headline and CTA, complemented by illustrative product shots on the right. Section rhythm is driven by alternating background colors, primarily white and Pale Lavender, creating distinct yet seamlessly flowing content blocks. Content arrangement frequently uses a split layout (text left, image/illustration right) or centered content stacks for headings and pricing tables. Feature sections often use a 4-column card grid, providing an organized display of information. The layout feels spacious, with ample vertical breathing room between sections. Navigation is a sticky top bar with a left-aligned logo, central navigation links, and right-aligned action buttons ('Login', 'Open an account').

## Agent Prompt Guide

### Quick Color Reference
- Text: #24282d (Midnight Ink)
- Background: #ffffff (Snowdrift)
- Primary CTA: #7d33f6 (Vivid Violet)
- Border/Divider: #eceef2 (Cloud Gray)
- Card Background: #f4edff (Pale Lavender)

### 3-5 Example Component Prompts
1. **Create a hero section:** Full-width background using the Hero Gradient. Left-aligned headline 'Best Business Account 2026' in Satoshi, 52px, weight 700, line-height 1.1, letter-spacing -0.2px, color Midnight Ink (#24282d). Below, body text 'Open an account...' in Satoshi, 15px, weight 400, line-height 1.6, letter-spacing 0.05px, color Graphite (#333333). Include a Primary Filled Button 'Open a business account' with background Vivid Violet (#7d33f6), text Snowdrift (#ffffff), 100px border-radius, and 12px 36px padding.
2. **Generate a feature card:** Use a Subtle Card container (transparent background, 24px border-radius, 24px padding). Inside, a heading 'Business Account' in Satoshi, 20px, weight 600, line-height 1.3, letter-spacing -0.09px, color Midnight Ink (#24282d). Below, body text 'With a quick registration...' in Satoshi, 15px, weight 400, line-height 1.6, letter-spacing 0.05px, color Ash Gray (#79797f). Include a small illustrative image 200px wide, with 24px border-radius.
3. **Design a navigation bar:** Fixed at the top, background Snowdrift (#ffffff). Left logo. Centered navigation links, e.g., 'Products', 'Solutions' as Navigation Links (text Graphite #333333, Satoshi, 16px, weight 500). Right-aligned 'Login' as a Nav Pill Button (bg #ffffff, text #000000, border #eceef2, 100px radius, 1px 6px padding) and 'Open an account' as a Primary Filled Button (bg #7d33f6, text #ffffff, 100px radius, 12px 36px padding).

## Similar Brands

- **Revolut** — Similar fintech focus with a clean, light UI and a prominent accent color (though less gradient-heavy).
- **N26** — Employs a white-dominant interface with rounded corners and a direct, approachable tone reinforced by typography.
- **Monzo** — Uses bright accent colors against a predominantly white and light gray background, paired with friendly, sans-serif typography.
- **Chime** — Features a light theme with clear, accessible UI design and often incorporates subtle gradients or soft visual elements in its branding.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #24282d;
  --color-snowdrift: #ffffff;
  --color-graphite: #333333;
  --color-ash-gray: #79797f;
  --color-pale-lavender: #f4edff;
  --color-cloud-gray: #eceef2;
  --color-desert-sand: #f5f5f4;
  --color-frosty-pearl: #bbbbc1;
  --color-vivid-violet: #7d33f6;
  --color-hero-gradient: #e9d4fb;
  --gradient-hero-gradient: linear-gradient(251deg, rgb(248, 240, 237) -9.1%, rgb(242, 228, 240) 36.43%, rgb(170, 147, 234) 105.93%);
  --color-pricing-card-gradient: #c786e1;
  --gradient-pricing-card-gradient: radial-gradient(circle at 0px 100%, rgb(247, 236, 238) 0px, rgb(231, 215, 239) 60%, rgb(199, 164, 230) 68%, rgb(159, 127, 225) 100%);
  --color-success-green: #00b67a;
  --color-light-success: #daf7db;

  /* Typography — Font Families */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.3px;
  --text-body: 15px;
  --leading-body: 1.6;
  --tracking-body: 0.05px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.09px;
  --text-heading: 36px;
  --leading-heading: 1.17;
  --tracking-heading: -0.11px;
  --text-display: 52px;
  --leading-display: 1.1;
  --tracking-display: -0.2px;

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
  --spacing-80: 80px;
  --spacing-176: 176px;

  /* Layout */
  --section-gap: 72px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-full: 48px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-full: 48px;
  --radius-cards: 24px;
  --radius-buttons: 100px;
  --radius-elements: 10px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.08) 0px 8px 32px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #24282d;
  --color-snowdrift: #ffffff;
  --color-graphite: #333333;
  --color-ash-gray: #79797f;
  --color-pale-lavender: #f4edff;
  --color-cloud-gray: #eceef2;
  --color-desert-sand: #f5f5f4;
  --color-frosty-pearl: #bbbbc1;
  --color-vivid-violet: #7d33f6;
  --color-hero-gradient: #e9d4fb;
  --color-pricing-card-gradient: #c786e1;
  --color-success-green: #00b67a;
  --color-light-success: #daf7db;

  /* Typography */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.3px;
  --text-body: 15px;
  --leading-body: 1.6;
  --tracking-body: 0.05px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.09px;
  --text-heading: 36px;
  --leading-heading: 1.17;
  --tracking-heading: -0.11px;
  --text-display: 52px;
  --leading-display: 1.1;
  --tracking-display: -0.2px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-176: 176px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-full: 48px;
  --radius-full-2: 100px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.08) 0px 8px 32px 0px;
}
```
