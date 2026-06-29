# Maya Tan — Personal Consulting Website

A premium, single-page personal brand website for **Maya Tan**, an independent growth and
market expansion consultant based in Singapore.

## Overview

Built as a fast, dependency-free static site (HTML + CSS + vanilla JS) for instant load times,
top-tier Lighthouse scores, and zero build tooling. Designed to feel like the online presence
of a sought-after consultant working with founders, startups, and scaling companies across
Asia-Pacific.

### Sections
- **Hero** — headline, value proposition, CTAs, portrait, and animated metric counters
- **About** — biography and an animated career timeline
- **Services** — five service offerings as elegant cards
- **Success Stories** — three case studies with measurable results
- **Testimonials** — founder & investor quotes with headshots
- **Insights** — thought-leadership / blog card grid
- **Process** — four-step working process
- **Personal Brand** — lifestyle gallery and credibility stats
- **Booking** — discovery call form, contact details, and FAQ
- **Footer** — navigation and monthly newsletter signup

## Design system
- **Colors:** white, charcoal, deep navy, warm beige, minimal gold accents
- **Type:** Fraunces (display serif) + Inter (sans) via Google Fonts
- **Motion:** scroll-reveal, animated counters, hover micro-interactions — all respect
  `prefers-reduced-motion`
- Fully responsive, mobile-first, SEO-optimized (meta tags, Open Graph, JSON-LD, sitemap, robots)

## Running locally

It's a static site — open `index.html` directly, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Files
```
index.html     # markup + SEO metadata + structured data
styles.css     # design system and responsive layout
script.js      # nav, scroll reveals, counters, form handling
favicon.svg    # brand mark
robots.txt     # crawler directives
sitemap.xml    # sitemap
```

## Notes
- Imagery uses Unsplash placeholders; swap the `src` URLs for Maya's professional photography
  before launch.
- Forms are wired with front-end validation and demo confirmation messages. Connect the
  `submit` handlers in `script.js` to a real endpoint (e.g. Formspree, a serverless function,
  or a CRM) to capture leads.
