# Master Homepage Creation Memory & Standards

> **Status:** Active & Permanently Enforced  
> **Applies to:** New Repositories, Redesigns, and Homepage Deployments (e.g. `12testers-14-days.github.io`)  
> **Official Parent Platform:** `https://appconsolelab.com`  
> **Primary Authority:** AppConsoleLab Testing Infrastructure

---

## 1. Core Operating Principles

1. **Reference Websites Are For Architecture Only, Never Content**:
   - Reference repositories (such as `12-testers-google-play.github.io`) provide visual hierarchy, section ordering, layout, and component blueprints.
   - **NEVER copy, scrape, or lightly spin text from reference websites.**
   - Every single headline, description, FAQ, review, and checklist item must be authored **100% from scratch** with fresh, human-sounding English.
2. **Language & Tone Mandate**:
   - **Reading Level:** Grade 8 conversational English understood by developers globally.
   - **Zero AI / Corporate Jargon:** Banned phrases include *"Quality Assurance Benchmarks"*, *"Hardware Attestation Matrix"*, *"Telemetry Disqualification"*, *"Delve into"*, *"In today's fast-paced digital landscape"*, or repetitive *"QA"* phrasing.
   - **Preferred Vocabulary:** Use grounded, familiar terms: *"Testing Team"*, *"Physical Android Phones"*, *"Real Users"*, *"Bug Reports"*, *"Testing Track Record"*, *"Daily App Opens"*.

---

## 2. Visual Design & Theme Specifications

1. **Modern SaaS Light Theme (Default)**:
   - Base Background: `#ffffff`
   - Subtle Alternating Section Background: `#f8fafc`
   - Card Background: `#ffffff` with subtle borders (`#e2e8f0`)
   - Text Headings: Deep slate navy `#0f172a`
   - Text Body: Rich slate `#334155` / `#475569`
   - Text Muted: `#64748b`
   - Brand Primary: `#0284c7` (Sky/Blue)
   - Brand Hover: `#0369a1`
   - Accent Green (Verified / Badges): `#16a34a` (Light background: `#dcfce7`)
   - Accent Amber (Warnings / Highlights): `#d97706` (Light background: `#fef3c7`)
   - Shadows: Soft, modern elevation (`0 1px 3px rgba(15,23,42,0.05)`, `0 4px 12px rgba(15,23,42,0.06)`)
2. **Hero Section Modern Gradient**:
   - The modern gradient background MUST encompass the **complete hero section**: starting from the top badge (*"Google Play Closed Testing Service"*) down through the primary action CTAs (*"View Plans"* / *"Chat on WhatsApp"*).
   - Gradient recipe: Subtle radial & linear blend from `#eff6ff` / `#f0f9ff` to `#ffffff` with soft backdrop lighting.
3. **Typography**:
   - Display Font: `Plus Jakarta Sans` or `Space Grotesk` (headings with tight kerning `letter-spacing: -0.025em` to `-0.03em`).
   - Body Font: `Inter` or modern system sans-serif (`font-size: 1rem - 1.05rem`, `line-height: 1.7`).

---

## 3. Brand Identity, Logo & Sublogo Standards

1. **Modern Squircle Emblem (`.logo-svg`)**:
   - Geometry: 38×38px container with smooth continuous curvature (`rx="10"` on a 40x40 scale or `rx="16"` on a 64x64 scale).
   - Multi-Stop Tech Gradient: `#0284c7` (Electric Sky) → `#2563eb` (Sapphire) → `#4f46e5` (Deep Indigo).
   - Inner Bevel Highlight: Top-lit stroke (`rgba(255, 255, 255, 0.3)` with `stroke-width="1.5"`).
   - Central Mark: Crisp white rounded Google Play silhouette with subtle faceted glass fold lines (`#2563eb` with 32% opacity).
   - Verification Badge: Embedded emerald green circle (`#10b981` to `#047857`) in the lower-right corner with a crisp white checkmark.
   - Elevation & Hover: Ambient soft drop-shadow (`drop-shadow(0 3px 8px rgba(37,99,235,0.22))`), smoothly lifting on hover (`translateY(-1.5px)` with elevation glow).
