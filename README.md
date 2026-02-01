# Exploratory Data Analysis (EDA) Lab - U18AII5202L

**Name:** POOJITH M  
**Roll No:** 23BAD083

## Overview
This repository contains Exploratory Data Analysis experiments performed using R programming language as part of the EDA Lab course.

## Experiments

| Experiment | Title | Dataset | Description |
|------------|-------|---------|-------------|
| [Experiment 1](Experiment1/) | Student Performance Analysis | Student academic records | Analyze student grades, subject-wise performance trends, and grade distributions |
| [Experiment 2](Experiment2/) | E-Commerce Transaction Analysis | Online transaction data | Analyze transaction patterns, detect outliers, and visualize sales intensity |
| [Experiment 3](Experiment3/) | Healthcare Data Analysis | Patient health records | Scatter plot matrix with color encoding, correlation analysis |
| [Experiment 4](Experiment4/) | Traffic Accidents Analysis | Traffic accident data | Multi-dimensional encoding for severity, frequency, and accident types |
| [Experiment 5](Experiment5/) | Student Performance Statistical Analysis | Student academic records | Statistical analysis and performance patterns across departments |
| [Experiment 6](Experiment6/) | Retail Business Data Analysis | Retail transaction data | Parallel coordinates, bubble charts, and trellis displays |

---

## Experiment 1: Student Performance Analysis

**Objective:** Perform EDA on student performance data to understand academic trends and grade distributions.

**Visualizations:**
- 📊 Bar Chart - Subject-wise average marks
- 📈 Line Chart - Performance trend (Test 1 vs Test 2)
- 🥧 Pie Chart - Final grade distribution

**Libraries:** `ggplot2`, `dplyr`, `tidyr`

[View Experiment 1 →](Experiment1/)

---

## Experiment 2: E-Commerce Transaction Analysis

**Objective:** Perform EDA on e-commerce transaction data to understand sales patterns and detect outliers.

**Visualizations:**
- 📊 Histogram - Transaction amount distribution
- 📦 Box Plot - Outlier detection by product category
- 🗺️ Heatmap - Monthly sales intensity

**Libraries:** `ggplot2`, `dplyr`, `lubridate`

[View Experiment 2 →](Experiment2/)

---

## Experiment 3: Healthcare Data Analysis

**Objective:** Analyze healthcare data to identify correlations between health indicators using scatter plot matrices with age-based color encoding.

**Visualizations:**
- 🔴🟢🔵 Scatter Plot Matrix - Color-coded by age groups (Young, Middle, Senior)
- 📊 Correlation Matrix - Health indicator correlations

**Libraries:** Base R graphics

[View Experiment 3 →](Experiment3/)

---

## Experiment 4: Traffic Accidents Analysis

**Objective:** Visualize traffic accident data using multi-dimensional encoding techniques.

**Visualizations:**
- 📍 Multi-dimensional Plot with:
  - Size → Accident Frequency
  - Color Gradient → Severity (Gold to Red)
  - Shape → Accident Type

**Libraries:** Base R graphics

[View Experiment 4 →](Experiment4/)

---

## Experiment 5: Student Performance Statistical Analysis

**Objective:** Perform statistical analysis on student performance data to identify patterns and correlations.

**Analysis Focus:**
- Summary statistics and distributions
- Department-wise performance comparison
- Correlation analysis
- Grade distribution analysis

**Libraries:** Base R and statistical packages

[View Experiment 5 →](Experiment5/)

---

## Experiment 6: Retail Business Data Analysis

**Objective:** Analyze retail business data using advanced multi-dimensional visualization techniques.

**Visualizations:**
- 📊 Parallel Coordinates - Sales, Profit, Discount by segment
- 🫧 Bubble Chart - Sales vs Profit with region encoding
- 🗺️ Trellis Display - Performance trends by region

**Libraries:** `ggplot2`, `GGally`, `dplyr`

[View Experiment 6 →](Experiment6/)

---

## Tools & Technologies
- **Language:** R
- **IDE:** RStudio
- **Key Libraries:** ggplot2, dplyr, tidyr, lubridate

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/poojith3010/23BAD083_U18AII5202L.git
   ```
2. Open the desired experiment folder
3. Install required R packages
4. Run the `.R` script in RStudio

## Repository Structure
├── Experiment5/
│   ├── README.md
│   ├── 5.student_performance.csv
│   └── Figures/
└── Experiment6/
    ├── README.md
    ├── EDA_ass_6.R
    ├── 6.retail_business.csv
    └── Figures/
        ├── parallel_coordinates.png
        ├── bubble_chart.png
        └── trellis_display.png
```
├── README.md
├── Experiment1/
│   ├── README.md
│   ├── EDA_ass_1.R
│   ├── 1.student_performance.csv
│   └── figures/
│       ├── bar_cahrt.png
│       ├── line_chart.png
│       └── pie_chart.png
├── Experiment2/
│   ├── README.md
│   ├── EDA_ass_2.R
│   ├── 2.ecommerce_transactions.csv
│   └── figures/
│       ├── histogram_plot.png
│       ├── box_plot.png
│       └── heatmap.png
├── Experiment3/
│   ├── README.md
│   ├── EDA_ass_3.R
│   ├── 3.healthcare_data.csv
│   └── Figures/
│       ├── scatter_plot.png
│       └── Correlation.png
└── Experiment4/
    ├── README.md
    ├── EDA_ass_4.R
    ├── 4.traffic_accidents.csv
    └── Figures/
        └── plot.png
```
