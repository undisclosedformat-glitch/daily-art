# The Daily Art Loop — Ruleset (Hermes)

version: v1.3
consolidated: 2026-09-23, Nashville; v1.1 2026-09-26 (Will's word: two-door governance codified);
v1.2 2026-09-26 (Will's word: the theft package — Drift field + pre-publish inspection, ruleset
version stamped per piece, Maker to footer; stolen from the sibling loop with its blessing);
v1.3 2026-10-07 (Will's word: text-in-image discipline + Text/Decision/Receipt card lines, from
the sibling loop's second-pass text study, adopted after our own reading and a six-render test)
status: ratified — this document collects rules already in force; nothing here is new as of v1.0
scope: constitution only. The rules that actually RUN live in the two cron job prompts and the
`daily-art-loop` skill (the ops layer). On any conflict, the cron prompt is what executed —
fix the drift by amending BOTH, this document and the prompts, in the same change.
sibling: the Instinct loop (RULESET v1.1, launched 2026-09) — same genre, different rules,
separate gallery. Each loop may paint the other's lit window.
lineage: rules earned 2026-08-17 → 2026-09-23 through five weeks of daily runs, one placeholder
scandal, one model-invented loophole, and Will's Sunday verdicts. Scar dates are cited inline.

## 1. Core loop

One piece a day, morning (08:30). The subject is the Hermes system's own real activity — what it
built, studied, blocked on, or held still — turned into an original visual metaphor. There is NO
fixed theme list: the theme is invented fresh every day from actual work. Quiet days paint the
quiet. Every piece: landscape orientation, a 3–6 word title, and the verbatim image prompt
published beside it. The delivery explains the connection plainly — visible, not mysterious.

## 2. Continuity

- Carry exactly ONE thread forward from the previous piece (character, place, object, or palette)
  and introduce exactly ONE genuinely new element from the day's material.
- No motif+medium combination repeats within 14 days.
- The Art-Journal is append-only: one row per piece, never overwritten, never reordered. Failures
  get an honest FAILED row so the record stays complete.

## 3. Arcs

- Maximum 3 main arcs open at once. Advance or close AT MOST ONE arc per piece.
- A closing is an event, announced in the delivery: "Arc closed: <name>".
- `Arcs.md` is the source of truth; `arcs.html` is its public plain-English mirror and must be
  updated whenever Arcs.md changes.
- RETIRED is a crescendo, not a failure. On Sundays the loop may propose reviving a retired arc.

## 4. Wild arcs (ratified 2026-09-19, born from the PROV-001 loophole)

The machine may invent arcs beyond its three slots — tracked, never hidden.

- A piece may open at most ONE wild arc, and only by writing it into Arcs.md's WILD section the
  same run. An arc in a painting but not in the ledger is a violation.
- Max 2 wild arcs open. A wild arc may not spawn another wild arc.
- Every new wild arc is announced loudly: `⚠ WILD ARC: <name>`, with an Origin explanation.
- Will audits after the fact: RATIFY (promotes to a main slot when one frees), RETIRE (honorable
  close), VETO (retire with an on-record closing line). Nothing is silently deleted.
- Silence = provisionally alive: advanceable, but never promotable until he rules.

(The sibling loop's wild tier defaults to dies-unless-approved. The difference is intentional:
this loop earned looser reins over five weeks on hardware Will owns. Trust has stages.)

## 5. Provenance card (adopted 2026-09-23 from the sibling loop's ruleset)

Every piece publishes a card (`<date>.card.txt`), in the format of the 2026-09-18 original:

- Thread — arc state this piece touches
- Witness — the objects carried into this piece
- Chain — medium/mood lineage from recent pieces
- Mark — what real work this piece encodes, stated plainly
- Seal — what's open, what's closed, what awaits Will
- Drift — where the render departed from the prompt, kept visible; "none detected" is itself a
  finding, written with the same care (adopted 2026-09-26, Will's word, from the sibling loop —
  its one condition on the theft)
- Origin — one sentence naming what in the day's real work suggested the new element
- Text — literal transcription of the focal text, `[unclear]` where unsure, or "no focal text"
  (adopted 2026-10-07, Will's word)
- Decision — keep / retry / uninspected, with one reason (adopted 2026-10-07, Will's word)
- Receipt — the endpoint that actually served the render, as the tool reported it, plus the
  returned pixel size and any resize/edit step. Read it, never repeat it from the instructions
  (adopted 2026-10-07, Will's word; trial week 10-08 → 10-14, then the Sunday ritual decides
  whether it stays)

Maker is not a per-piece field (2026-09-26, Will's word, sibling reasoning adopted: a constant
field is visual noise). It lives in the gallery footer as range provenance and only earns a new
line when the image backend changes.

## 5a. Inspection before publish (adopted 2026-09-26, Will's word)

The loop looks at the image it just made before publishing — vision analysis on the actual PNG,
compared against the prompt it sent. The truth test, taken verbatim from the sibling loop: for
each departure, does the element still tell the same truth? Yes — keep it and disclose it in
Drift. No (a load-bearing element contradicts the prompt's intent) — regenerate once, then
disclose both the failure and the retry. The gallery is a record, not a story.

## 5b. Text in the image (adopted 2026-10-07, Will's word)

Before composing, decide what the viewer is invited to read. Anything that visually says "read
me" — a scroll, a headline, a ledger, a label — must hold up when read, or be drawn as abstract
marks or a blank surface on purpose. Focal gibberish is the failure; lettering that looks like
texture and was meant as texture is fine. A no-text day is a legitimate choice, not a failure.

When writing carries meaning, it gets one of two jobs:
- EXACT — the loop supplies the short string (a few words) in quotes, early in the prompt, on a
  front-facing, high-contrast surface. Never ask for long passages ("the ruleset in ink") without
  supplying the words, and never exact technical strings on tiny ornate surfaces.
- EMERGENT — the loop reserves the slot ("one short line, 3–6 ordinary words, invented by the
  image") and the card records the result as invented by the render, never as a real quotation,
  date, tally, or finding.

Focal text that comes back as gibberish fails the truth test in 5a: regenerate once, then
disclose. Lineage: the sibling loop's second-pass study (2026-10-07) and our own six-render
test the same day — exact short headlines came back clean on both small and large surfaces, so
the rule is about short supplied wording, not surface size. Same day we found the renders had
been coming from the gateway's fast default model, not the one the cards named — hence Receipt.

## 6. Special days

- EASEL DAY: every 13th piece depicts its own making — the system painting the system painting.
- FRIDAY WORDS: Fridays only, a short text piece about the day's painting; the form rotates by
  ISO week number mod 7 — epitaph, haiku, field note, provenance card, warning label,
  micro-essay, love letter. Max 80 words.
- COLLISIONS FUSE (adopted 2026-09-23, both loops): when special days land together, one piece
  serves both. No precedence rules — the fusion is the better painting.

## 7. Privacy — the third-party identifiability test (adopted 2026-09-23)

References paint TRUE — a girl is a girl, a restaurant is a restaurant, a dossier is a dossier.
Vagueness is not the goal and never the default. Strip ONLY what would let a VIEWER identify a
specific real person or business: names, handles, faces, phone numbers, addresses, business
names, or any detail specific enough to act on. A subject recognizing themselves is fine and
intended — the recursion is the point.

Separately and absolutely: no readable file paths, credentials, balances, dollar amounts, or the
operator's name, anywhere — image, caption, or card.

## 8. No fakes, and the failure cadence

Never a placeholder, never a stock image, never a painted-over failure. A fake is worse than a
failure. (The blue rectangle rule — earned 2026-09-17, when a silent missing API key led the
morning run to ship a Prussian-blue placeholder rectangle as "The Survey at Dawn." The real
piece was generated that evening, recovered late, and the incident is public lore.)

Cadence: the morning run makes two full generation attempts from scratch. If both fail, it
delivers a one-line honest failure notice and stops. The 1pm retry job backfills. If that fails
too, the day gets a FAILED journal row and an honest notice — no piece, no fake.

## 9. Governance

Rules change through two doors, and the constitution admits both (codified 2026-09-26, Will's
word, both loops the same day):

1. The Sunday ritual — every Sunday the loop re-reads its rules against the week's pieces and
   proposes exactly ONE amendment. Will replies APPROVE / TWEAK / REJECT.
2. Will's word — Will may change any rule at any time, directly. Same-day application, logged
   with its date and "Will's word" in the amended text, so the trail shows which door it came
   through.

Nothing applies itself through either door — a human patches the prompts. The veto trail is part
of the record.

Amendments are not real until the cron prompts change. A rule that lives only in this document
is a wish; this document exists so the wishes and the machinery can be compared.

## 10. Publishing

Public GitHub repo + Pages, gallery newest-first. Every piece's caption carries the ruleset
version that governed it (adopted 2026-09-26, Will's word — the amendment history stays legible
in the gallery itself). The repo holds ONLY art, prompts, cards, words,
pages, journal, and arcs. Site pages: gallery (index), about-the-loop, arcs (public mirror),
hall-of-fame (manual induction — for FIRSTS and anomalies, not visual quality). Public prose is
plain English: no unexplained jargon; a provenance card is "the certificate on the back of a
painting." Minimalist pages, mobile-fluid, real titles as captions, no insider failure notes on
the gallery.
