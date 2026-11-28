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

### Session 3 — Nov. 26 — driver: Andre

- **Goal for this session:** Add an interactive demo to Explore that shows how more local sellers can give buyers more matching gear.
- **Key prompt I gave ChatGPT:** Help me add a network-effect demo to Explore on Hockey Gear Near You. Let visitors switch between one and three local hockey associations without clearing their search. Update the fictional listings and match count so searching goalie shows one match with one association and more with three. Briefly explain how more sellers help buyers find gear. Keep Save and Reserve for pickup working in both views. Use plain HTML and JavaScript with no external libraries. Show me exactly what to find and paste in github.dev and how to test it on the live site.
- **What worked:** I searched for "goalie" on the live explore page and got one match with one association and two matches with three. The search stayed in the box, and the goalie pads still showed saved and reserved when i switched back. 
- **What broke, and how I fixed it:** No issues 
- **Committed?** Yes, Add network-effect demo to explore

### Session 4 — Nov. 26 — driver: Andre

- **Goal for this session:** Replace the starter text on About and update Home to mention the demo reservation.
- **Key prompt I gave ChatGPT:** Help me update my homepage and about page on my website.
- **What worked:** The about page updated with the information on why I started this website and the homepage updated with number three explainng that you can save gear to compare options or try a demo pickup reservation.
- **What broke, and how I fixed it:** No issues
- **Committed?** Yes, Update home page and about page copy.
## Things that broke (running list)

| Date | What went wrong | What we tried | What finally fixed it |
|---|---|---|---|
| Nov. 25 | Codespaces showed a usage or budget limit. | Tried opening a Codespace from my repository. | Switched to `github.dev` to keep editing. |

## What a real version would need

Everything we wanted but faked or left out — real logins, a real database, payments, security, moderation, an app, staff, etc. For each one, say **why** it's needed and roughly **how hard or expensive** you think it would be.

| Feature we faked or skipped | Why a real company would need it | How hard / expensive? |
|---|---|---|
| Shared database for listings and reservations | Buyers and sellers need to see the same availability so two buyers can’t reserve the same goalie pads. | Medium difficulty. A managed database would have an ongoing cost, and the reservation system would need to prevent double bookings. |
| User accounts | Sellers would need to sign in so they can update the gear they have posted and see which items have been reserved. | Medium difficulty. A sign-in service could handle the accounts, but I would still need to make sure sellers can only edit their own listings. |
| Photo storage | Sellers would need to upload pictures of their gear so buyers can see the condition and decide if it is worth picking up. | Low to medium difficulty. I would need to set up photo uploads and limit how big the files can be. Storage would cost more as people add more pictures. |
| Payment processing | The marketplace would need a way to collect the small fee from the seller once a piece of equipment has actually been sold. | Medium difficulty. I would need to connect a payment service and figure out how to confirm that the sale went through. The service could also charge a fee for each payment. |
| Listing moderation | Buyers would need a way to report a listing if a seller leaves out something important, like a broken strap on a pair of goalie pads. | Medium difficulty. I could add a report button, and someone would need to check the reports and ask sellers to fix misleading listings. |

## Reflection (fill in at the end)

1. What surprised you most about building software with AI?
2. Which parts were easy, and which were hard? Why do you think that is?
3. If a competitor had the same AI tool, how long would it take them to copy your site?
