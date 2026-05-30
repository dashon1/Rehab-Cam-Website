# RehabCam — Remote Physical Therapy Monitoring Service

## Product Overview

RehabCam is a telehealth platform that connects patients recovering from injury or surgery with their physical therapists through AI-assisted video monitoring. Patients complete exercises at home while the platform tracks form, range of motion, and progress — giving therapists real clinical data between appointments.

## What's Included in This Repo

| File/Folder | Purpose |
|---|---|
| `index.html` | Full landing page (self-contained, no dependencies) |
| `docs/services.md` | Detailed service descriptions and how it works |
| `docs/pricing-guide.md` | Pricing tiers, what's included, billing FAQ |

## Target Market

- Post-surgical rehab patients (knee, hip, shoulder, spine)
- Chronic pain management patients doing ongoing PT
- Physical therapy clinics wanting to extend care between visits
- Sports medicine programs and athletic trainers

## Pricing

| Tier | Price | Best For |
|---|---|---|
| Basic | $49/month | Individual patients |
| Pro | $99/month | Patients + therapist portal access |
| Clinic | $199/month | PT clinics (up to 25 patients) |

## Tech Stack

- Landing page: Pure HTML/CSS (zero dependencies, deployable anywhere)
- Production app: React + WebRTC + TensorFlow.js pose estimation
- Backend: Node.js / Express
- Video: WebRTC peer-to-peer with cloud recording fallback

## Quick Deploy

```bash
# Serve locally
npx serve .

# Deploy to Netlify
netlify deploy --dir . --prod

# Deploy to Vercel
vercel --prod
```

## License

Proprietary — All rights reserved. Contact for licensing inquiries.
