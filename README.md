# Coal Quality Clustering (Looker Studio)

Clustering of coal samples into three categories from their quality and shape measurements, with the results presented in a Looker Studio dashboard. Project for the postgraduate specialization in Data Analytics (2023).

## Problem

A database with quality and shape measurements of coal (ash, thickness, moisture, volatile matter, total carbon and calorific value). The hypothesis: the samples can be grouped into three categories.

## Method

- Statistical analysis of the variables.
- Model trained on ash and thickness.
- Comparison of three dimensionality-reduction techniques: **PCA, t-SNE and UMAP**. UMAP produced the clearest separation into categories.

## Files

| File | Content |
|---|---|
| `1_Report_Clustering and categorization.pdf` | Looker Studio dashboard: problem, statistical analysis, model and results |

**Tools:** Python (pandas, seaborn, pylab, scikit-learn, UMAP), Looker Studio.

---

### En español

Agrupamiento de muestras de carbón en tres categorías a partir de sus mediciones de calidad y forma (cenizas, espesor, humedad, materia volátil, carbono total y poder calorífico). Se compararon PCA, t-SNE y UMAP, y UMAP dio la mejor categorización. Los resultados se presentan en un tablero de Looker Studio. Trabajo de la Especialización en Analítica de Datos (2023).
