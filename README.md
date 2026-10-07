# Fairco website: homepage directions

Four design directions for the new Fairco homepage, as static HTML for internal review. These are design drafts, not the production site. The live site will be built in WordPress / Beaver Builder.

## Pages

| File | Direction |
| --- | --- |
| `index.html` | Review hub with links to all four and a map of the photos in use |
| `a.html` | A · Field Standard |
| `b.html` | B · Heritage Patch |
| `c.html` | C · Brochure Black & Gold |
| `d.html` | D · No. 48 |

Every page is responsive. Narrow the browser window or open it on a phone to see the mobile layout.

## Viewing

Open `index.html` in a browser, or turn on GitHub Pages for this repository (Settings → Pages → Deploy from a branch → `main`, root folder) and share the Pages link.

All pages carry a `noindex` tag and `robots.txt` blocks crawlers, but this repository is public, so anyone with the link can see it.

## Swapping photos

Every photo lives in `images/`. To swap one, replace the file and keep the same file name. All four pages pick up the change. Photos are cropped to fit their frame (`object-fit: cover`), so a replacement only needs the same orientation and at least the size listed.

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

- Client logos
- Client testimonial
- Crew portrait
- Hero video (the pages show a still with a pause control where the video will go)
