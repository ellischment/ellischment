<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" width="100%" alt="Singular value decomposition A = U Σ Vᵀ drawn as three steps: a disk with a golden spiral is rotated, stretched and rotated again. The long axis is what a single confidence score reads; the squeezed axis is where errors can hide. Schematic, not data.">
</picture>

**Vasilisa Popova.** I study where a model's confidence and the truth come apart: LLM error detection, uncertainty quantification, evaluation tooling. Second-year student, Mathematics and Computer Science, Central University.

[ellischment.ru](https://ellischment.ru) · [ellischment.work@gmail.com](mailto:ellischment.work@gmail.com) · [По-русски](README.ru.md)

## Work

| Project | Question | Status |
|---|---|---|
| [**SGTA**](https://github.com/ellischment/sgta-research-preview) | Does the *stability* of an LLM's hidden state tell a confident error from a confident correct answer, where hidden-state geometry cannot? | Pre-registered protocol with thresholds and kill rules, hash-pinned and checked in CI. Code and tests. No results on real data yet. |
| [**umlip-curvature-uq**](https://github.com/ellischment/umlip-curvature-uq) | Can spread-based uncertainty detect systematic softening of phonon frequencies shared by several universal ML interatomic potentials? | Pipeline and tests. No results reported yet. |
| [**llm-trace-eval**](https://github.com/ellischment/llm-trace-eval) | What does an LLM eval look like through OpenTelemetry traces instead of a single accuracy number? | Small working scaffold, 50-example synthetic dataset, tests. Not a benchmark. |
| [**cu_final_ml_project**](https://github.com/ellischment/cu_final_ml_project) | Which artworks of the Art Institute of Chicago are likely to stay unseen, judging by metadata alone? | Course project, December 2025: CatBoost with SHAP analysis in one notebook. |

## How I work

- **Fix the test before the data.** SGTA fixes its hypotheses and thresholds first, and CI fails if the protocol changes without its hash.
- **Say what is not there.** Each repository lists what is unfinished or not implemented.
- **A failing call must not hide a run.** In llm-trace-eval a failed model call becomes an `ERROR` span and a wrong answer, and the run continues.

## Also

I build backends, automation and websites on commission in Python and Docker. Client work is private; see [ellischment.ru](https://ellischment.ru).
