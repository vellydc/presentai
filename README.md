# VocaLift

AI-powered presentation skills coach. Single-page app — type or record your presentation, get instant structured feedback (structure, clarity, opening/closing, improvement suggestions) powered by Claude.

## Usage

1. Open the deployed site (or `index.html` locally).
2. Enter your own Anthropic API key (stored in session storage only — never sent anywhere except Anthropic's API).
3. Type or record (🎙) your presentation script.
4. Click **✨ Analyze** to get feedback.

## Tech

Single static HTML file — vanilla JS, no build step, no backend. Calls the Anthropic Messages API directly from the browser.

## Deploy

This is a static site — deploy as-is to Vercel, Netlify, GitHub Pages, etc.
