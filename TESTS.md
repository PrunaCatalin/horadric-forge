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

### Trial 2 — 2026-10-27 — inputs loaded, predictions registered, not yet transmuted

Not the test that was planned. **No affix is on all five**, so this cannot confirm the
unanimous-carry rule. It discriminates between two rules instead, which trial 1 could
not do, and it doubles as the control for Materials Reserve.

| # | Dungeon | Region | Affix 1 | Affix 2 |
|---|---|---|---|---|
| 1 | Akkhan's Grasp | Hawezar | Materials Reserve | Shock Lance Elites |
| 2 | Bewitched Grotto | Skovos | Forgotten Wisdom | Poison Enchanted Elites |
| 3 | Sarat's Lair | Scosglen | Dungeon Delve | Deathly Shadows |
| 4 | Hallowed Ossuary | Fractured Peaks | Dungeon Delve | Shock Lance Elites |
| 5 | Basaltic Ascent | Skovos | Dungeon Delve | Avengers |

Tallies: Dungeon Delve 3/5, Shock Lance Elites 2/5, Materials Reserve 1/5,
everything else 1/5. Five dungeons, five regions. Transmutation (1), recipe valid.

**Predictions, written before the transmute.** The two rules disagree here, which is
what makes this worth spending five sigils on:

- **Unanimous carry** (what trial 1 suggested): nothing is on all five, so nothing
  carries. The output rolls two fresh affixes. Dungeon Delve would appear only by luck.
- **Majority carry**: Dungeon Delve sits on three of five and should appear on the output.

So: **Dungeon Delve on the output favours majority carry. Its absence favours unanimous
carry**, and is the second independent result pointing at the rule from trial 1.

**Materials Reserve is the control, and the position probe.** It is on exactly one input
— and that sigil was deliberately placed in **slot 1**, to test a third rule neither of
the above covers: that the cube reads the first item in the grid and ignores the rest.

Under unanimous or majority carry, Materials Reserve should not appear at all. Under
first-slot carry, it should, and so should Shock Lance Elites, the other affix on that
same sigil.

So the output separates three rules cleanly:

| Output shows | Rule |
|---|---|
| Neither Dungeon Delve nor Materials Reserve | unanimous carry |
| Dungeon Delve | majority carry |
| Materials Reserve, likely with Shock Lance Elites | first slot wins |

First slot winning would be the cheapest outcome by far: one good sigil plus four
spares, and the affix becomes targetable immediately.

The dungeon should again be unrelated to all five inputs. Trial 1 saw that once.

**Result.** Output: **Defiled Catacomb Escalation Sigil**, Fractured Peaks —
Vile Splendor + Avengers.

- No Dungeon Delve. **Majority carry is dead.** Three of five was not enough to move it.
- No Materials Reserve, no Shock Lance Elites. **First slot wins is dead.** Position in
  the grid does nothing; neither affix from the slot-1 sigil came through.
- Vile Splendor was on no input at all.
- Avengers was on exactly one input, Basaltic Ascent.
- Dungeon unrelated to every input again. Fractured Peaks was one input's region, but
  Defiled Catacomb was not among them.

The prediction written beforehand said neither Dungeon Delve nor Materials Reserve would
appear, and neither did.

**What this does not establish.** Trial 2 cannot tell unanimous carry apart from no carry
at all. With nothing shared across all five, both rules predict the same thing: two fresh
affixes. That is what came out. So the standing evidence for unanimous carry is still
trial 1 alone, n=1.

And Avengers is a warning about exactly that. It sat on one input out of five and landed
on the output anyway — a coincidence of precisely the kind that could have produced
Horadric Strongroom in trial 1. Seeing it happen here, in a trial where nothing could
have carried, is a reason to trust trial 1 less rather than more.

| Rule | Status |
|---|---|
| Majority carry | ruled out, trial 2 |
| First slot wins | ruled out, trial 2 |
| Unanimous carry | alive, supported by trial 1 only |
| No carry at all | alive, and trial 1 is explainable as luck |

### The weight hypothesis

Proposed after trial 2: affixes are not carried or not carried, they are **weighted**, and
the output rolls from a weighted pool. It splits into two versions that the data so far
cannot tell apart, and both survive everything above.

**Intrinsic weight.** Every affix has its own base frequency and the inputs change
nothing. Common affixes show up often on outputs because they show up often everywhere.
This is "no carry" wearing better clothes.

**Input weight.** Each input that carries an affix raises that affix's weight in the
output roll. Five of five is a strong push, three of five a weaker one, one of five
barely anything. Nothing is guaranteed at any count.

Input weight explains every observation without strain: Strongroom at 5/5 landed,
Dungeon Delve at 3/5 missed, Avengers at 1/5 landed anyway, Materials Reserve at 1/5
missed. So does intrinsic weight, if those affixes happen to be common ones.

**This is why the hypothesis matters: it changes what an experiment is.** A rule that
either carries or does not can be settled by one well-shaped run. A weighted rule cannot
be settled at all by a single run — any single outcome is consistent with any weight
short of zero or certainty. It has to be counted over many runs, and both versions only
separate once there is a baseline to compare against.

**The baseline is free.** It needs no transmutes: go through the sigil stash and tally how
often each affix appears across every sigil in there, say twenty or more. That gives the
natural frequency of each affix.

With the baseline in hand:

- Output affixes matching the natural frequencies, regardless of what went in → intrinsic
  weight, and there is no inheritance.
- Output affixes over-representing what the inputs carried → input weight is real, and
  stacking five of the same affix is the best play available even without a guarantee.

**One cheap question first.** In trial 1, were those five sigils picked *because* they all
had Horadric Strongroom, or did they simply all happen to have it? If they were not
selected for it, Strongroom is a very common affix, its appearance on the output needs no
explanation beyond base rate, and the evidence for any inheritance drops to nothing.

What the two outputs so far look like against their inputs:

| Output affix | Inputs carrying it |
|---|---|
| Horadric Strongroom (trial 1) | 5 of 5 |
| Veiled Elites (trial 1) | 0 of 5 |
| Vile Splendor (trial 2) | 0 of 5 |
| Avengers (trial 2) | 1 of 5 |

Two of four output affixes were on no input at all. Whatever the rule is, a large random
component is in it.

### Trial 3 — the one that actually decides it

Repeat trial 1's design: five sigils that **all** carry one affix, Materials Reserve for
preference. That is the only shape that separates the two surviving rules.

Carrying affix on the output means unanimous carry is real and the affix is targetable.
A fresh roll means there is no inheritance and trial 1 was a 13% fluke.

Two more runs of this shape would put it beyond argument. One is enough to act on.

### Still untested after this

Whether **both** affix slots can carry at once, which needs five sigils sharing both
affixes. Rare to assemble, so it waits.

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
