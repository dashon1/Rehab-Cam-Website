# Swiss Design Specification: Series A Investor Deck

## 1. Direction & Rationale

**Style Name:** Swiss Tech-Financial (International Typographic Style)
**Visual Essence:** Absolute clarity, mathematical precision, and authoritative confidence using a "Royal Blue & Tech Teal" palette on a strict grid.

**Rationale:**
- **Investor Confidence:** The "Series A" stage requires demonstrating operational maturity. Swiss Design's rigid grid and lack of decoration signal discipline, precision, and reliable execution.
- **Data Clarity:** Financials and market analysis demand the highest legibility. The International Typographic Style (Helvetica, extensive whitespace, flush-left text) is historically optimized for complex data communication.
- **High-Density Feasibility:** The modular grid allows for dense information (common in send-ahead decks) without clutter, maintaining hierarchy through size and position rather than decoration.

**Key Characteristics:**
- **Asymmetric Balance:** Content is balanced by whitespace, not centered symmetry.
- **Mathematical Grid:** All elements align to a 12-column modular grid with 24px baseline rhythm.
- **Functional Color:** Royal Blue establishes authority; Tech Teal highlights growth/opportunity.
- **Typography-First:** Hierarchy is established strictly through font size and weight (Helvetica).

**Examples:**
- **Stripe/Linear:** For the "Tech Teal" accent usage and clean typography.
- **Braun/Lufthansa:** For the grid discipline and Helvetica neutrality.

---

## 2. Slide Templates

**Overview:** 7 Core Templates + 1 Custom "Product Demo" Template.
**Content Density Strategy:**
- **Maximum:** 7 lines of body text per slide.
- **Pagination:** If content exceeds 7 lines (common in 30-page decks), content **MUST** be split into "Part 1/2" or "Overview/Detail" slides.
- **Grid:** All templates use the 12-column grid.

### 2.1 Title Slide (Hero)
**Purpose:** High-impact opening or major section definitions.
**Layout:** Asymmetric. Solid **Royal Blue** background.
**Typography:**
- Title (H1 72-96px): Bold, flush left, aligns to col 2. White.
- Subtitle (H3 36px): Regular, flush left, below title. Tech Teal.
- Metadata (Label 14px): Top-left or bottom-left. White/50%.
**Visual Patterns:**
- Massive whitespace (60%).
- Geometric accent: Single Tech Teal horizontal line (4px height) spanning col 2-4.
- Logo: Top-right, White.

### 2.2 Content Slide (Standard)
**Purpose:** Core narrative, problem/solution, market text.
**Layout:** 2-Column Asymmetric (Text Left / Context Right). White background.
**Typography:**
- Slide Title (H2 54px): Top-left, Royal Blue.
- Body (24px): Col 1-7. Black. Max 7 lines.
- Captions/Notes (16px): Col 9-12 (Right rail). Gray.
**Visual Patterns:**
- **Pagination:** If >7 lines, use title suffix "(1/2)" and continue on next slide.
- **Divider:** Thin Royal Blue line (2px) separating Title from content.

### 2.3 Data Slide (Financials/Market)
**Purpose:** Growth metrics, market size, business model.
**Layout:** Chart dominant. White background.
**Typography:**
- Slide Title (H2 54px): Top-left, Royal Blue.
- Key Insight (H3 36px): Bottom-left or Top-right callout.
**Visual Patterns:**
- **Chart Area:** Occupies central 8 cols (Col 3-10).
- **Big Number:** 96px Bold Royal Blue for key metric (e.g., "300%").
- **Chart Style:** Minimal. No background grid. Axis lines in Light Gray. Data bars in Royal Blue (Current) and Tech Teal (Growth/Future).
- **Table Alternative:** Zebra striping (very light blue), Royal Blue header row, Black text.

### 2.4 Comparison Slide (Competition)
**Purpose:** Competitive advantages, feature matrix.
**Layout:** Grid matrix. White background.
**Typography:**
- Column Headers (24px Bold): Royal Blue.
- Row Labels (24px Medium): Black.
**Visual Patterns:**
- **Matrix:** 4-5 columns max.
- **Markers:** Checkmarks (SVG) in Tech Teal. "X" or dashes in Gray.
- **Highlight:** Our column has a subtle Tech Teal background tint (5% opacity) + 2px Royal Blue top border.

