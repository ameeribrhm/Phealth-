# Personal Health — GitHub Pages PWA

A mobile-friendly personal wellness tracker. It is designed to be hosted free with GitHub Pages.

## Upload and publish

1. Download and unzip `personal-health-v3-github-files.zip`.
2. Create a new repository on GitHub (for example, `personal-health`).
3. Upload **all files inside this folder** to the repository root. Keep `index.html`, `style.css`, `app.js`, `manifest.json` and `sw.js` together.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub to publish the site. Open the Pages URL on your iPhone.
7. In Safari, tap **Share → Add to Home Screen** to install it.

## Included

- Overview with daily, weekly and monthly completion summaries, plus target-weight progress and weekly weigh-ins.
- Intermittent fasting tracker with 16:8, 18:6, 20:4, 24h, 36h, 48h, 72h, alternate-day example and custom fasts; editable start times, live elapsed/remaining time, completion history and an evidence-informed physiology guide.
- Monthly routine library: workouts, cardio, stretching, meditation, and skin/hair care.
- Workout exercise builder with sets, reps, load, unit and per-exercise notes.
- Run/walk cardio logs with distance, pace, duration and incline; calorie and average-heart-rate estimates.
- HIIT interval builder and a guided timer with start, pause, reset, next-exercise sound cues, and optional save-after-session.
- Guided HIIT, stretch and meditation sessions with exercise/rest intervals, a 10-second ready countdown, live timers and a 5-second finish countdown.
- Daily habits opens first, with the Daily routine log shown before Planned. Weekly planner, routine picker, custom habits, reordering, editing, deletion and previous-week carry-forward.
- Daily checklist/log, daily journal, profile settings, and a dedicated Current activity screen.
- JSON backup and restore.

## Important limitations

- **Guided timers:** the current activity timer runs while the app is active. If iOS suspends the web app in the background, the displayed timer catches up when you return; keep the app open during a session for the most reliable guidance.
- **Fasting education:** physiological stages are broad explanations, not hour-by-hour guarantees. There is no reliable universal hour at which autophagy begins. The app does not medically recommend prolonged fasts.
- **Heart rate:** average heart rate is a rough age/intensity estimate, not measured heart rate. It is clearly labelled as estimated. Use a wearable for actual readings.
- **Calories:** activity calories are approximate, based on entered duration/distance and body weight.
- **Storage:** data is kept in local browser storage on the device. Clearing browser data or changing devices can remove it. Export a JSON backup regularly.
- **Privacy:** no account or server database is used. Do not use this as a medical record or emergency tool.

## Update later

Replace the files in the GitHub repository with the newer versions and commit the changes. Your browser's local data should remain on that device, but export a backup before major updates.
