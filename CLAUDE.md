# NeuronCraft.ai - Public Website

## Project Overview
Static marketing site for NeuronCraft.ai, hosted on GitHub Pages. The site positions NeuronCraft as a security engineering and Azure cloud consultancy targeting CTOs and IT Directors at small-to-mid-sized companies.

## Tech Stack
- Static HTML/CSS/JS (no build tools, no framework)
- Hosted on GitHub Pages
- Font: Inter (Google Fonts)
- No dependencies

## Key Files
- `index.html` — Single-page site (services, about, contact)
- `style.css` — All styles, CSS custom properties for theming
- `assets/` — SVG backgrounds (neural-network.svg, brain-neurons.svg), brand icon (icon.svg + PNGs)
- `favicon.ico` — Multi-size favicon (16/32/48/64)
- `sitemap.xml` — For Google Search Console indexing
- `robots.txt` — Crawler permissions, points to sitemap

## Brand & Design
- Dark mode theme: `--bg: #0a0e1a`, `--accent: #38bdf8` (security blue)
- Neuron/neural network visual motif
- Professional, high-tech, trustworthy aesthetic
- Icon: stylized neuron node with "N" lettermark

## Voice & Tone
- Use **"we/our/us"** — never "I/my/me". The site is team-oriented, even though it's currently founded by one person with 15+ years of experience.
- Target audience: CTOs and IT Directors at growing companies
- Tone: confident, hands-on, results-driven — not salesy

## Content Rules
- Do not add stats/credential numbers without explicit user approval — claims must be verified and accurate
- Any new copy must be reviewed for first-person ("I/my/me") before committing

## Site Sections
- **Hero** — headline + "Request a Cloud Assessment" CTA
- **Services** — 2x2 grid, each card has description + benefit bullet points, "Let's Assess Your Environment" CTA at bottom
- **About** — founding story, expertise, track record
- **Contact** — email CTA (hello@neuroncraft.ai)

## Verified Certifications
- CISSP (Certified Information Systems Security Professional)
- AZ-500 (Azure Security Engineer)
- SC-100 (Microsoft Cybersecurity Architect)

## SEO
- Open Graph and Twitter card meta tags in `index.html`
- Canonical URL: `https://neuroncraft.ai/`
- OG image: `assets/icon-512.png`
- `sitemap.xml` and `robots.txt` at root
- Update `sitemap.xml` lastmod date when content changes

## Services (4 offerings)
1. Azure FinOps & Security Audit (cost savings, MFA/Entra ID gaps)
2. Virtual CISO / vCISO (SOC 2, HIPAA, PCI compliance)
3. Hardened Azure Environment (Bicep/Terraform, CIS landing zones)
4. Zero-Trust Migration Specialist (replace VPNs with Azure Private Link)
