# Easy Budget Tracker

A free, simple month-by-month budget planner and expense tracker. Plan your month in minutes, see where your money goes, and keep your data private.

**Live app:** [ezbudgettracker.app](https://ezbudgettracker.app)

**Current version:** 9.8

## Features

- **Monthly planning:** add income, bills, spending, savings, credit cards and loans, and see your remaining balance at a glance.
- **Repeating bills:** enter a bill once and change only the months that differ.
- **Credit card reminders:** set a due day, get a banner before it is due, and add due dates to your phone calendar (`.ics` export).
- **Spending limits:** set an overall limit and limits per category, with a warning as you get close.
- **Savings goals and planner:** a what-if savings calculator that shows what a little extra each month adds up to and how long a target will take.
- **Transactions and reports:** log spending, browse recent transactions, and view spending overviews and insights.
- **Grocery list:** plan shopping with its own spending limit. Checking off an item adds its price to your Groceries budget.
- **Collectibles tracking:** keep a separate list for collectibles spending.
- **Money owed to you:** track what others owe you.
- **Import and export:** bring in data from Excel or CSV and map it to your categories, or export to Excel or CSV.
- **Budgeting guides:** short guides, including budgeting a ₱20,000 salary, the 50/30/20 rule, an emergency fund, paying off credit card debt, and a monthly bills checklist.
- **Installable (PWA):** add it to your phone or desktop home screen. It opens offline using a cached copy.
- **Light and dark themes**, with a bottom tab bar on phones and a sidebar on tablets and desktops.

## Privacy

- Your budget is stored in **your own browser** (local storage). There is no server database and no account is required.
- Optional **Google sign-in** backs up a copy to your own Google Drive using the `drive.appdata` scope. This is a hidden app-only folder, so the app cannot see or touch any of your other Drive files.
- Nothing is sold or shared. See the [Privacy Policy](https://ezbudgettracker.app/privacy.html) and [Terms](https://ezbudgettracker.app/terms.html).

## Tech stack

- Plain HTML, CSS and JavaScript, with no framework and no build step
- Google Identity Services for sign-in and the Google Drive API (app data folder) for backup
- Service worker and web manifest for offline use and installation
- Hosted on [Netlify](https://www.netlify.com/)

## Project structure

```
index.html                  The whole app (HTML, CSS and JS)
sw.js                       Service worker (offline cache)
manifest.json               PWA manifest
icons/                      App icons and favicon
guides/                     Budgeting guide pages and stylesheet
privacy.html, terms.html    Legal pages
sitemap.xml, robots.txt     SEO files
google58aa16da169b3680.html Google Search Console verification
```

## Contact

Questions or feedback: see the contact email on the [Terms](https://ezbudgettracker.app/terms.html) page.
