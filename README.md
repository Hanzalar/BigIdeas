# Comprehensive Analysis of Public Safety in Pittsburgh

## Introduction
This project aims to identify the most dangerous places in Pittsburgh based on data-driven analysis of public safety metrics such as fatal accidental overdoses, severe car crashes, and EMS dispatches. Through detailed analysis of these metrics, we provide insights into areas requiring targeted interventions and resources to improve safety and public health.

## Team Name - Group 30 aka BigIdea Bandits
- **Gavin Zheng** - [gaz0319](https://github.com/gaz0319)
- **Hanzala Rehan** - [hanzalar](https://github.com/Hanzalar)

## Repository Structure
- ├── 2022CrashData.csv
- ├── Crashanalysis.ipynb
- ├── Map_of_Allegheny_County,Pennsylvania.png
- ├── Neighborhoods.shp
- ├── README.md
- ├── allegheny-county-pennsylvania-zip-codes-map.png
- ├── ems_dispatches.ipynb
- ├── mun.txt
- ├── overdoses.ipynb
- └── pittsburgh-nbhds.png


## Analytical Process

### Fatal Accidental Overdoses Analysis
[Overdoses Notebook](https://github.com/Hanzalar/BigIdeas/blob/main/overdoses.ipynb)
- **Objective**: Identify the Pittsburgh zip codes with the highest number of fatal overdoses.
- **Data Cleaning and Visualization**: We filtered the data to focus on incidents marked as accidents and aggregated the counts by zip code. Visualizations include a pie chart showing the distribution of overdoses by zip code and a bar graph detailing the most prevalent drugs involved.
- **Findings**: Zip code 15210 (covering areas like Mount Oliver and Baldwin) was identified as having the highest overdose rates, indicating a critical area for drug intervention programs.

### Severe Car Crash Analysis
[Crash Analysis Notebook](https://github.com/Hanzalar/BigIdeas/blob/main/Crashanalysis.ipynb)
- **Objective**: Analyze the distribution of severe crashes within Pittsburgh, with a focus on municipalities and timing.
- **Methodology**: We filtered the crash data to include only incidents with major injuries or fatalities. The analysis included time-series graphs to determine peak times for severe crashes and mapping severe crashes using GeoPandas to create a heatmap over a Pittsburgh map.
- **Insights**: Pittsburgh City emerged as a hotspot for severe crashes, particularly during early morning and late evening hours, underscoring the need for enhanced traffic safety measures.

### EMS Dispatch Analysis
[EMS Dispatches Notebook](https://github.com/Hanzalar/BigIdeas/blob/main/ems_dispatches.ipynb)
- **Objective**: Identify patterns in EMS dispatches across Pittsburgh.
- **Analysis**: After sampling the data due to its large volume, we mapped EMS dispatch locations to visualize high-activity areas.
- **Conclusions**: The central Pittsburgh area, including Mount Oliver, showed a high concentration of EMS calls, suggesting this as a critical region for emergency and healthcare services enhancement.

## Overall Findings and Conclusion
Our comprehensive analysis across multiple datasets revealed that certain areas in Pittsburgh, notably zip code 15210 and central city regions, are particularly vulnerable to public safety issues ranging from overdoses to traffic accidents and emergency medical incidents. These findings highlight the need for targeted safety interventions and continuous monitoring to reduce risks and enhance community wellbeing in Pittsburgh.

This project not only sheds light on the current state of public safety in Pittsburgh but also sets a foundation for future research and policy-making to systematically address the identified challenges.

## How to Use This Repository
To explore our findings and replicate the analysis:
1. Clone the repository to your local machine.
2. Ensure you have Python installed along with libraries such as Pandas, Matplotlib, and GeoPandas.
3. Run the Jupyter Notebooks to view the analysis and modify parameters to explore different aspects of the data.

We invite feedback, contributions, and discussions to further enhance the understanding and implications of this analysis. Please feel free to raise issues or submit pull requests on our repository.
