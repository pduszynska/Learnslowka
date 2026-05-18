LexiForge v14 Adaptive Memory + Idioms

Built-in entries: 103
New idiom/native chunk entries added: 10

Upload only index.html to GitHub Pages.

Important:
- This is a safe upgrade from v13 and preserves the existing local data path, so your progress is not wiped.
- It includes a starter idiom/native chunk pack inside the app.
- A separate idiom import JSON is also included.
- Cloud Sync is preserved.
- If your current progress is in cloud: Cloud Sync -> same sync code -> Download from cloud.

Included files:
- index.html
- lexiforge_v12_2_all_words_import.json
- lexiforge_v12_2_backup_template.json
- lexiforge_v14_idioms_native_chunks_import.json
- LEXIFORGE_V14_ARCHITECTURE_NOTES.txt

Note:
Full split Firestore architecture is documented but not activated in this ZIP. That migration should be tested carefully against your real cloud data because your current cloud document hit the Firestore 1MB limit.


IPAD PROGRESS BUILD
This build includes the uploaded backup: lexiforge_v12_2_backup.json.
On a fresh browser/iPad where LexiForge has no existing local data, index.html preloads:
- words
- progress
- stats/analytics (with a trimmed history for localStorage safety)

The full original uploaded backup is included as:
lexiforge_uploaded_progress_full_backup.json

If you already have local LexiForge data on the same GitHub Pages URL, this build will NOT overwrite it automatically.
To force this uploaded backup, clear the site's local storage or use Backup/Import if available.


V14.1 FIX:
- Idioms are now active inside the app menu as 'Idioms'.
- The 10 native chunks are automatically added to the local word library on load.
- This build keeps the uploaded v12.2 progress preload for iPad use without Firebase sync.
