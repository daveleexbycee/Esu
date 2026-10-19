# Eccentric Souls in Unity (ESU) Website

A complete, modern, mobile-responsive website for the philanthropic giving-circle community **Eccentric Souls in Unity**.

## Brand

- **Name:** Eccentric Souls in Unity  
- **Short / logo:** ESU  
- **Tagline:** “A place where good people help each other”  
- **Primary color:** Rich trustworthy green  
- **Tone:** Warm, inclusive, empowering, community-first, honest, hopeful  

## Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage — hero, values, how it works, impact, social proof, CTAs |
| `join.html` | Multi-step sign-up form (4 steps) with progress indicator |
| `about.html` | Philosophy, giving-circle model, mutual-support promise, future of philanthropy |
| `terms.html` | Terms & Conditions |
| `privacy.html` | Privacy Policy |

## Features

- Fully mobile-responsive
- Clean, modern design with generous white space and strong green brand color
- Smooth multi-step join form with validation and progress indicator
- Exact core messaging and values as specified
- Footer with full address on every page
- Placeholder sections for future growth (member directory, cause selection, success stories, gatherings)
- No build step required — pure HTML + Tailwind CDN + vanilla JS

## How to view

Simply open `index.html` in a browser, or serve the folder with any static file server:

```bash
# Example with Python
cd esu-site
python -m http.server 8000
```

Then visit `http://localhost:8000`

## Form behavior

The join form is client-side only. On successful completion it shows a thank-you message. To connect it to a real backend, replace the submit handler in `join.html` with an API call.

## Address

Eccentric Souls in Unity  
6219 Coral Lake Dr.  
Margate, FL 33063
