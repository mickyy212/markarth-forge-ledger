# The Markarth Forge — Ledger

The forge's ore stockpile ledger, buy/sell orders, profit, trends, employee roster and forge debt, as a single web page.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole site (page, styles and code) |
| `supabase.js` | Database library the site uses to save and load data |
| `prospector-how-to.mp4` | How-to video for prospectors |
| `woodcutter-how-to.mp4` | How-to video for wood cutters |
| `hunter-how-to.mp4` | How-to video for hunters |
| `sell-how-to.mp4` | Sell orders video (apprentice / expert blacksmiths) |
| `buy-how-to.mp4` | Buy orders video (apprentice / expert blacksmiths) |

All data (stockpile, orders, employees, debts) lives in Supabase, not in these files, so updating the files never changes the data.

## Hosting

It's a static site with no build step. On Netlify: **Add new site → Import an existing project → GitHub →** pick this repository, leave the build command empty and the publish directory as `/`, then **Deploy**.

## Updating

Replace `index.html` (and any changed videos) with **Add file → Upload files → Commit changes**. Netlify redeploys automatically.
