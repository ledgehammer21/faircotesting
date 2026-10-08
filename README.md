# Fairco website: design directions

Four design directions for the new Fairco homepage, with directions B and C built out to seven inner pages each, as static HTML for internal review. These are design drafts, not the production site. The live site will be built in WordPress / Beaver Builder.

## Pages

| File | Direction |
| --- | --- |
| `index.html` | Review hub with links to every page and a map of the photos in use |
| `a.html` | A · Field Standard |
| `b.html` | B · Heritage Patch |
| `c.html` | C · Brochure Black & Gold |
| `d.html` | D · No. 48 |

### Inner pages (directions B and C)

Each file exists twice, with a `b-` or `c-` prefix. The navigation in `b.html`, `c.html` and every inner page is live.

| File | Page |
| --- | --- |
| `b-development.html`, `c-development.html` | Landscape Development |
| `b-management.html`, `c-management.html` | Landscape Management, with sections for Landscape Maintenance, Water Management, Plant Health Care, Enhancements and Arbor Resources |
| `b-arbor-resources.html`, `c-arbor-resources.html` | Arbor Resources |
| `b-projects.html`, `c-projects.html` | Projects |
| `b-about.html`, `c-about.html` | About |
| `b-careers.html`, `c-careers.html` | Careers |
| `b-contact.html`, `c-contact.html` | Contact |

The forms on Careers and Contact are design mockups and do not send anything.

Every page is responsive. Narrow the browser window or open it on a phone to see the mobile layout.

## Viewing

Open `index.html` in a browser, or turn on GitHub Pages for this repository (Settings → Pages → Deploy from a branch → `main`, root folder) and share the Pages link.

All pages carry a `noindex` tag and `robots.txt` blocks crawlers, but this repository is public, so anyone with the link can see it.

## Swapping photos

Every photo lives in `images/`. To swap one, replace the file and keep the same file name. Every page that uses it picks up the change. Photos are cropped to fit their frame (`object-fit: cover`), so a replacement only needs the same orientation and at least the size listed.

| File | Size | Used for | Directions |
| --- | --- | --- | --- |
| `hero-boxed-trees.jpg` | 2000 × 1125 | Hero | A, B, C, D |
| `dev-excavators.jpg` | 1400 × 1050 | Landscape Development (also Careers in D) | A, B, C, D |
| `mgmt-pocket-park.jpg` | 1400 × 1050 | Landscape Management | A, B, C, D |
| `arbor-truck-wide.jpg` | 1400 × 933 | Arbor Resources | A, C, D |
| `arbor-truck-tall.jpg` | 1000 × 1250 | Arbor Resources | B |
| `crew-ironwood.jpg` | 1000 × 1250 (portrait) | Careers (hero tile in D) | A, B, C, D |
| `imp-install.jpg` | 1000 × 750 | Install column | A |
| `imp-manage.jpg` | 1000 × 750 | Manage column | A |
| `imp-protect.jpg` | 1000 × 750 | Protect column | A |
| `work-verrado.jpg` | 1400 × 1050 | Selected work | A, B, C, D |
| `work-morrison.jpg` | 1148 × 861 | Selected work | A, B, C, D |
| `work-estrella.jpg` | 1400 × 1050 | Selected work | A, B, C, D |
| `work-talkingstick.jpg` | 1400 × 1050 | Selected work | A, B, C, D |

Six photos are preview-resolution copies taken from the Verrado shoot (November 2022) in the shared Drive. They are sharp enough for review. For the production site, export from the full-size originals:

| File | Original in Drive |
| --- | --- |
| `mgmt-pocket-park.jpg` | `IMG_4400.jpg` (folder: Verrado4) |
| `imp-manage.jpg` | `IMG_4549.jpg` (folder: More Verrado) |
| `imp-protect.jpg` | `IMG_4559.jpg` (folder: Verrado5), right-hand crop |
| `dev-excavators.jpg` | `IMG_4661.jpg` (folder: Verrado) |
| `imp-install.jpg` | `IMG_4594.jpg` (folder: More Verrado) |
| `crew-ironwood.jpg` | `IMG_4597.jpg` (folder: More Verrado) |

If a replacement shows something different, update the `alt` text on that image in each page so the description still matches.

Logos and icons (`logo-landscape-group.png`, `logo-landscape-group-reversed.png`, `icon-c.png`) are in the same folder. `thumbs/` holds the preview images used on the hub page.

## Placeholders still in the pages

Placeholders show in square brackets on the page.

- Client logos
- Client testimonial
- Crew portrait
- Hero video (the pages show a still with a pause control where the video will go)
- Leadership headshots, and any leadership beyond the three named on About
- Photos for the ten projects on the Projects page that have none yet
- Open roles on Careers
- Resume upload on the Careers form
- Contact email address (domain to be confirmed)
