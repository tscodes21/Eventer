# afterglow ✳

A responsive event discovery and registration site for finding music, food, art, wellness and nightlife around Mumbai. Built with semantic HTML, CSS and vanilla JavaScript.

## Run locally

Open `index.html` in a browser, or serve this folder with any static file server. There are no build steps or dependencies.

## Features

- Search events by title, category, venue or description; switch between eight Indian cities.
- Filter by event category and open an event for its details.
- Register with client-side validation for name, email and phone number.
- Save selected city, registrations, newsletter signups and light/dark theme preference in browser Local Storage.
- Responsive desktop, tablet and mobile layouts, keyboard-accessible event cards and reduced-motion support.

## Project files

- `index.html` — page structure and accessible controls
- `styles.css` — responsive layout, theme tokens and interactions
- `app.js` — event data, search, filters, dialogs, validation and Local Storage

## Customize

Edit the `events` list near the top of `app.js` to change the sample events. Event photos currently use Unsplash image URLs and Google Fonts are loaded remotely, so those visual assets require an internet connection. Registrations are stored in the visitor's browser only; a real ticketing service needs a backend.

## Deploy

This is a static site and can be deployed directly from the repository root with GitHub Pages, Netlify, or Vercel. For GitHub Pages, set the source to the branch and root folder. For Netlify or Vercel, import the repository and use the root as the publish directory; no build command is required.

To submit, push the project to a GitHub repository and include both its repository URL and the deployed site URL.
