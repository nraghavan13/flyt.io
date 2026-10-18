# flyt.io roadmap

Static site on GitHub Pages. Audience: investors (funds, family offices, angels). Focus: healthtech first, emerging tech opportunistically.

Design: https://claude.ai/artifact/4VmLJsFymMQbGsP884nvET

## Phase 1 — Informational (current)

- Single static homepage: hero, focus (healthtech + emerging tech), services, approach, contact with a short founder line, disclosures
- Contact is a "Contact us" button linking to `mailto:flyt.io26@gmail.com`; the address itself is not shown (no domain mailbox yet)
- Location: San Francisco Bay Area
- Founder line: Niyati Raghavan, Investor (genomics background; healthtech investing and strategy at growth-stage funds)
- LinkedIn: https://www.linkedin.com/in/niyati-raghavan-840a9666/
- Built: index.html + styles.css (static, no build step)
- Still to add: regulatory disclosure text (footer currently has a generic "not an offer" disclaimer only)

## Phase 2 — Start a conversation and more interactive content

- "Start a conversation" flow replacing the plain mailto CTA
- Full About page: bio, portrait, prior roles and affiliations
- Insights / notes section (articles, sector notes)
- More interactive information on focus areas and services

## Nice to have: more complete email support (later phases)

- [ ] Set up `info@flyt.io` forwarding to `flyt.io26@gmail.com` (e.g. ImprovMX or Cloudflare Email Routing), then switch the site's links to `info@flyt.io`
- [ ] Later: full custom-domain mailbox (Google Workspace, Fastmail or similar), with SPF, DKIM and DMARC set up
- [ ] Contact form through a static-friendly form service (Formspree, Basin, Netlify Forms or similar), so no backend is needed
- [ ] Structured investor intake: firm, check size, sector, deal stage, timeline
- [ ] Spam protection on the form (honeypot field or privacy-friendly CAPTCHA)
- [ ] Automatic acknowledgement email to the sender, with expected response time
- [ ] Routing or labels by inquiry type (diligence, deal sourcing, sector mapping, portfolio support, emerging tech)
- [ ] Scheduling link (Cal.com or Calendly) in the CTA and in the auto-reply
- [ ] Newsletter / insights signup with double opt-in, tied to the Phase 2 insights section
- [ ] Compliance: retain and archive client communications as required, and add a privacy notice for data collected through forms
