# Apartment Tracker

A simple, private apartment-hunting tracker. Everything runs in your browser — no accounts, no servers, no data leaves your computer.

**Try it:** open the live version (link in the repo's About section) or download `index.html` and open it in your browser.

## What it does

- Track apartments through a status pipeline: Saved → Messaged → Replied → Tour Scheduled → Toured → Applied → Accepted/Rejected/Passed
- Rate apartments 1–5 stars and sort by ranking
- Upload or auto-fetch photos
- Schedule tours and see upcoming appointments at the top of the page
- Auto-fill apartment details by pasting a listing URL (Zillow, StreetEasy, Craigslist, etc.)
- Save a "📌 Save to Tracker" bookmarklet for one-click capture on sites that block the URL fetcher
- Pros/cons, notes, search and filter

## Sharing with a partner

Both of you open the page in your own browsers, click **Auto-save to file…**, and pick the same JSON file inside a shared Dropbox / Google Drive / iCloud folder. Click **⟳ Pull latest** to refresh with their changes. (Auto-save to file works in Chrome, Edge, and Arc.)

## Privacy

All apartment data is stored in your browser's localStorage. Nothing is sent to any server. The optional URL auto-fetch makes one request through a public CORS proxy (allorigins.win) only when you click Fetch.

## License

MIT — use it, fork it, share it with friends.
