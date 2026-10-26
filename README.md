# Ember Vigil

A Nordic winter-night survivors-like for the browser. Keep your lantern lit and survive until dawn.

**Play:** https://tommykalmer.github.io/EmberVigil/

## How to play
- Move with your finger (drag anywhere) or WASD / arrow keys. Your weapons fire by themselves.
- Collect the blue crystals to level up and pick an upgrade.
- Survive 10 minutes until dawn. Bosses arrive at 3, 6 and 9 minutes.
- Every game earns embers, even when you fall. Spend them on permanent upgrades and new heroes.
- Win a night to unlock the next one (10 nights in total, each harder and more rewarding).

## Tech
- One self-contained `index.html`: canvas rendering, synthesized WebAudio sound, no build step, no dependencies.
- CrazyGames SDK v3 is loaded automatically: rewarded ads (revive, double embers, reroll), midgame ads between runs, gameplay start/stop events and cloud saves. Outside CrazyGames a short test-mode ad stands in.
- Progress is saved in the browser (localStorage), and in the CrazyGames account when played there.

© AsterIQ Ab
