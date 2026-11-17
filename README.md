# ThirdOne IT Services

Bilingual (EN / ES) static landing page for ThirdOne, ready for Cloudflare Pages.

## Deploy on Cloudflare Pages

1. Open Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
2. Authorize GitHub and select `gderosa89/thirdone-website`.
3. Production branch: `main`. Framework: **None**. Build command: **leave blank**. Build output directory: **/** (repository root).
4. Deploy and verify the temporary `*.pages.dev` URL.
5. In Pages → **Custom domains**, add `thirdone.com.ar` and `www.thirdone.com.ar`, allowing Cloudflare to configure the web-specific DNS records.

## Corporate email

Microsoft 365 Exchange Online is independent from the web hosting. Do not modify or delete the email MX, SPF, DKIM, verification TXT or DMARC records while configuring Pages. The contact link points to `contact@thirdone.com.ar`; create this mailbox or alias in Microsoft 365 before announcing the site.

## Notes

- The SVG icon is a provisional interpretation of the selected ThirdOne logo, not a finalized vector asset.
- The website is static: it requires no build process, database or API keys.
- Navigation and language toggle work client-side. Contact opens the user's email application (mailto), not a server-side form.
- No claims of certified vendor partnerships, guaranteed 24/7 coverage or customer endorsements are made.
