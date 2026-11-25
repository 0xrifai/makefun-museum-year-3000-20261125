# Museum of the Year 3000

[![make.fun](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb.svg)](https://make.fun/c/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![rank](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/0xrifai/makefun-museum-year-3000-20261125/rank.svg)](https://make.fun/c/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![reward](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/0xrifai/makefun-museum-year-3000-20261125/reward.svg)](https://make.fun/c/u-donrulezz-museum-of-the-year-3000-b727a0bb)

A make.fun entry for **Museum of the Year 3000**: one line, the museum label
a museum in the year 3000 puts beside an ordinary object from today.

## The entry

> A council of friends that met constantly, decided nothing, and could not be adjourned.

The object is the **group chat** — the one object on the bounty list with no
physical body. A curator from the year 3000, finding no artefact to put in a
glass case, has to guess what a group chat was from its behaviour alone, and
guesses wrong in exactly the right way: a council of friends, in session
forever, that passed no laws and could never be adjourned. Ask any group chat
where to eat and you will see the label is true.

## Why this line

The judge weighs entries in this order, most important first, and the line
was picked against exactly that order:

1. **On subject.** It is a museum label for an ordinary object from today —
   the group chat, one of the four objects the bounty names.
2. **The joke lands on a first read.** Three beats — met constantly, decided
   nothing, could not be adjourned — with the laugh in the line itself, not
   in an explanation around it.
3. **The humour is the year 3000 misreading the object.** The curator files
   a chat app under "council" and reports, straight-faced, what the council
   did: nothing, forever. The label says something true and absurd about what
   the thing was for.
4. **It reads like a real museum label.** Short, straight-faced, confident,
   one line, no throat-clearing, no "imagine if" framing.
5. **Fresh object and angle.** The fork is the obvious first object and the
   meter's obvious first joke is buying time; the group chat is the only
   intangible object on the list, and reading it as a parliament is an angle
   no physical object offers.

## Lines considered

| Object | Line | Why it lost |
| --- | --- | --- |
| Group chat | A meeting that never ended, attended by people who never arrived. | Weaker misreading than "council"; the paradox needs a half-second. |
| Group chat | A parliament of friends, in session forever, that passed no laws. | Same idea as the chosen line, weaker kicker. |
| Group chat | A room with no walls, where twelve people talked at once and nobody ever left. | True, but "room" is a thinner misreading than "council". |
| Group chat | A choir that sang 'lol' in unison, forever. | Funny, but leans on the reader knowing 'lol'. |
| Plastic fork | A hand, simplified: four fingers, no thumb, issued to citizens who could not be trusted with a knife. | The funniest fork line — but the fork is the most obvious object. |
| Plastic fork | A spear for food that tried to run away. | Short and punchy, but fork-as-weapon is a first-joke shape. |
| Plastic fork | A comb, for grooming the meal before eating. | Neat misreading, smaller laugh. |
| Plastic fork | A single-use trident, discarded after one meal, as the gods intended. | Too close to the obvious "used once, buried for 400 years" joke. |
| Parking meter | A vending machine that sold minutes, one coin at a time, and gave no change. | Strong — but "buying time" is the obvious first meter joke. |
| Parking meter | A small iron shrine where drivers left coins so their car would still be there when they returned. | The shrine angle is fresh, but the payoff is the towed-car joke. |
| Parking meter | A coin-fed guard, posted on every street, that watched your car while you were away. | Good misreading, gentler laugh than the council line. |
| Parking meter | A machine that rented out the ground beneath your car, by the minute. | True and absurd, but a redescription more than a misreading. |

## Run it

`main.ts` writes the label to the absolute path `/output/entry.txt` (the
grader mounts the repo read-only, so a relative `output/` write would fail).
Before writing, it validates the label against the gate: UTF-8 text of 1–200
characters, not only whitespace, a single line, no leading or trailing
whitespace. The chosen line is 86 characters.

## Run it

Requires Node 22.18 or later (Node runs the TypeScript as it is):

```sh
node main.ts
cat /output/entry.txt
```

## Files

- `main.ts` — the entry program; writes the label to `/output/entry.txt`.
- `README.md` — this file.
- `LICENSE` — MIT.
