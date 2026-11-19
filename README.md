# P PREETI | Mathematics & Formal Verification Practice

An educational portfolio featuring introductory **Lean 4**, **Coq/Rocq**, and **Python** mathematical programming.

## Contents
- `lean/BasicProofs.lean`: elementary arithmetic and propositional logic theorems.
- `coq/BasicProofs.v`: corresponding proofs in Coq/Rocq.
- `python/number_theory.py`: primality, coprimality and prime enumeration.
- `tests/test_number_theory.py`: automated Python tests.

## Run
```bash
python python/number_theory.py
python -m pytest -q tests/
```

For Lean 4, install Lean via elan and run `lean lean/BasicProofs.lean`.
For Coq/Rocq, install Coq and run `coqc coq/BasicProofs.v`.

## Verification status
Python tests were run in the preparation environment; see `RESULTS.md`.
Lean and Coq examples are **not yet compiler-verified** in this environment. Run the commands above and resolve any version-specific issues before describing them as verified.

## Attribution
AI-assisted educational starter code, intended for personal study and further original development. This repository does not claim prior professional proof-assistant experience.
