# MercyCut Web v2 — Movement Clips

Simple web app, no prompt, no captions needed.

1. Upload a video.
2. Pick the person to follow (Person 1, 2, 3, or 4).
3. Press "Find Best Movement Clips" — it finds the ~2-minute windows with the most movement.
4. Tick the clips you want and press "Save Picked Clips".

Tracking speed & smoothness can be changed in the Movement card:
Fastest, Fast & Smooth, Most Accurate, Smoothest, plus individual controls.

Clips are saved automatically in this browser (local storage), so a refresh or an
accidentally closed tab does not lose your work. Only the project is stored — not the
video file — so open the same video again to preview and export. "Clear clips" in the
Clip Library starts a fresh session, and "Save Project" still downloads a JSON copy you
can keep or move to another computer.

Open `index.html` in Chrome directly (not in a preview panel).
No video is uploaded — everything runs in the browser tab, except the first-time
download of the person-detection model. This v2 version has no captions, no
transcripts and no Whisper: movement clips only.

## GitHub Pages

1. Upload `index.html` and this `README.md` to a GitHub repository.
2. In the repository: Settings > Pages > Build and deployment > Source: Deploy from a branch, Branch: main, Folder: / (root).
3. Save. Your site will be at https://<your-username>.github.io/<repository-name>/
