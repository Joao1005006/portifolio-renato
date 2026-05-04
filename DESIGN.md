---
name: Cyber-Minimalist Professional
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#bec8d2'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#88929b'
  outline-variant: '#3e4850'
  surface-tint: '#89ceff'
  primary: '#89ceff'
  on-primary: '#00344d'
  primary-container: '#0ea5e9'
  on-primary-container: '#003751'
  inverse-primary: '#006591'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#c0c1ff'
  on-tertiary: '#1000a9'
  tertiary-container: '#8d90ff'
  on-tertiary-container: '#1407ad'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c9e6ff'
  primary-fixed-dim: '#89ceff'
  on-primary-fixed: '#001e2f'
  on-primary-fixed-variant: '#004c6e'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  h1:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  code-inline:
    fontFamily: monospace
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 1.5rem
  section-gap: 8rem
  stack-sm: 0.5rem
  stack-md: 1rem
  stack-lg: 2rem
---

## Brand & Style

The design system is engineered to project the persona of a high-agency, technically proficient software engineer. It targets tech recruiters and potential collaborators who value precision and modern architectural thinking. The aesthetic fuses **Minimalism** with subtle **Glassmorphism** to create a "IDE-plus" atmosphere—one that feels like a premium development environment but remains accessible and polished.

The emotional response should be one of "calm authority." By leveraging deep, receding backgrounds and sharp, high-energy accents, the interface highlights the developer's technical output over decorative noise. This design system prioritizes clarity, structural integrity, and the beauty of logic.

## Colors

The palette is anchored in a sophisticated "Midnight Slate" base, providing a high-contrast foundation for technical data. 

- **Primary (Electric Cyan):** Used for primary actions, progress indicators, and core brand moments. It represents the "active state" of logic.
- **Secondary (Neon Mint):** Reserved specifically for highlighting specialized technical skills (C++, JavaScript) and "Success" states.
- **Tertiary (Digital Indigo):** Used for depth, such as secondary buttons or categorization of database-related content.
- **Neutral (Deep Slate):** A scale of slates from #020617 (background) to #94a3b8 (text) ensures a professional, non-stark dark mode that reduces eye strain.

## Typography

This design system utilizes a high-contrast typographic pairing to distinguish between narrative and technical data. 

- **Headlines:** Use **Space Grotesk** for its geometric, tech-forward personality. It feels engineered and precise. Use tight tracking on larger headers to maintain a sleek, modern look.
- **Body:** **Inter** is the workhorse here, providing maximum readability for project descriptions and personal bios.
- **Monospace:** Any reference to code snippet, database schema, or technical versioning must use a system monospace font to reinforce the developer-centric nature of the portfolio.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop, centered within the viewport to maintain focus. A 12-column system is used, but content is often offset to create dynamic asymmetrical balances typical of modern high-end portfolios.

Whitespace is used aggressively to separate projects. Large vertical gaps between sections (section-gap) ensure that the user’s focus remains on one "story" or skill at a time. Elements within cards or modules should follow a tight 8px (0.5rem) baseline grid to maintain a "technical spec" feel.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Glassmorphism**. Rather than traditional heavy shadows, this design system uses:

1.  **The Floor:** Background color #020617.
2.  **The Surface:** Background color #0f172a with a subtle 1px border (#1e293b).
3.  **The Float:** Semi-transparent surfaces (rgba(30, 41, 59, 0.7)) with a `backdrop-filter: blur(12px)`. This is reserved for navigation bars and modal overlays.
4.  **The Glow:** Subtle, low-opacity radial gradients (using the Primary Cyan) positioned behind key project cards to suggest a digital "aura" rather than a physical shadow.

## Shapes

The shape language is "Soft Tech." While the industry often uses sharp edges for a brutalist feel, this design system opts for **Rounded** corners (0.5rem base) to suggest a more refined, professional software product.

Interactive elements like buttons and input fields should utilize the standard `rounded-lg` (1rem) for a more approachable tactile feel, while decorative background elements or code blocks stay at the base `rounded` (0.5rem).

## Components

- **Buttons:** Primary buttons use a subtle linear gradient (Primary to Tertiary) with a hover effect that increases the "glow" (box-shadow) rather than changing the color. Text is always bold and high-contrast.
- **Project Cards:** Use a dark slate background with a 1px border. On hover, the border color transitions to the Primary Cyan. Images within cards should have a slight desaturation that returns to full color on hover.
- **Skill Chips:** Small, monospace labels with a low-opacity background tint of the skill's associated color (e.g., Cyan for C++, Green for JS). 
- **Code Snippet Blocks:** Styled to look like a premium IDE (e.g., VS Code "Night Owl" or "One Dark" themes). Include a "Copy" button and language indicator in the `label-caps` style.
- **Inputs:** Dark backgrounds with a subtle "inner shadow" to feel recessed. The focus state uses a 2px Primary Cyan border glow.
- **Timeline:** A vertical line for experience/education using a gradient stroke, with nodes that "light up" in the Secondary Green color.