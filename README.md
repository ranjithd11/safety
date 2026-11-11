# ACG course preview

A preview of the "Emergency Preparedness & Environmental Awareness" e-learning course (SCORM 1.2 package, English, Hindi and Marathi), published with GitHub Pages.

**Address:** https://ranjithd11.github.io/safety/

- Open it in Chrome or Edge on a laptop, or on a phone held sideways, with the sound on.
- Enter any name and a test employee ID. Progress and quiz attempts are saved **only in your own browser**; nothing is sent anywhere, and there is no report.
- This is a review copy, not the production course. The production package is uploaded to the company LMS.

## How it is published
The folder `public/` holds the unzipped SCORM package. The workflow in `.github/workflows/pages.yml` publishes it to GitHub Pages on every push to `main` (Settings > Pages > Source must be "GitHub Actions").

## Updating
Build the package, copy it into `public/`, then commit and push. Viewers may need a hard refresh (Ctrl+Shift+R) because Pages caches files for about 10 minutes.
