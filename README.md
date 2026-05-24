# NCGCL Operational Intranet

Internal intranet platform for **National Credit Guarantee Company Limited (NCGCL)** — central operational hub linking to the institution's policy overview pages, modeled on the editorial register of JP Morgan and Goldman Sachs corporate sites and aligned to the NCGCL Brand Guidelines (v5, 2025).

## Pages

| Page | File | Description |
|---|---|---|
| Operational Hub | `index.html` | Landing page with navigation to all sections |
| Guarantee Policy | `guarantee-policy.html` | Guarantee product framework overview |
| Investment Policy | `investment-policy.html` | Investment objectives and framework |
| Credit Risk & Capital Management | `credit-risk-capital.html` | Capital adequacy and risk framework |
| Delegation of Authority | `delegation-authority.html` | Approval limits and authority matrix |
| Impact Assessment Framework | `impact-assessment.html` | Development impact measurement |

## Brand Assets

| File | Use |
|---|---|
| `Company_Logo.png` | Original logo (black background) — kept for reference |
| `Company_Logo_transparent.png` | Light-background variant — used in page headers |
| `Company_Logo_dark_bg.png` | Dark-background variant — used in page footers |
| `DE1.png` | Stationery motif — used in hero panel and footer watermark |

## Brand System

Per NCGCL Brand Guidelines v5:

- Primary colors: Dark Cerulean `#035076`, Medium Green `#39A949`
- Secondary colors: Deep Cyan-Blue `#11688A`, Gunsmoke `#BABABA`, White
- Typography: Sharp Sans (display) / Satoshi (body) — with Source Serif Pro / Inter as web fallbacks
- Logo clear space: minimum of one "N" letter-width around the mark

## Live Site

After enabling GitHub Pages, the site is available at:
`https://<username>.github.io/ncgcl-intranet/`

## Local Preview

Open `index.html` in any modern browser. No build step required.

## Navigation

Every policy page links back to the hub via three routes:
1. The "Hub" link in the dark utility bar
2. The NCGCL logo (always returns to `index.html`)
3. The "← Hub" button in the page header
