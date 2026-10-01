# Limitations statement — Tanzania (TZA)

Run `20261001T110109Z` · provider `gee` · baseline 2015 · endline 2024

## 1. What is measured
Upward radiance in the visible and near-infrared, captured at approximately 01:30 local solar time, in
nW·cm⁻²·sr⁻¹, aggregated to administrative units. **Nothing in this product is a direct measurement of
electricity access, economic output or population.** Every such reading is an inference.

## 2. Dissemination verdict
**EXPERIMENTAL** — Publishable only as an EXPERIMENTAL statistic, clearly labelled as such and presented alongside the official source it complements. Reason: no independent official statistic: the correlation with population is a consistency check, not a validation.
Basis: Lit area vs population density · ρ = 0.817 (lower 95% bound 0.64) on 30 ADM1 units.
Independent official statistic supplied: NO — the population check is a consistency test, not a validation.

## 2b. Methodological safeguards applied in this run
- NTL product: a single product for all years: EOG VNL V2 annual (V2.1 / V2.2) · average_masked (versions: NOAA/VIIRS/DNB/ANNUAL_V21 · average_masked / NOAA/VIIRS/DNB/ANNUAL_V22 · average_masked)
- Indicators computed on top-coded values (p99.9).
- Gas flares: 50 gas-flare pixels (with halo) neutralised before any computation; share of national SoL removed — 2015: 4.7%; 2024: 1.7%.
- Electrification uncertainty: unlit inhabited population between 32,965,364 and 35,632,756 depending on the noise floor (0.15–0.5).
- Change detection: units below the p10 of initial SoL are shown but never flagged (17 unit(s)).
- Monthly series: 87 region-months dropped for cloud-free coverage below 80%, 341 rescaled for partial coverage.
- Population: 2015 ← population 2015; 2024 ← population 2020
- Growth (scenario E): between the median of the first and last three years; Theil-Sen trend reported alongside.
- Spatial autocorrelation: significant for Elasticity residuals (scenario A) (I = 0.41, effective n ≈ 70 of 168); Light per capita (scenario D) (I = 0.31, effective n ≈ 88 of 168) — the corresponding confidence intervals are too narrow.

## 3. Thresholds and their sensitivity
- Noise floor: **0.25 nW·cm⁻²·sr⁻¹**. 96.6% of national pixels fall below it in 2024.
  Every "unlit" figure in this product depends on this single number; a sensitivity test across
  0.15–0.50 is required before any figure is cited as a level rather than a rank.
- Urban-core threshold: **10.0 nW·cm⁻²·sr⁻¹**. Cross-country comparison is valid only at an
  identical threshold.
- Top-coding at p99.9 = 42.6. The brightest 1 % of pixels hold 75.6% of the
  national Sum of Lights, so national aggregates are sensitive to a small number of locations.

## 4. Known artefacts in this country
- **Gas-flare candidates detected: 4.** Each must be verified against a petroleum infrastructure map before any growth in its district is interpreted economically.
- **Blooming.** Lit-area figures overstate the true built footprint of cities; small ADM2 units adjacent to a
  large city inherit light that is not theirs.
- **Lost light: 470 km².** May reflect depopulation, outage or conflict — or a change in product
  version or cloud-free observation count. Not interpretable without that check.
- **Seasonality.** Month-of-year amplitude observed: 2.73×. Month-on-month comparisons are invalid without seasonal adjustment.
- **Sensor era.** VIIRS only. Any comparison with DMSP-OLS years (1992–2013) would be a comparison between two
  different physical quantities and is not made here.

## 5. What this product must not be used for
- Producing a level of GDP, of household income, or of the electrification rate.
- Ranking administrative units for budget allocation without a second, independent indicator.
- Any statement about activity that does not emit light: subsistence agriculture, daytime informal trade,
  indoor activity in well-insulated buildings, the care economy.
- Monitoring at a finer level than the units published here.

## 6. Boundaries and population
Administrative boundaries: geoBoundaries. If these differ from the official national boundaries,
the zonal figures differ accordingly. Population: WorldPop modelled surfaces, themselves an estimate with their
own error structure, which propagates into every per-capita and every "unlit population" figure here.




---

# Déclaration de limites — Tanzania (TZA)

Exécution `20261001T110109Z` · fournisseur `gee` · référence 2015 · fin de période 2024

## 1. Ce qui est mesuré
Une radiance ascendante dans le visible et le proche infrarouge, captée vers 01h30 heure solaire locale, en
nW·cm⁻²·sr⁻¹, agrégée par unité administrative. **Rien dans ce produit n'est une mesure directe de l'accès à
l'électricité, de la production économique ou de la population.** Chacune de ces lectures est une inférence.

