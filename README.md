# Perception and Use of Cultural Ecosystem Services of Urban Forest: Lessons from the Achimota Forest

📄 Full Report: [View Analysis](PERCEPTION AND USE OF CULTURAL ECOSYSTEM SERVICES OF URBAN FOREST/ LESSONS FROM THE ACHIMOTA FOREST.pdf)

## Overview
This project explores perceptions and use of cultural ecosystem services (CES) in Achimota Forest, Ghana, through a 2025 survey of 100 urban residents, examining demographic relationships, stakeholder views, awareness levels, promoting/inhibiting factors, and encroachment implications. Findings reveal high CES valuation, with spiritual/religious (43%) and educational (31%) benefits dominant, significantly associated with visit frequency (p<0.001), employment (p<0.001), and income (p<0.001). Awareness is 75%, linked to frequent visits (p<0.001), while barriers like maintenance (82%) and safety (43%) threaten sustainability. Encroachment, driven by politicians/business (46.6%), risks natural assets (58%), underscoring needs for participatory planning and conflict resolution to preserve CES amid urban pressures.

## Objectives
- Examine the relationship between demographic characteristics of urban forest users and categories of cultural ecosystem benefits.
- Assess stakeholder perceptions of cultural ecosystem benefits provided by the Achimota forest.
- Determine the level of awareness of cultural ecosystem services delivered by the Achimota forest.
- Identify factors promoting the delivery of cultural ecosystem services by the Achimota forest.
- Examine factors inhibiting the delivery of cultural ecosystem services by the Achimota forest.
- Evaluate the extent of encroachment into the Achimota forest and its implications for sustainability.

## Dataset Summary
- **Source**: Primary survey data from urban residents in Accra, Ghana, focusing on Achimota Forest (2025).
- **Sample Size**: 100 respondents.
- **Key Variables**: Demographics (age, gender, employment, income, marital status, ethnicity, religion, visit frequency); CES benefits (spiritual, educational, recreation, etc.); perceptions (importance, awareness); activities (religious, reflection, social); threats (encroachment, management); funding preferences.

## Methods
- Descriptive statistics (frequencies, percentages, means) and visualizations (bar plots, cross-tabulations) for profiling demographics and CES distributions.
- Inferential tests including chi-square/Fisher’s exact for associations (e.g., demographics vs. benefits, awareness vs. visit frequency) and logistic regression for predictors (e.g., employment/income on awareness).
- Co-occurrence analysis for benefit themes and threats; Cramér’s V for effect sizes.

## Key Findings
- Demographics: Youthful (88% aged 16–48), female-majority (58%), low-income (55% ≤1500 GHS), student-heavy (30%), Christian (95%), with diverse ethnicity (Akan 36%, Ewe 25%, Ga-Dangme 24%); varied visit frequency (19% never, 44% monthly+).
- CES benefits: Spiritual/religious (43%) and educational (31%) dominant; significant associations with visit frequency (75% tests p<0.05), employment (50%), income (50%), age (25%); co-occurrences: educational + sense of space (18%).
- Perceptions: 67% rate CES highly/significantly important; strong awareness-perception link (p<0.001); activities like religious (58%) enhance spiritual/social benefits (p<0.001).
- Awareness: 75% aware, driven by visit frequency (p<0.001), employment (p<0.001), income (p=0.040); media (16%) key source; aware recognize more benefits (e.g., spiritual 49.3% vs. 24%).
- Promoting factors: Religious activities (58%), reflection (27%), social interaction (25%) drive delivery; user fees (36%) preferred funding, linked to awareness (p=0.023).
- Inhibiting factors: Maintenance (82%), safety (43%); threats: encroachment (47%), management lack (41%); conflicts: traditional-political (49%); low encroachment concern (2%) but high threat perception.
- Encroachment: Low awareness (82% unaware of reclassification); politicians/business drive (46.6%); risks natural assets (58%), social CES (30%); high-impact groups (16%) recognize more benefits (mean=2.56).



## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr, stats

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "ggplot2"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). Perception and Use of Cultural Ecosystem Services of Urban Forest: Lessons from the Achimota Forest.
