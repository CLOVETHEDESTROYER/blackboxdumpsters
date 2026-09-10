# Black Box Dumpsters

Conversion-focused website redesign for Black Box Dumpsters in Albuquerque.

## Start locally

```bash
npm install
npm run dev
```

## Project notes

- Local preview: `http://127.0.0.1:5173/` while the development server is running.
- Production build: `npm run build`. Preview the build with `npm run preview`.
- `black-box-homepage-concept.png` is an early direction exploration, not a client-approved specification. The implemented design uses a split hero, pale green accents, editorial sections, and the refreshed logo.
- The quote form prepares an email draft using the existing public contact address. Visitors review and send it in their own email app. It does not transmit submissions to a backend, process payment, reserve inventory, or confirm availability.
- Confirm final prices, dimensions, weight allowances, phone number, permitted materials, service boundaries, and operating policies with the client before public launch. No unverified prices, phone number, ratings, or customer testimonials are displayed.
- Generated photographs depict Albuquerque-inspired scenes, not verified client equipment or completed jobs. The user requested the new branding on the generated dumpsters.

## Generated assets

Created with the built-in image-generation tool using its default available model. Both photographs used the generated logo as an image reference.

- `public/images/logo.png`: white geometric BLACK BOX wordmark, BOX enclosed in an outline, mint DUMPSTERS ON DEMAND tagline on black.
- `public/images/hero.png`: branded black dumpster at an Albuquerque stucco driveway in warm afternoon light, desert landscaping and Sandia mountain backdrop.
- `public/images/project.png`: matching branded dumpster beside an Albuquerque-inspired home renovation with neatly stacked lumber in daylight.

## Verification

- Production build passed.
- Browser checked the default desktop viewport and 390px mobile viewport; no mobile horizontal overflow and all images loaded.
- Checked mobile navigation, FAQ expansion, and quote form generation with sample data. No external email was sent.
- No browser console errors observed during these checks.
- Current Node 21 runs the build and dev server but is outside Vite's supported engine range. Use a supported Node LTS version for ongoing development.
