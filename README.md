# Peak Tracker — drop-in folder

Everything to add the **Peak Tracker** (+ Meds page) to a Patron-style dashboard.

## What's inside
| File | What it is | Needed? |
|------|-----------|---------|
| `peak.html` | The Peak Tracker page | **Required** |
| `meds.html` | Meds & substances tracker (Peak links to it) | **Required** |
| `icons.js` | Animated 3D card icons (peak + meds entries) | Optional — nicer card art |
| `brand.js` | Swaps the wordmark to the user's name | Optional |
| `db.js` | Supabase cloud sync (works without it) | Optional |
| `ADD-PEAK.md` | Step-by-step add guide + the card snippet | Read me |
| `PATREON-EP-3.md` | Copy-paste prompt to build Peak from scratch | Alternative |

## Quick start (2 minutes)
1. Copy **`peak.html`** + **`meds.html`** into your dashboard repo.
2. Add the card lines from **`ADD-PEAK.md`** to your `index.html` (`APPS` + `ART`).
3. Open the dashboard → tap **Peak**. Done.

Works with or without a wearable: **Manual** mode lets you rate your morning, log
caffeine/meds/water/supplements, and see your hour-by-hour energy curve. Connect
Whoop or an Apple-Watch shortcut for real recovery data.

It's a science-based **estimate** that personalizes to you over ~30 days — not a
medical measurement.
