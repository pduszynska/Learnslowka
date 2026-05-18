LexiForge v14.3 — Chunked Cloud Sync

This version keeps:
- latest uploaded progress backup
- active idioms/native chunks
- app features from v14.2

New in v14.3:
- Cloud sync uploads WORDS + PROGRESS + STATS in chunks
- Fixes Firestore 1MB document limit
- Uses collection:
  lexiforgeChunkSync/{syncCode}/chunks/{chunkId}
- Upload this device now sends chunked data instead of one giant JSON document
- Download from cloud reconstructs words + progress from chunks
- Smart Sync uses the new chunked architecture

Upload ONLY index.html to GitHub Pages.

After replacing index.html:
1. Open app.
2. Go to Cloud Sync.
3. Use the same sync code.
4. Click Upload this device.
5. It should upload words + progress without the 1MB error.

The old single-document sync may still exist in Firebase, but v14.3 uses a new safe chunked collection.
