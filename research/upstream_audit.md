# Upstream audit

        - Paper anchor: DoWhy: An End-to-End Library for Causal Inference
        - Upstream repo: https://github.com/py-why/dowhy
        - Local clone: /Users/Rb/Documents/LLM based projects /sources/py-why__dowhy
        - Branch: main
        - Commit: 5466215696b4f07f1476c39889bd46cf33345ead
        - File count scanned: 505
        - Text files scanned: 285

        ## Strengths

        - Repository exposes a dedicated docs surface.
- Repository appears to include a test surface.
- Repository has GitHub Actions or another CI entry point.

        ## Findings

        - Missing a top-level README, which makes onboarding and evaluation harder.
- No container packaging signal detected, which makes demos and deployment less portable.
- Mixed filename conventions detected: PascalCase, kebab-case, snake_case.
- Open maintenance markers detected: TODO in 28 file(s).
- Large files that may benefit from decomposition: .github/workflows/repo-assist.lock.yml (1678 lines), dowhy/causal_identifier/auto_identifier.py (1163 lines), dowhy/datasets.py (1144 lines).

        ## Dominant file types

        - `.py`: 253
- `.rst`: 85
- `.ipynb`: 49
- `.png`: 48
- `.csv`: 18
- `.yml`: 14
- `<none>`: 11
- `.md`: 9

        ## Maintenance markers

        - TODO: tests/test_notebooks.py, dowhy/do_sampler.py, dowhy/causal_graph.py, dowhy/graph.py, dowhy/datasets.py, dowhy/causal_estimator.py, dowhy/causal_model.py, dowhy/interpreters/propensity_balance_interpreter.py
