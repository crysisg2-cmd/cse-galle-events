# CSE Galle Branch Events

A lightweight, single-page event registration site inspired by the supplied CSE Anuradhapura events page.

## Files
- `index.html` — complete website (HTML/CSS/JavaScript in one file)
- `cse-logo.png` — cleaned/cropped version of the supplied logo

## Add events
Open `index.html` and find `const events = []`.
Add events using:
{
  title: "Event title",
  type: "online", // online | physical | hybrid
  date: "Date",
  time: "Time",
  venue: "Venue",
  description: "Short description",
  registrationUrl: "https://your-registration-form"
}

## Important
Replace the WhatsApp placeholder link and privacy-consent link in `index.html` with the official URLs before publishing.

## Publish
This is a static site and can be deployed directly to Cloudflare Pages, GitHub Pages, Netlify, or any normal web host. No database is required for the front-end.
