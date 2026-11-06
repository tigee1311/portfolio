# ayush-adi.vercel.app

Single-file portfolio. No build step.

Deploy
1. Replace `index.html` in your Vercel project with this one.
2. Keep `/profile.jpg` and `/screenshots/*.jpg` where they are. The page references them by the same paths as before.
3. Push. Vercel serves it as a static site.

Edit
- Copy lives in `<main>`. Each life chapter is a `.ch` block inside `.tl`.
- Project cards are `.proj` blocks. Swap the `href` on each to the real repo or demo link.
- Accent color and fonts are CSS variables at the top of `<style>`.
- ISS telemetry pulls from api.wheretheiss.at in the visitor's browser and falls back to static text if blocked.
- Agent cursors, boot screen, and all motion respect `prefers-reduced-motion` and hide below 700px.
