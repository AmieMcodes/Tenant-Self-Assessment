# Tenant Self-Assessment App — Human-Centered Workflow Demo

This repository contains a **sanitized portfolio version** of a real-world self-assessment application designed to collect structured input, reduce ambiguity, and present clear, actionable results.

The focus of this project is not visual polish or framework complexity —  
it’s about **designing assessment flows that feel understandable, neutral, and respectful to everyday users**, while still supporting meaningful downstream analysis.

---

## Why this app exists

Many assessment tools fail not because the logic is wrong, but because the experience is overwhelming, confusing, or emotionally loaded.

This project demonstrates how I approach form-based tools differently:
- one question at a time
- neutral language
- clear progression
- predictable outcomes

The goal is to help users complete an assessment **without stress or second-guessing**, and help organizations receive data that is actually usable.

---

## What this demo demonstrates

This portfolio version showcases:

- A **multi-step front-end assessment flow**
- Clean separation between input, state handling, and results rendering
- Local/session storage used intentionally for state continuity
- Neutral, reusable naming suitable for different domains
- A structure that can scale beyond a single static form

The emphasis is on **clarity and reliability**, not cleverness.

---

## Technical scope (intentionally simple)

- Plain **HTML / CSS / JavaScript**
- No build step required
- Runs entirely in the browser
- Multi-page flow (`index.html` → `results.html`)
- Lightweight client-side storage for results handoff

This simplicity is deliberate — it keeps the focus on **user flow and logic**, not tooling.

---

## What’s intentionally omitted

To respect client privacy, this repository excludes:

- Original client branding, logos, or copy
- Production datasets
- Admin credentials or dashboards

The code here represents the **core assessment experience only**.

---

## Notes on extensibility (from the production version)

In the full implementation, this system also supported:

- Dashboard-style configuration for non-technical admins  
- Adding, editing, or disabling questions without touching code  
- Exporting results to CSV / Excel for review and comparison  
- Versioned assessments with historical result tracking  

Those features are omitted here, but the underlying structure reflects how I design **modular, extensible systems** that can grow without becoming fragile.

---

## How to run

1. Clone or download the repository  
2. Open `index.html` in your browser  
3. Complete the assessment to view the results screen  

No setup required.

---

## Notes for reviewers

This project is meant to highlight:
- human-centered form design
- low-friction UX for sensitive or high-cognition tasks
- clean, maintainable front-end logic
- respect for both end users and administrators

It’s a small app by design — but a very intentional one.
