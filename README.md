# F1 Oracle — Moteur de décision explicable pour la conformité AML

**Objectif :** Vendre une technologie unique à 5 milliards de dollars.

## Structure

- `src_f1/` — Bibliothèques F1 (online_learn.f1, explain.f1, score.f1)
- `tests/` — Tests F1 (test_online_learn.f1, test_explain.f1, test_score.f1)
- `build/` — Runtime compilé (runtime.exe)
- `data/` — Datasets (Kaggle AML)
- `docs/` — Documentation (architecture, API, benchmark)
- `scripts/` — Scripts PowerShell (compiler.ps1, run_all.ps1)
- `results/` — Résultats de benchmark

## Phase 1 — Le noyau explicable

- `online_learn.f1` — Apprentissage en ligne (semaine 1)
- `explain.f1` — Explicabilité native (semaine 2)
- `score.f1` — Scoring des transactions (semaine 3)
- `test_oracle.f1` — Intégration (semaine 4)

## Critères de validation

- Précision ≥ 95%
- Faux positifs ≤ 0.5%
- 0 warning GCC
- Chaque prédiction explicable
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24061432.svg)](https://doi.org/10.5281/zenodo.24061432)
