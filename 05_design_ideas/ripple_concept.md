# The Ripple — Design Concept

## Origin

Proposed by a B.L.U.E. community member in the Discord brainstorming channels.

## Concept

The Ripple is a visual metaphor for how knowledge should spread:
- A single drop (one person learning) creates ripples that expand outward
- Ripples interact and overlap (different learners, different paths)
- No gatekeeping — the water is open to all
- The "splash" represents the moment of understanding

## Visual Identity

### Logo
- Concentric circles expanding from a center point
- Modular — can be simplified to a single dot with rings for small sizes
- Color: Blue gradient (deep ocean to bright cyan)

### ASCII Art Landing Page
- Interactive water simulation using text characters
- Ripples expand from cursor movement and clicks
- Characters fade from dense (`@`, `#`) to sparse (`.`, ` `) as ripples dissipate
- Central logo unaffected by ripples — the source of knowledge

### Role Icons (Proposed)
Instead of unique icons per field, use the same ripple base with different "disturbance patterns":
- Programming: Sharp, square-edged waves
- Arts: Soft, irregular waves  
- Science: Precise, symmetrical waves
- History: Layered, overlapping waves
- Math: Geometric spiral patterns

## Technical Implementation

The prototype uses:
- HTML5 Canvas for rendering
- JavaScript for ripple physics simulation
- ASCII character mapping for visual density
- No external dependencies — works offline

## Files

- `ripple_landing_page.html` — Working prototype with search bar
