# Transit Time Distribution (TTD) Toolkit v1.0

An interactive web-based tool for fitting transit time distribution models to tracer breakthrough curves from pulse-labeling experiments.

## Purpose

This toolkit fits **lognormal** and **gamma** distribution models to isotopic tracer data (δ²H or δ¹⁸O) using Nelder-Mead optimization. It provides:

- Tracer metrics: t_peak, t_mean, f_pulse, pore water velocity
- Model comparison via AIC/BIC criteria
- Interactive visualization of breakthrough curves and cumulative distribution functions

## Quick Start

### Online Access

Open the toolkit directly in your browser:

**[Launch TTD Toolkit](https://j-evaristo.github.io/ttd-toolkit/)**

### Local Access

1. Download `index.html` from this repository
2. Open the file in any modern web browser (Chrome, Firefox, Edge, Safari)
3. No installation or internet connection required after download

## Usage Instructions

### Step 1: Prepare Your Data

Format your data as CSV with two columns:

| Date | δ²H (or normalized_d2H) |
|------|-------------------------|
| 10/2/2014 | 58.04 |
| 10/7/2014 | 47.31 |
| ... | ... |

**Supported date formats:** MM/DD/YYYY, YYYY-MM-DD, MM/DD/YY

### Step 2: Input Parameters

1. **Paste CSV data** into the text area (or click "Load Demo Data" to test)
2. **Sample Name:** Identifier for your sample
3. **Reference Date:** Date of tracer injection (t = 0)
4. **Sample Depth:** Depth in cm (used for pore water velocity calculation)
5. **Data normalization:**
   - Check "Data is already normalized" if background has been subtracted
   - Otherwise, enter Background δ²H and Pulse δ²H values

### Step 3: Run Analysis

Click **"Run TTD Analysis"** to fit both models. Results appear in the Results tab.

### Step 4: Interpret Results

**Tracer Metrics:**

| Metric | Description |
|--------|-------------|
| t_peak | Time to peak concentration (days) |
| t_mean | Mean transit time from concentration-weighted average (days) |
| f_pulse | Fraction of pulse recovered at peak |
| Pore Water Velocity | Depth / t_mean (cm/day) |

**Model Comparison Table:**

| Metric | Description |
|--------|-------------|
| MTT/Residence Time | Mean transit time from fitted distribution |
| R² | Coefficient of determination |
| RMSE | Root mean square error |
| AIC | Akaike Information Criterion (lower = better fit) |

The model with lower AIC is marked with ★ as the preferred model.

### Step 5: Export

Download results as CSV from the Export tab for further analysis or reporting.

## Input Data Requirements

| Parameter | Description | Required |
|-----------|-------------|----------|
| Date column | Sampling dates | Yes |
| δ²H column | Isotope values (raw or normalized) | Yes |
| Reference date | Tracer injection date | Yes |
| Sample depth | Depth below surface (cm) | Optional* |
| Background δ²H | Pre-labeling isotope value | If not normalized |
| Pulse δ²H | Tracer isotope value | If not normalized |

*Required for pore water velocity calculation

## Technical Implementation

### Optimization Method

The toolkit uses **Nelder-Mead simplex optimization** with multi-start initialization to minimize sum of squared residuals between observed and modeled breakthrough curves. This approach matches the behavior of `scipy.optimize.curve_fit` in Python.

### Fitted Parameters

For each distribution:

| Parameter | Lognormal | Gamma |
|-----------|-----------|-------|
| Shape | σ (log-space std dev) | k (shape) |
| Scale | median | θ (scale) |
| Delay | time offset | time offset |
| Scaling factor | amplitude | amplitude |

### Mean Transit Time Calculation

- **Lognormal:** MTT = scale × exp(σ²/2)
- **Gamma:** MTT = k × θ

### Model Selection

AIC is calculated as:

```
AIC = 2k - 2ln(L)
```

where k = 4 (number of parameters) and L is the likelihood.

## Browser Compatibility

Tested and working in:

- Google Chrome (recommended)
- Mozilla Firefox
- Microsoft Edge
- Safari

## Limitations

- Bootstrap uncertainty analysis is not included in the web version (available in companion Python toolkit)
- Very large datasets (>1000 points) may slow performance
- Requires JavaScript enabled in browser

## Citation

If you use this toolkit in your research, please cite both the paper and software:

**Paper:**
> Evaristo, J., Wright, C.W., Bauser, H., Knighton, J.K., Johnson, D., Kim, M. (2026). Tracer Labeling and Transit Time Modeling in Soil-Plant Systems: Perspectives and a Call for Broader Dialogue in Ecohydrology. *Ecohydrology*. DOI: [10.1002/eco.70182](https://doi.org/10.1002/eco.70182)

**Software:**
> Evaristo, J., Wright, C.W., Bauser, H., Knighton, J.K., Johnson, D., Kim, M. (2026). TTD Toolkit (v1.0). Zenodo. DOI: [10.5281/zenodo.18318447](https://doi.org/10.5281/zenodo.18318447)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18318447.svg)](https://doi.org/10.5281/zenodo.18318447)

## Contact

For questions regarding the methodology, please contact the corresponding author as indicated in the associated manuscript.

---

*TTD Toolkit v1.0 | Developed for ecohydrological tracer analysis*
