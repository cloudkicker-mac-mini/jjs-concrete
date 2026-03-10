# JJ's Concrete — Website Brief

## Business Info
- **Company:** JJ's Concrete
- **Owner:** Jim Jones
- **Phone:** 425-309-4954
- **Service Area:** Snohomish County, WA
- **Services:** Residential concrete pouring (driveways, patios, sidewalks, foundations, retaining walls, stamped/decorative concrete)
- **Team:** Small crew, owner-operated

## Website Requirements
- **Single page website** (index.html) with sections that scroll
- **Mobile-first** — Jim's customers will mostly find him on their phones
- **No backend** — pure static HTML/CSS/JS, will be hosted on GitHub Pages
- **No email forms** — Jim isn't tech savvy, won't check email

## Sections
1. **Hero** — Bold headline, concrete imagery (use stock/placeholder), call-to-action buttons
2. **Services** — Cards showing: Driveways, Patios, Sidewalks, Foundations, Retaining Walls, Stamped/Decorative
3. **Concrete Calculator** — Simple calculator: enter length × width × depth → outputs cubic yards needed + estimated bags of concrete. Include a note "Get an exact quote — call Jim!"
4. **About** — Brief section about JJ's Concrete, family-owned, serving Snohomish County
5. **Service Area** — List of cities: Arlington, Marysville, Everett, Lake Stevens, Snohomish, Monroe, Granite Falls, Stanwood, Smokey Point
6. **Contact/CTA** — Big call and text buttons

## Action Buttons (appear in hero AND contact section)
- **Call button:** `<a href="tel:+14253094954">` — tapping calls Jim directly
- **Text button:** `<a href="sms:+14253094954">` — opens SMS to Jim
- Both should be large, thumb-friendly, prominent

## Design Direction
- **Colors:** Concrete gray tones + a bold accent (orange or safety yellow — construction vibes)
- **Font:** Inter (already in Metronic)
- **Style:** Clean, professional, trustworthy. Not flashy. A working man's business.
- **Icons:** KEEN icons only (ki-duotone with path spans)

## Technical
- Built on Metronic 8.3.2 template (assets already in place)
- Base href should be "./"
- Use style.bundle.css and scripts.bundle.js from assets/
- No external dependencies beyond what's in the template
- Must work perfectly on mobile

## File Structure
- `index.html` — the entire website (single page)
- `assets/` — Metronic assets (already copied)
- No other files needed
