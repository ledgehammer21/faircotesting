# Fairco website: design directions

Four design directions for the new Fairco homepage, with directions B and C built out as full sites, as static HTML for internal review. These are design drafts, not the production site. The live site will be built in WordPress / Beaver Builder.

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
| `b-management.html`, `c-management.html` | Landscape Management overview, linking to each service |
| `b-landscape-maintenance.html`, `c-landscape-maintenance.html` | Landscape Maintenance (under Management) |
| `b-water-management.html`, `c-water-management.html` | Water Management (under Management) |
| `b-plant-health-care.html`, `c-plant-health-care.html` | Plant Health Care (under Management) |
| `b-enhancements.html`, `c-enhancements.html` | Enhancements (under Management) |
| `b-arbor-resources.html`, `c-arbor-resources.html` | Arbor Resources (top-level menu item, also listed with the Management services) |
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

### Inner-page photos (directions B and C)

No photo appears twice within a direction: each inner page uses its own images, separate from the homepage. Most come from the Verrado shoot (November 2022) at preview resolution (1600 px wide); export production versions from the originals.

| File | Used on | Original |
| --- | --- | --- |
| `dev-hero.jpg` | Landscape Development hero | `IMG_4428.jpg` |
| `dev-partner.jpg` | Development, partnering section | `IMG_4686.jpg` (Verrado shoot) |
| `dev-salvage.jpg` | Development, native salvage | `Specimen 72 inch boxed Ironwood.jpg` |
| `dev-build.jpg` | Development, what we build | `IMG_0270.JPG` (At Work, September 2026) |
| `dev-handoff.jpg` | Development, after the build | `IMG_0296.JPG` (At Work, September 2026) |
| `mgmt-band.jpg` | Landscape Management photo band | `IMG_4339.jpg` (Verrado shoot) |
| `maint-hero.jpg`, `maint-list.jpg` | Landscape Maintenance | `IMG_4381.jpg`, `IMG_4536.jpg` |
| `water-hero.jpg`, `water-list.jpg` | Water Management | `IMG_4368.jpg`, `IMG_4579.jpg` |
| `phc-hero.jpg`, `phc-list.jpg` | Plant Health Care | `IMG_4545.jpg`, `IMG_4562.jpg` |
| `enh-hero.jpg`, `enh-list.jpg` | Enhancements | `IMG_4523.jpg`, `IMG_4304.jpg` |
| `arbor-hero.jpg`, `arbor-standards.jpg`, `arbor-species.jpg` | Arbor Resources | `IMG_4335.jpg`, `IMG_4342.jpg` (left crop), `IMG_4577.jpg` |
| `proj-hero.jpg` | Projects hero | `IMG_4772.jpg` |
| `proj-verrado.jpg`, `proj-morrison.jpg`, `proj-estrella.jpg`, `proj-tsr.jpg`, `proj-lakes.jpg` | Projects cards | `DJI_0106.JPG`, `Lakeview Trails.jpg`, `Estrella Newland Community.jpg`, `TSR.jpg`, `Morrison Ranch - Lake - Complete.jpg` |
| `about-hero.jpg` | About hero | `DJI_0033.JPG` |
| `careers-hero.jpg`, `careers-crew.jpg` | Careers | `IMG_4707.jpg`, `IMG_4591.jpg` (Verrado shoot) |
| `contact-hero.jpg` | Contact hero | `DJI_0070.JPG` |

Arbor Resources uses three supplied stock photos: `arbor-lush-hero.jpg`, `arbor-lush-street.jpg` and `arbor-lush-groves.jpg` (the Highland Groves at Morrison Ranch entry). Confirm the stock license before launch; these are 736 to 1024 px wide, so source larger files for production. `arbor-hero.jpg`, `arbor-standards.jpg` and `arbor-species.jpg` are no longer used.

`reporting-tools.png` (water budget and run-time calculator mockup) sits on the Water Management page.

### Hero video (directions B and C)

`hero-video.mp4` (H.264) and `hero-video.webm` (VP9 fallback) are the 35-second reel from the current fairco.ca homepage (`fairco-intro.mp4`), re-encoded at 1280 px wide with no audio for review. `hero-video-poster.jpg` is its first frame. The video autoplays muted on a loop, the button in the corner pauses and plays it, and it starts paused for visitors who have reduced motion turned on. For production, re-export from the original at 1920 px.

### Headshots and client logos

- `head-*.jpg`: leadership headshots, square crops at 600 × 600, used on About, Landscape Management and Arbor Resources.
- `logo-*.png`: the 20 client logos from the current fairco.ca homepage, captured at the size that site serves them. Request original vector or high-resolution files from each client, or from whoever built fairco.ca, before launch.

The `imp-*` photos (direction A's homepage) also appear on B and C inner pages: `imp-manage.jpg` and `imp-protect.jpg` on Landscape Management, `imp-install.jpg` on About.

If a replacement shows something different, update the `alt` text on that image in each page so the description still matches.

Logos and icons (`logo-landscape-group.png`, `logo-landscape-group-reversed.png`, `icon-c.png`) are in the same folder. `thumbs/` holds the preview images used on the hub page.

## Placeholders still in the pages

Placeholders show in square brackets on the page.

- Crew portrait
- Photos for the ten projects on the Projects page that have none yet
- Open roles on Careers
- Resume upload on the Careers form
