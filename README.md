# AutoRepFlow: Automation & AI Agency Website

A responsive, single-page marketing website for **AutoRepFlow**, an automation, AI and CRM services agency that helps small and mid-sized businesses remove manual work and scale.

**Live site:** https://autorepflow.vercel.app

---

## Overview

AutoRepFlow presents the agency's services, tech stack, case studies and contact options in one fast static page. There is no framework and no build step: the whole site is a single `index.html` plus image assets, deployed on Vercel.

## Sections

| Section | What it shows |
|---|---|
| **Hero** | Headline, "Book a Call" and "Case Studies" buttons, and key stats (200+ businesses, 98% satisfaction, +$350k revenue generated) |
| **Overview video** | A 60-second walkthrough of how the agency turns manual operations into automated systems (`video.mp4`) |
| **Tech stack** | Logos grouped by category: Automation & Workflow, CRM & Sales, Marketing Automation, AI Voice & Communication, Analytics & Reporting, and AI / LLM & RAG |
| **Services** | Five offerings: Automation & AI Workflows, GoHighLevel CRM Setup, Dedicated Experts, AI Voice Agents, and 1-1 Consultation |
| **Global reach** | Scrolling country flags for the markets clients come from |
| **Case studies** | Four real projects: CosmeticRx, White City Logistics, DHCS and Empower Psychotherapy |
| **Why AutoRepFlow** | The audit-first, built-to-last, measure-everything approach, plus office locations (USA, Pakistan, Remote) |
| **Process** | Three steps: Discovery & Audit, Build & Deploy, Optimize & Scale |
| **Industries** | Real estate, e-commerce, healthcare, logistics, SaaS, financial services and more |
| **Testimonials** | Client reviews in a carousel |
| **Contact** | Contact form, direct team emails and response-time promise |
| **Footer** | Navigation, newsletter signup, office address and legal links |

## Tech Stack

- **HTML** (100% of the codebase), with styling and behavior kept in `index.html`
- **Static assets:** PNG/JPG logos and flags, and an MP4 overview video
- **Hosting:** Vercel

## Project Structure

```
autorepflow/
├── index.html          # The entire website
├── Logo.png            # Brand logo
├── video.mp4           # 60-second overview video
├── *.png / *.jpg       # Tech stack logos (Make, n8n, Zapier, HubSpot,
│                       #   GoHighLevel, Vapi, ElevenLabs, OpenAI, Claude,
│                       #   LangChain, Pinecone, Power BI, Tableau, ...)
└── usa.png, uk.png,    # Country flags used in the "Global reach" section
    pak.jpg, ...
```

## Run Locally

No install needed.

**Option 1:** open `index.html` directly in your browser.

**Option 2:** serve it locally:

```bash
# clone the repo
git clone https://github.com/inayatrahimdev/autorepflow.git
cd autorepflow

# any static server works
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy

The site is deployed on Vercel as a static project.

1. Push the repo to GitHub.
2. Import it in [Vercel](https://vercel.com/new).
3. Leave the framework preset as **Other**. No build command or output directory is needed.
4. Deploy. Every push to the main branch redeploys automatically.

## Customize

- **Text and sections:** edit `index.html` directly.
- **Logos and flags:** drop the new image into the repo root and update its `<img>` path in `index.html`.
- **Case studies and testimonials:** copy an existing card block and replace the content.
- **Contact details:** search `index.html` for the email addresses and office address and update them.
- **Contact form:** connect the form to your preferred backend or form service (for example Formspree, Make.com or n8n) so submissions reach your inbox.

## Author

**Inayat Rahim**
AI Engineer · Islamabad, Pakistan
GitHub: [@inayatrahimdev](https://github.com/inayatrahimdev)

## License

All rights reserved unless a license file is added. Brand names, logos and client case-study content belong to their respective owners.
