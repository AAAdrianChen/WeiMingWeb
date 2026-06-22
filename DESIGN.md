---
name: Professional Deep Blue
colors:
  surface: '#ffffff'
  surface-dim: '#f5f5f5'
  surface-bright: '#ffffff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f5f5'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#0f172a'
  on-surface-variant: '#475569'
  inverse-surface: '#1e293b'
  inverse-on-surface: '#f8fafc'
  outline: '#e2e8f0'
  outline-variant: '#cbd5e1'
  surface-tint: '#1e3a5f'
  primary: '#1e3a5f'
  on-primary: '#ffffff'
  primary-container: '#152a45'
  on-primary-container: '#93c5fd'
  inverse-primary: '#2563eb'
  secondary: '#2563eb'
  on-secondary: '#ffffff'
  secondary-container: '#dbeafe'
  on-secondary-container: '#1e3a5f'
  tertiary: '#1e293b'
  on-tertiary: '#ffffff'
  tertiary-container: '#334155'
  on-tertiary-container: '#cbd5e1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbeafe'
  primary-fixed-dim: '#bfdbfe'
  on-primary-fixed: '#1e3a5f'
  on-primary-fixed-variant: '#1d4ed8'
  secondary-fixed: '#dbeafe'
  secondary-fixed-dim: '#bfdbfe'
  on-secondary-fixed: '#1e3a5f'
  on-secondary-fixed-variant: '#1d4ed8'
  tertiary-fixed: '#e2e8f0'
  tertiary-fixed-dim: '#cbd5e1'
  on-tertiary-fixed: '#1e293b'
  on-tertiary-fixed-variant: '#475569'
  background: '#fafafa'
  on-background: '#0f172a'
  surface-variant: '#f5f5f5'
typography:
  display:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1440px
---

## Brand & Style
This design system is built on a foundation of absolute clarity and high-end technical precision. The brand personality is authoritative yet understated, designed to evoke a sense of reliability and expert craftsmanship in the B2B technology space.

The aesthetic follows a **Minimalist** philosophy combined with **Corporate Modern** sensibilities. A disciplined, deep blue palette replaces the distraction of arbitrary color, anchoring the UI in a sense of trust and engineering rigor. The emotional response should be one of "calm confidence"—a professional environment where complex data feels manageable and high-stakes decisions feel supported by a stable, no-nonsense interface.

## Colors
The palette is anchored by a deep, authoritative navy (**Primary: #1E3A5F**) that evokes institutional trust and engineering depth. A vibrant but disciplined blue (**Accent: #2563EB**) serves as the sole functional highlight for CTAs, active states, and key metrics, ensuring calls-to-action are unmistakable without breaking the calm tone.

The system relies on a curated scale of neutral greys and slate blues to establish depth without introducing visual noise.
- **Secondary colors** (#3B82F6) are used for secondary icons, supporting text, and hover states.
- **Tertiary and Neutral tones** (#64748B, #94A3B8) define surface areas, dividers, and disabled states.
- **Dark surfaces** (#0F172A, #1E293B) are reserved for high-impact case study sections and footer areas, creating dramatic contrast while maintaining the blue-grey family to avoid a "gaming" aesthetic.
Whitespace is treated as a functional color; the background is a crisp, clean off-white (#FAFAFA) to maximize legibility and provide the "breathability" expected of a premium B2B platform.

## Typography
This design system utilizes **Geist** for its entire typographic stack. Chosen for its developer-centric precision and modern geometric construction, it reinforces the technical B2B aesthetic.

Hierarchy is established through weight and scale rather than color. Headlines use tight letter-spacing and heavy weights to command attention, while body text maintains a generous line-height for sustained reading. All labels are optimized for clarity, with a preference for uppercase styling in UI-specific identifiers to create a rhythmic distinction from narrative content.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop, centering content within a 1440px container to ensure readability on ultra-wide monitors. A 12-column system is used to organize complex dashboards and data views.

The spacing rhythm is based on a strict 8px linear scale. We prioritize "large-scale" whitespace (the `xl` unit) to separate major sections, creating the "luxury" feel of an uncrowded interface. On mobile devices, the 12-column grid collapses to a single-column flow with 16px side margins, while gutters are maintained at 24px to prevent visual density from becoming overwhelming.

## Elevation & Depth
Depth is communicated through **Low-contrast outlines** and **Tonal layers** rather than heavy shadows.

1.  **Level 0 (Surface):** The base background (#FAFAFA).
2.  **Level 1 (Planes):** Subtle 1px borders (#E2E8F0) to define containers and cards.
3.  **Level 2 (Interaction):** Slight tonal shifts (#F5F5F5) for hovered states.
4.  **Level 3 (Overlays):** For modals or dropdowns, a sharp 1px slate border is used to "cut" through the background, occasionally paired with a very soft, high-diffusion grey shadow (0px 10px 30px rgba(0,0,0,0.05)) to suggest a physical lift.

Glassmorphism is used sparingly for persistent navigation bars, employing a high-density background blur (20px) to maintain focus on the content beneath.

## Shapes
To maintain a professional and "engineered" look, the design system utilizes **Soft (Level 1)** roundedness.

A corner radius of `0.25rem` (4px) is the standard for buttons, input fields, and small UI components. This subtle rounding removes the "aggression" of sharp points while maintaining a structured, rectangular profile. Larger containers, such as cards or modals, may scale up to `rounded-lg` (8px) to soften the overall layout, but circles and pill shapes are strictly reserved for specific components like avatars or status indicators (chips).

## Components

### Buttons
- **Primary:** Solid accent blue (#2563EB) background, white text. No border. High contrast.
- **Secondary:** White background, 1px accent blue border, dark blue text.
- **Ghost:** No background or border. Dark blue text. Used for tertiary actions.

### Input Fields
Inputs use a minimalist 1px border (#E2E8F0) that transitions to 1px accent blue (#2563EB) on focus. Labels sit outside the field in a `label-md` style for maximum clarity.

### Chips & Tags
Used for categorization, chips feature a light neutral background (#F4F5F5) with `body-sm` typography. They do not have borders unless they are actionable (e.g., removable filters).

### Cards
Cards are defined by their 1px light grey borders rather than shadows. They should have generous internal padding (`md` or `24px`) to ensure content does not feel cramped.

### Lists & Tables
Data-heavy views utilize thin horizontal dividers (#E2E8F0). Alternate row striping is discouraged; instead, hover states on the entire row using a soft neutral tint provide the necessary visual tracking.
