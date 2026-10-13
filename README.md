# Southern Charm Painting Co. — GitHub Pages

Static HTML/CSS/JavaScript website for `southerncharmpaintingco.com`, centered on Mount Airy, NC, with nearby North Carolina and Virginia community pages.

## Included
- Custom SVG logo in `assets/logo.svg`, following the supplied SC monogram and colors.
- Homepage, five service pages, About, Portfolio, Contact, Privacy, 404, and service-area hub.
- Community pages under `areas/` including Mount Airy, Dobson, Pilot Mountain, Fancy Gap, Cana, Hillsville, and other nearby towns/communities.
- SEO titles, meta descriptions, canonical URLs, basic homepage structured data, sitemap, and robots.txt.
- Responsive navigation and mobile estimate CTA.

## GitHub Pages deployment
1. Create a GitHub repository, such as `southern-charm-painting`.
2. Upload the contents of this folder into the repository root. `index.html`, `CNAME`, `robots.txt`, and `sitemap.xml` must be at root.
3. In repository Settings → Pages, deploy from the `main` branch and `/ (root)`.
4. Configure DNS for `southerncharmpaintingco.com`. GitHub Pages commonly uses these apex A records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`. Confirm current GitHub instructions before changing DNS. If you want `www`, configure a CNAME to your GitHub Pages hostname.
5. After DNS propagates, set the custom domain in Settings → Pages and enable HTTPS when available.

## Required before launch
- Replace placeholder business email and phone details.
- Connect the estimate form to a real form service (Formspree, Basin, or a CRM). The current form opens an email draft and does not submit automatically.
- Replace Unsplash sample photography with authorized, ideally original project photos. Do not describe stock photos as company projects.
- Add the owner's genuine story and publish credentials only after verification.
- Confirm the operating service area, especially Virginia locations.
- Community pages are a practical named-town list within the wider regional radius, not a guarantee every address is within driving range.
- Add unique local information and actual project examples to each area page before relying on SEO. Remove or noindex pages for areas you do not serve; avoid thin doorway pages.
- Update the privacy policy for actual analytics and form vendors.
- Verify canonical URLs and sitemap after the custom domain and HTTPS work.
- Verify the site in Google Search Console and submit `https://southerncharmpaintingco.com/sitemap.xml`.

GitHub Pages serves static files only, so there is no PHP or server-side form handler in this package.
