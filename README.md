# Vibe — Marketing Website

Static marketing site for the Vibe app. Deployable to GitHub Pages in 2 minutes.

## Files
- `index.html` — Main landing page
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `.nojekyll` — Disables Jekyll so GitHub Pages serves raw HTML

## Deploy to GitHub Pages

### Option A: New standalone repo (recommended for Stripe)
1. Create a new GitHub repo called `vibe-app` or `getvibe`
2. Copy the contents of this `website/` folder into the root of that repo
3. Push to GitHub
4. Go to **Settings → Pages → Source: Deploy from branch → branch: main / root**
5. Your site will be live at `https://yourusername.github.io/vibe-app`

### Option B: Custom domain (best for Stripe)
After step 4 above, go to **Settings → Pages → Custom domain** and enter your domain (e.g. `getvibe.app`). Add a CNAME record in your DNS pointing to `yourusername.github.io`.

## Update email addresses
Replace `hello@getvibe.app` and `privacy@getvibe.app` throughout with your real contact email before going live.

## Stripe verification checklist
- [ ] Site is publicly accessible (not 404)
- [ ] Business description is clear (the For Businesses section covers this)
- [ ] Privacy Policy is linked and accessible
- [ ] Terms of Service is linked and accessible  
- [ ] Contact email is real and working
- [ ] Domain matches what you register with Stripe
