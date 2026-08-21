# PaidFast 💸

**Free overdue-invoice reminder generator for freelancers and small businesses.**
Live at: https://wnordbergg.github.io/paidfast/

## What it does
Pick your situation (days overdue, amount, tone) and get a ready-to-send reminder email:
- 🙂 Friendly nudge — for honest oversights
- 😐 Firm reminder — clear deadline, asks for a payment date
- 😠 Final notice — formal demand with consequences

English & Swedish. Late-fee/interest line optional. Everything is generated **locally in your browser** — nothing you type is uploaded anywhere.

## Why
Chasing late payments is universally hated admin work, and existing tools (Chaser, Upflow, Kolleno…) are priced and designed for accountants and mid-market finance teams — not the freelancer with three overdue invoices. This tool is the free first step; an automated reminder service is being built on top of it (join the waitlist in the app).

## Tech
Single static HTML file per page. No build step, no dependencies, no tracking cookies. Anonymous aggregate counters via [Abacus](https://abacus.jasoncameron.dev); waitlist emails go to a private ntfy inbox. Hosted free on GitHub Pages.

## Pages
| Page | Purpose |
|---|---|
| `/` | The generator (EN/SV, `#en`/`#sv` deep links) |
| `/templates.html` | Copy-paste reminder templates + cadence guide |
| `/final-notice.html` | Final-notice how-to + what's legal (EU/SE/US) |
| `/sv/` | Swedish landing page |

## License
MIT — take the templates, they're yours.
