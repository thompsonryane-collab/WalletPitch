# ieSRA — Wallet Pitch

**Intelligent Energy Simulation • Reconnaissance • Analytics**

A mobile-first, single-file digital pitch card for **ieSRA** — the Navy energy AI command hub. Designed to render full-screen on a phone with zero scrolling, zero external dependencies, and instant load times.

🔗 **Live Demo:** [eSimReconAI Command Hub](https://thompsonryane-collab.github.io/iNED-v01/SimMobile_v106.html)

---

## Overview

This wallet pitch is a pocket-sized sales card that aligns ieSRA capabilities directly to the **Navy AI Strategy FY27 milestones**. Show it on your phone, let someone scan the QR, or send them the link — the entire pitch fits on one screen.

### Priority Use Cases

- Energy Resilience Modeling
- Predictive Maintenance
- Navy Energy Reporting & Briefings
- Cost & Schedule Risk Analysis
- Environmental Compliance Automation

### Key Advantages

- ✅ **Zero CDN Dependencies** — fully self-contained HTML
- ✅ **Air-Gap & Classified Ready** — runs offline, no network calls required
- ✅ **No Vendor Lock-In** — plain HTML/CSS, fully owned
- ✅ **Fields in Under 1 Day** — single file deployment

---

## Tech Notes

| Feature | Implementation |
|---|---|
| **Layout** | `100svh` viewport-locked flexbox, no scroll |
| **Scaling** | `vh`-based root font size — auto-fits any screen |
| **Fonts** | Rajdhani + Share Tech Mono (Google Fonts, falls back gracefully offline) |
| **QR Code** | Inline base64 SVG — crisp at any resolution |
| **Assets** | 100% embedded — no external images or scripts |

## Deployment

### GitHub Pages

1. Upload `index.html` to the repository root
2. **Settings → Pages → Branch: `main` → Save**
3. Live at `https://[username].github.io/[repo-name]/`

### Local / Offline

Open `index.html` in any modern browser. No build step, no server, no dependencies.

---

## Files

```
├── index.html        # The wallet pitch (GitHub Pages entry point)
└── README.md         # This file
```

---

*ieSRA — The Navy AI Strategy set the milestones. ieSRA hits every one.*
