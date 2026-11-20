# DD BEATS — Custom HTML Website

A responsive, multi-page static website built with HTML, CSS and vanilla JavaScript.

## Files
- `index.html` — Home
- `music.html` — Four embedded YouTube playlists
- `deals.html` — Affiliate product grid and category filters
- `contact.html` — Contact form
- `privacy.html` — Starter privacy notice
- `disclosure.html` — Affiliate disclosure
- `assets/style.css` — All styling and responsive layout
- `assets/app.js` — Product data, social links and interactions

## 1. Preview on your computer
1. Extract the ZIP file.
2. Open the `dd-beats-website` folder.
3. Double-click `index.html` to preview in a browser.
4. Internet is required for Google Fonts, remote demo images and YouTube embeds.

## 2. Customize before publishing
Open `assets/app.js`:
- The contact and newsletter forms are configured for `anildhammabeats2002@gmail.com` (reserved for future integrations).
- In `deals`, replace the sample products with real products you have checked.
- Replace each `YOUR_AFFILIATE_LINK_HERE` with your own approved affiliate URL.
- Update product names, category, description, verified price text, label and image.
- Keep affiliate URLs accurate and use only links issued by the relevant affiliate program.

Social profile links are already configured:
- YouTube: https://www.youtube.com/@DhamDhammaBeats
- Instagram: https://www.instagram.com/boomba_ba_da/
- Facebook: https://www.facebook.com/61594689844189/

## 3. Free hosting — recommended: Netlify
Netlify supports drag-and-drop deployment of static sites. Its current Free plan has a monthly credit limit, so check current plan limits before relying on it for high traffic.
1. Create a free account at https://www.netlify.com/
2. Extract this ZIP on your computer.
3. Open https://app.netlify.com/drop while signed in.
4. Drag the extracted `dd-beats-website` folder into the drop area.
5. Netlify publishes the site and gives you a `*.netlify.app` address.
6. In the Netlify site dashboard, check Forms / form detection and trigger a new deploy if needed. Test both forms with a real submission.
7. You can later connect a custom domain, but domain registration normally costs money.

Contact and newsletter forms use Netlify Forms markup. They will not store submissions when you simply open the files locally or host them on a static host that does not process Netlify Forms. For Netlify, confirm form detection is enabled and check the Forms area after deployment.

## 4. Alternative hosting
GitHub Pages can host static HTML/CSS/JS for personal, portfolio or project websites. However, GitHub's official documentation says Pages is not intended or allowed as free hosting for websites primarily directed at facilitating commercial transactions. Since DD BEATS has affiliate marketing as its main priority, use a host whose terms permit your intended commercial/affiliate use rather than assuming GitHub Pages is suitable.

## Important launch checklist
- [ ] Replace all sample products and placeholder affiliate links.
- [ ] Verify product prices, availability, descriptions and claims.
- [ ] Apply for affiliate programs and follow each program's disclosure/link rules.
- [ ] Review the Privacy Policy and Affiliate Disclosure for your actual practices and applicable law.
- [ ] Test the contact and newsletter forms after deploying.
- [ ] Test all social links and YouTube playlists on mobile.
- [ ] Add your own logo/artwork and optimized images if desired.

## Notes
This is a static front-end website. It does not include a shopping cart, payment processing, user accounts, a database, or an admin dashboard. Product editing is intentionally simple: edit the `deals` array in `assets/app.js`. No real discounts or affiliate commissions are represented by the sample cards until you replace their data.
