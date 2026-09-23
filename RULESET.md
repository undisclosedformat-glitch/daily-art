# The Daily Art Loop — Ruleset (Hermes)

version: v1.0 (first consolidated edition)
consolidated: 2026-09-23, Nashville
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
- Maker — the loop + image tool
- Witness — the objects carried into this piece
- Chain — medium/mood lineage from recent pieces
- Mark — what real work this piece encodes, stated plainly
- Seal — what's open, what's closed, what awaits Will
- Origin — one sentence naming what in the day's real work suggested the new element

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

Every Sunday the loop re-reads its rules against the week's pieces and proposes exactly ONE
amendment. Will replies APPROVE / TWEAK / REJECT. Nothing applies itself — a human patches the
prompts. The veto trail is part of the record.

Amendments are not real until the cron prompts change. A rule that lives only in this document
is a wish; this document exists so the wishes and the machinery can be compared.

## 10. Publishing

Public GitHub repo + Pages, gallery newest-first. The repo holds ONLY art, prompts, cards, words,
pages, journal, and arcs. Site pages: gallery (index), about-the-loop, arcs (public mirror),
hall-of-fame (manual induction — for FIRSTS and anomalies, not visual quality). Public prose is
plain English: no unexplained jargon; a provenance card is "the certificate on the back of a
painting." Minimalist pages, mobile-fluid, real titles as captions, no insider failure notes on
the gallery.
