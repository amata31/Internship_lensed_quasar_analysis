# Gravitationally lensed high-z quasar candidate

This repository contains Python notebooks developed to investigate a candidate gravitationally lensed high-redshift quasar using optical and near-infrared spectroscopic observations.

The project was carried out during a research internship at the Gemini Observatory and focuses on spectroscopic data processing, template fitting, and quantitative model comparison to evaluate the physical nature of the source.

---

## 🚀 Project Objective

The analysis aims to:

* Process and combine multi-instrument spectroscopic large-scale observations.
* Normalize data to photometric points and resample data into uniform wavelength bins.
* Evaluate competing physical scenarios through template fitting.
* Test the gravitational lensing hypothesis.
* Extract physical information from spectral features.
* Process images and construction of Point Spread Function with data from Hubble Space Telescope.

The workflow follows a reproducible scientific data analysis pipeline:

**1,2: data ingestion → preprocessing → template fitting → model evaluation → visualization**

**3: data ingestion → image preprocessing → estimate parameters -> selection of objects → PSF construction**

---

## 🛠 Methods & Tools

### Tools

* Python
* NumPy
* SciPy
* Astropy
* Matplotlib
* Jupyter Notebook
* Photutils

### Methods

* Spectral normalization and flux rescaling
* Multi-source data integration
* Spectral resampling and binning
* Template-based model fitting
* Reduced χ² model comparison
* Scientific visualization and residual analysis
* Image processing and PSF construction

---

## 📂 Repository Structure

```text
├── Quasar_P1.ipynb   # Data preparation, normalization, template construction, and preliminary model testing
├── Quasar_P2.ipynb   # Automated fitting, reduced χ² analysis, and model comparison.  Diagnostic plots and visualizations
├── Quasar_P3.ipynb   # Image proccessing, calculation of initial parameters, construction of PSF and preparation for substraction with GALFIT.
```

---

## 🔒 Data Availability

The observational data and final publication figures are not included in this repository because they are part of ongoing scientific research.

The notebooks are shared to demonstrate the analysis workflow, fitting methodology, and model evaluation procedures.

---

## 📌 Project Status

Research project completed as part of a Gemini Observatory internship. Results are currently under scientific publication.

---

## 💡 Skills Demonstrated

* Scientific data processing
* Data cleaning and normalization
* Model fitting and optimization
* Statistical model evaluation
* Multi-source data integration
* Scientific visualization
* Quantitative problem solving

---

## 👩‍💻 Author

**Aurora Mata Sánchez**
M.Sc. Astrophysics

