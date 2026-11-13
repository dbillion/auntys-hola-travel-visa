# Aunty's Hola Travel & Visa

A React landing page for the London-based travel and visa assistance business.

## Stack
- React + Vite
- GSAP + ScrollTrigger for scroll and entrance animation
- Remotion Player for the looping cinematic hero composition
- GitHub Pages via GitHub Actions

## Local development
```sh
pnpm install
pnpm dev
```

## Production build
```sh
GITHUB_PAGES=true pnpm build
```

## Configure WhatsApp
Open `src/site/App.jsx` and set `WHATSAPP_NUMBER` to the business number in international format, digits only (for example, UK country code + number, without + or spaces). Until configured, WhatsApp links use the WhatsApp share/chat picker.

## Enquiry form
The static form validates the enquiry in the browser and opens WhatsApp with the enquiry details. It does not store personal information or collect passport documents. Connect a secure backend/CRM before adding private document uploads, payments, or customer accounts.

## Content checks before launch
- Add the real WhatsApp number and business email.
- Confirm the exact visa assistance scope, countries, operating hours and legal business details.
- Replace any stock imagery with licensed brand photography when available.
- Do not promise visa approval; eligibility and decisions belong to the relevant authorities.
