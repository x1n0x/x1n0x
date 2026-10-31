# Vladislav

**Data analyst — Python, pandas, applied machine learning.** Based in Almaty, Kazakhstan.

I build small, complete analytical projects and write up what they actually show,
including when the answer is "this data cannot support that conclusion". Most of
what is here is end-to-end: data collection, cleaning, modelling, and a README
that states the method and its limits rather than only the best metric.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/SQL-4169E1?style=flat&logo=postgresql&logoColor=white)

---

## Selected work

**[Planetary-Ocean-Simulator](https://github.com/x1n0x/Planetary-Ocean-Simulator)** — Interactive water-world simulator  
Full-sphere shallow-water ocean physics solved with Dedalus v3 and rendered on a
CesiumJS globe. Drag a moon, change rotation rate, watch tides and currents
respond. FastAPI backend, React/TypeScript front end, zarr data contract, live
anomaly detection.  
`Python` `TypeScript` `FastAPI` `React` `WebGL`

**[WC-2026-Prediction](https://github.com/x1n0x/WC-2026-Prediction)** — World Cup 2026 match and title model  
Poisson and LightGBM models producing W/D/L probabilities and tournament odds,
with a bilingual stadium-style dashboard.  
[Live dashboard](https://x1n0x.github.io/WC-2026-Prediction/) · `LightGBM` `scikit-learn` `Poisson regression`

**[almaty-springs](https://github.com/x1n0x/almaty-springs)** — Geospatial study of natural springs around Almaty  
Building an open inventory of springs on the Ile-Alatau slope from
OpenStreetMap, DEM elevation and field measurements: where springs occur, how
discharge tracks snowmelt, and how many residents live within a walk of one.
First campaign done: six springs sampled, two of them absent from OSM.  
[Live map](https://x1n0x.github.io/almaty-springs/reports/map.html) · `Overpass API` `EXIF/GPS` `DEM` `Leaflet`

**[time-series-temperature-forecast](https://github.com/x1n0x/time-series-temperature-forecast)** — Winter temperature forecasting for Almaty  
Lag-based regression on five winter seasons, with leak-free rolling features and
chronological validation. Notable for what it refuses to do: the write-up
explains why forecasting the following winter would not have been
methodologically sound, and stops there.  
`pandas` `scikit-learn` `statsmodels`

**[customer-churn-ml](https://github.com/x1n0x/customer-churn-ml)** — Churn prediction with explainability  
Logistic regression, gradient boosting and random forest on the same pipeline,
compared on ROC-AUC and recall, with coefficient-level interpretation of the
churn drivers.  
`scikit-learn` `imbalanced classification`

**[tookem](https://github.com/x1n0x/tookem)** — Production site for an electrical-equipment manufacturer  
Static landing page for Elektromir, an Almaty switchboard manufacturer. No
framework and no build step: hand-written HTML, CSS and JavaScript, a 2GIS map
integration, and full SEO markup (Open Graph, JSON-LD, sitemap, security
headers). Live at [tookem.kz](https://tookem.kz/).  
`HTML` `CSS` `JavaScript` `SEO`

---

## Fundamentals, implemented from scratch

Short projects written to understand a method rather than to use a library:

| Project | What it does |
|---|---|
| [face-recognition-linear-algebra](https://github.com/x1n0x/face-recognition-linear-algebra) | Eigenfaces and PCA in pure NumPy — identity as a linear subspace |
| [gradient-descent-visualization](https://github.com/x1n0x/gradient-descent-visualization) | Gradient descent as geometry: step size, convergence, and how it fails |
| [happy-face-recognition](https://github.com/x1n0x/happy-face-recognition) | A transparent image-classification pipeline with error analysis |
| [fortnite-player-analytics](https://github.com/x1n0x/fortnite-player-analytics) | Latent player structure and an interpretable skill index |

---

## Currently

Collecting field data for **almaty-springs** and extending the ocean simulator's
anomaly detection.

Open to junior data analyst roles.

---

## Contact

[Telegram](https://t.me/x1n0x)
