# JJ's Concrete — Website Brief

## Business Info
- **Company:** JJ's Concrete
- **Owner:** Jim Jones
- **Phone:** 425-309-4954
- **Service Area:** Snohomish County, WA
- **Services:** Residential concrete pouring (driveways, patios, sidewalks, foundations, retaining walls, stamped/decorative concrete)
- **Team:** Small crew, owner-operated

## Design Rules
- **100% CUSTOM** — no frameworks, no Bootstrap, no Metronic, no Tailwind
- **Hand-crafted HTML + CSS + vanilla JS only**
- **Construction industry aesthetic** — rugged, bold, industrial
- **Think:** textured concrete backgrounds, bold sans-serif type, dark slate + orange/amber accents
- **Google Fonts:** Use something bold and industrial (e.g., Oswald for headings, Open Sans for body)
- **All CSS in a single `<style>` block or separate styles.css** — keep it simple
- **No external dependencies** beyond Google Fonts CDN

## Website Requirements
- **Single page website** (index.html) with sections that scroll
- **Mobile-first** — Jim's customers will mostly find him on their phones
- **No backend** — pure static HTML/CSS/JS, hosted on GitHub Pages
- **No email forms** — Jim isn't tech savvy, won't check email

## Sections
1. **Hero** — Full-viewport, bold headline "JJ's Concrete", tagline "Solid Work. Fair Price. Snohomish County.", call-to-action buttons
2. **Services** — 6 service cards with icons (use emoji or SVG, NOT icon libraries): Driveways, Patios, Sidewalks, Foundations, Retaining Walls, Stamped & Decorative
3. **Concrete Calculator** — Interactive tool: enter length (ft) × width (ft) × depth (inches) → outputs cubic yards needed. Formula: (L × W × (D/12)) / 27. Add note "Want an exact quote? Call Jim!" with call button
4. **About** — Owner-operated, small crew, pride in quality work, serving Snohomish County for years
5. **Service Area** — Cities served: Arlington, Marysville, Everett, Lake Stevens, Snohomish, Monroe, Granite Falls, Stanwood, Smokey Point
6. **Contact/CTA** — Big prominent call and text buttons, phone number displayed large

## Action Buttons
- **Call:** `<a href="tel:+14253094954">📞 Call Jim</a>` — tapping calls directly
- **Text:** `<a href="sms:+14253094954">💬 Text Jim</a>` — opens SMS
- Both should be LARGE, thumb-friendly, prominent on mobile
- Appear in hero section AND contact section
- Sticky header should also have a small call button

## Visual Design
- **Background:** Dark slate/charcoal (#2C3E50 range) with concrete texture via CSS (noise/gradient patterns, no images)
- **Accent:** Construction orange (#E67E22) or amber for CTAs and highlights
- **Text:** White (#FFFFFF) on dark, dark on light sections
- **Cards:** Slight glass-morphism or raised concrete block feel
- **Section alternation:** Alternate between dark and slightly lighter sections for visual rhythm
- **Typography:** Bold, uppercase headings. Clean readable body text.
- **CSS textures:** Use CSS gradients, noise patterns, or subtle repeating patterns to simulate concrete texture without images

## Technical
- `index.html` — entire website
- `styles.css` — all custom styles (optional, can be inline)
- `script.js` — calculator logic + smooth scroll (optional, can be inline)
- NO images needed — pure CSS/SVG design
- Must work on iPhone Safari, Chrome, and desktop browsers
- Smooth scroll behavior
- Sticky navigation
