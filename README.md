# Campus Nails — Static Site

Student-run nail studio one-page site (HTML/CSS/JS only). Works on any static host, including GitHub Pages.

## Files
- `index.html` — content + sections
- `style.css` — layout, colors, animations
- `script.js` — mobile nav toggle + smooth scroll

## Run locally
Double-click `index.html` or run a local server (recommended so relative links behave):
```sh
# from this folder
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages
1. Create a GitHub repo and push these three files (plus this README).
2. In GitHub: Settings → Pages → Source = “Deploy from a branch”. Pick your default branch and `/ (root)`.
3. Save. After a minute, your site will be at `https://<user>.github.io/<repo>/`.

## Customization checklist
- Update contact details (IG handle, phone, booking link) in `index.html`.
- Swap gallery tiles for real photos (replace text with `<img>` or background images).
- Adjust hours/pricing copy under Services and Pricing.
- Add a favicon: place `favicon.ico` in this folder and add `<link rel="icon" href="favicon.ico">` inside `<head>`.
- If using a custom domain, add a `CNAME` file with your domain and configure DNS to GitHub Pages.

## Optional niceties
- Hook a real booking link (Cal.com, Calendly, Google Forms).
- Add simple analytics (e.g., Plausible) by inserting their script near the end of `index.html`.
- Compress images for faster loads (aim <300 KB each).
