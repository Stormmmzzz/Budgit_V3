Budgit — minimalist subscription and savings tracker

Files
- index.html: app structure
- script.js: app logic and local data
- sty.css: styling and responsive layout
- fonts/: bundled Nexa Pro and Nexa Text Pro variable font files

Run
1. Extract the complete ZIP and keep the fonts folder beside the three app files.
2. Open index.html directly, or use VS Code Live Server.
3. Data is stored locally in this browser. Back up your browser data before clearing site storage.

Fixes in this update
- Dashboard upcoming-payment and recent-transaction cards now use the selected subscription logo/image.
- Subscription artwork is constrained to its icon container and uses object-fit: contain so very large/tall images do not overflow.
- Dark-mode active/upcoming stat labels have explicit contrast and remain visible.
- Currency changes trigger exchange-rate refresh for every subscription currency. Converted totals and list amounts use cached Frankfurter rates; if a rate is unavailable, the list shows the original currency rather than pretending a 1:1 conversion. Internet access is required for live exchange rates.
- Savings check-ins support daily, weekly, and monthly intervals for both target goals and recurring habits. At the chosen time, while the app is open on the Savings tab, the user can answer YES/NO and enter the actual amount saved. Saved/spent amounts can also be logged at any time.
- Nexa Pro and Nexa Text Pro fonts are bundled and loaded locally.
- Settings credit: Created by Stephan Ngenda.

Reminder note
Browser timers only run while the app tab is open. The savings check-in will not pop up when the browser is fully closed.

Font licence note
The supplied font archive identifies the fonts as Demo / Trial. Review its licensing terms and obtain a suitable licence before commercial distribution.
