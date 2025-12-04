# Global Maternal Mortality Ratio (MMR) Analysis (1985-2023)

A comprehensive data visualization project analyzing global maternal mortality trends, regional disparities, and factors influencing maternal health outcomes across 189 countries over nearly four decades.

## 📊 Project Overview

This project examines the **Maternal Mortality Ratio (MMR)**—the number of maternal deaths per 100,000 live births—using data from 1985 to 2023. The analysis reveals critical insights about global health inequalities, progress toward UN Sustainable Development Goal 3.1, and evidence-based pathways to reducing preventable maternal deaths.

### Key Findings

- **69.5% global reduction** in maternal mortality from 1985 (376) to 2023 (115)
- **8,000-fold disparity** between best and worst performing countries
- **Sub-Saharan Africa** accounts for approximately 50% of global maternal deaths
- Current progress is **~40% of the pace required** to meet SDG 3.1 target (70 deaths per 100,000 by 2030)
- Strong inverse correlation between national income and maternal mortality

### Dataset Statistics

| Metric | Value |
|--------|-------|
| Total Observations | 7,371 |
| Countries Covered | 189 |
| Time Period | 1985-2023 (39 years) |
| MMR Range | 1 - 8,045 |
| Mean MMR | 229 |
| Median MMR | 68 |

## 📈 Visualizations Included

### Exploratory Data Analysis (EDA)
1. **MMR Distribution Histogram** - Right-skewed distribution with SDG target reference line
2. **Global Trend Line Chart** - 39-year decline in average maternal mortality
3. **Income Group Box Plot** - Relationship between economic development and maternal outcomes

### Main Visualizations
4. **Animated Choropleth Map** - Geographic visualization of MMR by country over time
5. **Regional Heatmap** - 5-year interval comparison across World Bank regions
6. **MMR Reduction Scatter Plot** - Baseline MMR vs. percentage reduction by country
7. **Success Stories Line Chart** - Countries achieving greatest absolute MMR reductions

## 🌍 Regions Analyzed

- Middle East, North Africa, Afghanistan & Pakistan
- Sub-Saharan Africa
- Latin America & Caribbean
- Europe & Central Asia
- East Asia & Pacific
- South Asia
- North America

## 🛠️ Setup Instructions

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook, JupyterLab, or VS Code with Jupyter extension

### Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/stiipp/DataViz-Final-Project.git
    cd DataViz-Final-Project
    ```

2. **Create a virtual environment (recommended)**

    **Windows:**
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

    **macOS/Linux:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install required packages**

    ```bash
    pip install pandas matplotlib seaborn numpy plotly jupyter
    ```

### Required Libraries

| Library | Version | Purpose |
|---------|---------|---------|
| `pandas` | ≥1.3.0 | Data manipulation and analysis |
| `matplotlib` | ≥3.4.0 | Static visualizations (histogram, line chart) |
| `seaborn` | ≥0.11.0 | Statistical visualizations and heatmaps |
| `numpy` | ≥1.20.0 | Numerical computations |
| `plotly` | ≥5.0.0 | Interactive visualizations (choropleth, box plots) |
| `jupyter` | ≥1.0.0 | Notebook environment |

### Running the Analysis

1. **Launch Jupyter Notebook**

    ```bash
    jupyter notebook
    ```

    Or if using VS Code, simply open the `.ipynb` file directly with the Jupyter extension installed.

2. **Open the notebook**

    ```
    CSD_G3_CURILAN_TAGUIBAO_VILLAROZA_Final_Course_Project.ipynb
    ```

3. **Run all cells**

    - **Option 1**: Press `Shift + Enter` on each cell sequentially
    - **Option 2**: Use `Cell` → `Run All` from the Jupyter menu
    - **Option 3**: In VS Code, click `Run All` at the top of the notebook

## 📋 Dataset Description

### File: `MMR_with_region_income.csv`

| Column | Description |
|--------|-------------|
| `Country Name` | Full country name |
| `Country Code` | ISO 3-letter code |
| `Year` | Year of observation (1985-2023) |
| `Maternal_Mortality_Ratio` | Deaths per 100,000 live births |
| `Region` | World Bank regional classification |
| `IncomeGroup` | World Bank income classification |

## 🎯 SDG 3.1 Context

> *"By 2030, reduce the global maternal mortality ratio to less than 70 per 100,000 live births."*

| Metric | Value |
|--------|-------|
| Current Global Average (2023) | 115 |
| SDG Target | 70 |
| Gap Remaining | 45 deaths per 100,000 |

## 👥 Authors

**4CSD Group 3**
- Curilan
- Taguibao
- Villaroza

*Data Analysis & Visualization Course - Final Project*

## 📚 Data Sources

- World Bank Maternal Mortality Estimates

## 📄 License

This project is for educational purposes.

---

*"No woman should die giving life."* — UNFPA
