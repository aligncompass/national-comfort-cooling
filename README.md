# National Comfort Cooling — AlignCompass customer site

Content-driven **Astro** site for **National Comfort Cooling** (HVAC — AC repair,
maintenance & replacement, Miami FL). Built from the AlignCompass customer-site
template; all copy and design tokens live in
[`src/data/content.json`](src/data/content.json). Imagery is served from
Cloudinary (cloud `aligncompass`, folder `national-comfort-cooling`).

- **Live:** https://aligncompass.com/national-comfort-cooling/
- **Stack:** Astro + Tailwind, static output, `base: /national-comfort-cooling`.
- **Deploy:** linked to Vercel — every push to `main` auto-deploys; the apex
  repo (`aligncompass/aligncompass-site`) proxies `/national-comfort-cooling/*`
  to this project's `.vercel.app` alias.

## Develop

```bash
npm install
npm run dev      # local dev server
npm run build    # static build -> dist/
```

To change copy, design tokens, sections, or imagery, edit
`src/data/content.json` and push -- do not hand-edit generated HTML.

## Notes

Originated as the ALI-76 design-taste proof build (Linear ALI-77 productionized
it). Brand colors/fonts, exact service area, business hours, address, license #,
reviews, and photography should be confirmed against the real business; the
booking CTA is currently phone-only.
