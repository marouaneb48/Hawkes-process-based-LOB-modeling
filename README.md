# LOB Modeling with Hawkes Processes

This project explores the use of **Hawkes processes** to model event dynamics in **limit order book (LOB)** data. The goal is to capture self-exciting behavior in high-frequency financial markets and evaluate the effectiveness of Hawkes-based models for order book event simulation, calibration, and forecasting.

## 📁 Notebooks Overview

### – *Exploratory Analysis of Event Intervals*
- Loads and visualizes LOB event data.
- Fits exponential distributions to inter-arrival times.
- Provides initial statistical insights for model design.

###  – *Autocorrelation and Time Series Diagnostics*
- Performs autocorrelation (ACF) analysis on inter-event durations.
- Evaluates the temporal structure and memory of the data.
- Prepares groundwork for model selection.

### – *Spline-Based Interpolation*
- Applies cubic spline interpolation to event time series.
- Enhances temporal resolution and data smoothness.
- Useful for simulating or approximating missing values.

### – *Hawkes Process Simulation*
- Implements Hawkes processes with exponential kernels.
- Simulates self-exciting event dynamics.
- Introduces custom `Hawkes` module for modeling.

###  – *Parameter Calibration *
- Runs large-scale simulations with varied Hawkes parameters.
- Performs grid search to assess model sensitivity.
- Analyzes parameter impacts on simulated event behavior.

###  – *Model Evaluation and Residual Analysis*
- Conducts residual diagnostics on fitted Hawkes models.
- Uses ACF and statistical tests to assess model fit.
- Helps validate model suitability for real-world data.

## 🧰 Tools & Libraries

- `numpy`, `pandas`, `matplotlib` – Core data analysis and visualization
- `scipy.stats`, `statsmodels` – Statistical modeling and tests
- `CubicSpline` – Interpolation of time series
- `Hawkes` (custom module) – Simulation and calibration of Hawkes processes
- `tqdm`, `itertools` – Simulation and performance support

## 📌 Project Highlights

- Models high-frequency LOB events using **self-exciting point processes**
- Combines **simulation, interpolation, and statistical diagnostics**
- Lays the foundation for advanced **market microstructure modeling**

## 📂 Usage

1. Clone the repository or download the notebooks.
2. Ensure all required libraries are installed.
3. Run notebooks sequentially for full workflow understanding.

## 📄 License

This project is for academic and research purposes.

---

