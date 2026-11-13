# ArogyaDrill

Adaptive micro-learning drills for India's frontline health workers: ASHAs, ANMs and nursing students.

**Live app:** https://arogyadrill.netlify.app

## Problem

India has about 10 lakh ASHAs and over 2 lakh ANMs. They are the first contact for maternal and child care in villages, but refresher training is rare, long and classroom-based. Protocol slips (danger signs in pregnancy, newborn care, ORS/zinc, referral thresholds) cost lives.

## What it does

- Short timed drills (about 1 minute per question) on maternal health, child health, nutrition, communicable disease, emergencies and NCDs.
- Spaced repetition: questions answered wrongly come back sooner; mastered ones fade out.
- Bilingual: Hindi and English, switchable in one tap.
- Offline-first, single-file web app: works on low-end Android phones on weak networks. No login, no data collected.

## Run locally

```sh
python3 -m http.server 8080
# open http://127.0.0.1:8080
```

No build step, no API keys.

## Status and limits

- Prototype. Content is for practice and revision, not a substitute for official MoHFW/NHM training modules.
- No field deployment data yet; a pilot with a Karnataka partner is planned.

## Licence

MIT. Author: Akshay Wagh (@akshaywagh1998). AI coding assistants were used in building this app.
