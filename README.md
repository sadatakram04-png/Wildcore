# WILDCORE PRO — Amethyst Tactical Fitness System

Installable, Arabic-first iPhone PWA. No build tools required.

## Included
- Amethyst / violet tactical interface with mobile navigation
- Training sessions for strength, speed, endurance and mobility
- Progressive exercise ladder and an 8-week load-management outline
- Workout timer, exercise completion tracking and session history
- Local Coach Intelligence: readiness notes, weekly-load observations, four-week activity projection, rule-based Q&A and a personal training-notes journal
- Hydration, meal journal, sleep and weight logs
- Optional GPS distance tracking while the app remains open (HTTPS + location permission)
- Weekly activity summary, local persistence and JSON backup/restore
- PWA manifest, violet app icons and offline service-worker cache

## Publish/update from iPhone
1. Open the existing GitHub repository.
2. Choose Add file → Upload files.
3. Upload every file in this folder to the repository root, replacing same-named files.
4. Commit to `main`; GitHub Pages redeploys automatically.
5. Refresh the same Pages URL in Safari. If the old version persists, close the installed web app and reopen it after a short wait.

## Important capability limits
- Coach Intelligence is an offline, rule-based assistant using the records on this device. It is not a connected generative AI model and does not provide medical advice.
- Performance projections are simple arithmetic extrapolations from logged activity, not guarantees of future fitness results.
- Records are stored in local browser storage on this device. Export a JSON backup before clearing Safari data or changing devices.
- GPS needs HTTPS and location permission; iOS background tracking is not guaranteed.
- Cloud accounts/sync, real conversational AI, push notifications and Apple Health/HealthKit require a separate backend/API or native iOS implementation.
- Stop exercise for pain, dizziness, chest pain or unusual breathlessness; seek appropriate medical advice when needed.
