# MindCare – Mental Health Risk Prediction Agent

Educational wellness screening web app. **Not a medical diagnosis.** In India call 112 in an emergency.

## Run
Double-click `index.html` (no install, no server needed). Data is stored in the browser (localStorage).

## Files
- `index.html` – page shell
- `style.css` – lavender/mint theme, dark mode, responsive layout
- `app.js` – questions (`Q`), scoring (`predict`, `risk`), recommendations (`recs`), history storage (`L`, `S`, `submit`), high-risk e-mail alert (`saveAlert`, `fireAlert`, `mailto`), daily check-in, mood calendar, MindCare chat

## Features
Assessment (3 steps + review), risk result with factor bar chart, daily checklist, history with bar chart, daily check-in and mood calendar, trend detection, high-risk e-mail alert (opens an e-mail draft), MindCare AI chat with crisis message, dark mode, print to PDF.

## Honest limits
- The risk score is a transparent weighted rule, not a trained model. The Model Lab page stays empty until real results from training on the Kaggle dataset exist.
- No backend, login or admin dashboard. The alert opens a draft in the mail app; it does not send e-mail by itself.
