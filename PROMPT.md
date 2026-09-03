# Build prompt

Create a single-page, cinematic WebGL experience called **YAKŌ** (夜光,
"nightglow"): a five-chapter night descent through Rokujō Ward, a fictional
rain-lit megacity. The result should feel like an editorial art book moving
through a live 3D world, not a conventional product landing page.

## Experience

- Use a fixed full-viewport Three.js canvas as the environmental layer.
- Build the towers, street canyon, signage, transit rails, cables, drones,
  holography, wet asphalt, rain, smog and the orbital relay procedurally.
- Drive one continuous camera path from page scroll. Each section should feel
  like a new composed shot rather than a hard scene replacement.
- Add restrained two-level bloom, radial chromatic aberration, film grain,
  scanlines, vignette, depth haze, and a rare signal tear.
- Keep the palette near-black, blue-charcoal, cyan, magenta, warm amber, and a
  single vermilion relay disc.

## Layout

- Structure the page as a hero, an underlevel chapter, a vertical-stack chapter,
  a wired-market chapter, an ascent closing, and a manifesto footer.
- Use oversized left-aligned English headings, large vertical Japanese display
  type, small technical labels, chapter numbers, fine rules, and generous
  negative space.
- Paint the editorial plates at runtime rather than shipping stills, and drive
  the bottom of the active viewport with procedurally drawn silhouette cutouts:
  parapets, stall lamps, vending machines, girders, banners, umbrella crowds,
  cloud banks, skylines.
- Foreground layers should arrive at full visual opacity, remain pinned while
  their section is active, then fade and blur away during the handoff.
- Centre any play icon within the image frame itself, excluding the caption area.

## Motion

- Reveal headings word by word and supporting elements individually.
- Use slow, precise section transitions, subtle parallax, and eased camera
  interpolation.
- Let the navigation, chapter rail, cards, and foreground layers respond to the
  active section.
- Include reduced-motion behaviour that preserves the complete reading
  experience.

## Interaction and quality

- Use a custom cursor only for fine pointer devices.
- Provide working anchor navigation, a full-viewport mobile menu, responsive
  layouts, semantic landmarks, and accessible labels.
- Keep runtime assets local and use relative paths so the site works under a
  repository subpath.
- Avoid frameworks, build tooling, analytics, trackers, remote fonts, image
  assets of any kind, generic glassmorphism, excessive glow, and decorative
  motion without narrative purpose.
- Verify at desktop and approximately 390 × 844, check all assets for 404s,
  parse every inline script, inspect the browser console, and test one complete
  scroll/navigation interaction before shipping.
