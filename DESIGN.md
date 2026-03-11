# OperON Design System

A semantic outline of the OperON visual language for UI generation.

## 1. Core Identity & Theme
- **Theme**: Dark Mode, Tech-focused B2B, Futuristic.
- **Concept**: Task as a Service (TaaS), scalable neural operations.

## 2. Colors & Tokens
- **Background**: Deep Black `#050505`
- **Text Primary**: White `#FFFFFF` 
- **Text Secondary**: Gray `#9ca3af`
- **Primary Accent**: Brand Orange `#FF6B00`
- **Secondary Accent**: Light Orange `#FFA500`

## 3. Typography
- **Font Family**: Inter (sans-serif)
- **Headings**: Extrabold, tight tracking (`tracking-tight`), often using typography gradients or pure white.
- **Body**: Light or normal weight, relaxed line height.

## 4. Components & Styles
- **Glass Cards**: 
  - Background: `rgba(255, 255, 255, 0.03)`
  - Backdrop Filter: `blur(12px)`
  - Border: `1px solid rgba(255, 255, 255, 0.1)`
  - Border Radius: typically `rounded-3xl`
  - Hover State: Border color shifts to `rgba(255, 107, 0, 0.4)`, slight lift `transform: translateY(-5px)`, and subtle orange glow shadow.
- **Buttons**:
  - Primary: Background `#FF6B00`, Text White, fully rounded (`rounded-full` or `rounded-xl`), hover effect to brighter orange with orange glow shadow.
  - Secondary/Glass: Glass card style, text white, border hover `#FF6B00`.
- **Badges/Tags**:
  - Background: `#FF6B00` at 10% opacity, border `#FF6B00` at 30% opacity, text `#FF6B00`, uppercase, extreme tracking (`tracking-widest`), small text.

## 5. Visual Flourishes
- Neural mesh grid backgrounds.
- Floating glowing orbs (radial gradients of `#FF6B00` at high blur layer).
- Scroll progress bars.

## 6. Design System Notes for Stitch Generation
Platform: Web, Desktop-first
Theme: Dark, futuristic, B2B tech
Background: Deep Black (#050505) with subtle neural grid patterns
Cards/Surfaces: Glassmorphism (#ffffff at 3% opacity with 12px backdrop blur), 1px solid white border at 10% opacity, rounded-3xl
Primary Accent: Brand Orange (#FF6B00)
Typography: Inter (Google Font) - extrabold for headings, light for paragraphs
Buttons: Rounded, bold, #FF6B00 with subtle glow on hover
