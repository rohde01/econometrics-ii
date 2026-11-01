# Econometrics II

University of Copenhagen · MSc Economics · Spring 2026 · 7.5 ECTS  
Course code AØKA08007U · [Course description](https://kurser.ku.dk/course/a%C3%98ka08007u)

Time-series econometrics, covering likelihood analysis, dynamic and conditional models, misspecification testing, unit roots, cointegration and volatility models. The four assignments cover growth-at-risk, geopolitical risk as a predictor, a cointegrated VAR and ARCH effects in US excess returns.

## Contents

| Folder | Contents |
| --- | --- |
| `assignments/assignment-<n>/` | Assignments 1–4 with `assignmentN.tex` and PDF, the notebook, its data, tables and figures |
| `exam/` | `exam_final.tex`, the full exam answer |
| `notes/` | Peer feedback, improvement plans and my plans for the assignments and the exam. gitignored. |
| `materials/` | Course-provided material. |

## Topics

- Likelihood analysis
- Dynamic and conditional models
- Misspecification
- Non-stationarity and unit roots
- Cointegration
- ARCH and GARCH

## Tools

Python, uv, LaTeX

## Build

Each LaTeX source sits next to its PDF. Rebuild a PDF from its folder with:

```bash
tectonic -Z continue-on-errors assignment1.tex
```

`exam/exam_final.tex` reuses figures and tables from `assignments/assignment-1` and `assignment-3`, so build it from `exam/`. The `Assignment_N.xlsx` data files are the course's, but they stay next to the notebooks that read them.
