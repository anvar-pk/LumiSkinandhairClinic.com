LUMI SKIN & HAIR CLINIC — GUNJUR SEO PAGE

Contents
- index.html: existing homepage, preserved with one added navigation link: “Dermatologist in Gunjur”.
- dermatologist-in-gunjur/index.html: full new SEO landing page.
- sitemap-entry.xml: URL entry to merge into the existing sitemap (do not replace an existing sitemap wholesale).

Static HTML deployment
1. Back up the current live files/repository.
2. Upload/merge index.html into the same location as the current homepage. It retains the original design and content, with one navigation link added.
3. Upload the dermatologist-in-gunjur folder so its index.html is at /dermatologist-in-gunjur/index.html.
4. Merge the sitemap-entry.xml URL into the existing sitemap.xml and update lastmod to the real publication date if desired. Do not replace the full sitemap with the snippet.
5. Commit and deploy, then test https://lumiskinandhairclinic.com/dermatologist-in-gunjur/ and the homepage link.

Important compatibility note
These are static HTML files based on the saved Lumi index HTML. If the live GitHub repository is a Next.js app, do not upload these HTML files blindly over the app. The page should instead be implemented as an app route (for example app/dermatologist-in-gunjur/page.tsx or pages/dermatologist-in-gunjur.tsx) and the homepage navigation updated in the existing component.

The package is prepared for upload; it has not been published to GitHub or the live website.
