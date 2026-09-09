# Hi, I'm Jaswant 👋

Digital Marketing Associate across two sibling companies in Lucknow, India — **LDE** (Royal Enfield · Bajaj 3-wheelers) and **Swift Trucks LLP** (Tata Commercial Vehicles) — spanning 22 locations. I'm the sole digital marketing function across both, reporting directly to the owner, which means I design and build most of the systems the business runs on — not just the campaigns.

Self-taught. I ship working tools fast, in whatever stack gets the job done, and I'd rather have something live than "perfect." (Started with a workplan mapping out how all of this would get built — long since superseded by the systems themselves.)

## What I've built

**[LeadForge](https://kzleadforge.up.railway.app/)** *(live — login required)* — a custom Flask/PostgreSQL CRM built from scratch, now on its 40th-plus iteration, used across both companies. Canonical lead IDs per brand, Meta and WhatsApp Business API integration, automated Google Sheets reconciliation, role-based assignment, and a peer sync between a local instance and a Render deployment. **826+ leads under active, trackable management; ~600 previously unattended Meta leads recovered; response time cut to under 30 minutes.**

**Google Business Profile infrastructure** — took the combined GBP footprint from 2 to **17 verified, fully-optimised locations**, and built the tooling to run it at that scale:
- **Review Tracker** — Apps Script + SerpApi tool that counts monthly GBP reviews and benchmarks competitor ratings, plus a Map SEO Gap Report that diffs listing quality against competitors.
- **Search Console Tracker** — Apps Script tool pulling weekly Search Console performance (clicks, impressions, CTR, position) across the brand websites and social platform properties.

**WhatsApp campaign infrastructure** — a browser-based console that sorts monthly export workbooks (insurance, service, DMS, lost-customer) into ready-to-send win-back, service, and insurance broadcast lists, plus a Gupshup webhook logger writing straight to Google Sheets. **50,000+ segmented contacts under management**, handling up to 50k entries in a single pass. *(Internal tool — not publicly deployed.)*

**Digital asset operations** — a Google Apps Script intake and lifecycle logger for marketing assets across 22 locations, with automatic categorisation and daily reconciliation. **198+ assets tracked end-to-end.**

**Video content scripting** — a script library for in-house video shoots (brand promotion reels and ads) across all three brands, kept consistent and reusable across shoot days. *(Internal tool — not publicly deployed.)*

**Dealership websites** — five production sites, each with EMI calculators, comparison tools, structured data, and ongoing technical SEO/AEO — no backend, shipped to Cloudflare Pages and Netlify:
[LDE (combined)](https://kzlde.pages.dev/) · [Royal Enfield](https://kzldere.pages.dev/) · [Bajaj](https://ldebajaj.pages.dev/) · [Swift Trucks](https://kzswiftrucks.pages.dev/)

## Tools I've open-sourced

| Project | What it is |
|---|---|
| [KZ Downloader](https://github.com/jass666/KZ-Downloader) — [live](https://kzdownloader.pages.dev/) | Browser GUI that generates yt-dlp commands for downloading from any social profile/channel |
| [The Auction Manual](https://github.com/jass666/Google-ads) — [live](https://adguide.pages.dev/) | A single-page, scrollspy'd reference covering Google Ads + Meta Ads end to end |
| [Current Affairs Deck](https://github.com/jass666/kzcurrent) — [live](https://kzcurrent.pages.dev/) | Single-file revision tool for competitive exam current affairs (UPSC, SSC, Railways, Banking, Defence, Teaching) |
| [Revision Notes Hub](https://github.com/jass666/Revision_notes) — [live](https://kznotes.pages.dev/) | Static, browser-based revision hub for exam prep, topic pages driven off a JSON registry |
| [shellref](https://github.com/jass666/shellref) — [live](https://shellref.pages.dev/) | Fast browser cheat sheet for CMD/PowerShell/WSL/Unix commands, with a command generator |
| [Meeting Code Extractor](https://github.com/jass666/meeting-code-extractor) | Pulls Meeting ID/Passcode out of MS Teams invites — runs entirely client-side |
| [win-cache-cleaner](https://github.com/jass666/cache-cleaner) | Portable PowerShell script to clear browser caches and Windows junk files |
| Cash Ledger — [live](https://kzledger.pages.dev/) | Personal expense ledger: imports PDF/CSV/Excel bank statements, auto-categorises transactions, syncs via Google Drive |

Everything above is deliberately no-backend, no-build-step: plain HTML/CSS/JS shipped straight to Cloudflare Pages. I like tools that a non-technical person can just open and use.

## Stack

`Python` · `Flask` · `PostgreSQL` / `SQLite` · `Google Apps Script` · `JavaScript` (vanilla) · `HTML/CSS` · `Cloudflare Pages/Workers` · `Git`

## Right now

Expanding Answer Engine Optimization (AEO) across LDE's GBP footprint, and building out the Instagram/Meta analytics side of LeadForge.

---
📫 [jaswantkanojia04@gmail.com](mailto:jaswantkanojia04@gmail.com) · [LinkedIn](https://www.linkedin.com/in/jaswant-kanojia-a978642b3/) · Open to Marketing Operations, MarTech, or CRM Operations roles — remote included.
