---
name: Cyber-Minimalist Portfolio
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#ffb786'
  on-tertiary: '#502400'
  tertiary-container: '#df7412'
  on-tertiary-container: '#461f00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#ffb786'
  on-tertiary-fixed: '#311400'
  on-tertiary-fixed-variant: '#723600'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
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
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 120px
---

## Brand & Style
This design system is built for an AI Automation Engineer portfolio, prioritizing a high-tech, futuristic aesthetic that remains rooted in professional clarity. The brand personality is precise, innovative, and sophisticated. 

The design style is a hybrid of **Minimalism** and **Glassmorphism**. It utilizes a deep black environment to allow "electric" accents and data-driven visuals to pop. By removing unnecessary ornamentation and focusing on structural integrity and light-based hierarchy, the UI evokes the feeling of a high-end command center or a sophisticated neural network interface.

## Colors
The palette is dominated by "Deep Space" tones to ensure maximum contrast for the accent colors. 

- **Primary (Electric Blue):** Used for primary actions, active states, and core branding elements.
- **Secondary (Cyan):** Reserved for glow effects, data visualizations, and highlighting AI-driven components.
- **Background:** A pure `#0a0a0a` to provide a true-black canvas that disappears on OLED screens.
- **Surface:** A slightly lighter `#1a1a1a` used for glassmorphic cards and containers.
- **Typography:** High-contrast off-white for readability, with a muted grey for metadata and secondary descriptions.

## Typography
The typography system relies on **Geist** for its technical precision and modern feel. It is paired with **JetBrains Mono** for labels and technical metadata to reinforce the engineering focus of the portfolio.

- **Display Text:** Large, tight letter-spacing for a bold, cinematic feel.
- **Body Text:** Generous line-height to ensure readability against the dark background.
- **Monospaced Accents:** Used for tags, status indicators, and snippets of logic or "AI reasoning" to ground the design in code.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop (12 columns) and a fluid 4-column model on mobile. 

- **Generous Whitespace:** Sections are separated by large vertical gaps (120px+) to allow the engineer's work to breathe and feel "premium."
- **Safe Margins:** Content is centered with significant horizontal margins to prevent information density fatigue.
- **Alignment:** Strict adherence to a 4px baseline grid ensures that technical diagrams and UI elements feel mathematically aligned.

## Elevation & Depth
Depth is achieved through **Glassmorphism** and light emission rather than traditional shadows.

- **Surface Layers:** Use a semi-transparent surface color (`#1a1a1a` at 60% opacity) with a `20px` background blur to create a frosted glass effect.
- **Inner Glows:** Instead of drop shadows, use subtle `1px` top borders (linear-gradient) to simulate light hitting the edge of a transparent pane.
- **Accent Glows:** Use `box-shadow` with high blur radii (30px-60px) and low opacity (20%) using the Electric Blue or Cyan colors to suggest that AI components are "energized."

## Shapes
The design system uses **Soft** roundedness. While the aesthetic is futuristic, overly rounded "pill" shapes are avoided to maintain a professional, engineered look. Corners are clipped at `4px` to `12px` to feel precise but modern. Icons should use consistent stroke weights (1.5px or 2px) with slightly rounded caps.

## Components

### Buttons
- **Primary (Filled):** Electric Blue background with a subtle cyan outer glow. Text is white.
- **Secondary (Outlined):** `1px` border in Subtext color, transitioning to Electric Blue on hover with a faint background tint.
- **Ghost:** Monospaced text with an arrow icon that animates on hover.

### Glass Cards
Used for project showcases. Features a `1px` semi-transparent border, backdrop-filter blur, and a subtle gradient overlay that follows the mouse cursor to simulate light reflection.

### Progress & Flow Indicators
- **Animated Flows:** Use thin, glowing Cyan lines with "marching ants" animation to represent data moving between nodes.
- **Progress Bars:** Minimalist tracks with a glowing leading edge on the progress fill.

### Inputs & Chips
- **Fields:** Darker than the surface, with a primary blue bottom-border that illuminates when focused.
- **Tech Chips:** Monospaced font, small padding, and a subtle background tint that correlates to the specific technology category (e.g., LLM, Automation, DevOp).

### Iconography
Avoid stock photography. Use custom-styled vector icons and abstract nodes-and-edges diagrams to represent complex AI architectures.