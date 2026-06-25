# MATHEC — Missing Data Report

Interactive web tool for detecting missing data in the MATHEC registry.  
Upload any Excel or CSV file → instant report, filterable by pathology and severity.

**Live app:** *(paste your Vercel/Netlify URL here after deployment)*

---

## What it does

- Detects missing values: empty cells, `NA`, `ND`, `NF`, `99`, `999`, `-`, `.`, `/`, `NR`, `manquant`
- View missing data **by patient** (who needs follow-up) or **by variable** (which column is systematically empty)
- Filter by pathology (SSc, MS, CD, OTHER MAI)
- Filter by severity: critical (>50%), warning (20–50%), complete (<20%)
- Export results as CSV
- Data never leaves your computer — everything runs in the browser

---

## For the team

1. Open the link above in any browser (Chrome, Firefox, Edge)
2. Drag and drop your registry Excel or CSV file
3. The report generates instantly
4. Use **Export CSV** to save the missing data list

No installation. No login. No data uploaded anywhere.

---

## Deploy your own copy

### Vercel (recommended)
1. Fork this repository on GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import your fork
3. Click Deploy — done. You get a permanent URL.

### Netlify
1. Go to [netlify.com](https://netlify.com) → Add new site → Import from Git
2. Connect your GitHub repo → Deploy
3. Done. You get a permanent URL.

---

## Maintenance

To update the app, edit `index.html` and push to GitHub.  
Vercel/Netlify will automatically redeploy within ~30 seconds.

---

*MATHEC · Hôpital Saint-Louis · AP-HP*
