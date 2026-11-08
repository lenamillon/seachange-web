# seachange.agency

Static website for SeaChange, deployed on Vercel.

- `index.html` – home page
- `insights/` – blog (`/insights`) and posts (`/insights/<slug>`)
- `thank-you.html` – shown after the contact form is sent
- `assets/` – styles, fonts, images and scripts

Forms (contact and newsletter) submit to HubSpot (portal 146401104).
`vercel.json` turns on clean URLs, so `thank-you.html` is served at `/thank-you`.
