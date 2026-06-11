# Family Meal Planner 🍽️

A free, open-source meal planner and grocery list builder. Pick the week's dinners, get a grocery list organized by store section, and walk it with Walmart shopping mode. Built by [Hustle at Home Mom](https://www.youtube.com/@HustleatHomeMom) for her own family — now yours to use and remix.

**Try it live:** https://meal-planner-rouge-mu.vercel.app

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/ashnicholes-droid/meal-planner)

## Features

- **Weekly planner** — build a meal library, add dinners to your week, and the grocery list assembles itself with quantities combined across recipes.
- **Grocery list by store section** — Produce, Meat & Seafood, Dairy & Eggs, Pantry, and more, so you can shop in one pass.
- **Pantry staples** — salt, oil, and spices are skipped by default; check anything you're running low on to add it back.
- **Recipe import, four ways:**
  - **From URL** — paste a link from most major recipe sites
  - **From PDF** — drop in a saved recipe PDF; it finds the ingredient list (read entirely in your browser, nothing is uploaded)
  - **Paste text** — paste any ingredient list
  - **Via Claude** — copy a prompt into an AI chat and paste the JSON back
- **Walmart shopping mode** — opens a pre-filled Walmart search for each item, one reusable tab, with check-off progress. (Walmart doesn't allow apps to fill carts directly, so this is the honest next-best thing.)
- **Backup / Restore** — export your meal library as JSON and import it anywhere.
- **12 starter recipes included**, scaled for a family of six.

## Run your own

It's a single HTML file with no build step and no server:

- **Easiest:** download `index.html`, double-click it, done. Works offline (fonts and PDF import need internet).
- **Host it:** click the Deploy button above to put your own copy on Vercel for free, or drop the file on any static host.

## Your data stays yours

Everything you add is stored in your own browser (localStorage). There's no account, no database, and no analytics. Use the **Backup** button regularly — clearing browser data clears your meals.

## License

[MIT](LICENSE) — use it, change it, share it.
