
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
