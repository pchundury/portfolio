# Personal site (GitHub Pages + custom domain)

This is a fully static site (plain HTML/CSS) designed to be:
- keyboard accessible
- screen-reader friendly
- typography-first (black/white; no color reliance)
- easy to deploy on GitHub Pages

## Deploy on GitHub Pages
1. Create a GitHub repo (any name is fine, e.g., `pramod-site`)
2. Upload these files to the repo root
3. GitHub → Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / root
4. Your site will be live at a GitHub Pages URL

## Custom domain
1. In GitHub → Settings → Pages, set your Custom Domain (e.g., `yourdomain.com`)
2. Add DNS records at your domain registrar:

### Apex + www (recommended)
A records for `@`:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

CNAME record for `www`:
- `www` → `yourusername.github.io`

3. Add a `CNAME` file in the repo root that contains your domain:
   - Example contents: `yourdomain.com`

## TODO
- Replace placeholder email and profile links
- Replace `assets/cv.pdf` with your real CV
- Replace publication links with DOI/PDF links
