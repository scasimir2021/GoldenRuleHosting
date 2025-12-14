# Golden Rule Hosting

**Full-service Airbnb Management & HOA/COA Compliance Consulting in Metro Atlanta**

## Overview
Golden Rule Hosting provides comprehensive short-term rental management and compliance consulting services in the Metro Atlanta area. This repository contains the project website and documentation following the Blueprint Framework v7.2.

## Live Site
Visit the live site at: `https://scasimir2021.github.io/GoldenRuleHosting/`

## Project Structure

```
GoldenRuleHosting/
├── index.html                          # Main website (GitHub Pages)
├── golden-rule-hosting.html            # Original HTML file
├── docs/                               # Framework documentation
│   ├── AI_EXECUTION_PROMPT.md         # Builder AI role
│   ├── VALIDATION_PROMPT.md           # Validator AI role
│   ├── REFINEMENT_PROMPT.md           # Refiner AI role
│   └── BLUEPRINT_FRAMEWORK_v7_2_COMPLETE.md
├── src/                                # Source files (future use)
├── assets/                             # Static assets (future use)
└── README.md                           # This file
```

## Framework

This project follows the **Blueprint Framework v7.2**, which includes:
- **Builder AI** — Executes blueprint deterministically
- **Validator AI** — Enforces contracts and blocks invalid releases
- **Refiner AI** — Proposes improvements via PLAN only

### Framework Features
- Deterministic builds
- Contract enforcement
- Safe evolution through governance
- Multi-agent orchestration ready

## GitHub Pages Setup

The site is hosted using GitHub Pages. To deploy:

1. Push changes to the `main` branch
2. GitHub Pages automatically serves `index.html` from the root
3. Access the site at the GitHub Pages URL

### Enable GitHub Pages
Go to repository Settings → Pages → Source: Deploy from a branch → Branch: main → Root → Save

## Development

### Local Preview
To preview locally, simply open `index.html` in a browser:
```bash
$BROWSER index.html
```

Or use a simple HTTP server:
```bash
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Important Notes

- Forms and the portal demo store data in `localStorage` (browser-only, no backend)
- Replace demo contact details, vendor links, and portfolio links before going live
- The HTML file is self-contained with embedded CSS and JavaScript

## Services Offered

- Full-service Airbnb management
- HOA/COA compliance consulting
- Property optimization
- Guest communication
- Revenue management
- Maintenance coordination

## Contact

For inquiries about Golden Rule Hosting services, please visit the website.

## License

© 2025 Golden Rule Hosting. All rights reserved.
