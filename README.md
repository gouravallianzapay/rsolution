# R-Geo Solution — Client Website Demo

Independent, responsive frontend proposal built with React 19, TypeScript, Vite and Tailwind CSS. This does not modify or connect to the live rgeosolution.com website.

## Run locally

Requires Node.js 22+ and npm.

```bash
npm ci
npm run dev
```

Open the local URL printed by Vite (default http://localhost:4173).

```bash
npm run build
npm run preview
npm test
```

`npm test` builds first, then runs DOM-based smoke checks covering all pages, service links, layer switching, zoom, markers, slider keyboard-compatible input, mobile menu state and form error/success flows. This is not a replacement for browser visual/device testing.

## Pages

Home, About, Services, 16 service detail pages, Industries, Courses, Work Showcase, Contact and a 404 view. Deep links require the static host to fall back to index.html (SPA routing).

## Demo boundaries

- No enquiry is transmitted or stored. Form confirmation is explicit about this.
- Interactive map geometry is synthetic; it is not geographic survey data.
- Before/after comparison uses one source illustration plus a synthetic overlay, not a measured project result.
- The delivery process is a suggested project journey, not a verified company procedure.
- No client logos, new testimonials, certifications, performance figures or project outcomes were invented.
- No course fees, next batch dates or placement guarantees were added.
- Pages are marked noindex, nofollow for the proposal demo.
- Source images are bundled locally, avoiding remote hotlink dependencies.

See CONTENT_SOURCES.md for verified company information and imagery credits.

## Before a production launch

Confirm content and permission for existing company imagery/testimonial, approve final branding and course details, connect enquiry handling with appropriate privacy terms, replace illustrative work with approved case studies, complete browser/device and accessibility QA, and change the noindex metadata only when approved.
