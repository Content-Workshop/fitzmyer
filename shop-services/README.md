# Fitzmyer: Shop & Services page (concept mockup)

A one-page HTML/CSS mockup of a new **Shop & Services** page for fitzmyer.com (WordPress + Elementor).
Open `index.html` in a browser to view it.

## Direction
- **Structure:** Anchor Pump's services page (the client's favorite reference). Intro and quote button → core services → inside our shop → brand band → why us → quote form and service area.
- **"Shop" means the physical repair shop**, not online sales. The "Inside Our Shop" section mirrors Anchor's shop photos and capabilities list.
- **Style:** Phoenix Pumps. Bold uppercase hero, white service cards with outlined "See Details" buttons, pale section bands.
- **Brand:** Fitzmyer's Elementor global colors (`#012C64`, `#117DC2`, `#2987C5`, `#333333`, `#F3F6FF`) and fonts (Montserrat for headings, Roboto for body text).
- **Copy:** taken from fitzmyer.com (homepage, Pump Types and Pump Manufacturers pages), lightly tightened. Nothing new is claimed, such as warranties, 24/7 service, years in business or certifications.

## Placeholders to replace
| Item | Where |
|---|---|
| Logo PNG (currently a text wordmark) | Header and footer |
| Hero photo (repair shop, 1920×700) | Hero |
| Repair bench photo (4:3) | Intro |
| 4 shop photos | "Inside Our Shop" gallery |
| Shop equipment, lifting capacity, testing | "What our shop handles" list (marked "Confirm with client") |
| 8 manufacturer logos | "Brands We Sell, Service & Repair" band |
| "See Details" link targets | Service cards (all point to the quote form for now) |
| Quote form | Connect to the existing Gravity Forms **Request A Quote** form (ID 2) |

## Building it in Elementor
Each `<section>` maps to one Elementor section. The service cards map to Icon Box widgets in a 4-column inner section, and the shop gallery maps to an Image Gallery or Image Carousel widget. Add **Shop & Services** to the main menu between Pump Types and Blog.

## Open questions for the client
- What's in the shop? We need equipment (lathes, cranes, balancing, test stand), lifting capacity, and shop photos.
- Are there service claims we should add, such as a repair warranty, turnaround times, field service or emergency service?
- Which manufacturers is Fitzmyer *authorized* to service? The band currently says "sell, service & repair" for the brands featured on the homepage.
