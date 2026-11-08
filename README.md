# Crimson Motorsports website

Live at **https://crimsonmotorsports.com** (backup address: https://crimson-motorsports.onrender.com).

Every time a change is saved (committed) to the `main` branch here on GitHub, Render publishes
the new version automatically in about a minute.

## What's in here
| File / folder | What it is |
|---|---|
| `index.html` | The whole page |
| `config.js` | **Quick settings.** Turn the GoFundMe button on and off here |
| `assets/team/` | Team portraits (640 × 800 px, smiling) |
| `assets/img/` | Logos, race photos, car images, social share card |
| `404.html` | "Page not found" page |
| `robots.txt`, `sitemap.xml` | Help Google find the site |

## Turn on the GoFundMe button
1. Open `config.js` here on GitHub and click the pencil icon (Edit).
2. Paste the link between the quotes: `donateUrl: "https://www.gofundme.com/f/your-page",`
3. Click **Commit changes**. About a minute later a **Donate** button shows in the top bar and a
   "Want to chip in today?" box shows under the partnership levels.
4. To hide it again, set it back to `""`.

## Bigger changes
Ask Claude in the "Sponsorship CRM" project. Claude edits the files and pushes them here.