2. **Wordmark & Typography**:
   - Primary Brand: `12 Testers` in deep ink slate (`#0f172a`, font-weight `800`, `letter-spacing: -0.028em`).
   - Accent Phrasing: `For 14 Days` in vibrant gradient text (`linear-gradient(135deg, #0284c7 0%, #2563eb 52%, #4f46e5 100%)`).
   - Byline: `by` in uppercase metadata tracking (`font-size: 0.65rem; font-weight: 700; letter-spacing: 0.08em; color: #94a3b8;`).
   - Sublogo: Official AppConsoleLab light theme logo (`assets/ACL_Logo_Light_theme.png`) strictly sized to **`40px` height** (`height: 40px; width: auto; object-fit: contain;`) with centered vertical alignment.
3. **Asset Consistency**:
   - `favicon.svg`, `assets/logo.svg`, `assets/og-image.svg`, and header/footer inline SVGs must share this identical visual language and color palette.

---

## 4. Header, Navigation & Layout Rules

1. **Header Placement**:
   - The site navigation header MUST be the **topmost element** on the page.
   - **NEVER place announcement bars, policy banners, or ticker ribbons above the header.**
2. **Navigation Structure**:
   - Left: Logo emblem + Wordmark + AppConsoleLab sublogo.
   - Right: Clean links (`Home`, `How It Works`, `Pricing`, `Reviews`, `FAQs`, `Guides`) + Primary WhatsApp Chat Button (`btn-whatsapp` with pulsing green dot).
   - Mobile: Responsive hamburger toggle that smoothly switches between open and close icons.
3. **No Layout Clutter**:
   - Between the primary hero CTAs and the next section, never inject misaligned, duplicate, or unrelated "How It Works" text blocks. Every section must have balanced padding (`4rem to 5.5rem`).

---

## 5. Homepage Sections & Narrative Flow

Every homepage must follow this high-converting architectural sequence:

1. **Hero Section**:
   - Trust badge with pulse dot (*"Google Play Closed Testing Service"*).
   - **H1 Heading:** Exact primary keyword: **`12 Testers For 14 Days`**.
   - Subheading: Explains how personal accounts achieve production access approval without stress.
   - Dual CTAs: "View Plans & Pricing" + "Chat on WhatsApp".
   - Hardware proof pills: *20+ Real Physical Devices • 14 Consecutive Days • Zero Bots • 100% Money-Back Guarantee*.
2. **How It Works (4-Step Sequential Flow)**:
   - Step 1: Track setup & Google Group invite.
   - Step 2: 20+ real Android testers join via Play Store opt-in links.
   - Step 3: 14 days of active daily engagement & mid-test bug fix update.
   - Step 4: Apply for production with completed 7 questionnaire answers.
3. **Real Phones vs. Emulators & Bot Swaps (Comparison Table)**:
   - Directly contrast Reddit/Discord swaps (70%+ resets, ghost testers, zero telemetry) against managed physical device cohorts (100% retention, real crash logs, 99%+ approval).
4. **Dedicated SEO Keyword Block**:
   - Placed immediately above the "Passing Google Review" section.
   - Focus question targeting search intent: *"Why is 12 Testers For 14 Days Required and How Does It Ensure Production Access?"*
   - Explains Google's personal account policy, continuous 336-hour opt-in retention, active telemetry, and avoiding Day 13 counter resets.
5. **Passing Google Review & The 7 Questionnaire Prompts**:
   - Educate the developer on what Google reviewers look for at the end of Day 14.
   - Outline the 7 review questions and explain why publishing a mid-test update (v1.0.1) is the #1 approval trigger.
6. **Pricing & Plans Section**:
   - Deliverables MUST match the main repository package points (34 total deliverable points across tiers):
     - **Basic Plan ($20)**: 25 physical testers assigned, 14 days active testing, crash logs, questionnaire support.
     - **Premium Plan ($39 - $50)**: 50 physical testers assigned, priority onboarding, enhanced daily engagement, dedicated supervisor, guaranteed approval assistance.
   - Official Ordering Notice: *"Visit our official website at appconsolelab.com for instant onboarding..."*
