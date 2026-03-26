# Chicago Food Inspections — Case Study

This case study uses the **Chicago Food Inspections dataset**, publicly available on [Kaggle](https://www.kaggle.com/datasets/chicago/chicago-food-inspections) and the [Chicago Open Data Portal](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5). The dataset contains over 200,000 records of food establishment inspections conducted by the Chicago Department of Public Health since 2010, covering restaurants, grocery stores, school cafeterias, and other food-handling facilities across the city.

## Purpose

This case study is designed to help students become familiar with core data analysis tasks using a real-world, messy dataset. Working through the notebook, students will practice:

- **Data loading and cleaning** — handling missing values, parsing dates, normalising text columns
- **Exploratory data analysis (EDA)** — understanding distributions, value counts, and summary statistics
- **Grouping and aggregation** — computing failure rates by risk category, facility type, ZIP code, and time period
- **Time series analysis** — tracking trends over years and identifying seasonal patterns
- **Text parsing** — extracting structured information from free-text violation descriptions
- **Entity-level analysis** — following individual businesses across multiple inspections to measure improvement or chronic non-compliance
- **Data visualisation** — bar charts, heatmaps, histograms, Pareto curves, and dual-axis plots using Matplotlib and Seaborn


## Getting Started

1. Install dependencies (Python 3.8+):
   ```bash
   pip install pandas matplotlib seaborn
   ```
2. Open the notebook and run all cells in order. The first cell will automatically download the dataset from the Chicago Open Data Portal (~250 MB).

## The 20 Analysis Questions

The notebook walks through 20 questions across five themes:

**Inspection patterns** — which facility types are inspected most, how risk correlates with failure, how outcomes are distributed.

**Temporal trends** — how failure rates have changed year over year, whether seasonal patterns exist, and which month/year combinations show anomalous rates.

**Geographic analysis** — which ZIP codes have the highest absolute number of failures and the highest normalised failure rates.

**Business-level analysis** — inspection frequency per business, recovery rates after a failure, top improvers, and chronically non-compliant establishments.

**Violation analysis** — most common violations in failed inspections, which violations best discriminate failures from passes, associations between violation types and facility categories, and the link between violation count and inspection outcome.
