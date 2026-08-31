# 02 - The chronological, multi-tradition format

This is the central design document. The book is a history of philosophers ordered in time, and it
covers more than one tradition. Those two commitments pull against each other, and most of the work
of the book is in how that tension is resolved.

Citation keys resolve in [`sources.md`](sources.md).

---

## The problem, stated precisely

Chronology is a single line. The history of philosophy is not.

Between roughly 600 and 300 BCE, the Presocratics, Socrates, Plato and Aristotle were at work in
Greece; the Upanishads, the Buddha, and the early systematic schools in India; Confucius, Laozi,
Mozi and Zhuangzi in China. These are contemporaries. They were almost entirely unaware of each
other.

That produces a genuine dilemma with three answers, and the book has to pick one deliberately:

| Approach | What it does | What it costs |
|---|---|---|
| **Strict global interleave** | Order every chapter by date, regardless of tradition | Destroys continuity. A reader following an argument through three generations of Confucian thought is interrupted by Parmenides. Conversations get cut into fragments |
| **Tradition blocks** | Complete each tradition end to end, then start the next | Not a chronological book. It restarts the clock repeatedly, loses all simultaneity, and structurally invites the appendix problem (see F5 below) |
| **Braided: era, then tradition** | Divide into eras by date; inside each era run each tradition as a continuous stretch; close the era looking across | Some repetition at era boundaries; requires era boundaries that are defensible for every tradition |

**Recommendation: braided.** (judgement.) It is the only one of the three that keeps continuity
within a tradition at chapter scale while keeping simultaneity visible at book scale, and it is the
only one that gives every tradition the same structural standing.

**What the sources do and do not support here.** [Humphreys 2019] on [Grayling 2019] is direct
evidence against the third option in the table, tradition material folded in as a minor section.
[Adamson 2014- ] demonstrates that continuous, unhurried treatment of a tradition works, but he
achieves it with a volume per tradition, which *is* the tradition-blocks row above. He is evidence
for the continuity property that braiding preserves, not for braiding over blocking. Braiding is this
folder's own adaptation of that property to a single volume, and it is asserted as a judgement rather
than as a finding.

---

## Ordering rules

**Attribution.** O1-O5 are this folder's own rules `(judgement)`. No source prescribes them; they are
what the principles in `01` and the evidence in the sources imply for a book of this shape. Where a
rule has scholarly grounding, the grounding is cited inside the rule and is marked as such. Disagree
with any of them freely, but replace them with something, because the failure modes below are what
fills the vacuum.

### O1. Era boundaries are dates, not European period names *(judgement; grounding: [Park 2013])*

"Ancient", "Medieval", "Renaissance", "Early Modern" are periods of European history. Applying them
globally is not a neutral convenience: the Song dynasty is not "medieval", and calling it that
imports a European clock as the world's clock.

**Rule:** label eras by date range as the primary heading, and name the local period inside each
tradition's section. So the era is "c. 600 BCE to c. 200 CE", and within it a section is headed
"Greece: the classical period" and another "China: the Hundred Schools". The date range is the
shared spine; period names stay local to the tradition they belong to.

This matters more than it looks. [Park 2013] documents that the familiar Greeks-to-Kant progression
is not a natural fact but a construction of European scholarship between 1780 and 1830, which
replaced earlier histories that began in Egypt or Western Asia and reclassified those traditions as
religion rather than philosophy. A chronological book that adopts the standard period scheme without
comment inherits that construction silently.

### O2. Order within an era by period of activity, not by birth *(judgement)*

A thinker enters the conversation when they produce work, not when they are born. Use the floruit
or the date of the principal work.

### O3. Composite and undated texts are placed by period of formation, and the uncertainty is stated *(judgement)*

The Upanishads, the *Daodejing*, the Presocratic fragments and much early Buddhist material do not
have a single author or a firm date. Place them by the period scholars assign to their formation,
and say in the text that the dating is contested and roughly what the range is. Never present a
convenient date as a settled one.

### O4. Era boundaries are cut where a tradition changes, and the cut is justified in the text *(judgement)*

Do not inherit boundaries. Choose them, and tell the reader in one or two sentences why the book
breaks here. If a boundary is clean for one tradition and arbitrary for another, say that too.

### O5. Proportion is fixed before the drafting, not after *(judgement; grounding: [Humphreys 2019] on [Grayling 2019])*

Decide the share of the book each tradition gets, and the rule that share follows, before writing.
Otherwise the proportions fall out of which material was easiest to write, which in practice means
the tradition the author already knows.

