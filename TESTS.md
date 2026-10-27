# Sigil Amalgamation — test log

Open question: does the Horadric Cube's `5x Nightmare Sigil -> 1x Escalation Sigil`
recipe carry the inputs' affixes onto the output, or does the output roll fresh?

No guide answers this. These tests answer it from the game itself.

## Read this before trusting a result

A Nightmare Sigil rolls roughly two affixes out of a pool of fifteen or more.
So any single sigil has a rough **1 in 7** chance of showing Materials Reserve by
luck alone. One trial proves nothing in either direction.

That is why test D exists. D is the control: same recipe, inputs that carry **no**
Materials Reserve. If C and D come out at similar rates, there is no inheritance and
we were reading noise. If C hits every time and D never does, inheritance is real.

Three runs of each is the minimum worth drawing a line under. Fewer is a hint, not
an answer, and it gets written down as a hint.

## Tests A and B cost nothing

Load the cube, read, then **cancel**. No sigils are consumed. Do these first.

### Test A — are mixed dungeons accepted?

Load five Nightmare Sigils from five **different** dungeons.

Does the Transmute button light up, or does the cube refuse them?

This settles the `(?)` currently on the site: one guide says the five sigils need
not share a dungeon, every other guide says they must.

| Result | Meaning |
|---|---|
| Accepted | same dungeon is not required; site note corrected |
| Refused | same dungeon required; the outlier guide is wrong |

### Test B — what does the preview show?

Load five valid sigils. Look at the preview pane before confirming.

Does it name the output's **affixes**, or only "Escalation Sigil"?

If it shows affixes, every test below gets answered without spending a single sigil,
and we can run as many trials as you have sigils for.

## The actual experiment

### Test C — all five carry Materials Reserve

Five Nightmare Sigils, every one of them with Materials Reserve.

### Test D — control: none carry Materials Reserve

Five Nightmare Sigils, **none** with Materials Reserve. Same dungeon rules as C.

This one feels like a waste of sigils. It is the test that makes C mean anything.

### Test E — only if C and D disagree

Three with Materials Reserve, two without. Does a majority carry it over, or is
there a threshold?

Skip E entirely if C and D come out the same. There would be nothing to measure.

## What to send

Typing beats photographing for the inputs. Per trial:

1. **Type** the five inputs: dungeon name and affixes. Short is fine —
   `Farai Cliffs: Materials Reserve + Blood Blisters` x5.
2. **Photo** of the cube with the five loaded, preview visible.
3. **Photo** of the output sigil's tooltip.

Photos 2 and 3 are the ones that matter. The tooltip must be legible.

## Results

### Trial 1 — 2026-10-27 — tests A, B and a partial C in one run

Five Nightmare Sigils, five different dungeons, three different regions:

| # | Dungeon | Region | Affix 1 | Affix 2 |
|---|---|---|---|---|
| 1 | Tormented Forest | Skovos | Horadric Strongroom | Volcanic |
| 2 | Submerged Ruins | Skovos | Horadric Strongroom | Avengers |
| 3 | Crusaders' Cathedral | Kehjistan | Horadric Strongroom | Deathly Shadows |
| 4 | Hierophant Pyre | Nahantu | Horadric Strongroom | Suppressor Elites |
| 5 | Putrescent Larder | Nahantu | Horadric Strongroom | Volcanic |

Output: **Belfry Zakara Escalation Sigil**, Hawezar — Horadric Strongroom + Veiled Elites.

**Test A: mixed dungeons are accepted.** Five dungeons across three regions, and the
cube matched the recipe. The `(?)` on the site is resolved: the outlier guide was right,
the five sigils do not have to share a dungeon.

The recipe panel's counter proves it rather than the button colour alone. With the five
loaded it read **Transmutation (1)** and TRANSMUTE was lit; with one item left in the
cube afterwards it read **Transmutation (0)** and TRANSMUTE was greyed out. The counter
is a live validity check — load a recipe and read it before spending anything.

**Test B: no affix preview.** Nothing in the cube names the output's affixes ahead of
the transmute. You only learn them after committing.

**The pattern, and how far it actually goes.** Three things happened at once:

- The affix on **all five** inputs, Horadric Strongroom, is on the output.
- The second affix differed across inputs (Volcanic twice, Avengers, Deathly Shadows,
  Suppressor Elites). The output's second affix is Veiled Elites, which was on **none**
  of them.
- The output dungeon, Belfry Zakara in Hawezar, matches no input and sits in a region
  none of the inputs came from.

So: dungeon is rolled fresh, the slot the inputs disagreed on is rolled fresh, and the
slot they all agreed on carried through. That reads as a rule: **a shared affix carries,
everything else rerolls.**

One trial. A specific affix lands on a sigil by luck maybe one time in seven, so a
coincidence here is unlikely but nowhere near ruled out. This is a hint with a mechanism
behind it, not a confirmed rule.

### Next: trial 2 settles it

Five Nightmare Sigils that all carry **Materials Reserve**, any dungeons.

If the rule holds, the output is an Escalation Sigil with Materials Reserve, on demand.
That is the original question answered, and it turns the affix from a lottery into
something you can build toward.

If the output comes back without it, Strongroom in trial 1 was luck and there is no
inheritance.

Either way the result is worth having, and the test costs five sigils.

## What we already know

Confirmed, and not in dispute:

- Nightmare Sigils roll Materials Reserve themselves. Confirmed on Blizzard's forums
  alongside Gem Reserve, Gold Reserve and Strongroom. An Escalation Sigil is not
  required to get the affix.
- Sigil affixes are final once rolled. There is no reroll anywhere, cube included.
- Inside an Escalation dungeon you pick the next portal from its affixes. The
  Branching Pathways War Plan node adds two extra portals per transition.
- A Reserve affix stashes 8 Horadric Chests. Materials Reserve holds gold, basic and
  legendary crafting materials, Bundled Herbs, Angelbreath, Veiled Crystals and
  Forgotten Souls.

Reported but unconfirmed:

- Sigil affixes changing on their own while the sigil sits in the stash. If a trial
  result looks impossible, this is the first thing to suspect.
- Around 40+ Forgotten Souls per Materials Reserve chest. Single source, old season.