### 2.5 Quote / Vision Slide
**Purpose:** Founder vision, customer testimonial, social proof.
**Layout:** Centered or indent-heavy. Light Gray background (`#F5F7FA`).
**Typography:**
- Quote (H2 48-64px): Regular, Tight leading (1.1). Royal Blue.
- Attribution (24px): Bold. Black.
- Role (20px): Gray.
**Visual Patterns:**
- **Graphic:** Large stylized quotation mark (SVG) in Tech Teal (20% opacity) behind text.
- **Whitespace:** High (50%+).

### 2.6 Section Break
**Purpose:** Transition between the 6 major chapters.
**Layout:** Solid Royal Blue background.
**Typography:**
- Section Number (144px): Massive, Outline-only or Tech Teal. Top-left.
- Section Title (H1 72px): Bold, White. Center-left.
**Visual Patterns:**
- **Contrast:** High impact reset.
- **Progress:** Small "timeline" dots at bottom indicating section 1-6.

### 2.7 Product Demo (Custom)
**Purpose:** App screenshots, physical product views, diagrams.
**Layout:** Full-width or Split. White background.
**Typography:**
- Label (18px): Pointing to features. Royal Blue.
- Description (22px): Side column.
**Visual Patterns:**
- **Device Frame:** Minimal, vector-based laptop/phone frame (Gray stroke).
- **Shadow:** Deep, soft shadow (0 20px 40px rgba(0,0,0,0.15)) to lift product off grid.
- **Zoom:** Circular "magnifying glass" effect for detail shots (Tech Teal border).

### 2.8 Closing / Team Slide
**Purpose:** Team photos, contact info, "Ask".
**Layout:** Grid of photos or Centered CTA. White background.
**Typography:**
- Names (24px Bold): Royal Blue.
- Roles (18px): Tech Teal.
- Contact (H3 36px): Center-bottom.
**Visual Patterns:**
- **Photos:** Grayscale portraits with Royal Blue duotone effect on hover (if interactive) or simple rectangular crop (no radius).
- **Grid:** 4-up or 6-up strictly aligned.

---

## 3. Visual Guidelines

**Images & Photography:**
- **Style:** Objective, documentary-style. No staged stock.
- **Treatment:** Rectangular crops ONLY (0px border radius).
- **Sourcing Guidance:** Use high-resolution interface screenshots for "Product", clean architecture/office shots for "Market", and professional headshots for "Team".
- **Duotone (Optional):** For background/mood images, use Royal Blue mapping to unify distinct photo styles.

**Icons:**
- **Library:** Lucide or Heroicons (SVG).
- **Style:** Stroke-based (2px).
- **Color:** Tech Teal for action/feature icons. Royal Blue for navigation/ui.
- **Size:** 32px (standard), 64px (feature highlights).
- **Restriction:** ❌ NO Emojis.

**Charts & Data:**
- **Palette:** 
  - Primary Data: Royal Blue `#0047AB`
  - Secondary/Accent Data: Tech Teal `#00C2CB`
  - Neutral/Context: Gray `#E5E7EB`
- **Style:** Flat. No shadows on bars. No 3D.
- **Typography:** Axis labels 16px (Gray). Data labels 20px Bold (Blue).

**Shapes & Dividers:**
- **Lines:** 2px solid. Used to separate headers from content or define grid columns.
- **Rectangles:** Used as background for "Our Column" in comparisons or "Callout" boxes.
- **No Decoration:** No random circles, globs, or brush strokes.

**Animation (Transition):**
- **Page Load:** Immediate (0s) or very fast Fade (0.2s). Swiss design implies static print perfection.
- **Elements:** Staggered slide-up (20px distance, 0.4s duration, ease-out) for text blocks.
- **Charts:** "Grow" animation for bars (0.8s ease-out).

---

## 4. Implementation Restrictions

**MANDATORY for html_ppt_agent:**
- ❌ **NO specific content**: Templates must use placeholders like "{{Market Size}}", "Client Name", "Metric". NEVER include fake company names ("Acme") or specific financial data.
- ❌ **NO Emojis**: Use SVG icons only.
- ❌ **Pagination Enforcement**: If a slide's text exceeds 7 lines, the agent **MUST** split it into two slides (e.g., "Market Opportunity (1/2)" and "Market Opportunity (2/2)").
- ✅ **Grid Alignment**: Every element must snap to the 12-column grid defined in tokens.
- ✅ **Color Usage**: Royal Blue is for "Voice" (Titles, Primary Data). Tech Teal is for "Insight" (Growth, Highlights, Accents).
- ✅ **Token-Based**: All dimensions must use values from `swiss-series-a-ppt-tokens.json`.

---

