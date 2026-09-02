# Bryan Dunleavy — Personal Hub

Canonical static hub for **[bryandunleavy.github.io](https://bryandunleavy.github.io)** with custom domain **[bryandunleavy.com](https://bryandunleavy.com)** (`CNAME` committed in-repo). Pure HTML + Tailwind CDN + Font Awesome — no build step.

This repo is the source of truth for the personal hub (family, realtor story, community, buy/sell lead forms). Bryan’s eXp listings site remains at [bryandunleavy.exprealty.com](https://bryandunleavy.exprealty.com/).

## Pages

| Page | File | Notes |
|------|------|--------|
| Home | `index.html` | Hero, pillars, contact form |
| Family | `family.html` | Story with Emily, gallery |
| Realtor | `realtor.html` | Bio, services, testimonials, listings CTAs |
| Community | `community.html` | Parade, AOH, St. Baldrick’s |
| Buy | `buy.html` | Buyer intake form (`lead_type=Buyer`) |
| Sell | `sell.html` | Valuation request (`lead_type=Seller`) |

Also present: `.nojekyll`, `CNAME` → `bryandunleavy.com`, `images/`.

## GitHub Pages setup

1. Repo: `bryandunleavy.github.io` (user site) or equivalent with Pages enabled on `main` / root.
2. Settings → Pages → Source: Deploy from branch `main` / `/ (root)`.
3. Custom domain: `bryandunleavy.com` (file `CNAME` already set). Point DNS (A/AAAA or CNAME per GitHub docs) and enable HTTPS once DNS verifies.
4. `.nojekyll` skips Jekyll processing so paths and assets stay as committed.

Local preview:

```bash
cd bryandunleavy.github.io
python -m http.server 8000
# open http://localhost:8000
```

## Forms (Formspree)

Buy, Sell, and the Home contact form post to Formspree placeholders:

- Buy / Sell: `https://formspree.io/f/YOUR_FORM_ID`
- Home: `https://formspree.io/f/your-form-id`

**Before going live:** create a Formspree form, replace the placeholder ID(s) in the HTML `action` attributes. Until replaced, client-side handlers open a **mailto** draft to `bryan.dunleavy@exprealty.com` so leads are not lost.

Hidden fields on funnel pages:

- Buy: `lead_type=Buyer`
- Sell: `lead_type=Seller`

## Images — use real photos before traffic

`images/` still has placeholder visuals. **Swap in real photography before any public traffic or ads.** Keep similar aspect ratios where possible. Source photos for cropping live under `images/real-photos/` when ready.

## SEO

**No SEO work yet** — no sitemap, no structured data beyond basic meta descriptions, no Search Console setup in this pass. Add later when content and photos are final.

## Design

- Primary: `#0f4c3a`
- Background: `#f8f5f1`
- Type: Playfair Display (headlines) + Inter
- External listing links on Home, Realtor, Buy, and Sell → https://bryandunleavy.exprealty.com/

## Contact

- Phone: (864) 357-5375
- Email: bryan.dunleavy@exprealty.com
- Instagram: [@bryandunleavyrealtor](https://www.instagram.com/bryandunleavyrealtor/)
- Professional site: [bryandunleavy.exprealty.com](https://bryandunleavy.exprealty.com/)

---

Built for the Upstate. Let’s find your happy place.
