---
name: Obsidian Minimalist Portfolio
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#cfc4c5'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#988e90'
  outline-variant: '#4c4546'
  surface-tint: '#c6c6c6'
  primary: '#c6c6c6'
  on-primary: '#303030'
  primary-container: '#000000'
  on-primary-container: '#757575'
  inverse-primary: '#5e5e5e'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#000000'
  on-tertiary-container: '#767575'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 80px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  stack-sm: 1rem
  stack-md: 2rem
  stack-lg: 4rem
  stack-xl: 8rem
---

## Brand & Style
The design system is rooted in a "fully black" aesthetic that prioritizes void as a structural element. The brand personality is industrial, high-end, and uncompromisingly modern, tailored for professionals who want their work to speak louder than the UI. It leans heavily into **Minimalism** with a touch of **Digital Brutalism**, stripping away all non-essential decorations to focus on content, motion, and precise typography. 

The emotional response should be one of "quiet luxury"—a sense of calm, focus, and authority. The interface acts as a dark canvas where photography and text become the sole protagonists.

## Colors
The palette is strictly monochromatic to maintain an intense, focused atmosphere.

- **Primary (Pure Black #000000):** Used for the global background and deepest layers. It creates an infinite canvas effect.
- **Neutral (Deep Grey #121212):** Used for primary containers, card surfaces, and section dividers to provide subtle depth without breaking the "all black" feel.
- **Tertiary (Medium Grey #1A1A1A):** Used for hover states, input fields, and UI elements that require distinct separation from the background.
- **Accent (Pure White #FFFFFF):** Reserved exclusively for primary text, icons, and active interactive states. This provides maximum contrast and legibility.
- **Subtle Text (#888888):** A mid-tone grey for secondary information and meta-data to establish visual hierarchy.

## Typography
The system utilizes **Geist** for its clinical, technical precision and neutral character. It is paired with **JetBrains Mono** for labels and technical metadata to reinforce the industrial, developer-adjacent aesthetic.

- **Scale:** Large display sizes use tight tracking and leading to create impactful, monolithic blocks of text.
- **Hierarchy:** Contrast is achieved through weight and color (White vs. Grey) rather than complex font pairings.
- **Readability:** Body text maintains a generous line-height (1.6) to ensure comfort against the high-contrast black background.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to maintain tight control over line lengths and whitespace composition. 

- **Desktop:** A 12-column grid with a 1440px max-width. Margins are intentionally wide (64px) to create a "gallery" feel.
- **Mobile:** A 4-column grid with 24px margins. Content scales vertically with significant breathing room between sections.
- **Rhythm:** Spacing follows an 8px base unit. Section vertical spacing is aggressive (stack-xl), pushing the user to focus on one piece of content at a time.

## Elevation & Depth
This design system avoids traditional shadows entirely. Depth is communicated through **Tonal Layers** and **Low-Contrast Outlines**.

- **Level 0 (Base):** Pure Black (#000000).
- **Level 1 (Surfaces):** Dark Grey (#121212) surfaces.
- **Interaction:** Elements are elevated using 1px solid borders in #1A1A1A or #FFFFFF depending on priority. 
- **Glassmorphism:** Used sparingly for fixed navigation bars—a background blur (20px) with a 10% white tint to create a "dark glass" effect that reveals content passing underneath.

## Shapes
The shape language is strictly **Sharp (0px)**. Rectilinear forms reinforce the industrial and architectural tone of the system. 

- All buttons, input fields, and cards must have square corners.
- Images and media should be masked in hard-edged containers.
- The only exceptions are circular icons or profile avatars where a 100% radius is required for functional recognition.

## Components
Consistent component behavior is vital for the "High-End" feel:

- **Buttons:** Primary buttons are White (#FFFFFF) with Black text. Hover state involves a slight opacity dip (90%) or a "hollow" transition where the background becomes black with a white 1px border.
- **Inputs:** Underline-only or 1px bordered boxes. Use JetBrains Mono for placeholder text. Active state is a bright white border.
- **Cards:** No shadows. Use #121212 backgrounds. Hover triggers a subtle "lift" effect—either a 1px white border appearing or the background shifting to #1A1A1A.
- **Navigation:** Minimalist text links. Active state indicated by a small white dot or a subtle underline.
- **Chips/Labels:** Monospaced text inside 1px grey borders. No background fill.
- **Transitions:** All interactive elements should have a 200ms ease-out transition. Page reveals should use a staggered "fade and slide up" motion for text blocks.