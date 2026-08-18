# Siddarth Mally — Portfolio

Personal portfolio site for **Siddarth Mally**, Cybersecurity Analyst specialising in Governance, Risk & Compliance (GRC) and Third-Party Risk Management (TPRM).

### 🌐 [siddarthmally.com](https://siddarthmally.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Siddarth_Mally-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddarth-mally-451565242/)
[![GitHub](https://img.shields.io/badge/GitHub-siddarthmally38--star-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/siddarthmally38-star)
[![Email](https://img.shields.io/badge/Email-siddarthmally38@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:siddarthmally38@gmail.com)

---

## About

Cybersecurity GRC and Third-Party Risk Management professional with **4+ years** of experience conducting vendor risk assessments, security due diligence, inherent risk analysis, and remediation tracking across **financial services** and **healthcare** environments.

| | |
|---|---|
| **Current role** | Cybersecurity Analyst — PNC (Nov 2025 – Present) |
| **Previously** | Cybersecurity GRC / Third-Party Risk Analyst — Bausch + Lomb (Aug 2022 – Oct 2025) |
| **Education** | MS Cybersecurity, Saint Peter's University · BS Information Science, NJIT |
| **Location** | USA |

**Frameworks:** NIST CSF · NIST SP 800-53 · ISO 27001 · ISO 27017 · HITRUST · SOC 1 / SOC 2 Type II · PCI DSS · HIPAA · GDPR · CCPA/CPRA

**GRC tooling:** ServiceNow · One Trust · Zen GRC · SharePoint · Confluence

---

## Featured Projects

| Project | Focus | Stack |
|---|---|---|
| [driftguard-llm](https://github.com/siddarthmally38-star/driftguard-llm) | LLM drift monitoring | Python, Docker |
| [sentinel-triage](https://github.com/siddarthmally38-star/sentinel-triage) | Alert triage automation | Python, Docker |
| [siem-dashboard](https://github.com/siddarthmally38-star/siem-dashboard) | SIEM visualisation | TypeScript, Python |
| [threathound](https://github.com/siddarthmally38-star/threathound) | Threat hunting | Python |
| [intrusion-detection-prevention-system](https://github.com/siddarthmally38-star/intrusion-detection-prevention-system) | IDS/IPS | Python |
| [network-intrusion-detection-using-machine-learning](https://github.com/siddarthmally38-star/network-intrusion-detection-using-machine-learning) | Network IDS with ML | Jupyter |
| [online-payments-fraud-detection-with-machine-learning](https://github.com/siddarthmally38-star/online-payments-fraud-detection-with-machine-learning) | Payment fraud ML | Jupyter, Python |
| [realtime-fraud-detection](https://github.com/siddarthmally38-star/realtime-fraud-detection) | Streaming fraud detection | Python |
| [email-phishing-detection](https://github.com/siddarthmally38-star/email-phishing-detection) | Phishing classification | Python |
| [log-analysis-anomaly-detection](https://github.com/siddarthmally38-star/log-analysis-anomaly-detection) | Log anomaly detection | Python |

---

## Running Locally

No build step and no dependencies — the site is vanilla HTML, CSS, and JavaScript.

```bash
python -m http.server 4173
```

Then open <http://localhost:4173>. A local server is required (rather than opening `index.html` directly) because content is loaded from JSON via `fetch`.

## Editing Content

All content lives in `data/` as JSON — no HTML editing needed for routine updates.

| File | Controls |
|---|---|
| `data/profile.json` | Name, title, bio, contact details |
| `data/hero.json` | Landing headline, summary, avatar, social links |
| `data/about.json` | About paragraphs and headline statistics |
| `data/experience.json` | Roles, dates, locations, responsibilities, company logos |
| `data/education.json` | Degrees, institutions, campuses, certifications |
| `data/skills.json` | Skill categories and entries |
| `data/projects.json` | Project cards, cover art, repository links |
| `data/contact.json` | Contact section and form fields |
| `data/site-config.json` | Meta tags, branding, site-wide settings |

See [CUSTOMIZATION.md](CUSTOMIZATION.md) for detailed field documentation.

## Structure

```
├── index.html              # Page shell — sections filled in at runtime
├── CNAME                   # Custom domain (siddarthmally.com)
├── assets/
│   ├── css/styles.css      # All styling; palette set via CSS variables
│   ├── js/main.js          # Fetches JSON and renders every section
│   └── img/
│       ├── profile.jpg     # Hero avatar
│       ├── logos/          # Company & institution logo fallbacks
│       └── projects/       # Project cover art
└── data/                   # All site content as JSON
```

### Images

- **Company logos** — bundled SVG badges render first, then upgrade to the official logo once it loads and clears a minimum resolution. Nothing breaks offline or when a remote logo stalls.
- **Project covers** — bundled SVGs themed per project, layered over the original Font Awesome icon so a failed image falls back rather than leaving a gap.

## Deployment

Hosted on GitHub Pages from `main`, served at [siddarthmally.com](https://siddarthmally.com) via the `CNAME` file with DNS pointed at GitHub's servers. Pushing to `main` triggers a rebuild automatically.

## Colour Palette

| Token | Value |
|---|---|
| Primary (teal) | `#154D57` |
| Secondary (beige) | `#B7A08B` |
| Accent | `#D4B896` |
| Background (cream) | `#FEFAF7` |

Defined as CSS variables at the top of `assets/css/styles.css`.

---

## Contact

- **Email** — [siddarthmally38@gmail.com](mailto:siddarthmally38@gmail.com)
- **Phone** — +1 (201) 772-4845
- **LinkedIn** — [siddarth-mally](https://www.linkedin.com/in/siddarth-mally-451565242/)
- **GitHub** — [siddarthmally38-star](https://github.com/siddarthmally38-star)
- **Portfolio** — [siddarthmally.com](https://siddarthmally.com)

## License

Released under the [MIT License](LICENSE).
