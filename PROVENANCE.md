# PROVENANCE — how this rendering came to be

*Shona (chiShona), chair 100. Floor 23,213 verses.*

This is the record of how the text in this repository was produced and what had
to be corrected in it. A machine-assisted rendering has no standing unless you
can see how it was made, so this file says both — **including the faults, and
including the ones found by accusing the machine of things it had got right.**

---

## The approach

Every verse is rendered from the Hebrew of that verse, under a written discipline
— `docs/methodology/translation-discipline/sn.md` in the Selah repository, itself
written in Shona. Seven rules govern it: the Hebrew token is the unit; the Name
stays the Name; both truths of Deuteronomy 6:4; no foreknowledge (Genesis 22:1
does not know Genesis 22:13); numbers and marks stay put; the translator has no
word of its own; a hard verse is laid bare, not smoothed.

**The `⟨ ⟩` brackets do two different jobs.** `⟨את⟩` is the Hebrew
direct-object marker, which Shona has no word for; it is left standing so the
reader sees it. Bracketed Shona words are ones the Hebrew did not write but
Shona grammar requires — visibly marked, so you can always tell what the Hebrew
said from what the grammar needed.

## Why the register looks the way it does

Two facts about standard Shona set the whole Name table, and both are
orthographic rather than theological.

**Standard Shona has no `l`.** It writes `r` where its neighbours write `l`. So
`אלהים` cannot be *Elohim* here; it is **`Erohimu`**.

**Shona builds open syllables** — a syllable ends in a vowel. So a
transliteration cannot end on a consonant or stack two of them. `יהוה` is
**`Yahwe`**, not *Yahweh*. `צבאות` is **`Tsevaoti`**. `אל` is **`Er`**.

If you have read another Selah chair, `Yahwe` will look truncated. It is not.
Ilocano's certified form is `Yahweh`; Shona's is `Yahwe`, for the reason above.

## The fight on this chair is `Mwari`

`Mwari` is the ordinary Shona word for God and it is the most important
rejection in the discipline. **It is not a bad word. It is the right word. But
it is not the Name.** Every printed Shona Bible uses `Jehovha` or `Mwari` where
the Hebrew has יהוה, and a reader of those cannot see what the Hebrew said.

So `יהוה` is `Yahwe` here, everywhere, without exception.

**But `mwari` and `vamwari` in lower case are correct**, and are used, where the
text means the gods of the nations — the golden calf of Exodus 32, Baal-zebub of
Ekron, Dagon, the gods of Syria. Transliteration is reserved for the One; Shona's
own word does the work for the others.

**And `tenzi` and `ishe` are correct for a human lord or master.** Genesis 44:19
is Judah addressing Joseph — *my lord asked his servants* — and reads `Tenzi
wangu`. Genesis 39:3 is Potiphar, *his master saw*, and reads `tenzi wake`. Those
are not erasures of the Name; they are the Hebrew אדון, which means a master.

## What was corrected, and what the corrections cost

The Name: at the last reading before this file was written, **546 of 547 seats
carried `Yahwe`**, and the single exception was not a Name fault at all — see
below.

The object marker `⟨את⟩`: **1,544 seats, none lost.** The fault has never run in
the direction of dropping it. It has run the other way: a marker appearing on a
token whose Hebrew has none.

That class turned out to be **misnamed**. It is not an invention. The verse's
real את is present and correctly marked, and the marker was **also copied onto
an earlier token** — `לקחה → ⟨את⟩ atora` sitting immediately before
`את → ⟨את⟩`. Genesis 21:2 shows the mechanism: `אשר` carries the *gloss* of the
following word as well as the *marker* of the one after it, so a span of the row
slid leftward and the marker travelled with it. Because the real marker is
identifiable, removing the copy is arithmetic and not a judgment.

Two word-choice corrections were made in the first hour, both found by reading
the opening verses:

- `פני` — *face* — had come out as `tsigiri`, which means a **foundation**.
  Genesis 1:2 read *above the foundation of the water*. Corrected to `chiso`.
- `דגת` — *fish* — had come out as `mhodzi`, which means **seed**. Genesis 1:26
  had them ruling over *the seeds of the sea*. Corrected to `hove`.

## Exodus 11:5–8

**Three verses in this book are not in Shona.** Exodus 11:6, 11:7 and 11:8 were
produced in **Yiddish**, entirely — and `exodus/11/5`, produced in the same
request, renders *the firstborn* as `vachembero`, which is closer to *the
elderly* than to `dangwe`.

All four share a single timestamp, which is how we know they came from one
request. They are recorded here rather than quietly fixed because **a reader has
a right to know that a machine can leave the language altogether for the space of
one call**, and that nothing in the structural checks noticed: the marker count
passed, the word-bleed list saw nothing, and the whole run surfaced only because
the Name was passed through unglossed in one of them.

They are marked for re-rendering. If you are reading a version where they are
still Yiddish, that pass has not run yet.

## What is machine and what is human

**Everything in the verse files is machine-produced.** No human has read most of
these verses. The discipline was written by a human and a machine together; the
corrections above were made by a machine reading its own output against the
Hebrew, which catches form faults and misses others.

**No native speaker of Shona has yet read this rendering.** That is the largest
open item and no amount of internal checking substitutes for it. See
`CONTRIBUTING.md` — and read it before correcting anything, because some of what
looks wrong here is deliberate.

## The floors it cleared before it began

Two, both recorded in the Selah repository:

- a round-trip noun probe — **19 of 20**
- a stability probe, asking the same twenty items twice and comparing —
  **69%, with verbs at 71%** (`dev/experiments/1026_the_stability_probe.clj`)

The second exists because the chair before this one passed the first at 17 of 20
and then produced `נבא` in 48 different renderings. **Knowing a word and settling
on it are different properties**, and only the second probe can see the
difference.

## Dates

Lit 2026-09-27 at 01:03:21 local time. The working record of the burn, in the
order things were found, is `NOTES.md`.
