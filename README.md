# ArogyaDrill

Adaptive micro-learning drills for India's frontline health workers: ASHAs, ANMs and nursing students.

**Live app (latest, offline-capable):** https://akshaywagh1998.github.io/arogyadrill/

Original demo: https://arogyadrill.netlify.app (older build, Hindi partial)

## Problem

India has about 10 lakh ASHAs and over 2 lakh ANMs. They are the first contact for maternal and child care in villages, but refresher training is rare, long and classroom-based. Protocol slips (danger signs in pregnancy, newborn care, ORS/zinc, referral thresholds) cost lives.

## What it does

- Short timed drills (about 1 minute per question) on maternal health, child health, nutrition, communicable disease, emergencies and NCDs.
- Spaced repetition: questions answered wrongly come back sooner; mastered ones fade out.
- Bilingual: all 66 questions, options and explanations in both Hindi and English, switchable in one tap.
- Works offline: a service worker caches the app on first visit, so it opens with no network afterwards; it can be added to the home screen like an app (PWA).
- Daily streak that resets after a missed day, so the habit count is honest.
- No login, no data collected: progress stays on the phone.

## Changelog

- **2026-11-14:** Hindi completed for all 66 questions (was 12); installable offline PWA (manifest + service worker); streak now counts consecutive days only.

## Run locally

```sh
python3 -m http.server 8080
# open http://127.0.0.1:8080
```

No build step, no API keys.

## Status and limits

- Prototype. Content is for practice and revision, not a substitute for official MoHFW/NHM training modules.
- No field deployment data yet; a pilot with a Karnataka partner is planned. Kannada is the next language.
- Hindi text was written with AI help and checked against the English source; a review by a practising ANM or trainer is still pending.

## Licence

MIT. Author: Akshay Wagh (@akshaywagh1998). AI coding assistants were used in building this app.
