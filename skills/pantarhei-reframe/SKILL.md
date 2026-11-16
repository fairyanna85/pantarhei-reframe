---
name: pantarhei-reframe
description: >-
  Sense-making and problem framing, for when the user does not yet know what the real problem is. Use when someone is confused, overwhelmed, stuck without knowing why, or vaguely dissatisfied; asks to make sense of a situation, untangle a mess, reframe something, get perspective or clarity, find what is really going on, or work out what question to ask. Runs the Lens Rotation: the problem as stated, four to six one-line reframes from named lenses (coaching and life questions from Ferriss, Robbins, Rohn and Bungay Stanier; reframing, whose problem is it, jobs to be done, iceberg, ladder of inference, what is in my control, problem or polarity), then one crisp problem statement with scope. Works for work, career, relationships and personal situations. Not for generating ideas (use pantarhei-brainstorm), diagnosing a defined problem (use pantarhei-solve), or choosing between options (use pantarhei-decide). Not for code or factual lookups.
---

# Panta Rhei Reframe — The Lens Rotation

Most bad solutions answer the wrong problem well. This skill does not solve anything. It turns a
fuzzy situation into a problem statement worth solving, and shows the user two or three ways of
seeing it they had not considered.

Load before starting:
- `references/catalog.json`: lenses, question banks and methods.
- `references/models.json`: framing models from the shared library (map vs territory, relativity,
  framing, inversion, first principles, local maxima, asymmetric warfare, tendency to act).
- `references/shared-rules.md`.

## 1. Take the problem as stated

Quote the user's own words in one line as **v0**. Do not improve it yet.

If the message is emotionally charged, apply `frame.affect-labeling` first: name the feeling in
one precise word, as an observation, and move on. Do not counsel.

## 2. Read the domain

State in one line which kind of situation this is (`frame.sense-domains`): **clear** (known answer
exists), **complicated** (expert analysis will find it), **complex** (only probing and learning will
show it), **chaotic** (stabilise first). The reading sets what the handoff will be.

## 3. Rotate the lenses

Choose four to six lenses that are most likely to *change* the problem statement, not decorate it.
Selection guide:

| Situation signal | Lenses to try first |
|---|---|
| Personal, career, life direction | frame.ferriss-questions, frame.coaching-questions, frame.control-map, frame.hamming-question |
| Low agency, complaint, "why me" | frame.robbins-questions, frame.control-map, frame.affect-labeling |
| Influences, environment, people around | frame.rohn-questions, frame.stakeholder-map, frame.humble-inquiry |
| Organisation, team, recurring friction | frame.iceberg, frame.lights-on, frame.polarity, frame.stakeholder-map |
| Product, customer, market | frame.jobs-to-be-done, frame.how-might-we, frame.reframing-canvas |
| Conflict, assumptions about others | frame.ladder-of-inference, frame.humble-inquiry, frame.sensemaking |
| Messy, many interlocking issues | frame.wicked-problems, frame.iceberg, frame.abstraction-ladder |
| Going in circles | mm.inversion, mm.first-principles-thinking, mm.global-and-local-maxima, frame.question-burst |

Output each as one line: **lens name (origin)** → the problem restated through it.

```
v0  "My team keeps missing deadlines and I'm exhausted."
──────────────────────────────────────────────────────────────
Iceberg (systems thinking)        → The misses are a pattern; what structure produces them?
Whose problem? (Gause & Weinberg) → Who set the deadlines, and do they experience the misses as a problem?
Polarity (Johnson)                → Speed vs. quality is being treated as solvable; it is a tension to manage.
Control map (Epictetus; Covey)    → I control scope and staffing requests; I do not control the launch date.
Ferriss questions                 → What would this look like if delivery were easy?
```

Mark the one or two reframes most likely to be **live** (they change what gets worked on) with ●.

## 4. Write v1

One paragraph, no more:
- **Problem:** one sentence, specific enough that someone could tell when it is solved.
- **Whose:** who owns it.
- **In scope / out of scope:** one line each.
- **The question to carry forward:** one question, written for the next stage.

## 5. Hand off

Pick from the domain reading and v1, state it, stop:
- Options are needed → "Next step: generate options for v1 (Panta Rhei Brainstorm does this)."
- The problem is defined and needs structure or diagnosis → "Next step: structure and diagnose v1 (Panta Rhei Solve does this)."
- Options already exist and the problem was only obscuring them → "Next step: choose between the options now visible (Panta Rhei Decide does this)."

## Rules specific to Frame

- **Reframes are not solutions.** Never append advice to a reframe.
- **Question banks are paraphrased.** Use our wording from the catalog; credit the author; never
  reproduce the original list.
- **Practitioner sources are prompts.** Ferriss, Robbins, Rohn and Bungay Stanier are coaching
  practice, not research. They earn their place by producing a better question, which is all they
  claim.
- **Personal situations:** keep the user's own words prominent; do not psychologise or diagnose.
  If distress is serious, step out of the method and respond to the person.
