# Design System — Story on Steroids

## Colors
- Background: #000000 (pure black — no tint)
- Primary accent: #00d4ff (electric cyan)
- Before/bad state: #ff6b6b (warm red)
- Text primary: rgba(255,255,255,0.92)
- Text muted: rgba(255,255,255,0.35)
- Divider/glow: rgba(120,200,255,0.7) with box-shadow spread

## Typography
- Headings: system-ui, -apple-system, BlinkMacSystemFont (native stack) — tight tracking, heavy weight
- Body: same stack, lighter weight
- Labels: 10–11px, letter-spacing: 1.5–2px, uppercase, 800 weight

## Elevation & Surfaces
- Cards: border-radius 20–22px, border 1px rgba(255,255,255,0.06)
- Active states: box-shadow with cyan glow
- Divider line: 1.5px white + box-shadow cyan glow

## Motion
- Interactions: 200–300ms ease
- Intro animations: 1s delay, then gentle sweep
- Avoid heavy JS animation libraries — CSS transitions preferred

## Component: Before/After Slider
- Vertical white line (1.5px) with baby-blue glow
- Handle: 40px white circle with chevron arrows (SVG, not emoji)
- Labels: pill badges — cyan for Pro, red for Phone
- Background: #000000 absolute
- 9:16 aspect ratio, max-width 320px centered, border-radius 22px
