# Lavasa Connect — multi-page website

## Files
- `index.html` — landing page
- `status.html` — utility status
- `outages.html` — outage notice board and causes
- `payments.html` — UPI app shortcuts and net-banking links
- `help.html` — contact routes, complaint form, saved reports and FAQ
- `assets/style.css` — responsive design system
- `assets/app.js` — shared navigation and SVG icon renderer
- `assets/*.svg` — vector payment-app icon assets

## Open locally
Extract the ZIP, then open `index.html` in a modern browser. Keep the `assets` folder next to the HTML files. For the best experience, serve the folder through a static local server or host it on HTTPS.

## Features
- Responsive layout for phones, tablets and laptops
- Separate pages and active navigation
- Custom SVG line icons; no emoji interface icons
- UPI deep-link handoff for Google Pay, PhonePe, Paytm and generic UPI
- Bank/provider links open in new tabs
- Complaint reports saved in browser local storage and exportable as JSON
- Accessible labels, keyboard-friendly native forms and reduced-motion support

## Important production limitations
This is a front-end prototype, not an official utility service.
- Live outage status needs an official provider feed or authenticated admin dashboard.
- Restore times and causes must be verified and entered by an authorised person.
- Local Lavasa electricity/water helpline numbers must be confirmed before adding them.
- Complaint reports currently remain on the same browser/device. A secure backend is needed for shared reports and delivery to the utility team.
- UPI handoff depends on device/app support. Users must confirm recipient and amount in the payment app.
- Confirm the correct electricity and water billers and their payment portals before public launch.
