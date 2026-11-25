---
name: impeccable
description: Polish web interfaces to human-crafted editorial standards—eliminating AI slop, refining typographic rhythm, spacing, and micro-details while preserving existing architecture.
---

# Impeccable Design Standards

When polishing, maintaining, or adding elements to this portfolio, follow these rules strictly:

1. **Zero AI Slop:** Never reintroduce generic SaaS card grids, nested bordered pills inside cards, multi-color sticker icons, or redundant uppercase eyebrow labels above clear section headings.
2. **Editorial Restraint:** Maintain open layouts anchored by `1px` hairline borders, generous vertical whitespace, and crisp left-aligned typographic hierarchy across Desktop and Mobile.
3. **Strict Token Adherence:** Use only the existing `:root` and `[data-theme="dark"]` CSS variables. Never introduce arbitrary hex colors, pure `#000000`, or loud gradients.
4. **Optical Alignment & Media:** Ensure portraits use `object-fit: cover` with proper `object-position` framing, and verify all asset paths use exact case-sensitive filenames inside `images/`.
5. **Separation of Motion & Theme:** Keep CSS transitions strictly limited to color properties (`background-color`, `color`, `border-color`) and let GSAP + ScrollTrigger + Lenis handle all `transform` and `opacity` animations across all viewports.
6. **Surgical Edits Only:** When asked to fix or polish a specific section, modify only the targeted component without altering working sections, language switchers (ID/EN), modals, or scroll triggers.
