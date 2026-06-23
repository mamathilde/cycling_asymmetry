# Analysis of the Effects of Pedal Force Asymmetry (PFA) on Efficiency and Force Effectiveness in Cycling

## Study Context

We had 15 subjects for this study.

We asked participants to bike with 4 pedal force asymmetry conditions (0%, 10%, 20%, 30%) by asking them to match a pedal force target displayed on a monitor in front of them during 5 min.

We measured pedal force and metabolic data.

## Repository Structure

```text
├── code.qmd      # Main analysis script
├── data/         # Processed data files (one per subject)
└── figures/      # Figures included in the manuscript
```

## Data

This folder contains processed data files (one per subject), computed from force and metabolic recordings collected during the study.

# Dataset Column Headers

Below is a description of the column headers in the dataset and their units, where applicable. Values are averages of two 30-s trials.

- **Condition**: Trial condition (`1p5` = 1.5 W/kg, `2p5` = 2.5 W/kg, `Noasym` = no-feedback trial).
- **SI_pow (%)**: Symmetry index calculated from mechanical power output.
- **SI_force (%)**: Symmetry index calculated from pedal force.
- **Ft_mean (N)**: Mean tangential force.
- **Fr_mean (N)**: Mean radial force.
- **Tot_power (W)**: Measured mechanical power output.
- **Cadence (rpm)**: Pedaling cadence.
- **RF_norm (N)**: Right force norm.
- **LF_norm (N)**: Left force norm.
- **VO2_Normalized (mL/kg/min)**: Oxygen consumption normalized to body mass.
- **Gross_Metabolic_power (W)**: Gross metabolic power.
- **Net_Metabolic_power (W)**: Net metabolic power.
- **Normalized_Net_Metabolic_Power (W/kg)**: Net metabolic power normalized to body mass.
- **RER**: Respiratory exchange ratio.
- **FE (%)**: Force effectiveness.
- **Efficiency (%)**: Net efficiency.
- **Percents**: Asymmetry target.
- **pow_condition**: Mechanical power output condition (`1p5` = 1.5 W/kg, `2p5` = 2.5 W/kg).
- **SI_force_base**: Symmetry index minus the symmetry index measured during the baseline condition (`Noasym`).






Raw force and metabolic data are not included — contact the author to request access.



## How to Run

This project uses [Quarto](https://quarto.org). 

You can run the analysis in RStudio (version used: 2026.05.0+218) by opening `code.qmd` and clicking *Render*, or by running all chunks in order.

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
