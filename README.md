# سَمْت | SAMT
## Strategic Aviation Management & Transformation
### International Aviation Leadership Fellowship

This package contains the **SAMT Hybrid Executive Website — Version 4.0**.

It preserves the cinematic single-page executive experience while adding five detailed, interconnected pages and controlled interactive overlays.

## Website Architecture

```text
SAMT_hybrid_website_v4.0/
├── index.html                  # Cinematic executive homepage
├── programme.html              # Strategic case, executive summary, purpose and design pillars
├── journey.html                # Interactive 16-week journey and development gates
├── stations.html               # Interactive UAE, UK, France, USA and return preparation stations
├── selection.html              # Selection gates, scoring model and cohort composition
├── governance-impact.html      # Governance, impact measures, risks and approval boundary
├── assets/
│   ├── styles.css              # Shared responsive bilingual design system
│   ├── app.js                  # Language, motion, modals, drawers, tabs and interactions
│   ├── hero-desktop.jpg        # Desktop hero visual
│   ├── hero-mobile.jpg         # Mobile hero visual
│   └── SAMT_programme_brief_v1.0.pdf
└── README.md
```

## Core Features

- Arabic-first interface with full RTL support
- Full English interface and persistent language preference
- One cinematic executive homepage plus five detailed pages
- Interactive leadership flight path with phase pop-ups
- Executive decision brief side drawer
- Interactive 16-week programme timeline
- Interactive preparation station selector
- Selection gates and proposed assessment weighting
- Governance responsibility explorer
- Impact measurement tabs and risk controls
- Responsive desktop, tablet and mobile layouts
- Keyboard navigation, visible focus states and reduced-motion support
- Static architecture compatible with GitHub Pages
- No framework, package manager or build process required

## Preview Files

- `preview/home-desktop.png`
- `preview/home-mobile.png`

## Approved Identity

**سَمْت | SAMT**  
**Strategic Aviation Management & Transformation**  
**الزمالة الدولية لإعداد قادة منظومة الطيران**  
**International Aviation Leadership Fellowship**

Approved terminology:

**محطات إعداد | Preparation Stations**

## GitHub Pages Deployment

1. Create a GitHub repository.
2. Upload **all files and folders** from this package to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select the `main` branch and `/root` folder.
6. Save and wait for publication.

The expected URL format is:

```text
https://USERNAME.github.io/REPOSITORY-NAME/
```

Do not upload only `index.html`; the detailed pages depend on the shared `assets` folder.

## Content and Approval Status

This website is an executive concept demonstrator. References to host countries, institutions or programme formats are proposals and remain subject to official coordination, security review, legal review, cost validation and formal approval.

Concept approval is intentionally separated from final implementation, budget and external commitments.

## Editing

- Edit shared colours, typography and layout in `assets/styles.css`.
- Edit interactions and dynamic page content in `assets/app.js`.
- Edit page-specific text in the relevant HTML file.
- Arabic and English text use paired `data-ar` and `data-en` attributes.

## Version

**SAMT Hybrid Executive Website — Version 4.0**  
**Status:** Ready for executive concept review and GitHub Pages demonstration.
