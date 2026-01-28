# Alto Paraná – Baseline inputs (VM0006)

This folder contains Google Earth Engine (GEE) scripts used to support the
construction of a baseline for avoided forest degradation in Alto Paraná,
Paraguay, under the VM0006 REDD+ methodology.

The approach is designed for **productive mosaic landscapes**, where native
forest remnants are narrow, edge-dominated, and embedded within agricultural
matrices.

---

## Contents

### `agb300.js`
AGB-based stratification of native forest using a 300 m grid.

- Aboveground Biomass source: **NASA/ORNL Biomass Carbon Density v1 (~2010)**
- Forest mask: **MapBiomas Paraguay – native forest (class 3)**
- Forest condition represented through **forest fraction at 300 m**
- Stratification based on **AGB percentiles (P33 / P66)**:
  - High carbon stock
  - Medium carbon stock
  - Low carbon stock

This script provides:
- Wall-to-wall carbon stock stratification
- Mean and median AGB (Mg C/ha) and tCO₂e/ha per stratum
- Pixel-level outputs (AGB, stratum, lat/lon) for baseline calculations

This layer defines **emission factors** for degradation transitions.

---

## Planned additional scripts

The following complementary indicators may be added in this folder:

- NDVI temporal metrics (trend, variability)
- BSI or bare-soil related indices
- Additional edge or fragmentation metrics

These indicators are intended to support:
- Activity data identification
- Persistence checks for degradation signals
- QA/QC of stratification results

They do **not** replace AGB-based emission factors.

---

## Methodological notes

- AGB is used exclusively to quantify carbon stock differences between strata.
- Spectral indices (NDVI, BSI) are treated as **supporting evidence** for
  degradation dynamics, consistent with VM0006 guidance.
- No direct conversion of spectral indices to carbon stock is performed.
- All analyses are wall-to-wall and reproducible using public datasets
  accessed through Google Earth Engine.

---

## Data policy

No raw geospatial data are stored in this repository.

All datasets are accessed dynamically via Google Earth Engine, including:
- NASA/ORNL Biomass Carbon Density
- MapBiomas Paraguay
- FAO GAUL administrative boundaries

---

## Intended use

- Baseline construction for avoided forest degradation
- Transition matrix development
- Internal benchmarking and technical documentation
