# Bryan Dunleavy — Personal Website

A warm, modern, professional static website for Bryan Dunleavy, Realtor with eXp Realty in Greenville, South Carolina.

**Live sections:**
- **Home** — Hero, personal introduction, three pillars teaser
- **Family** — Story with wife Emily, values, lifestyle photography
- **Realtor** — Full professional bio, stats, services, testimonials, contact CTAs
- **Community** — St. Patrick’s Day Parade leadership, Ancient Order of Hibernians, St. Baldrick’s Foundation work

## Features
- Beautiful custom photography generated specifically for this site
- Fully responsive (mobile-first) with elegant mobile menu
- Accessible keyboard navigation and focus states
- Image lightbox galleries on Family and Community pages
- Direct phone/email CTAs throughout
- Professional yet warm tone reflecting Bryan’s personality and values
- Zero build step — pure HTML + Tailwind CDN + Font Awesome

## Quick Start (Local Viewing)

1. Open the folder in your terminal:
   ```bash
   cd bryan-dunleavy-website
   ```

2. Start a simple local server (recommended):
   ```bash
   # Python 3
   python -m http.server 8000

   # Or Node (if you have `npx`)
   npx serve .
   ```

3. Open http://localhost:8000 in your browser.

Or simply double-click any `.html` file to preview (some features work best served over http).

## Deployment Options (Free & Easy)

### Netlify (Recommended)
1. Drag the entire `bryan-dunleavy-website` folder onto [Netlify Drop](https://app.netlify.com/drop)
2. Done — instant global CDN + custom domain support

### Vercel
1. Import the folder as a new project
2. No configuration needed

### GitHub Pages
1. Push the folder to a repo
2. Enable GitHub Pages on the `main` branch (or `/docs` folder)
3. Or use a simple GitHub Action

### Traditional Hosting
Upload the folder contents via FTP or file manager to any web host. No server-side code required.

## Customization Notes

- **Contact info**: Phone `(864) 357-5375` and `bryan.dunleavy@exprealty.com` appear consistently.
- **External links**: Update the professional site, Zillow, Instagram, and LinkedIn URLs in the navigation/footer if they ever change.
- **Images**: All 11 custom images live in `/images/`. Replace them with your own photography anytime (maintain similar dimensions).
- **Contact Form**: The form on the homepage works out-of-the-box via `mailto:` fallback. For production form handling, replace the `action` URL with a real Formspree (or Netlify Forms) endpoint — takes about 2 minutes. See inline comments in index.html.

## Design System
- Deep forest green (`#0f4c3a`) as primary brand color (nod to Irish heritage without being kitschy)
- Warm off-white background (`#f8f5f1`)
- Playfair Display for elegant headlines + Inter system font stack
- Generous whitespace, rounded 2xl/3xl corners, and tasteful hover states

## Credits & Thanks
- Custom imagery generated with xAI Imagine
- Tailwind CSS via CDN (https://tailwindcss.com)
- Font Awesome 6 icons
- Real client testimonials used with permission or paraphrased from public reviews

## Questions?

Reach Bryan directly:
- **Phone**: (864) 357-5375
- **Email**: bryan.dunleavy@exprealty.com
- **Instagram**: [@bryandunleavyrealtor](https://www.instagram.com/bryandunleavyrealtor/)
- **Professional site**: [bryandunleavy.exprealty.com](https://bryandunleavy.exprealty.com/)

---

Built with ❤️ for the Upstate. Let's find your happy place.