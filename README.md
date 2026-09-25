# Signal

A small browser game. You are a night radio operator.

Voices drift across the band. You cannot hear anything while you are searching
for it: moving the dial is static. Stop moving to hear. Hold still and the
static softens into a voice, then locks.

Play: [github.io](https://vvoice659.github.io/signal)

## Controls

- Move the mouse (or drag on touch) to tune the dial.
- Stop moving. Holding still locks the nearest voice.
- Nothing else.

## The mechanic

The whole game is one exchange: listening and searching are the same dial.
Search and you hear only static; hold and you hear one voice, but you commit to
where you already are. A voice only locks if you stop moving on top of it.

- Static softens across a wide band as you near a voice, so you can feel your
  way in. Only the nearest voice shows a faint band; there is no map.
- Nights get busier and voices drift more. Night 1-2 a voice barely sways.
  Night 3 it sways enough that you hold a beat longer to lock it.
- Three nights, a quota each. Miss the quota and the run ends.

## Files

- `index.html` — the whole game, one file, no dependencies.
- `manifest.json` — bundle metadata.
