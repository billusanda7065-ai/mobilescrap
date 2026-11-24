SCRAPMOB WEBSITE — FREE STATIC STARTER

Files:
- index.html: responsive website, price checker, seller form, demo admin area
- config.js: set your WhatsApp number here

IMPORTANT LIMITATIONS:
1. This is a front-end prototype. Rates and requests are stored in the visitor's browser only.
2. The admin table will NOT receive requests from other people's phones. A real shared database/backend and secure admin login are required before public business use.
3. WhatsApp opens a pre-filled message after the seller taps Submit. The seller must press Send in WhatsApp.
4. Upload field is currently a photo-link field; it does not upload files to a server.
5. Rates are blank until you enter sample rates in the Admin area. Do not publish made-up prices.
6. Do not collect sensitive identity documents or IMEI data in this prototype.

SETUP:
1. Open config.js in a text editor.
2. Replace 91XXXXXXXXXX with your WhatsApp number including India country code, digits only.
3. Upload index.html and config.js to a static host such as Netlify Drop or Cloudflare Pages.
4. Test on your own phone before sharing.

FREE HOSTING:
- Netlify: https://app.netlify.com/drop
- Cloudflare Pages: https://pages.cloudflare.com/

For a real public launch, add a free-tier backend (for example Supabase/Firebase) with authentication, database rules, image storage and protected admin access. Free tiers have limits and may change. A browser-only admin panel is not secure.
