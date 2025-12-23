# Design Specification - Rehab-E-Cam Landing Page

## 1. Direction & Rationale
**Style Strategy**: **Modern Minimalism (Premium)** customized for **PropTech**.
The design bridges the gap between "Construction Reality" and "AI Precision". We use a clean, white-dominant foundation (Trust/Professionalism) punctuated by **Royal Blue** (Corporate/Medical grade trust) and **Tech Teal/Bright Green** (Innovation/Profit).
**Visual Essence**: "The Clarity of X-Ray Vision." The interface feels lightweight and precise, using glassmorphism hints in AR feature showcases to mimic the product's "heads-up display" experience, while keeping the main marketing content grounded and accessible.

## 2. Design Tokens

### 2.1 Color System
**Primary Palette (Brand):**
- **Primary (Royal Blue)**: `#3B82F6` (Main actions, Headers)
- **Secondary (Bright Green)**: `#22C55E` (Success, ROI, Money/Profit)
- **Accent (Tech Teal)**: `#0891B2` (AR/Tech highlights, replacing standard Teal)

**Neutral Palette:**
- **Surface 900 (Text)**: `#0F172A` (Dark Navy - deep, authoritative)
- **Surface 100 (Bg)**: `#F3F4F6` (Light Grey - section contrast)
- **Surface 0 (Card)**: `#FFFFFF` (Pure White)
- **Border**: `#E2E8F0` (Slate-200)

**Usage Rule**: 90% Neutral/White, 10% Royal Blue. Green used *only* for positive metrics (ROI, Savings) and success states.

### 2.2 Typography (Inter + Mono)
- **Headings**: `Inter` (Bold 700). Tight tracking (-0.02em). Clean, authoritative.
- **Body**: `Inter` (Regular 400). High readability.
- **Data/Tech**: `Roboto Mono` (Regular 400). Used for ROI numbers, technical specs, and "AR overlay" text elements to reinforce the "Tool" aesthetic.

### 2.3 Spacing & Radius
- **Grid**: 8px base.
- **Section Spacing**: 96px (Desktop), 64px (Mobile). High breathability to imply "Ease of use".
- **Card Padding**: 32px (Standard).
- **Radius**: 12px (Modern, friendly but professional). 
- **Buttons**: 8px radius (Slightly sharper than cards for action focus).

## 3. Component Specifications

### 3.1 Hero Section (The "X-Ray" Moment)
- **Structure**: Split layout (Text Left / Visual Right).
- **Visual**: Large mobile device mockup displaying the "Live X-Ray" AR view. The device should "float" (shadow `0 20px 25px -5px rgba(0,0,0,0.1)`).
- **Background**: White `#FFFFFF` with a subtle background pattern (`brand_pattern.png` at 5% opacity).
- **Typography**: H1 (64px) in Dark Navy. "AI-Powered" or "X-Ray" keywords highlighted in Royal Blue.
- **CTA**: Primary Button (Royal Blue, 56px height). Secondary Button (Outline, "Watch Demo").

### 3.2 Feature Cards (The "Toolbox")
- **Pattern**: 3-Column Grid.
- **Card Style**: White background, 1px Border `#E2E8F0`. Hover: Lift -4px + Shadow `lg` + Border Color `#3B82F6` (Blue).
- **Iconography**: 48px Brand Icons in Blue Circle (Light Blue bg `#EFF6FF`).
- **Content**: H3 (24px) + Body (16px). Simple, direct.

### 3.3 Split Feature Sections (The "Deep Dive")
- **Layout**: 50/50 alternating zig-zag.
- **Text Side**: H2 (48px) + Body + Bullet points with Green Checkmarks (`#22C55E`).
- **Visual Side**: Full-bleed screenshot or enclosed device mockup.
- **Decoration**: Subtle "Tech" lines or crosshairs (1px dashed slate-300) behind images to reinforce "Precision/Measurement" theme.

### 3.4 ROI/Benefit Metrics
- **Style**: Dark Section (Dark Navy `#0F172A`).
- **Text**: White.
- **Numbers**: `Roboto Mono`, Bright Green `#22C55E`, Huge (64-80px).
- **Label**: Inter, Slate-400, Uppercase tracking.
- **Vibe**: "Institutional Grade Data."

### 3.5 Pricing Table
- **Layout**: 3 Cards. Center card ("Pro") elevated (scale 1.05, shadow-xl, Blue top border).
- **Headings**: Inter Bold.
- **Price**: Inter Bold (Large).
- **Features List**: Checkmarks in Blue.
- **CTA**: Full width buttons.

### 3.6 Navigation & Footer
- **Nav**: Sticky White. Logo Left. Links Center. "Get App" Button Right.
- **Footer**: Dark Navy `#0F172A`. White text. 4-column layout (Product, Company, Resources, Legal).

## 4. Layout & Responsive Patterns

### 4.1 Responsive Strategy
- **Desktop (1280px+)**: 12-col grid. Generous 96px gaps.
- **Tablet (768px-1024px)**: 8-col grid. 64px gaps. Hero text scales down (64px → 48px).
- **Mobile (<768px)**: Single column stack. 48px gaps.
  - **Nav**: Collapses to Hamburger menu.
  - **Hero**: Image moves *below* text (Text First hierarchy).
  - **Cards**: Stack vertically with 24px gap.

### 4.2 Interaction
- **Scroll**: Sticky Nav appears after 100px scroll.
- **Hover**: Buttons lift -2px. Cards lift -4px.
- **Animation**: "Fade Up" (300ms ease-out) for text elements as they scroll into view.
- **Parallax**: Very subtle (5%) on the Hero Phone Mockup to create depth against the pattern background.

## 5. Interaction Standards
- **Buttons**:
  - Normal: `#3B82F6`
  - Hover: `#2563EB` (Darker Blue) + Scale 1.02
  - Active: Scale 0.98
- **Inputs**: Focus ring 2px `#3B82F6` (Blue).
- **Transitions**: All hover effects `transition-all duration-200 ease-out`.
