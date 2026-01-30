# Final_project_202002946
The repository for the final project of GEOG5415M Programming for Spatial Data Science

# Backgrouds
Health inequalities refer to unequal differences in health between social groups or places, and they are one of the issues that must be addressed in urban planning. One of the main determinants of health inequalities is socioeconomic deprivation. Several studies have investigated this relationship at the national level. For example, Marmot et al. (2020) observed that life expectancy tends to be shorter in more deprived areas in England. However, it is also important to analyse this relationship at a local scale, because health inequalities are not evenly distributed within cities and because local authorities are responsible for many practical countermeasures.

This project investigates the association between deprivation and health inequality in Leeds, using life expectancy as a measure of health outcomes and the Index of Multiple Deprivation (IMD) as a measure of area-level deprivation. By combining and analysing these datasets, the project aims to provide insight into how deprivation correlates with life expectancy across neighbourhoods in Leeds, providing evidence that can support local decision-making for the public good.

# Data in the Repository
202002946.ipynb contains the code necessary to run the analysis.

lebymsoas.xlsx contains life expectancy at birth. The dataset was provided by the Office for National Statistics (2021) and is available at https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/lifeexpectancies/adhocs/13926lifeexpectancyatbirthandage65yearsbysexformiddlelayersuperoutputareasmsoasengland2016to2020.

imd2019_msoa_level_data.csv contains IMD scores (2019) obtained from mySociety (2019) and is available at https://research.mysociety.org/sites/imd2019/about/.

MSOA_Dec_2011_Boundaries_Generalised_Clipped_BGC_EW_V3_2022_-5730664396045573288.zip contains MSOA boundary data (2011) from the Office for National Statistics and is available at https://geoportal.statistics.gov.uk/datasets/ons::middle-layer-super-output-areas-december-2011-boundaries-ew-bgc-v3-1/about. The file is zipped due to its large size; unzip it before running 202002946.ipynb.

MSOA_(2011)to_MSOA(2021)to_Local_Authority_District(2022)Best_Fit_Lookup_for_EW(V2).csv contains a lookup dataset linking MSOA 2011 to Local Authority Districts. This dataset is provided by the Office for National Statistics (2025) and is available at https://geoportal.statistics.gov.uk/datasets/ons::msoa-2011-to-msoa-2021-to-local-authority-district-2022-best-fit-lookup-for-ew-v2/about.

# 202002946.ipynb
This notebook conducts an analysis to examine the association between life expectancy and IMD scores. It begins by reading all the necessary datasets, followed by data cleaning and wrangling to prepare the data for analysis. Data visualization is used throughout to explore patterns and support the cleaning process. Next, a linear regression model is fitted to quantify the relationship between life expectancy and deprivation. Finally, two visualizations are created to illustrate the findings and provide insights that can support public decision-making and the public good.

# To run 202002946.ipynb
To run the 202002946.ipynb file, first unzip MSOA_Dec_2011_Boundaries_Generalised_Clipped_BGC_EW_V3_2022_-5730664396045573288.zip into the same directory. Make sure all other data files are also located in the same directory as 202002946.ipynb.

# References
Marmot, M., Allen, J., Boyce, T., Goldblatt, P. and Morrison, J. 2020. *The Marmot Review 10 Years On*. [Online]. London: Institute of Health Equity. [Accessed 29 January 2026]. Available at: https://www.instituteofhealthequity.org/resources-reports/marmot-review-10-years-on
