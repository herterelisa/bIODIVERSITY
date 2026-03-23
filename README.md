# Biodiversity Patterns in New York Counties


An end-to-end data science analysis of species richness and rarity across New York counties, combining EDA, statistical inference, and predictive modeling.

---

## Central question
> Do counties with higher total species richness also support more rare or at-risk species, and can we predict rare species counts from basic ecological variables?

---

## Project phases
`01 Data cleaning` → `02 EDA` → `03 Bootstrap inference` → `04 Regression modeling` → `05 Cross-val evaluation`

---

## Techniques
| Technique | Purpose |
|---|---|
| Data cleaning | Prepare species-level county dataset |
| Exploratory analysis | Richness and rarity patterns across counties |
| Bootstrapping | Statistical inference on ecological hypotheses |
| Linear regression | Estimate rare species from richness variables |
| Ridge regression | Regularized model to reduce overfitting |
| Cross-validation + RMSE | Model evaluation |

---

## Key variables
- **Target:** rare species count per county
- **Main predictor:** total species richness
- **Unit of analysis:** New York county

## Stack
`pandas` `numpy` `matplotlib` `seaborn` `scikit-learn`

> Inference uses bootstrapping to make minimal assumptions about the distribution of species data across counties.