7. **Customer Reviews Section**:
   - 4 to 6 authentic reviews with unique names, developer countries, app niches, and star ratings.
8. **FAQs Section**:
   - 5 to 7 high-impact, uniquely answered developer questions. No arbitrary filler questions.
9. **Site Footer**:
   - Matching modern squircle logo + AppConsoleLab attribution.
   - Four organized link columns: Service, Compliance, Support, Legal.
   - Copyright notice & Google Play / Android trademark disclaimers.

---

## 6. Outbound Referral & Analytics Tracking Strategy

To ensure traffic originating from satellite/niche repos is accurately attributed in Google Analytics, Plausible, and server logs on `appconsolelab.com`, **all outbound links to `https://appconsolelab.com` MUST include direct referral and UTM tagging**:

| Link Placement | Target URL with Tracking Parameters |
| :--- | :--- |
| **Pricing Header Link** | `https://appconsolelab.com/?ref=<domain>&utm_source=<domain>&utm_medium=referral&utm_campaign=pricing_header` |
| **Official Ordering Banner** | `https://appconsolelab.com/?ref=<domain>&utm_source=<domain>&utm_medium=referral&utm_campaign=pricing_banner` |
| **Basic Plan Order Button** | `https://appconsolelab.com/?ref=<domain>&utm_source=<domain>&utm_medium=referral&utm_campaign=pricing_basic` |
| **Premium Plan Order Button**| `https://appconsolelab.com/?ref=<domain>&utm_source=<domain>&utm_medium=referral&utm_campaign=pricing_premium` |
| **In-Article Guide CTAs** | `https://appconsolelab.com/?ref=<domain>&utm_source=<domain>&utm_medium=referral&utm_campaign=article_<slug>` |
| **Schema.org Offer URLs** | `https://appconsolelab.com/?ref=<domain>&utm_source=<domain>&utm_medium=referral` |

*(Replace `<domain>` with the active repository domain, e.g. `12testers-14-days.github.io`)*

---

## 7. Technical SEO & Schema.org Standards

Every homepage deployment must include a unified **Schema.org JSON-LD architecture** containing:

1. **`@type: Organization`**:
   - Name: Matched to target brand (e.g. `"12 Testers For 14 Days"`)
   - URL: `https://<domain>/`
   - Logo: `https://<domain>/assets/logo.svg`
   - Customer Service Contact Point with international language array.
2. **`@type: WebSite`**:
   - Canonical URL, site name, and potentialAction search query definition.
3. **`@type: Product` / `AggregateOffer`**:
   - Pricing plans ($20 to $50) with tracked offer URLs routing to `appconsolelab.com`.
4. **`@type: FAQPage`**:
   - Maps all homepage FAQ questions and answers verbatim for Google rich result eligibility.
5. **Metadata Tags**:
   - Canonical `<link rel="canonical" href="https://<domain>/">`
   - OpenGraph (`og:title`, `og:description`, `og:image`, `og:url`, `og:site_name`)
   - Twitter Cards (`summary_large_image`)
   - Robots: `index, follow`
   - `sitemap.xml` and `robots.txt` present in root.

---

## 8. Deployment Checklist

Before finalizing any repository homepage:
- [ ] Header is the topmost element (no text/tickers above).
- [ ] AppConsoleLab sublogo is set to `height: 40px;` with light theme logo asset.
- [ ] Brand SVG logo uses the modern 38x38 squircle app badge.
- [ ] Full hero section has the modern light gradient background.
- [ ] Section between CTAs and How It Works is clean without misaligned elements.
- [ ] Pricing section has 34 deliverable checklist points across Basic & Premium.
- [ ] All outbound links to `appconsolelab.com` carry the `ref` and `utm_*` tracking parameters.
- [ ] JSON-LD structured data is 100% valid.
- [ ] Committed and pushed via Git API, GitHub Pages verified with HTTP 200.
