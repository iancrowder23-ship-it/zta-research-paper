# ZTA Research Paper — 2-Day Writing Plan (UPDATED)

> **Goal:** Complete an 8-page argumentative research paper on Zero Trust Architecture in 2 days.
> **Argument:** The perimeter security model is broken → ZTA is the necessary response → here's the evidence → here's an honest reckoning with the criticisms → here's where it's going.
> **Rule:** All writing is done by YOU. I help with structure, feedback, and proofreading only.

---

## The Argumentative Arc (Keep This in Mind While Writing)

```
I.   Introduction         → Hook + Thesis: the status quo is a liability
II.  The Broken Model     → Prosecution: here's the evidence it's failing
III. What Is ZTA?         → Introduce the solution (plain language first)
IV.  How ZTA Works        → Technical explanation of the solution
V.   ZTA in Practice      → Real-world proof the solution works
VI.  Benefits             → Affirmative case
VII. Counterarguments     → Steel-man the opposition, then rebut it
VIII.Future               → The trajectory — where this is going
IX.  Conclusion           → Land the thesis
```

Every section should feel like it's **building toward** the next one.

---

## How We Work Together

| What YOU do | What I do |
|---|---|
| Write all paragraphs in your own words | Review structure and flow |
| Take notes from sources in your own words | Give section-specific writing guidance |
| Make argument and evidence decisions | Proofread for grammar, clarity, tone |
| Fill in the `.tex` file | Fix LaTeX formatting / citation issues |

**Workflow per section:**
1. Read your source(s) for that section
2. Dump raw notes in your own words in the matching `/Notes/` file
3. Write paragraphs in the `.tex` file
4. Paste the section here and say "proofread this" — I give line-by-line feedback without rewriting

---

## DAY 1 — Research + Sections I–IV

### Morning Block (2–3 hrs) — Gather Your Sources
- [ ] Download/access all sources (see `/Sources/sources-list.md`)
- [ ] Skim each source, find relevant sections
- [ ] Take raw notes in your own words in the matching note files
- [ ] Minimum sources needed: **6–7**

### Afternoon Block (3–4 hrs) — Write Sections I–IV

| Section | File | Target | Key Job |
|---|---|---|---|
| Abstract | `notes-abstract.md` | ~150 words | Argue, don't just describe |
| I. Introduction | `notes-intro.md` | ~0.5 pg | Hook hard, state thesis clearly |
| II. Broken Status Quo | `notes-broken-model.md` | ~1.25 pg | Evidence-heavy prosecution of perimeter security |
| III. What Is ZTA? | `notes-what-is-zta.md` | ~1 pg | Plain → slightly technical; introduce the 3 principles |
| IV. How ZTA Works | `notes-how-it-works.md` | ~1.5 pg | Technical deep-dive; NIST model, components |

---

## DAY 2 — Finish Writing + Polish

### Morning Block (3–4 hrs) — Write Sections V–IX

| Section | File | Target | Key Job |
|---|---|---|---|
| V. In Practice | `notes-in-practice.md` | ~1 pg | Case studies as proof the argument works |
| VI. Benefits | `notes-benefits.md` | ~0.5 pg | Affirmative case; connect back to Section II problems |
| VII. Counterarguments | `notes-counterarguments.md` | ~0.75 pg | Steel-man criticism, then rebut each one |
| VIII. Future | `notes-future.md` | ~0.5 pg | Confident, forward-looking |
| IX. Conclusion | `notes-conclusion.md` | ~0.5 pg | Restate thesis, land it hard |

### Afternoon Block (2–3 hrs) — Polish + References
- [ ] Reread the full paper — does the argument build from section to section?
- [ ] Fill in all `\cite{}` commands in the `.tex` file
- [ ] Build `references.bib` from `/Sources/sources-list.md`
- [ ] Run `pdflatex` twice, verify PDF
- [ ] Final proofread — paste full paper here for review

---

## Sources to Find

| Key | Full Source | Where to Get It | Covers |
|---|---|---|---|
| `nist2020` | NIST SP 800-207 — Zero Trust Architecture | csrc.nist.gov (free PDF) | Sections III, IV |
| `kindervag2010` | Kindervag — No More Chewy Centers (Forrester) | Google Scholar | Sections II, III |
| `beyondcorp2014` | Ward & Beyer — BeyondCorp (USENIX) | research.google.com | Sections III, V |
| `eo14028` | Executive Order 14028 (2021) | federalregister.gov | Section V |
| `cisa2023` | CISA Zero Trust Maturity Model v2.0 | cisa.gov (free PDF) | Sections IV, V |
| `ibm2024` | IBM Cost of a Data Breach Report (latest year) | ibm.com/security | Section II |
| `source7` | IEEE/ACM peer-reviewed ZTA article | IEEE Xplore / ACM DL | Sections IV or VII |

---

## Word Count Budget

| Section | Pages | ~Words |
|---|---|---|
| Abstract | — | 150 |
| I. Introduction | 0.5 | 125 |
| II. Broken Status Quo | 1.25 | 310 |
| III. What Is ZTA? | 1.0 | 250 |
| IV. How ZTA Works | 1.5 | 375 |
| V. In Practice | 1.0 | 250 |
| VI. Benefits | 0.5 | 125 |
| VII. Counterarguments | 0.75 | 190 |
| VIII. Future | 0.5 | 125 |
| IX. Conclusion | 0.5 | 125 |
| **TOTAL** | **~8 pages** | **~2,025 words** |

---

## LaTeX Quick Reference

```latex
% Writing under a subsection (delete the comment, add your text below):
\subsection{Hook}
% Open with a concrete example...     ← DELETE this line
Your actual paragraph goes here.

% Citing inline:
\cite{nist2020}        % → (Rose et al., 2020) with apalike style
\citep{kindervag2010}  % → (Kindervag, 2010) — parenthetical
\citet{beyondcorp2014} % → Ward and Beyer (2014) — narrative

% Once .bib file is ready, uncomment in the .tex file:
\bibliography{references}
```

---

## Ask Me To...
- **Proofread** — paste a section and say "proofread this"
- **Check argument flow** — "does this section connect to the next?"
- **Format a .bib entry** — paste a source citation, I'll format it
- **Fix LaTeX errors** — paste terminal output, I'll diagnose
- **Final full-paper review** — paste everything at the end
