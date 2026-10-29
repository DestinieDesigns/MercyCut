# MercyCut Web v2 — Movement Clips

Simple web app, no prompt, no captions needed.

1. Upload a video.
2. Pick the person to follow (Person 1, 2, 3, or 4).
3. Press "Find Best Movement Clips" — it finds the ~2-minute windows with the most movement.
4. Tick the clips you want and press "Save Picked Clips".

Tracking speed & smoothness can be changed in the Movement card:
Fastest, Fast & Smooth, Most Accurate, Smoothest, plus individual controls.

Open `index.html` in Chrome directly (not in a preview panel).
No video is uploaded — everything runs in the browser tab, except the first-time
downloads of the person-detection model and, if used, Whisper models in older versions.
This v2 version does not use Whisper or captions.

## GitHub Pages

1. Upload `index.html` and this `README.md` to a GitHub repository.
2. In the repository: Settings > Pages > Build and deployment > Source: Deploy from a branch, Branch: main, Folder: / (root).
3. Save. Your site will be at https://<your-username>.github.io/<repository-name>/
