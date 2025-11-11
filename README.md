cat > README.md <<'EOF'
# Tenant Self-Assessment App (Portfolio Version)

This is a **front-end assessment flow** built to demonstrate form logic, result rendering, and clean HTML/CSS/JS structure.  
This version has been **sanitized for public display** — original client branding, logos, and identifiers were removed.

## What it shows
- Plain HTML/CSS/JS (no build step required)
- Multi-page flow (`index.html` → `results.html`)
- Local/session storage handoff between pages
- Clean, neutral naming for portfolio use

## How to run
1. Clone or download this repo.
2. Open `index.html` in your browser.
3. Complete the assessment to see the results screen.

## Notes
- Images/logos were intentionally removed for client privacy.
- Storage key renamed to \`app_v10_results\` to keep it generic.
EOF

## Dashboard & Plugin Architecture
In the production version of this project, I also built **dashboard-style plugins** that allowed non-technical users to:
- Add, edit, or deactivate questions without touching code  
- Export response data to CSV or Excel for analysis  
- Manage versioned assessments and compare results over time  

These features are **excluded here** to keep client data private, but the underlying architecture demonstrates how I design modular, reusable components that can be safely extended by future admins or developers.
