# Plastic-skin evaluation protocol

Technical report: **A Reproducible Protocol for Evaluating Plastic-Skin Artifacts in Generative Portrait Images**.

Author (pen name): Miles Carter · Correspondence: support@bananaproai.app

This repository hosts the LaTeX source and PDF of a methods/protocol paper. It defines a taxonomy and human rating procedure for “plastic skin” artifacts in still, photorealistic adult portraits.

## Versions

| Version | What it is | Paths / assets |
|---------|------------|----------------|
| **v0.1** | Protocol-only note (taxonomy + human protocol; **no** quantitative experiment) | Root `main.tex` / `main.pdf`; Release [v0.1.0](https://github.com/mart-openclaw/plastic-skin-protocol/releases/tag/v0.1.0); Zenodo [10.5281/zenodo.22929445](https://doi.org/10.5281/zenodo.22929445) |
| **v0.2** | Protocol version 2 + **pilot dual-pass** experiment (headless VLM rater; real on-disk numbers only; not a generator leaderboard; VLM ≠ human) | Tree `v02/` (when present); Release [v0.2](https://github.com/mart-openclaw/plastic-skin-protocol/releases/tag/v0.2); Zenodo v2 [10.5281/zenodo.22936528](https://doi.org/10.5281/zenodo.22936528) |

v0.1 root files are retained. Soft product cite only: https://bananaproai.app (Resources / Appendix).

## Downloads (v0.2)

- PDF: https://github.com/mart-openclaw/plastic-skin-protocol/releases/download/v0.2/plastic-skin-protocol-v02.pdf
- Artifacts tarball: https://github.com/mart-openclaw/plastic-skin-protocol/releases/download/v0.2/plastic-skin-v02-artifacts.tar.gz
- Zenodo record: https://zenodo.org/records/22936528

## v0.2 tree (in-repo when present)

| Path | Description |
|------|-------------|
| `v02/paper/main.pdf` | Compiled v0.2 PDF |
| `v02/paper/main.tex` | v0.2 LaTeX source |
| `v02/CHANGELOG_v02.md` | Diff vs v0.1 |
| `v02/metrics/` | Covariates + per-stimulus metrics / RESULTS summaries |
| `v02/ratings/` | Dual-pass rating JSON |
| `v02/stimuli/` | Stimulus JPGs + build notes |
| `v02/scripts/` | Pilot run scripts |

If the full `v02/` tree is not on `main`, use the **v0.2** release assets above.

## Compile (v0.2)

```bash
cd v02/paper
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
```

## Suggested categories

- Primary: **cs.CV**
- Optional: **cs.AI**

## License

Text and figures: CC BY 4.0 (you may reuse with attribution).

Product URLs are resource pointers only, not performance claims.
