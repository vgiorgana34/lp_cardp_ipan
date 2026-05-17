# lp_cardp_ipan

Landing page for **Dr. Luis Enrique Estrada** — cardiólogo intervencionista en Puebla.
Served at `cardiologopuebla.ipancorazon.com` via Cloudflare Pages.

## Stack

- Pure static HTML + inline CSS + vanilla JS — no framework, no build step
- Images: AVIF via Sirv CDN (`aigenci.sirv.com/IPAN/`)
- Hosted on Cloudflare Pages (auto-deploy on push to `main`)

## Theme

Cálido Orgánico — Lora (display) + Source Sans 3 (body), navy `#234b6e` + soft sky `#6bb5d4` + cream `#fffcf8`.

## Deploy

`git push` to `main` → Cloudflare Pages auto-builds and publishes.

## CTAs

- **Hash links** (`#cta-2`): nav + footer "Agendar consulta" → scroll to contact section
- **WhatsApp**: hero + contact section + floating button → `wa.me/+525580313331` with prefilled message
- **Phone**: hero + contact section → `tel:5580313331`
