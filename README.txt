LexiForge v10

Built-in words: 93

New/fixed:
- Swipe Sort is now a right/left correctness game:
  word + translation appear; swipe/tap right if correct, left if incorrect.
- Learning stages:
  New -> Seeded -> Familiar -> Learning -> Strong -> Mastered -> Long-term.
- App decides stage from attempts, correct answers, skill strength and mode variety.
- Spaced reminders: mastered words come back later instead of disappearing.
- Green/red feedback across games.
- Better Today counter:
  attempts, correct, accuracy, XP, words touched.
- Mini Crossword.
- Word Tiles / Scrabble-style game.
- Download App Version button inside the app.
- Duplicate protection remains.
- Upload JSON and Backup remain.

Upload index.html to GitHub Pages.
Open via hosted URL, not Files preview.


New in v10:
- Firebase Cloud Sync using Firestore.
- Cloud Sync mode in the app.
- Smart Sync: uploads if cloud is empty/older, downloads if cloud is newer.
- Manual Upload this device / Download from cloud buttons.
- Auto-sync option.
- Local storage and backup JSON still remain.

How to use:
1. Upload index.html to GitHub Pages.
2. Open the app from the GitHub Pages URL.
3. Go to Cloud Sync.
4. Enter the same hard-to-guess sync code on every device.
5. On your main device, click Upload this device.
6. On another device, enter the same code and click Download from cloud or Smart Sync.

Firestore collection used:
lexiforgeSync / <your sync code>
