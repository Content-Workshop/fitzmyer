# Fitzmyer: Shop & Services page (concept mockup)

A one-page HTML/CSS mockup of a new **Shop & Services** page for fitzmyer.com (WordPress + Elementor).
Open `index.html` in a browser to view it.

## Direction
- **Structure:** Anchor Pump's services page (the client's favorite reference). Intro and quote button → core services → brand band → capabilities → quote form and service area.
- **Style:** Phoenix Pumps. Bold uppercase hero, white service cards with outlined "See Details" buttons, pale section bands.
- **Brand:** Fitzmyer's Elementor global colors (`#012C64`, `#117DC2`, `#2987C5`, `#333333`, `#F3F6FF`) and fonts (Montserrat for headings, Roboto for body text).
- **Copy:** taken from fitzmyer.com (homepage, Pump Types and Pump Manufacturers pages), lightly tightened. Nothing new is claimed, such as warranties, 24/7 service, years in business or certifications.

## Placeholders to replace
| Item | Where |
|---|---|
| Logo PNG (currently a text wordmark) | Header and footer |
| Hero photo (repair shop, 1920×700) | Hero |
| Repair bench photo (4:3) | Intro |
| 8 product photos | "Shop by Pump Type" cards (image file names noted on each) |
| 8 manufacturer logos | "Brands We Sell, Service & Repair" band |
| "See Details" link targets | Service cards (all point to the quote form for now) |
| Quote form | Connect to the existing Gravity Forms **Request A Quote** form (ID 2) |

## Building it in Elementor
Each `<section>` maps to one Elementor section. The card grids map to Icon Box / Image Box widgets in a 4-column inner section. The filter chips on the pump-type grid are optional; drop them for a static grid. Add **Shop & Services** to the main menu between Pump Types and Blog.

## Open questions for the client
- Should "Shop" mean quote requests only (as mocked), or real online purchasing (WooCommerce)?
- Are there service claims we should add, such as a repair warranty, turnaround times, field service or emergency service?
- Which manufacturers is Fitzmyer *authorized* to service? The band currently says "sell, service & repair" for the brands featured on the homepage.