The cautionary case is concrete. [Grayling 2019] is billed by its publisher as "the first
authoritative and accessible single-volume history of philosophy to cover both Western and Eastern
traditions", surveying "in tandem" the traditions of India, China and the Persian-Arabic world.
[Humphreys 2019] reports that "non-western thought accounts for barely one-eighth of the book and is
presented in a rather tokenistic fashion" - an eighth for everything outside the West, taken
together. The billing and the page count disagree, and the page count is what the book actually did.

---

## Context per thinker

The recurring question is how much scene-setting each philosopher gets. Three kinds of context, with
different budgets:

1. **Enabling context - always include.** The problem the thinker inherited and who left it open.
   Without this the position is an opinion floating free. This is the property [Copleston 1946-1975]
   was praised for, showing each thinker's links backwards and forwards, and it is the thing that
   justifies chronological order at all.

2. **Biographical context - include sparingly, for momentum.** A life gives a chapter narrative
   drive, which is a real asset. [Durant 1926] built an entire successful book on biographical
   portraits. The risk is that biography is easier to write than philosophy and expands to fill the
   chapter. **Rule:** biography earns space only where it bears on the thought (Socrates' trial,
   Spinoza's excommunication, Confucius' failure to find a ruler who would employ him), or where a
   short vivid detail buys the reader's attention for a hard passage.

3. **Political and social context - include only when it changed the philosophy.** Not as
   background colour. If the reader can follow the argument without it, cut it. (synthesis)

A useful discipline: **context is a debt the argument pays back.** If a paragraph of setup does not
make some later paragraph of philosophy easier to follow, it is decoration.

---

## Continuity and influence

The whole value of chronological order is that it can show ideas moving. That makes influence claims
the load-bearing claims of the book, and the easiest to get wrong.

### Three relations, never conflated

- **Documented transmission.** There is evidence of texts, translations, teachers or institutions
  carrying an idea from A to B. Greek philosophy into Arabic and then into Latin. Buddhism from
  India into China. State these plainly and say what the channel was.

- **Parallel development.** Two traditions reached similar positions with no evidence of contact.
  Greek and Indian atomism is the standard case: [Berryman 2022] notes striking parallels while
  recording that the tradition that Democritus knew the Indian "gymnosophists" is "difficult to
  authenticate". State these as parallels, explicitly, and say that no transmission is established.

- **Retrospective comparison.** A resemblance that you, the author, are drawing for the reader's
  benefit, with no historical claim at all. These are often the most illuminating passages in a
  global history. Mark them as yours. "Hume and the Buddhist no-self arguments converge here, though
  neither knew of the other" is honest; the same sentence with "as Hume learned" is fabrication.

### The rule

**Resemblance is not evidence of influence.** Never let similarity alone carry a transmission claim.
When the evidence is genuinely thin, say what the state of the question is rather than picking a
side for narrative convenience.

This rule is not a novelty of this folder. It is [Skinner 1969]'s **mythology of parochialism**: the
historian mistakes an author's references and falsely attributes influence on the basis of random
similarities between texts. It is the fourth of his four mythologies, and the one most dangerous to a
multi-tradition chronology, because such a book will keep finding real resemblances between
traditions that never met.

[Berryman 2022] models the phrasing that avoids it: it distinguishes the poorly-attested
Greek-to-India story from the possibility that Islamic atomism was affected by classical Indian
debates, which "has been more extensively considered".

### Traditions that did not interact

Do not manufacture a connection to keep the narrative seamless. Long stretches of parallel,
non-interacting development are the historical truth of the material, and saying so is more
interesting than a fake through-line. The era-closing section (below) is where this gets handled
honestly: what these people shared was a moment in time, not a conversation.

---

## The unit of the book

`(judgement)` throughout this section. A recommended shape, to be confirmed in [`04-structure-and-apparatus.md`](04-structure-and-apparatus.md):

```
Part: an era, labelled by date range
  Opening: what changes in this era, and where the book cuts it and why
  Tradition run A: consecutive chapters, one per thinker or school
  Tradition run B: consecutive chapters
  Tradition run C: consecutive chapters
  Closing: the synchronic chapter (below)
```

### The synchronic era-closing chapter

Short, and one per era. It is the piece that earns the multi-tradition framing rather than merely
claiming it. It does three things:

1. States what was going on at the same time in each tradition, so simultaneity is visible.
2. Identifies genuine contacts in the era, with the channel named.
3. Draws the retrospective comparisons that are worth drawing, marked as the author's own.

Without this chapter, a braided book is just tradition blocks with extra headings.

### On "great men"

