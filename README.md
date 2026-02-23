# Causal Impact Estimation (Regression Adjustment + IV)

## Business Question
How do we estimate causal impact when treatment is not randomized and unobserved confounding may bias naive comparisons?

## Data
Customer-level dataset with outcomes, a treatment indicator, and observed covariates (Quarto/R workflow).

## Methods (What I did)
- **Naive estimate vs adjusted estimate**
- **Regression adjustment** to control for observed confounders
- **OVB demonstration** to show why missing variables bias estimates
- **Instrumental Variables (IV/2SLS)** to address endogeneity

## Deliverable
- `report.qmd`: full Quarto report with results + diagnostics

## Reproduce
Open `report.qmd` in RStudio → click **Render**  
or run: `quarto render`

## Keywords
Regression Adjustment, OVB, IV, 2SLS, causal inference
