# Sami Fishes & Aquariums — Online Store

Premium quality aquariums and ornamental fish — Lahore, Pakistan.
Built as a zero-monthly-cost store: static site + Google Sheets as product database + WhatsApp checkout.

## Files
- `index.html` — the store (deploy this; works on Netlify/Cloudflare Pages free tier)
- `admin.html` — password-protected admin panel (add/edit/remove products)
- `apps-script-code.txt` — Google Apps Script that connects admin.html to the products Google Sheet
- `launch-guide.html` — payments, hosting, branding & marketing playbook
- `products-template.csv` — template for the products sheet
- `photos/` — extracted product photos

## Config (top of index.html)
- `WHATSAPP_NUMBER` — order destination
- `BANK` — payment details shown in checkout
- `SHEET_CSV_URL` — published Google Sheet CSV (product catalog)
- `INSTAGRAM_EMBED_HTML` — optional Instagram feed widget

## Links
- Instagram: https://www.instagram.com/sami_fishes_aquariums/
- Facebook: https://www.facebook.com/groups/848514917098911/
