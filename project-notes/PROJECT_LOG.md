# Project log

Keep this up to date as you go — a few lines per work session is enough. It's much harder to reconstruct at the end.

**Team name:** Andre
**Startup name:** Hockey Gear Near You
**Live site link:** https://andrerovers.github.io/hockey-gear-near-you/

---

## Work sessions

Copy this block for each session.

### Session — [Nov 25th] — driver: [Andre]

- **Goal for this session:** Set up Hockey Gear Near You and eight fictional gear listings
- **Key prompt I gave ChatGPT** (paste the important ones):
  1. My startup is Hockey Gear Near You. it's a local marketplace where hockey families can buy affordable used gear and sell equipment their kids have outgrown. Help me update the homepage text in index.html and replace the sample listings in data.js with eight fictional listings across different categories, including skates, sticks, gloves, and goalie gear. Give each listing a category, a size or relevant measurement, a price in Canadian dollars, a condition, and a general pickup area. Use generic product names and keep the existing layout and student prototype footer. I'm using github.dev , so show me exactly what code to change and where to put it.
- **What worked:** I confirmed all eight appeared on the explore page.
- **What broke, and how we fixed it:** Codespaces showed a usage or budget limit, so i switched to github.dev to keep editing.
- **Committed?** Yes — commit message: Add eight fictional hockey gear listings.

### Session — Nov. 26 — driver: Andre

- **Goal for this session:** Add a demo pickup reservation to the Explore page.
- **Key prompt I gave ChatGPT:** Help me add a mock pickup reservation to the Explore page for Hockey Gear Near You. In app.js, add a Reserve for pickup button beside Save on each listing. When someone clicks it, change that listing’s button to Reserved and show “Demo reservation confirmed. No pickup has been arranged.” Keep Save working and reset the demo reservations when the page refreshes. I’m using github.dev, so show me exactly what lines to find and where to paste the code.
- **What worked:** I tested the live site. Clicking “Reserve for pickup” changed the listing to “Reserved” and showed a demo confirmation.
- **What broke, and how I fixed it:** No issues
- **Committed?** Yes, commit message: Add demo pickup reservations

## Things that broke (running list)

| Date | What went wrong | What we tried | What finally fixed it |
|---|---|---|---|
| Nov. 25 | Codespaces showed a usage or budget limit. | Tried opening a Codespace from my repository. | Switched to `github.dev` to keep editing. |

## What a real version would need

Everything we wanted but faked or left out — real logins, a real database, payments, security, moderation, an app, staff, etc. For each one, say **why** it's needed and roughly **how hard or expensive** you think it would be.

| Feature we faked or skipped | Why a real company would need it | How hard / expensive? |
|---|---|---|
| | | |

## Reflection (fill in at the end)

1. What surprised you most about building software with AI?
2. Which parts were easy, and which were hard? Why do you think that is?
3. If a competitor had the same AI tool, how long would it take them to copy your site?
