R1 Chess v1.6
SAVE/RESUME FIX
- Uses Rabbit Creation persistent storage (window.creationStorage.plain) as the primary R1 save.
- Values are Base64 encoded for the Rabbit storage API.
- Startup awaits the asynchronous R1 load before creating a fresh game.
- localStorage remains a desktop/browser fallback.
- Saves after moves, Undo, New Game and on hide/close.
- Restores full chess position, player side, special-rule state, repetition state,
  last move, Undo history and completed-result state.


v1.7: requests a screen wake lock while foregrounded and revises levels 1-10 so higher levels use progressively stronger, complete iterative search rather than partial-timeout/random behavior.
