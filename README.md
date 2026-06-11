# OG-website

One-page landing site for **Origin Group AB** (origingroup.se).

- Single viewport, no scrolling — everything lives in the hero section
- Pure static HTML + CSS, no build step, no dependencies
- Links to Golf Coach and Beach Coach, contact via team@origingroup.se

## Preview locally

Open `index.html` directly in a browser, or serve it:

```powershell
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Any static host works (Cloud Run + nginx like the Coach landings, Firebase Hosting, etc.).
DNS for origingroup.se currently lives at Wix — when going live, change only the
web records (A/CNAME) and leave the Google Workspace MX records untouched.