## 2. Verdict de diffusion
**EXPERIMENTAL** — Diffusable uniquement comme statistique EXPÉRIMENTALE, explicitement étiquetée comme telle et présentée à côté de la source officielle qu'elle complète. Motif : no independent official statistic: the correlation with population is a consistency check, not a validation.
Base : Lit area vs population density · ρ = 0.817 (borne basse IC 95 % : 0.64) sur 30 unités ADM1.
Statistique officielle indépendante fournie : NON — la corrélation avec la population est un contrôle de cohérence, pas une validation.

## 2 bis. Garde-fous méthodologiques appliqués dans cette exécution
- Produit NTL : un seul produit pour toutes les années : EOG VNL V2 annual (V2.1 / V2.2) · average_masked (versions : NOAA/VIIRS/DNB/ANNUAL_V21 · average_masked / NOAA/VIIRS/DNB/ANNUAL_V22 · average_masked)
- Indicateurs calculés sur les valeurs écrêtées (p99.9).
- Torchères : 50 pixels de torchères (halo compris) neutralisés avant calcul ; part de la SoL nationale retirée — 2015 : 4.7%; 2024 : 1.7%.
- Incertitude sur l'électrification : population non éclairée comprise entre 32,965,364 et 35,632,756 selon le plancher de bruit (0.15 à 0.5).
- Détection de changement : les unités sous le p10 de la SoL initiale sont affichées mais jamais signalées (17 unité(s)).
- Série mensuelle : 87 mois-région écartés pour couverture sans nuage inférieure à 80%, 341 corrigés de leur couverture partielle.
- Population : 2015 ← population 2015; 2024 ← population 2020
- Croissance (scénario E) : annual growth between the median of years 2015–2017 and that of years 2022–2024.
- Autocorrélation spatiale : significative pour Elasticity residuals (scenario A) (I = 0.41, n effectif ≈ 70 sur 168) ; Light per capita (scenario D) (I = 0.31, n effectif ≈ 88 sur 168) — les intervalles de confiance correspondants sont trop étroits.

## 3. Seuils et sensibilité
- Plancher de bruit : **0.25 nW·cm⁻²·sr⁻¹**. 96.6% des pixels nationaux passent
  en dessous en 2024. Tout chiffre « non éclairé » dépend de ce seul nombre ; un test de sensibilité sur
  0,15–0,50 est exigé avant de citer un niveau plutôt qu'un rang.
- Seuil de cœur urbain : **10.0 nW·cm⁻²·sr⁻¹**. Une comparaison entre pays n'est valide qu'à
  seuil identique.
- Écrêtage au p99.9 = 42.6. Les 1 % de pixels les plus brillants concentrent
  75.6% de la somme des lumières nationale : les agrégats nationaux sont sensibles à un très petit nombre
  de lieux.

## 4. Artefacts identifiés dans ce pays
- **Torchères suspectées : 4.** Chacune doit être vérifiée sur une carte des infrastructures pétrolières avant toute interprétation économique de la croissance du district concerné.
- **Halo lumineux.** Les surfaces éclairées surestiment l'emprise bâtie réelle ; une petite unité ADM2 voisine
  d'une grande ville hérite d'une lumière qui n'est pas la sienne.
- **Lumière perdue : 470 km².** Peut traduire une dépopulation, une coupure ou un conflit — ou un
  changement de version du produit ou du nombre d'observations sans nuage. Non interprétable sans cette vérification.
- **Saisonnalité.** Amplitude mensuelle observée : 2.73×. Les comparaisons de mois à mois sont invalides sans correction saisonnière.
- **Ère du capteur.** VIIRS uniquement. Toute comparaison avec les années DMSP-OLS (1992–2013) opposerait deux
  grandeurs physiques différentes et n'est pas faite ici.

## 5. Usages proscrits
- Produire un niveau de PIB, de revenu des ménages ou de taux d'électrification.
- Classer des unités administratives pour une allocation budgétaire sans un second indicateur indépendant.
- Toute affirmation sur une activité qui n'émet pas de lumière : agriculture vivrière, commerce informel diurne,
  activité intérieure en bâtiment bien isolé, économie du soin.
- Un suivi à un niveau plus fin que les unités publiées ici.

## 6. Limites administratives et population
Limites : geoBoundaries. Si elles diffèrent des limites officielles nationales, les chiffres zonaux
diffèrent d'autant. Population : surfaces modélisées WorldPop, elles-mêmes une estimation dotée de sa propre
structure d'erreur, qui se propage dans chaque chiffre par habitant et chaque « population non éclairée ».


