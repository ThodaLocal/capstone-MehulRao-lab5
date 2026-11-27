# UrbanNest Realty — Real Estate Listing Platform

**Web Dev I Lab Assignment 5 (Capstone)** · Theme: **Real Estate Listing Platform**
Built with pure **HTML5 & CSS3** — no JavaScript.

A fully responsive real-estate website for a Gurugram property agency, with verified property listings, filters, agent profiles and a site-visit inquiry form.

## Sections Implemented

- **Header / Nav** — sticky header with logo, primary navigation (internal links) and a "Book a Visit" CTA; includes a "Skip to main content" link for accessibility
- **Hero / Banner** — full-width banner image with headline, tagline, a property search bar (location / type / budget) and a stats strip (listings, families housed, rating)
- **Property Listings** — filter sidebar (property type, budget, BHK chips, amenities — visual only) beside a grid of 6 property cards with photos, For Sale / For Rent badges, price, beds / baths / area specs and the listing agent
- **Why UrbanNest** — 4 feature cards (verified listings, transparent pricing, home-loan assistance, legal help) plus 3 client testimonials
- **Agents** — 3 agent cards with photo, area of expertise, experience and call / email links
- **Inquiry Form** — site-visit / callback form with labelled, required fields (name, phone, email, property of interest, message)
- **Footer** — brand info, social icons (inline SVG), explore links, popular areas and contact details

## Layout Techniques

- **CSS Flexbox** — header, navigation, search bar, hero stats, spec rows, card footers, social icons
- **CSS Grid** — listing layout (sidebar + grid), property cards, features, testimonials, agents, contact layout, footer
- **CSS variables** (`:root`) for the colour palette, fonts, radius and shadow
- **Relative units** throughout — `rem`, `%`, `vw`, plus `clamp()` for fluid headings
- **Visual polish** — hover lift on cards, `transition: all 0.25s ease`, and a `heroRise` keyframe animation on the hero content
- **Accessibility** — semantic landmarks (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`), meaningful `alt` text on every image, `aria-label`s on navigation and social links, and a `<label>` for every form field

## Breakpoints

| Breakpoint | What changes |
|---|---|
| Desktop (above 1024px) | Full layout — 2-column property grid with sticky filter sidebar, 4-column features, 3-column agents/testimonials |
| Tablet (≤1024px) | Features drop to 2 columns, footer to 2 columns, narrower filter sidebar |
| Mobile (≤768px) | Header stacks, filter sidebar moves above listings, all grids become single-column, contact form stacks |
| Small phones (≤480px) | Features and footer single-column, tighter spacing, card actions stack |

## How to Open

1. Download or clone this repository.
2. Open `index.html` in any modern browser — no server or build step needed.
3. Optional: enable **GitHub Pages** (Settings → Pages → deploy from `main` branch) to view it online.

## Project Structure

```
capstone-MehulRao-lab5/
├── index.html
├── style.css
├── images/
│   ├── hero.jpg
│   ├── prop1.jpg … prop6.jpg
│   └── agent1.jpg … agent3.jpg
└── README.md
```

*Images: Unsplash (free to use). Property details, prices and agent contacts are sample data created for this academic project.*
