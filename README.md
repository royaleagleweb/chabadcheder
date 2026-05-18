# Cheder Menachem of Inverrary — Website

Static website for **Cheder Menachem of Inverrary**, a Chabad-based Pre-1A program serving the Inverrary community.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `about.html` | About |
| `program.html` | Program |
| `staff.html` | Our Staff |
| `enrollment.html` | Enrollment |
| `faq.html` | FAQ |
| `contact.html` | Contact |

## Deployment (Cloudflare Pages)

This is a plain static site — no build step required.

**Cloudflare Pages settings:**
- Framework preset: `None`
- Build command: *(leave blank)*
- Output directory: `/` (root)

## Adding Photos

Each page has `<image-slot>` placeholders. To add real photos:
1. Find the `<image-slot id="...">` element in the relevant HTML file
2. Replace it with `<img src="path/to/photo.jpg" alt="Description" style="width:100%;height:100%;object-fit:cover">`

## Contact

- Email: Info@Chedermenacheminverrary.com
- Phone: 917-615-6960
