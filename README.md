# Radial Defence — playable ad preview

Live: **https://kyrylhalmiz.github.io/rd-playable-preview/** — the current build.

First build: **https://kyrylhalmiz.github.io/rd-playable-preview/og/** — the original merge hook,
kept unchanged: placeholder art, no game meshes, the merge button and nothing else.

Each page is one self-contained HTML build of the Radial Defence merge hook, published here only so
it can be opened on a phone.

The current build carries **the game's own art** — the tower, the five cannon bodies, the meadow and the
horde's run cycle, exported from the Unity project — and its effects are the game's own particle
prefabs replayed. Between rounds it shows the shipped build's upgrade screen: "Round complete!",
then a Heal button and a Cannon button at the shipped prices and layout. No store URLs, no
endpoints, no account data.

Source lives elsewhere; this repo holds a generated artefact and nothing else.

`hands/index.html` is the hands hook: the sheet's white tower with arms, hands that reach for the gun thrown from the pad and hold it, five guns from Desert Eagle to rocket launcher, a zombie horde and the ogre boss, all generated from the reference sheet.
