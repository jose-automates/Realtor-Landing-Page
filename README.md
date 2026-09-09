# Vanessa Bennett — Luxury Realtor Landing Page Template

**Version:** 3.0  
**Elementor Version:** 3.35.7  
**Theme:** Twenty Twenty-Five 1.4  

---

## What's Included

| File | Description |
|------|-------------|
| `Elementor-Kit.zip` | Full Elementor Kit (layout, global colors, fonts, settings) |
| `static/index.html` | Standalone HTML version — opens directly in any browser |
| `README.md` | This file |

---

## Requirements

- WordPress (latest recommended)
- Elementor **Free** (v3.20+)
- Elementor **Pro** (v3.20+)
- Theme: **Twenty Twenty-Five** (free, available in WordPress theme directory)
- PHP 7.4 or higher
- Permalinks set to **Post Name** (Settings → Permalinks)

---

## Option A — Elementor Version (WordPress)

### Step 1 — Prepare your WordPress site
1. Install and activate **Elementor** and **Elementor Pro**
2. Install and activate the **Twenty Twenty-Five** theme
3. Go to **Settings → Permalinks** and select **Post Name** → Save Changes

### Step 2 — Import the Kit
1. Go to **Elementor → Tools** in your WordPress admin
2. Find the **Import/Export Kit** option
3. Upload `Elementor-Kit.zip`
4. Make sure all options are checked (Site Settings, Templates, Content)
5. Click **Import** and wait for it to complete (2–4 minutes)

### Step 3 — Set your Homepage
1. Go to **Settings → Reading**
2. Set **"Your homepage displays"** to **A static page**
3. Select **Vanessa Bennett** from the dropdown
4. Click **Save Changes**

### Step 4 — Regenerate Styles
1. Go to **Elementor → Tools**
2. Click **Regenerate CSS & Sync Library**
3. Visit your homepage — it should now look exactly like the demo

### Step 5 — Customize
Open your page in the Elementor editor and replace:
- **Name & headline** — Update "Vanessa Bennett" to your name
- **Photos** — Replace all property listing images with your own
- **Videos** — Replace the background and showcase videos with your own
- **Contact form** — Connect to your preferred form service (see note below)
- **Google Maps** — Update the embedded map address to your location
- **Colors** — Edit via **Elementor → Site Settings → Global Colors**
- **Fonts** — Edit via **Elementor → Site Settings → Global Fonts**

---

## Option B — Static HTML Version

The static version requires **no WordPress, no server, and no plugins**.

### Open directly in browser
1. Extract the static ZIP folder
2. Double-click `index.html` — it opens in your browser immediately

### Deploy online (recommended)
1. Go to [netlify.com](https://netlify.com) and create a free account
2. Drag and drop the entire extracted folder onto the Netlify dashboard
3. Your site is live instantly with a free URL

### Windows one-click launcher
A `start.bat` file is included. Double-click it to launch a local server and open the site automatically — useful if you want to test form behavior locally.

---

## Contact Form

The contact form is built with **Elementor Pro Forms**. To make it functional:

- **Recommended:** Connect to [Formspree](https://formspree.io) or [Netlify Forms](https://docs.netlify.com/forms/setup/) (both free tiers available)
- In the Elementor editor, click the form → Edit → Actions After Submit → Add your form endpoint

---

## Fonts Used

| Font | Usage |
|------|-------|
| Poppins | Headings, buttons, UI |
| Open Sans | Hero titles |
| Playfair Display | Accent headings, italic style |
| Inter | Body text, descriptions |
| Libre Baskerville | Section subtitles |
| Roboto | Form fields |

All fonts are loaded from Google Fonts and require an internet connection.

---

## Replacing Images

Images are **not included** in the Elementor Kit — you will need to replace them with your own. The template uses the following image slots:

- **Hero background** — Full-width background image (`B1.webp`)
- **Stats section** — Single feature image
- **Property listings** — 6 property photos (recommended size: 800×600px)
- **About section** — Agent portrait or property photo

---

## Troubleshooting

**Colors look wrong after import**  
→ Go to Elementor → Tools → Regenerate CSS & Sync Library

**Page looks unstyled**  
→ Make sure Twenty Twenty-Five theme is active and Permalinks are set to Post Name

**Import stuck or timed out**  
→ Increase PHP limits in wp-config.php:
```php
define('WP_MEMORY_LIMIT', '512M');
set_time_limit(300);
```

**Images missing after import**  
→ Replace images manually in the Elementor editor — this is expected behavior for Kit imports

**Form not submitting**  
→ Connect the form to Formspree or Netlify Forms (see Contact Form section above)

---

## Support

If you have questions or run into issues, please leave a comment on the product listing page. Include your WordPress version, Elementor version, and a description of the issue.

---

*Thank you for your purchase!*
