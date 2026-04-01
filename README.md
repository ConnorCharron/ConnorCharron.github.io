# Atlantic Climate Control – Website Clone

A pixel-faithful static HTML/CSS replica of the Atlantic Climate Control website.

## Structure

```
atlantic-climate-control/
├── index.html              # Homepage
├── css/
│   └── style.css           # All styles
├── js/
│   └── main.js             # Navigation logic
└── pages/
    ├── heat-pumps.html
    ├── solar-panels.html
    ├── battery-storage.html
    ├── rebates.html
    ├── about.html
    └── contact.html
```

## How to Use

1. **Locally** – Open `index.html` in any browser. No build step required.
2. **GitHub Pages** – Push to a GitHub repo, then go to:  
   Settings → Pages → Source: `main` branch → `/root` → Save.  
   Your site will be live at `https://yourusername.github.io/atlantic-climate-control/`

## Customization

- **Colors/fonts** – All CSS variables are in the `:root` block at the top of `css/style.css`
- **Content** – Edit text directly in each HTML file
- **Images** – Replace the SVG placeholder illustrations with real photos by swapping in `<img>` tags
- **Contact form** – Currently shows a success message on submit. Connect to a backend (Formspree, EmailJS, etc.) by updating the `handleSubmit` function in `contact.html`

## Adding Real Photos

Replace any `<div style="background:linear-gradient(...)">` placeholder with:
```html
<img src="../images/your-photo.jpg" alt="Description" />
```

## Tech Stack

- Pure HTML5 + CSS3 (no framework)
- Google Fonts (DM Sans)
- Font Awesome 6.5 icons (CDN)
- Vanilla JS for mobile nav toggle

## Contact Info in the Site

- Phone: +1 (902) 707-3114
- Email: sales@atlanticclimatecontrol.ca
- Location: Dartmouth, Nova Scotia
