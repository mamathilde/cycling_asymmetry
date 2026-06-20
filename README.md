# Analysis of the Effects of Pedal Force Asymmetry (PFA) on Efficiency and Force Effectiveness in Cycling

## Study Context

We had 15 subjects for this study.

We asked participants to bike with 4 pedal force asymmetry conditions (0%, 10%, 20%, 30%) by asking them to match a pedal force target displayed on a monitor in front of them during 5 min.

We measured pedal force and metabolic data.

## Repository Structure

```text
├── code.qmd      # Main analysis script
├── code.html     # Rendered output (no R needed to view)
├── data/         # Processed data files (one per subject)
└── figures/      # Figures included in the manuscript
```

## Data

This folder contains processed data files (one per subject), computed from force and metabolic recordings collected during the study.

Raw force and metabolic data are not included — contact the author to request access.

## How to Run

This project uses [Quarto](https://quarto.org). You can either:

- View the results directly by opening `code_github.html` in a browser.
- Re-run the analysis in RStudio (version used: 2026.05.0+218) by opening `code.qmd` and clicking *Render*, or by running all chunks in order.

**R version:** 4.3.2

**Key packages:** `lme4`, `lmerTest`, `ggeffects`, `tidyverse`, `performance`

## Figures

Figures included in the manuscript are available in the `figures/` folder.

## Contact

**Mathilde MONTEL**  
ENS Rennes M2S Laboratory / University of Colorado Boulder  
montelmathilde@gmail.com

**Alena M. GRABOWSKI**  
University of Colorado Boulder  
alenagrabowski@gmail.com
