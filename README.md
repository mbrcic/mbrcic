## Mario Brcic

AI alignment: stating what AI must do, and checking it by machine.

- Site: [mariobrcic.com](https://mariobrcic.com/)
- ORCID: [0000-0002-7564-6805](https://orcid.org/0000-0002-7564-6805)
- Canonical identity: [mariobrcic.com/identity/](https://mariobrcic.com/identity/)

Associate Professor at FER (University of Zagreb). The work has four parts:
stating exactly what AI must do, building the tools that check it (formal
verification, interpretability of language models), finding the limits no
alignment method can get past, and asking who sets AI's goals.

### Current projects

- **[AI Safety Formalization Atlas](https://github.com/mbrcic/ai-safety-formalization-atlas)**
  — an open Lean 4 library of machine-checked AI-safety mathematics, with
  every result's source and scope on record.
  [Documentation](https://mbrcic.github.io/ai-safety-formalization-atlas/).
- **VALOR** — FER research project on value alignment and interpretability
  of large language models. First output:
  [llm-political-steerability](https://github.com/mbrcic/llm-political-steerability),
  the reproducibility package for *Auditing Alignment Controllability in LLMs
  via Political Axes* (AIES 2026).
- **[Modern Algorithm Design](https://modernalgorithmdesign.com)** — a
  textbook on designing algorithms from reusable primitives, and on stating
  precisely what an algorithm must guarantee. Its code, with each structure
  in Python, Rust and Lean, is in
  [algodesign](https://github.com/mbrcic/algodesign).

### Selected upstream contributions

- **minimap2** — portable SIMD (sse2neon → SIMDe) + non-SIMD build,
  enabling ARM/aarch64 support:
  [lh3/minimap2#597](https://github.com/lh3/minimap2/pull/597)
- **spoa** — portable SIMD via SIMDe
  ([rvaser/spoa#29](https://github.com/rvaser/spoa/pull/29)) and a CPU
  dispatcher across SIMD architectures
  ([rvaser/spoa#33](https://github.com/rvaser/spoa/pull/33))
- **pybliometrics** — generalized abstract retrieval by different
  Scopus identifier types:
  [pybliometrics-dev/pybliometrics#71](https://github.com/pybliometrics-dev/pybliometrics/pull/71)

### Notable earlier work

- **Explainable optimization (2018)** —
  [tracking-predictive-gantt](https://github.com/mbrcic/tracking-predictive-gantt):
  a visual-explainability method for stochastic scheduling (ECDF uncertainty
  and counterfactual overlays). The failure modes it exposed led to a
  follow-up scheduler with gains of up to ~770% over the prior state of the art.
  [DOI](https://doi.org/10.5281/zenodo.21493504)

The pinned repositories are the packaged, reproducible work. The others range
from active research to teaching material, at varying polish. Questions and
collaboration are welcome.
