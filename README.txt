R1 Chess v1.3 - production candidate

Changes from v1.2:
- Fixed Random side preference. Random remains selected and rerolls White/Black every New Game.
- Threefold repetition draw.
- 50-move rule (100 halfmoves).
- Insufficient-material draws: K vs K, K+B vs K, K+N vs K, bishops-only same-color complex.
- Persistent W/L/D statistics separately for Levels 1-5.
- Undo restores repetition state and permits a revised game result to be recorded.
- Retains castling, en passant, Q/R/B/N promotion, five distinct AI levels.
- No engine/debug/offline diagnostic text.

Stats are stored in localStorage on the device/browser.
