# AI Data Analytics Workshop · Public Site Prototype

Open `index.html` for a local preview. For public hosting, publish `index.html` **and** the `data/` folder without changing the relative directory structure.

## Publish via GitHub Pages

1. Create a new public GitHub repository (subject to your organisation's approval).
2. Upload `index.html` and the entire `data` folder to the repository root.
3. Go to Settings > Pages > Build and deployment > Deploy from a branch > main / (root), and save.
4. Wait for GitHub Pages to provide the public HTTPS link. Test the Download Dataset and Copy Prompt actions on that URL.

This is a static learning website: no logins, server, analytics, APIs or Gemini integration. Prompts are copied into Gemini by the learner. Progress/checklists stay in the learner's browser only (localStorage). Gemini output is not automatically verified by the website.

## Before going public

- Secure approval to publicly post any KDN association/branding, and ensure that training material is cleared for public distribution.
- The dataset is published aggregate data from https://data.gov.my/data-catalogue/arrivals_soe modified with deliberately injected training anomalies. Do not interpret the training CSV as official statistics.
- Do not publish trainer-only injection manifests, answer keys, internal policies, private personal data or operational records.
- Verify source attribution, applicable dataset terms, and your organisation's web publishing/security requirements.
- Test Gemini upload limits, CSV file processing, actual downloads and Canvas capabilities using a workshop participant account before delivery.
- Public GitHub repos expose all committed files. Never include secrets or confidential files.
