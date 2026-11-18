# My Money Manager PWA

A private, local-first salary and expense tracker configured with your ₹60,000 monthly plan.

## Included
- Expense entry and categories
- Editable monthly budget limits
- Monthly income, actual expenses, remaining/unallocated money
- Savings and SIP contribution tracker
- Emergency fund progress against ₹2,16,000
- Month-by-month history
- JSON backup/restore and CSV expense export
- PWA manifest and service worker for offline use after first load

## Deploy / install
A PWA must be served over HTTPS (or localhost) to install and use its service worker.
1. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to a static host such as GitHub Pages, Netlify, or Cloudflare Pages.
2. Open the HTTPS URL in Chrome on Android.
3. Chrome menu (⋮) -> **Install app** or **Add to Home screen**.

## Privacy and data
All records are stored in this browser's localStorage. No account or cloud sync is used. Data does not automatically move to another device or browser. Use **History & backup -> Export backup** regularly. Import the JSON backup on a new device to restore it.

## Starting budget
Income ₹60,000. Planned expense limits: Rent ₹10,000; Family ₹15,000; EMI ₹5,000; Food ₹5,000; Travel ₹1,000; Other ₹1,000. Planned allocations: Emergency fund ₹12,000/month; SIP ₹5,000/month; short-term savings ₹3,000/month; buffer ₹3,000/month.

The app records actual transactions; it does not automatically assume that a planned amount was paid. Add expenses and savings contributions as they happen.
