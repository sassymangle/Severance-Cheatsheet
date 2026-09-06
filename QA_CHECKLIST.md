# Pre-release QA Checklist

Use this before publishing changes to the cheatsheet.

## Core controls

- [ ] Difficulty selector loads all five modes.
- [ ] Evidence checkbox cycles **Found → No → Clear**.
- [ ] Reset Investigation clears evidence selections.
- [ ] Reset keeps the selected difficulty.
- [ ] Compact mode toggles correctly.
- [ ] Hide/show ruled-out ghosts toggles correctly.
- [ ] Selected difficulty is remembered after refreshing the page.

## Difficulty logic

- [ ] Beginner uses the full normal evidence pool.
- [ ] Intermediate uses the full normal evidence pool.
- [ ] Professional uses the full normal evidence pool.
- [ ] Nightmare does not eliminate a ghost merely because one normal evidence was not found.
- [ ] Nightmare forced evidence is handled separately from ordinary evidence.
- [ ] Severed does not expose ordinary evidence as usable evidence.
- [ ] Severed only allows forced/special evidence to affect evidence filtering.

## Special cases

- [ ] Parvulus is not incorrectly eliminated by Ghost Orbs.
- [ ] Banshee reduced-evidence EVP behavior is preserved.
- [ ] Hantu forced Freezing behavior is preserved.
- [ ] Obake forced Laser Grid behavior is preserved.
- [ ] Shade forced Painting behavior is preserved.
- [ ] Wraith forced UV behavior is preserved.
- [ ] Strey forced Ghost Orbs behavior is preserved.

## Ghost cards

- [ ] All 24 ghosts render.
- [ ] Every ghost card shows Hunt / Speed.
- [ ] Every ghost card shows Model Flicker.
- [ ] Every ghost card shows Best Check.
- [ ] Every ghost card shows its practical Tell.
- [ ] Ruled-out ghosts fade rather than disappearing by default.

## Visual / device checks

- [ ] Desktop layout is readable at 100% browser zoom.
- [ ] Narrow/second-monitor layout does not overflow horizontally.
- [ ] Mobile-width layout stacks cleanly.
- [ ] Found evidence is immediately obvious.
- [ ] No evidence is visually distinct from Found.
- [ ] Footer credits show Sykes Games and llnutcracker.

## Release sanity check

- [ ] Browser tab title says **Severance Ghost Cheatsheet — Mayhem Edition**.
- [ ] No visible text says “Prototype”.
- [ ] `index.html` is in the repository root.
- [ ] `.nojekyll` is present.
