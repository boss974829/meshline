# Meshline

A harbor-city strategy desk. Nine relays. Two benches. Twelve cables.

**Open the desk:** [play Meshline](https://htmlpreview.github.io/?https://github.com/boss974829/meshline/blob/main/docs/index.html)

**Repository:** [boss974829/meshline](https://github.com/boss974829/meshline)

Razor charts a relay, shears its integrity, and takes it once it is soft. Keel mends, raises plates, sets lures, and anchors anything steady. Five relays win the night. Heat at 100 makes that bench sit a cable out.

## How to play

1. Pick a callsign.
2. Choose **Razor**, **Keel**, or **Gallery**.
3. Select a relay, then spend band on one action. The other bench answers.
4. Gallery can step the cable or let it run.

Your best mark stays in this browser only.

## Benches

| Bench | Actions |
| --- | --- |
| Razor | Chart (1), Shear (3), Take (3) |
| Keel | Mend (1), Seal (2), Lure (2), Anchor (3) |

Band refills by 2 after each full cable, up to 5.

## Source

The desk logic lives in [`src/lib/meshline/engine.ts`](src/lib/meshline/engine.ts). The screen is [`src/components/meshline/meshline-app.tsx`](src/components/meshline/meshline-app.tsx). The same rules are also in [`docs/index.html`](docs/index.html), which is what the open link above plays.
