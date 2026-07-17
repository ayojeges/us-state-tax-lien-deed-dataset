# U.S. State Tax Lien & Tax Deed Dataset (2026)

A sourced, machine-readable dataset classifying **all 50 U.S. states** by their property-tax-sale
system — **tax lien** vs **tax deed** vs **redeemable deed** — with statutory interest/penalty
rates, redemption periods, and the **primary statute + official source** for every row.

Each state is also scored 0–100 on nine investing dimensions (effective yield, penalty
structure, redemption speed, auction access, competition, capital entry, process safety, legal
stability, OTC availability) and given a **composite score**.

> **Live, always-current version & full methodology:** https://taxliensimple.com/dataset
> Per-state guides (sourced to statute): https://taxliensimple.com/guides
> State-vs-state comparisons: https://taxliensimple.com/compare
> Free 52-page due-diligence playbook (PDF): https://taxliensimple.com/tax-sale-due-diligence-playbook

## Why this exists
Most "best states for tax lien investing" content misclassifies states (e.g. labeling Florida a
tax-*deed* state when it sells tax-lien *certificates* first under Fla. Stat. §197.432). This
dataset fixes that with a statute cited on every row, so analysts, writers, and tools can rely
on it instead of rebuilding it.

## Files
- [`data/us-state-tax-lien-deed-2026.csv`](data/us-state-tax-lien-deed-2026.csv) — 50 states × 19 columns
- [`data/us-state-tax-lien-deed-2026.json`](data/us-state-tax-lien-deed-2026.json) — same, structured

## Columns
`slug, state, system, investor_accessible, max_rate, penalty_or_interest, redemption_period,
statute, official_source` + 9 scored dimensions + `composite_score`.

## License & attribution
**CC-BY 4.0** — free to use with attribution to **TaxLienSimple** (https://taxliensimple.com).
Also on [Kaggle](https://www.kaggle.com/datasets/taxliensimple/us-state-tax-lien-deed-2026).

## Citation
> TaxLienSimple (2026). *U.S. State Tax Lien & Tax Deed Dataset.* https://taxliensimple.com/dataset

## Cite this dataset
**DOI: [10.5281/zenodo.21185506](https://doi.org/10.5281/zenodo.21185506)**

Also available on: [Zenodo](https://zenodo.org/record/21185506) · [Hugging Face](https://huggingface.co/datasets/ayojeg/us-state-tax-lien-deed-2026) · [Kaggle](https://www.kaggle.com/datasets/taxliensimple/us-state-tax-lien-deed-2026) · [GitHub](https://github.com/ayojeges/us-state-tax-lien-deed-dataset) — canonical source: https://taxliensimple.com/dataset