The chapter-per-philosopher unit quietly asserts that philosophy is made by individuals. Often it
was made by schools, commentators, translators and institutions, and some of the people doing it
have been written out. [Adamson 2014- ] deliberately covers the Hippocratic corpus, the Platonic
Academy, the role of women in ancient philosophy, and Jewish and Christian as well as Muslim
thinkers in the Islamic world, and [Rorty 1984] specifically faults doxography for neglecting those
who worked at the borders of philosophy, science, politics, economics, morality and medicine.

**Rule:** allow chapters whose subject is a school, a text, a translation movement or a debate, not
only a named individual. If every chapter is one man's name, the structure has made a claim the
history does not support.

---

## Failure modes of this format

These are the ones the chronological survey is specifically prone to. General ones are in
[`01-what-makes-it-good.md`](01-what-makes-it-good.md).

**F1. Doxography.** The list of names arrives pre-supplied by the format, and summarising each in
turn feels like the job. It is not. [Rorty 1984] names this genre and treats it as the one to avoid,
describing it as mummifying famous philosophers. Detection: if the chapters could be reordered
without loss, the book is a doxography with dates on it.

**F2. The escalator.** Treating the sequence as progress, with each thinker a step toward the
present and the present as the summit. Chronological order invites this because time runs one way
and the reader is at the end of it. Rorty's **Geistesgeschichte** is the legitimate relative of this
impulse: an account of how we came to ask the questions we now ask, which is what makes a canon
defensible [Rorty 1984]. The illegitimate version treats every past thinker as an imperfect draft of
us. The multi-tradition framing makes the escalator harder to sustain, which is one of its benefits:
several traditions running at once do not form one staircase.

**F3. Prolepsis.** "Aristotle anticipated Darwin." [Skinner 1969] names this the mythology of
prolepsis, and its defining error is conflating the significance an observer finds in a statement
with what the statement meant. A chronological book is unusually exposed, because it always knows
what came next and is always tempted to foreshadow.

**F4. Manufactured coherence and the doctrine myth.** Two more of the four mythologies in
[Skinner 1969]: imposing a tidy system on work that had none, and treating scattered remarks as a
settled position or blaming a writer for not answering a question they never asked. A survey chapter
wants a clean shape, and that want is the pressure.

**F5. The appendix problem.** Non-Western traditions handled as a section appended to the real book
rather than as part of its spine. This is the failure [Humphreys 2019] identifies in
[Grayling 2019], and it is structural rather than attitudinal: once a tradition is placed outside
the chronological frame, no amount of respectful writing inside that section fixes it. The braided
structure exists to prevent it.

**F6. The false through-line.** Inventing continuity between traditions to keep one narrative
running. This is the fourth mythology in [Skinner 1969], **parochialism**: falsely attributing
influence on the basis of random similarities between texts. The mirror image of F5, over-connection
rather than exclusion, and equally untrue.

**F7. Inherited canon as natural fact.** Taking the standard sequence of names as given. [Park 2013]
shows the canon was actively reshaped between 1780 and 1830, on grounds that included a racialised
philosophical anthropology, and that earlier histories had started elsewhere. Whatever the book's
final list, it should be a chosen list, and the choosing should be visible somewhere in the front or
back matter.

**F8. Scope claimed wider than delivered.** [Garfield & Van Norden 2016] make the point in its
sharpest form: work that covers only the European canon should say so in its name. Applied here, the
title and the table of contents have to agree.

---

## Checklist

Run against the outline, and again against each era once drafted.

**Structure**
- [ ] Is one of the three ordering approaches chosen deliberately, and stated somewhere in the plan?
- [ ] Are era headings date ranges, with period names kept local to each tradition?
- [ ] Is each era boundary justified in the text, including where it is arbitrary for some tradition?
- [ ] Does every era have a synchronic closing section?
- [ ] Is the per-tradition share of the book decided in advance, with the rule written down?
- [ ] Does the actual page count match that share? Measure it, do not estimate it.

**Continuity**
- [ ] Does each chapter name the problem inherited and the problem handed on?
- [ ] Would the book break if two chapters were swapped? If not, chronology is doing no work.
- [ ] Is every influence claim classified as documented transmission, parallel development, or the
      author's own comparison, and phrased accordingly?
- [ ] Is there any influence claim resting on resemblance alone?

**Context**
- [ ] Does every paragraph of context pay for itself in a later paragraph of philosophy?
- [ ] Has biography stayed inside its budget?

**Failure sweep**
- [ ] Escalator: does the book imply the present is the summit?
- [ ] Prolepsis: any thinker described as anticipating a later doctrine?
- [ ] Coherence: any thinker given more system than the texts support?
- [ ] Appendix: is any tradition outside the chronological spine?
- [ ] Great men: is any chapter's subject a school, a text or a debate rather than an individual?
- [ ] Does the title honestly describe the scope of the contents?
