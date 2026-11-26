# Dynamic Entry

A top-down tactical SWAT game that runs in the browser. Breach the front door, clear every room, and get every suspect and hostage out alive before the timer runs out.

**Play:** https://helmutgranda.github.io/dynamic-entry/

The whole game is a single file, `index.html`, with no build step.

## Saving

Progress saves automatically in each player's browser: best score and rank per mission, missions played, loadout and settings. Updates to the game keep that progress. Players can copy a save code from the **Progress** screen to back up their progress or move it to another browser or device.

## Updating

Edit the game, then run `./publish.sh "What changed"` from the folder that holds `dynamic-entry.html`. Players who have the game open see a banner offering to reload into the new version.
