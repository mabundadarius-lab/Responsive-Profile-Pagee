# Responsive Profile Page

A responsive profile page with glassmorphic cards, built with plain HTML, CSS and JavaScript. No build step or dependencies.

## Features

- Profile card with an initials avatar, role, location, email, bio and skill tags
- Stats summary (projects, followers, following) and a recent activity feed
- Editable profile: the "Edit profile" form updates the card live, with a bio character counter
- Changes are saved in the browser (localStorage), so they survive a refresh
- Glassmorphism styling: translucent cards, backdrop blur and soft gradient glows
- Responsive layout: a sticky sidebar on desktop, stacked sections on tablet and mobile
- Accessible: labelled inputs, visible focus rings, `aria-live` save message, reduced-motion support

## Customise

- Replace the default values in the `defaults` object near the bottom of `index.html`.
- Edit the stats and activity items directly in the HTML.
- Change the colours in the `:root` variables at the top of the stylesheet.

## Run locally

Open `index.html` in any browser.

## Deploy

- **GitHub Pages:** Settings > Pages > deploy from the `main` branch, root folder.
- **Vercel / Netlify:** import the repository; no build settings needed.
