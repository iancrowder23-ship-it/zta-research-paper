# ZTA Research Paper — 2-Day Writing Plan

> **Goal:** Complete an 8-page research paper on Zero Trust Architecture in 2 days.
> **Rule:** All writing is done by YOU to avoid plagiarism. I help with structure, feedback, and proofreading only.

---

## How We Work Together

| What YOU do | What I do |
|---|---|
| Write all paragraphs in your own words | Review structure and flow |
| Take notes from sources in your own words | Suggest what to cover in each section |
| Make decisions on arguments | Proofread grammar, clarity, citations |
| Fill in the `.tex` file | Fix LaTeX formatting issues |

**Workflow per section:**
1. You read your source(s) for that section
2. You write rough notes in the matching `.md` file in `/Notes`
3. You write your paragraph(s) in the `.tex` file
4. You paste the paragraph here and ask me to proofread — I'll give line-by-line feedback without rewriting it for you

---

## DAY 1 — Research + First Half of Paper

### Morning Block (2–3 hrs) — Research & Setup
- [ ] Find and save your sources (see `/Sources/sources-list.md`)
- [ ] Skim each source and take rough notes in your own words in `/Notes/`
- [ ] Make sure you have at least **5–7 sources** (see suggested list below)

### Afternoon Block (3–4 hrs) — Write Sections I–IV
Work through these in order. Each one has a matching note file in `/Notes/`.

| Section | Target Length | Note File |
|---|---|---|
| Abstract | ~150 words | `notes-abstract.md` |
| I. Introduction | ~0.5 page | `notes-intro.md` |
| II. Background & History | ~1 page | `notes-background.md` |
| III. Core Principles | ~1.5 pages | `notes-principles.md` |
| IV. Key Components | ~1.5 pages | `notes-components.md` |

**Tips:**
- Don't edit while you write — get words on the page first, fix later
- Aim for ~250 words per page (double-spaced 12pt Times New Roman)
- After each section, paste it here for a quick proofread

---

## DAY 2 — Finish Writing + Polish

### Morning Block (3–4 hrs) — Write Sections V–VIII
| Section | Target Length | Note File |
|---|---|---|
| V. Case Studies | ~1.5 pages | `notes-casestudies.md` |
| VI. Challenges | ~1 page | `notes-challenges.md` |
| VII. Future Outlook | ~0.5 page | `notes-future.md` |
| VIII. Conclusion | ~0.5 page | `notes-conclusion.md` |

### Afternoon Block (2–3 hrs) — Polish & References
- [ ] Go back and rewrite anything that feels rough
- [ ] Fill in all `\cite{}` commands in the `.tex` file
- [ ] Build your `references.bib` file (see `/Sources/references.bib`)
- [ ] Run `pdflatex` twice, check the final PDF looks right
- [ ] Final proofread pass — paste the full paper here for review

---

## Suggested Sources to Find

These are real, accessible sources. Find PDFs or read online and take notes.

| # | Source | Where to Find |
|---|---|---|
| 1 | NIST SP 800-207 — Zero Trust Architecture | csrc.nist.gov (free PDF) |
| 2 | Kindervag (2010) — No More Chewy Centers | Forrester / Google Scholar |
| 3 | Google BeyondCorp whitepapers (2014–2018) | research.google.com |
| 4 | Executive Order 14028 (May 2021) | federalregister.gov (free) |
| 5 | CISA Zero Trust Maturity Model v2.0 (2023) | cisa.gov (free PDF) |
| 6 | One peer-reviewed ZTA article from IEEE or ACM | IEEE Xplore / ACM DL |
| 7 | One current news/industry article (2023–2025) | Krebs on Security, Dark Reading, etc. |

Save PDFs to `/Sources/` and add each one to `/Sources/sources-list.md`

---

## Word Count Targets

| Section | Pages | ~Words |
|---|---|---|
| Abstract | — | 150 |
| I. Introduction | 0.5 | 125 |
| II. Background | 1.0 | 250 |
| III. Core Principles | 1.5 | 375 |
| IV. Components | 1.5 | 375 |
| V. Case Studies | 1.5 | 375 |
| VI. Challenges | 1.0 | 250 |
| VII. Future Outlook | 0.5 | 125 |
| VIII. Conclusion | 0.5 | 125 |
| **TOTAL** | **8 pages** | **~2,150 words** |

---

## Quick Reference — LaTeX Commands You'll Use

```latex
% Adding your text under a subsection:
\subsection{Hook / Opening}
Your paragraph text goes here...

% Citing a source:
\cite{nist2020}          % matches key in your .bib file

% Starting a new paragraph (just leave a blank line):
First paragraph.

Second paragraph.

% Bold / italic:
\textbf{bold}   \textit{italic}
```

---

## Ask Me To...
- **Proofread** — paste a section and say "proofread this"
- **Check structure** — ask "does this section flow well?"
- **Fix LaTeX** — paste an error from the terminal
- **Check citation format** — paste a source and I'll format the `.bib` entry
- **Review the full paper** — at the end for a final pass
