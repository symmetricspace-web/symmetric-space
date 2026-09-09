# Symmetric Space — website v1

Static first concept for a techno music label & events brand.

## Files
- `index.html` — page structure/content
- `styles.css` — visual system, responsive layout and animations
- `script.js` — mobile menu
- `assets/logo.png` — supplied Symmetric Space logo

## Before publishing
Current content:
- Event: 09 October 2026 — Sigma Club, Ibiza
- Lineup: Semreh, Joton
- Instagram: @symmetricspace
- SoundCloud: https://soundcloud.com/symmetricspace

Still to replace:
- ticket URL
- release title and artist
- additional artist names
- contact email
- `EST. 2026` if another year is preferred

## Font
The CSS asks for `"UNISON"` first, then falls back to Space Grotesk.
For an exact match to the flyer typography, place the licensed UNISON webfont files in the project and add an `@font-face` declaration in `styles.css`.

## Publish with Vercel + Namecheap
1. Upload this project to GitHub.
2. Import the GitHub repository into Vercel.
3. In Vercel, add your domain (e.g. `www.yourdomain.com`).
4. In Namecheap > Domain List > Manage > Advanced DNS, add the DNS records Vercel gives you.
5. Wait for DNS propagation; Vercel will issue HTTPS automatically.

You can also publish the static files on Namecheap hosting if you already have a hosting plan.


## Current V3 direction
The site intentionally uses **no event flyer, photography or video** yet.
The supplied Symmetric Space logo is the only image asset. Artwork, event
photos, videos, release covers and other media can be added later without
changing the overall site structure.
