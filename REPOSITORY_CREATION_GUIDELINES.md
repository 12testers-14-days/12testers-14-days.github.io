# Repository Creation & Web Development Guidelines

> **IMPORTANT PRINCIPLE**: Reference websites are provided strictly for layout, structural hierarchy, and design inspiration. **Never copy or scrape text verbatim from reference websites.** Always write 100% fresh, natural, human-sounding content.

---

### 1. Content Originality & Voice
- **Natural, Human Writing**: Write in clear, conversational, 8th-grade reading level English that developers anywhere in the world can easily read.
- **No Artificial Corporate Jargon**: Do not use terms like "Quality Assurance Benchmarks", "Telemetry Disqualification", "Hardware Attestation Matrix", or repetitive "QA" phrasing. Use simple, grounded words such as "Testing Track Record", "Our Testing Team", "Testing Results", and "App Checks".
- **Unique FAQs**: Include strictly the questions requested by the user. Do not invent arbitrary extra FAQs. Improve wording so each answer feels helpful and original.
- **Authentic Reviews**: Adapt customer reviews with small, meaningful changes to sentence structure and tone so they read genuinely and never sound like carbon copies.

---

### 2. Header, Navigation & Layout
- **No Unwanted Text Above Header**: Never place announcement bars or policy disclaimers above the site header unless specifically instructed. The header navigation bar must be the topmost element.
- **Clean CTA Alignment**: Keep primary call-to-action buttons clean, balanced, and uncluttered (e.g., "Get 12 Testers Now" and "Chat on WhatsApp"). Never squeeze unrelated navigation buttons or links between primary CTAs.
- **Section Integrity**: Verify that every section flows logically without overlapping cards, misaligned flex containers, or orphaned components.

---

### 3. Theme & Styling
- **Default Theme Selection**: When requested to build a modern light theme, use crisp, high-contrast colors:
  - Base Background: `#ffffff`
  - Subtle Alternate Background: `#f8fafc`
  - Headings: Deep slate navy `#0f172a`
  - Body Text: Rich slate `#334155` / `#475569`
  - Accent / Primary: `#0284c7` (Sky/Blue)
  - Success / Highlights: `#16a34a` (Emerald green)
  - Borders: Crisp light slate `#e2e8f0`
  - Soft subtle card shadows: `0 1px 3px rgba(0,0,0,0.05)`
- **Responsive by Default**: Full support for Desktop (>1024px), Tablet (768px - 1024px), and Mobile (<768px) with a functioning hamburger menu that toggles cleanly.

---

### 4. SEO & Schema Standards
- Target the exact primary keyword in `<title>`, `<meta name="description">`, `<h1>`, and throughout headings and body copy naturally.
- Implement 100% valid JSON-LD schemas (`Organization`, `WebSite`, `Service`, `HowTo`, `BreadcrumbList`, `FAQPage`, `Product`).
- Ensure canonical URL, favicon, OpenGraph, and Twitter tags match the target domain.
