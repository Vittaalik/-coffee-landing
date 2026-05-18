# Coffee House Landing Page — CSS Design

**Date:** 2026-05-18  
**File:** `public/styles.css`

## Palette
| Role | Hex |
|---|---|
| Background | `#FFF8F0` |
| Primary text | `#3E2723` |
| Accent / brand | `#6F4E37` |
| Buttons | `#D4A574` |

## Typography
- Font family: Georgia, serif
- Hero heading: ~4.5rem, letter-spacing 0.05em
- Section headings: 2rem
- Body: 1rem / 1.7 line-height

## Layout
- Container: `max-width: 960px`, horizontally centered (`margin: 0 auto`)
- Sections separated by generous padding (80px top/bottom)

## Sections

### Hero
- Height: `100vh`, flexbox center (both axes)
- Semi-transparent dark overlay over a coffee-image background
- Large `<h1>` + subtitle paragraph + CTA button
- Button: background `#D4A574`, hover → darken + `translateY(-2px)` + box-shadow

### About
- Text-only, max-width 700px, centered
- Subtle top border in `#D4A574`

### Menu
- CSS Grid `repeat(2, 1fr)`, gap 24px
- Cards: white background, border-radius 8px, box-shadow
- Hover: `translateY(-4px)` + deeper shadow, transition 0.3s ease

### Contact
- Three-column flex layout (address / phone / hours)
- Background `#6F4E37`, text `#FFF8F0`

## Responsive (breakpoint 768px)
- Hero h1 scales to 2.5rem
- Menu grid → single column
- Contact columns → vertical stack
