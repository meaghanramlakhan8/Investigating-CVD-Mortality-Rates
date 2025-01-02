# Investigating Hypertension-Related Cardiovascular Disease Mortality in US Adults

## Overview
This repository contains an in-depth analysis of hypertension-related cardiovascular disease (CVD) mortality among US adults aged 35 and older, spanning the years 2000 to 2019. Using data from the Centers for Disease Control and Prevention (CDC) and supplementary health insurance coverage data, this project examines demographic and geographic disparities, trends over time, and the impact of health insurance on mortality rates.

## Data Sources
- **CDC Mortality Data (2000–2019)**: Over 1 million observations, providing comprehensive demographic, geographic, and mortality details.
- **Health Insurance Coverage Data**: Includes county-level insurance coverage statistics to explore correlations with mortality.

## Key Questions
- How do demographic factors such as race, age, sex, and geography influence hypertension-related CVD mortality rates?
- Have public health initiatives effectively reduced mortality over time?
- How do geographic and demographic disparities persist, and what is their relationship to health insurance coverage?

## Analysis Summary
- **Trend Analysis**: A clear decline in hypertension-related CVD mortality rates was observed over two decades, with regional and demographic variations.
- **Disparities**: Persistent racial and geographic disparities were identified, particularly among Black Americans and residents of southern states.
- **Insurance Impact**: While higher insurance coverage correlates with lower mortality rates, disparities remain among racial groups with similar coverage levels.
- **Behavioral Trends**: Strong predictors of mortality include physical inactivity, obesity, and smoking, often concentrated in regions with higher mortality rates.

## Usage
### Dependencies
Install the necessary R packages:
```R
install.packages(c("dplyr", "ggplot2", "quarto", "stringr", "RSQLite", "mapdata", "maps"))
```

### Installation
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/yourusername/Investigating-CVD-Mortality-Rates.git
```

### Execution
Run the Quarto file to replicate the analysis:
```bash
quarto render Final_Report.qmd
```

## Key Findings
1. **Trends Over Time**: Significant progress in reducing mortality rates, though improvements have slowed in recent years.
2. **Demographic and Geographic Disparities**: Higher mortality rates persist among Black Americans and in southern states.
3. **Behavioral Predictors**: Physical inactivity, obesity, and smoking strongly correlate with higher mortality rates.
4. **Health Insurance**: Greater coverage correlates with reduced mortality but does not eliminate disparities.

## Future Work
- Expand analysis to include more socioeconomic variables and additional data sources.
- Assess the effectiveness of public health interventions targeted at high-risk groups.
- Explore policy recommendations for reducing disparities in hypertension-related mortality.

## Acknowledgments
- **Centers for Disease Control and Prevention** for providing mortality data.
- **County Health Rankings & Roadmaps** for supplemental behavioral data.
- Researchers and analysts whose work supports cardiovascular health equity.

## Contributors' names and contact info:

- Min Choi 
- Shakty Juarez
- Meaghan Ramlakhan
- Pinar Targil

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
