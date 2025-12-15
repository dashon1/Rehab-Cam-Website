# Content Structure Plan - Rehab-E-Cam Landing Page

## 1. Material Inventory
**Content Files:**
- `docs/audience_messaging_framework.md`: Core value props, segment-specific messaging (Investors, Flippers, Contractors).
- `Rehab_E_Cam_Brand_Guidelines.md`: Visual identity, logo usage, color palette.
**Visual Assets:**
- `imgs/brand_primary_logo.png`, `imgs/brand_horizontal_logo.png`
- `imgs/brand_app_store_mockup.png`, `imgs/brand_mobile_app_mockup.png`
- `imgs/brand_feature_icons.png` (AR Camera, Calculator, etc.)
- `imgs/brand_product_showcase.png` (Live X-Ray demo)

## 2. Website Structure
**Type:** SPA (Single-Page Application) Marketing Landing Page
**Reasoning:** The primary goal is conversion (redirect to app). A linear, narrative-driven single page allows for a controlled storytelling flow: Problem → Solution (AR Tech) → Proof → Value → Conversion. It reduces friction and focuses user attention on the "Get the App" CTA.

## 3. Page/Section Breakdown

**Visual Asset Column Rules:**
- ✅ **Content Images**: Product UI, specific icons, team/testimonials.
- ❌ **Decorative Images**: Backgrounds, abstract patterns (handled in Design Spec).

### Page 1: Home / Landing Page (`/`)
**Purpose**: Convert visitors into app users by demonstrating AR value and ROI.

| Section | Component Pattern | Content Source | Content to Extract | Visual Asset (Content ONLY) |
|---------|------------------|----------------|-------------------|------------------------------|
| **Hero** | Hero Pattern | `audience_messaging_framework.md` (Executive Summary) | Headline: "The Field Evidence Layer..." or "Collapse Inspection & Analysis..."<br>Subhead: "Reduce time-to-close by 40%..."<br>CTA: "Get the App" / "Start Free Trial" | `imgs/brand_mobile_app_mockup.png` (Hero device shot) |
| **Social Proof** | Logo Strip | `audience_messaging_framework.md` (Segment II) | "Trusted by 1,000+ flippers" / Partner logos (Procore, Autodesk) | Partner Logos (if available) or Placeholder |
| **Key Features** | Feature Grid (3-col) | `brand_guidelines.md` (Icon Set) + Messaging | 1. Live X-Ray AR (See pricing while walking)<br>2. Deal Analysis (Investor math)<br>3. Scope Generation (Lender-ready SOWs) | `imgs/brand_feature_icons.png` (AR Camera, Calculator, Clipboard) |
| **Feature Spotlight 1** | Split Feature (Left-Right) | `audience_messaging_framework.md` (Pillars) | **Live X-Ray AR**: "See pricing while you walk." AR overlays eliminate office work. | `imgs/brand_product_showcase.png` (AR Interface view) |
| **Feature Spotlight 2** | Split Feature (Right-Left) | `audience_messaging_framework.md` (Pillars) | **Deal Analysis**: "Investor-grade logic." Calculate ARV and max offer on-site. | `imgs/brand_mobile_app_mockup.png` (Analysis Screen) |
| **Benefits / ROI** | Data Card Grid | `audience_messaging_framework.md` (Segment I & II) | "Reduce flip timelines from 162 to 120 days"<br>"Zero scope creep"<br>"Lender-ready from Day 1" | - |
| **Testimonials** | Review Carousel | `audience_messaging_framework.md` (Voice/Tone) | User quotes (Investor, Flipper, Contractor personas). Focus on "Time saved" and "Accuracy". | User Avatars (Placeholders) |
| **Pricing** | Pricing Table (3-col) | `audience_messaging_framework.md` (CTAs) | Plans: Free (Trial), Pro (Flipper), Enterprise (Portfolio). Focus on "ROI" and "Scale". | - |
| **FAQ** | Accordion List | `audience_messaging_framework.md` (Pain Points) | Integration with Procore? (Yes)<br>Data accuracy?<br>Device support? | - |
| **Footer** | Footer Pattern | `brand_guidelines.md` | Links: Contact, Privacy, Terms. Social links. | `imgs/brand_horizontal_logo.png` |

## 4. Content Analysis
**Information Density:** Medium
**Content Balance:**
- Images: High (App screenshots, AR visualizations are critical)
- Data/Charts: Medium (ROI metrics, pricing)
- Text: Medium (Concise value props, bullet points)
**Primary Focus:** Visual demonstration of the "Live X-Ray" technology to build trust in the "Magic" of the product.
