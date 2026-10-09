# Session Conversation Log — Bharathanatyam

*Extracted from Claude Code session data on 2026-04-08*
*2 messages across 1 session(s)*

---
## Session be460e09

### [2026-03-14 11:03] Jay

quickly undersatnd what you've done here. going to make you do some edits

### [2026-03-14 11:03] Claude

Here's what this project is:

**Bharatanatyam Practice App** — a single-page HTML app for practicing Bharatanatyam dance steps (adavus) with audio.

**Key features:**
- **Two adavu types**: Thatadavu (1-8, missing 4) and Naatadavu (1-6)
- **Three speed segments** per audio file, separated by markers (m2/m3 timestamps in `markers.json`). Each audio file has all 3 speeds recorded sequentially, and markers define where speed 2 and speed 3 begin
- **Practice mode**: Select type → number → speed (1/2/3/All), hit Play. It plays just that speed segment (with 1.5s overlap at boundaries). Has loop toggle
- **Setup mode** (gear icon): Play full audio files and tap "Mark Speed 2"/"Mark Speed 3" to set the boundary timestamps
- **Audio files** live in `audio/` as mp3s (naming: `thatadavu-1.mp3`, etc.). The root also has source `.oga` files and combined recordings

All markers are pre-set in `markers.json` for every file. Ready for edits — what do you need?
