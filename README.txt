PsychoWithSanskar NORCET v4 BETA

Features:
- Existing 524-question NORCET practice platform
- Firebase Google sign-in
- Firestore user profiles
- Cloud score sync
- Global Top 50 leaderboard

Firebase setup already required:
- Google provider enabled
- Firestore created
- GitHub Pages domain authorized

IMPORTANT SECURITY NOTE:
This beta client syncs XP directly to Firestore for testing. It is NOT anti-cheat secure yet.
For production leaderboard integrity, move score calculation to trusted server-side code (Cloud Functions/Cloud Run) before treating rankings as competitive or monetized.

Deploy files to the GitHub Pages repository root:
index.html
manifest.json
sw.js
firebase-config.js
