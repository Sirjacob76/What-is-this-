# What is this? — the "Huh" app

Point your phone at a household mystery, ask a question, and get a plain-English
diagnosis: what it is, why it's like that, how much it matters, what to do next,
and a safety flag for anything involving gas, wiring, mold, or water.

**Live app:** once GitHub Pages is enabled, it's served at the repo's Pages URL
(`index.html` is the app).

## How it works
- Single self-contained HTML file — no build step, no server, no dependencies.
- Runs entirely in your browser. Bring your own API key; it's stored only in your
  browser (localStorage) and never leaves your device except to the AI provider
  you pick.
- **Google Gemini** (free tier, no card) is the default provider; **Claude** is an
  optional toggle.

## Features
- Camera capture or photo upload (auto-downscaled before sending)
- Voice input (works on HTTPS / GitHub Pages)
- "See a sample answer" — try the full flow with no key
- Save the answer as a shareable image; native Share on mobile
- In-session history of past mysteries

## Get a free key
Google AI Studio: https://aistudio.google.com/apikey (~30 seconds, no credit card)
