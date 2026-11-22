# ইজি ভাড়া (EzBhara)

A bilingual (Bangla/English) rental-management prototype for phone and laptop screens.

## Try the prototype

Open `index.html` in a modern browser. It includes a sample monthly-bill and cash-payment workflow for fictitious unit numbers. No tenant identity information is included.

To publish it as a static demo with GitHub Pages:

1. Open this repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. After GitHub Pages finishes publishing, open the URL shown on that settings page.

## Important prototype limitations

This is a browser-only prototype. It stores entries in the current browser's `localStorage`; it does not sync between devices or users. It has no login, server, access controls, cloud backup, tenant dashboard, email notifications, service-request workflow, or secure document/photo storage. Do not enter real tenant names, contact details, photos, NID/passport numbers, agreements, or payment records. Anyone using the same browser profile can access its saved prototype entries. Clearing browser data may erase them.

The prototype demonstrates only monthly charges, cash payments, basic due calculation, and a printable receipt. It is not ready for managing real tenants or collecting real payments. A production version needs secure backend storage, owner and tenant authentication/permissions, backups, privacy safeguards, and testing before use.
