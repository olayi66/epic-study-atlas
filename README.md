# Epic Study Atlas

Interactive study app built from the [UI Health Care Epic Resources A–Z index](https://epicsupport.sites.uiowa.edu/epic-resources).

- Big picture: patient journey across Epic applications; Chronicles → Clarity → Caboodle data flow
- Applications: deep dives (workflow, master files, Clarity tables, exam tips)
- Full A–Z index of every Iowa resource, grouped by area
- Master file and Clarity table cheat sheets with a join diagram
- SmartTools comparison, flashcards, and a randomized quiz

Single static `index.html` — no build step. Deployed on Netlify.

## Mobile app

The site is an installable Progressive Web App (PWA):

- **Android (Chrome):** open https://epic-study-atlas.netlify.app and tap **Install app** in the header, or menu ⋮ → *Install app*.
- **iPhone/iPad (Safari):** open the site, tap **Share** → **Add to Home Screen**.
- Launches full-screen with its own icon, has a bottom tab bar (Home, A–Z, Lessons, Cards, Quiz), and works offline after the first visit (service worker in `sw.js`).
- Home-screen shortcuts: Flashcards, Quiz, A–Z index (`?tab=flash`, `?tab=quiz`, `?tab=index`).
