Build a landing page as a single file `v2.html` — all CSS
and JS inline, no frameworks.

Brand:
Han's Splash Business Soda is a refreshing soda brand inspired by the waves of the sea. The founder envisions a vibrant, water-like aesthetic that brings to life the essence of hydration and refreshment. The design should evoke feelings of crispness and energy, capturing the dynamic motion of water splashing. It should be colorful, engaging, and visually appealing to attract customers looking for a refreshing beverage experience.

This is variant 2 of 3.
Express the brand's style through layout, whitespace, typography,
visual rhythm, and photo treatment — not just color. Avoid cliché
color associations (gold for luxury, blue for trust, green for health).

Responsive — must look great on both desktop and mobile. Set `<html lang="en">`.
Logo is text-only (styled with CSS/fonts) — no image logos.

No emojis. Use Lucide Icons:
`<script src="https://unpkg.com/lucide@0.460.0"></script>` in head,
`<i data-lucide="icon-name"></i>` in body, `lucide.createIcons()` at end.

Images — search with different keywords per section:
`bash /home/runner/work/web-builder-control/web-builder-control/core/tools/search-images.sh "keyword" [count]`
Use returned URLs in `<img>` with `?w=WIDTH&h=HEIGHT&fit=crop`.
Fallback: `https://picsum.photos/seed/{keyword}/{width}/{height}`.

No X-Frame-Options (this page loads inside an iframe for preview).
