BUDGIT - UPDATED PROJECT

Files:
- index.html: app structure
- script.js: application logic
- sty.css: styling
- fonts/: local Nexa Pro font files

Run locally:
1. Extract the complete project folder.
2. Keep index.html, script.js, sty.css, and fonts/ together.
3. Open index.html with VS Code Live Server for best results.

Updates in this version:
- Savings goal creation is split into focused popup steps.
- Savings target dates and entry dates use Budgit's own in-app calendar (same one as the subscription renewal step), not the browser's.
- Check-in time is chosen on an in-app analog clock: tap or drag the hour, then the minute.
- Savings check-ins appear as a dimmed full-screen popup on whichever tab you are on when the reminder time is reached (while Budgit is open), with a 10-minute snooze.
- Insights includes a monthly budget overview and subscription evaluator.
- Subscription details includes an evaluator action.
- Choosing “Save for it” (or starting a timer on a “Save for this purchase” result) creates a linked savings goal. Existing assessments already marked Saving are added automatically.
- Budget label says “Money available”.

Notes:
- Exchange rates require internet access. When rates cannot be retrieved, cross-currency totals may be unavailable rather than silently treating currencies as equal.
- Reminder popups work while the app is open. Browser tabs that are fully closed cannot show in-app reminders.
- Please test the new workflows in a browser before replacing your working copy. Back up your current data first.
- Ensure your font files are used according to their licence.

V5.2 additions:
- Subscription files open in an in-app viewer (images, PDFs, text) with image thumbnails; nothing opens in a new tab.
- Real logos in logos/ for Netflix, YouTube, Disney+, McDonald's, Spotify, Apple and Prime.
- Subs tab icon is a calendar with a loop; Decide tab icon is a question mark in a circle.
- Subscriptions can be filtered by category/status and sorted.
- Decide asks for the normal price on discounts, and the product count and per-product worth on bundles.
- Decision engine scores each purchase 0-100 using need, importance, how long you've wanted it, affordability, deal quality and credit use.
- Monthly budget tracker (add purchase / add savings) and spending-trend charts on Insights.

V5.2 follow-up:
- Monthly budget uses a pencil button (top right) instead of the bottom "Adjust budget" button.
- Deleting a budget entry asks for confirmation in an in-app popup; trash icons are red.
- All dropdowns are now in-app bottom sheets instead of the device's native picker.
- Logos show in the Active Subscriptions and Upcoming Bills popups.
- Subscription details stay in phone layout on wide screens.
- Every delete/erase confirmation (budget entry, file, subscription, savings goal, erase all data) now uses the in-app popup; no browser confirm boxes remain.
