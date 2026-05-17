LexiForge v12 Repair + Analytics

Built-in words: 93

Upload only index.html to GitHub Pages.

Important:
- v12 migrates local v11, v10 or v9 data if present in the same browser.
- If your real progress is in cloud, use Cloud Sync -> same sync code -> Download from cloud.
- This build focuses on repairing broken games and improving analytics.

Fixed/rebuilt:
- A/B/C/D
- Reverse
- Cloze
- Collocations
- Word Tiles
- Sentence Order
- Daily Quest as a guided session
- Analytics
- Audio feedback for correct/wrong answers

Added:
- Hangman / one-letter submission game
- Learning Analytics: attempts, accuracy, stage-ups, average attempts to Strong/Mastered, recent activity, weak/strong words


Checked before sending:
- JavaScript syntax check with node --check: passed.
- Headless browser smoke test: nav rendered, A/B/C/D, Reverse, Cloze, Collocations, Word Tiles, Sentence Order, Daily Quest, Analytics and Letter Game opened without page errors.
- Cloud autosync is now conservative: local save every answer; cloud upload only after about 20 local changes or manual sync.
