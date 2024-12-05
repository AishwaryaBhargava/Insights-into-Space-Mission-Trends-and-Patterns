# Insights into Space Mission Trends and Patterns

This repository contains a comprehensive analysis of global space missions, showcasing trends, patterns, and insights derived from a rich dataset of historical and recent space exploration efforts.

## Project Overview

Space exploration has undergone remarkable transformations over the years, marked by advancements in technology, shifting industry dynamics, and varying levels of participation across the globe. This project uses data visualization and analysis to uncover key trends, disparities, and financial insights in global space missions.

### Key Highlights:
1. **Mission Distribution:** A world map showing mission counts by country, highlighting the dominance of spacefaring nations like the United States and Russia.
2. **Mission Outcomes Over Time:** Trends in success, failure, and partial failure rates, showcasing technological and operational improvements.
3. **Financial Insights:** Comparative analysis of mission costs across countries, revealing significant financial disparities.
4. **Industry Evolution:** Trends in activity by government-run space agencies and private companies, reflecting the shift from government-driven initiatives to private-sector innovation.
5. **Temporal Patterns:** Heat maps visualizing the density of missions over decades, including historic peaks during the Apollo era and recent advancements driven by private companies.

## Visualizations

This repository includes interactive and static visualizations:
- **Choropleth Map:** Geographic disparities in mission counts.
- **Area Plot:** Success vs. failure trends over decades.
- **Box Plot:** Mission cost comparisons.
- **Line Plot:** Most active companies over time.
- **Heat Map:** Mission density by month and year.
- **Sunburst Chart:** Mission success rates by country and company.

## Data

The dataset is sourced from Kaggle and contains details of space missions spanning multiple decades. It includes key attributes such as mission date, location, country, mission status, and costs. Preprocessing steps include:
- Cleaning missing or inconsistent values.
- Standardizing date formats.
- Extracting country and location information for granular analysis.

Dataset link: [Space Missions Dataset](https://www.kaggle.com/datasets/mysarahmadbhat/space-missions)

## Tools and Libraries

- **Python Libraries:**
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for static visualizations
  - `plotly` for interactive visualizations

## Repository Structure

```
📂 Insights-into-Space-Mission-Trends-and-Patterns
├── 📁 data
│   └── space_missions.csv
├── 📁 Plots
│   └── [Visualization Files]
├── IV_Final_Code.ipynb
├── IV_Final_Code.py
├── IV_Final_Report.pdf
├── requirements.txt
└── README.md
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/AishwaryaBhargava/Insights-into-Space-Mission-Trends-and-Patterns.git
   cd Insights-into-Space-Mission-Trends-and-Patterns
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook IV_Final_Code.ipynb
   ```

4. Explore the visualizations in the `visuals` folder or generate your own by running the code.

## Report

A detailed project report is available in [IV_Final_Report.pdf](IV_Final_Report.pdf), covering:
- Data preprocessing steps.
- Methodologies and tools used.
- Findings and interpretations.
- Significance of the insights derived.

## Author

**Aishwarya Bhargava**  
[Portfolio](https://aishwaryabhargava.github.io/portfolio/#home) | [LinkedIn](https://www.linkedin.com/in/aishwarya-bhargava05/) | [GitHub](https://github.com/AishwaryaBhargava)
