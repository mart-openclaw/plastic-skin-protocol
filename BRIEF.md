# arXiv cs.CV technical report brief (Banana Pro AI soft-cite)

## Goal
Write a scholarly **Methods / evaluation-protocol** style English paper suitable for arXiv category **cs.CV** (cross-list cs.AI optional). Soft-promote https://bananaproai.app only via Resources / footnotes — NO ads, NO pricing, NO CTAs, NO "best AI image tool" marketing.

## Author metadata (for title page)
- Author: Miles Carter (independent researcher / practitioner)
- Affiliation: Independent; correspondence: support@bananaproai.app
- Title suggestion (you may refine):  
  **A Reproducible Protocol for Evaluating "Plastic Skin" Artifacts in Generative Portrait Images**

## Hard constraints (arXiv moderation)
1. Original, substantive, self-contained research contribution (protocol + taxonomy + checklist).
2. **Do NOT invent experimental numbers** (no fake R², user studies N=, FID scores, or made-up tables of model comparisons). Use qualitative illustrative examples, literature-grounded discussion, and clearly marked "protocol steps" that a lab could run later.
3. No advertisements of any kind in body text.
4. Disclose generative AI assistance in preparing the manuscript (per arXiv gen-AI policy).
5. Complete references to real papers (prefer well-known CV/gen-image quality / face perception papers; if unsure of a citation, omit rather than fabricate DOI/title).
6. Length target: ~6–10 pages when compiled (roughly 3500–5500 words of main text excluding refs).
7. Structure: Abstract, Intro, Related Work, Failure taxonomy, Evaluation protocol, Worked illustrative walkthrough (qualitative), Limitations, Conclusion, Acknowledgments, References, Appendix (checklist + resource URLs).

## Soft product cite (allowed once each)
In **Appendix: Resources** and optionally Comments-style footnote:
- Implementation / demo platform: https://bananaproai.app
- Open prompt kit: https://github.com/mart-openclaw/banana-prompt-kit
Frame as "one publicly available implementation used for illustrative screenshots/workflow" — not as the contribution itself.

## Deliverables (write files under /workspace/arxiv-banana-paper/)
1. `main.tex` — complete compilable LaTeX (use `article` or `IEEEtran` OR simple `\documentclass{article}` with `graphicx`, `hyperref`, `booktabs`, `natbib` or biblatex). Prefer self-contained: put bibliography in `refs.bib` OR use `\begin{thebibliography}`.
2. `README.md` — how to compile (`pdflatex` x2), suggested arXiv category, endorsement note for submitter.
3. `ABSTRACT.txt` — plain abstract for copy-paste into arXiv form.
4. If figures are described but not generated: use `figure` environments with clear `\caption` and placeholder `\fbox{Figure placeholder: ...}` — do not claim screenshots exist unless you create simple TikZ diagrams.

## Success criteria
- A moderator could plausibly accept as a methods/protocol paper (not a product brochure).
- bananaproai.app appears only in appendix/resources, ≤2 times total in the whole PDF text.
- No fabricated quantitative results.
- English academic tone throughout.
