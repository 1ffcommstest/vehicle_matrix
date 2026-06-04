[README(1).md](https://github.com/user-attachments/files/28590710/README.1.md)
# Luxembourg Investment Vehicle Matrix

An interactive reference table covering the full range of Luxembourg investment vehicles and structures, designed for embedding in Foleon publications and other digital formats.

Built and maintained by [Luxembourg for Finance](https://www.luxembourgforfinance.com) — the Agency for the Development of the Financial Centre.

---

## What it does

Displays all major Luxembourg investment vehicles across two families — **Asset Management Vehicles** and **Multi-Purpose Vehicles** — with the following attributes for each:

- Investible assets
- Amount of regulation
- Target investors & clients
- Cross-border passporting
- Typical industries

On **desktop**, the full comparison matrix is visible at a glance. On **mobile**, the layout switches to expandable cards with filter buttons by vehicle family or industry focus.

---

## Vehicles covered

**Asset Management**
UCITS · UCI Part II · SIF · SICAR · RAIF · SCS & SCSp · IORP

**Multi-Purpose**
SOPARFI · Securitisation Vehicle & Fund · Fiduciary Contracts · SPF · Life Insurance Contracts

---

## Deployment

This tool is designed to be hosted as a static HTML file on GitHub Pages and embedded via iframe in a Foleon Doc.

### GitHub Pages setup

1. Upload `index.html` to the root of this repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your tool will be live at `https://yourusername.github.io/vehicle-matrix/`

### Foleon embed

1. In your Foleon Doc, add an **Embed** element to a full-width page
2. Paste the GitHub Pages URL as the iframe source
3. Set iframe height to at least **720px** for desktop views
4. Republish the Foleon Doc

---

## Files

| File | Description |
|---|---|
| `index.html` | The complete tool — HTML, CSS, and JS in a single file |
| `README.md` | This file |

---

## Design notes

- Colour palette follows LFF brand conventions (`#0a2342` navy, `#1a6faf` blue, `#3eb0e0` sky)
- Background: `#DCE8F5`
- Asset Management group: blue accent · Multi-Purpose group: amber accent
- Fonts: DM Sans (body) + DM Mono (vehicle codes), loaded from Google Fonts
- No external dependencies beyond Google Fonts

---

## Related tools

- [Luxembourg Fund Vehicle Selector](https://github.com/yourusername/fund-tool) — interactive decision tree guiding users to the right vehicle for their strategy and investor base

---

## Maintainer

Luxembourg for Finance Communications Team  
[luxembourgforfinance.com](https://www.luxembourgforfinance.com)
