# chicago

# chicago-businesses
Chicago community dataset using business license data from the City of Chicago's data portal, crime data from Chicago PD built out in chicago-crime, as well as figures for socioeconomic factors from the Chicago Metropolitan Agency for Planning (CMAP). 

The chicago-businesses R script creates the data set as well as corresponding summary tables and the underlying objects used to create the final dataset. The final data set is the result of several joins of tables containing the independent data sets. Cleaning and manipulation was required to pull together a complete data set that is usable for analysis. 

The subsequent chicago-community-analysis script attempts to draw conclusions from the data pulled through chicago-businesses, including observing heteroskedasticity among the observations, attempts to normalize the data, identifying correlations between variables of interest through plotting, and grouping similar neighborhoods through k-means clustering.

This project uses data downloaded at the following public sources:

Business License data: https://data.cityofchicago.org/Community-Economic-Development/Business-Licenses/r5kz-chrr/about_data

CMAP community factors: https://datahub.cmap.illinois.gov/search?categories=%252Fcategories%252Feconomy&q=Community%20Data%20Snapshots

CPD crime data: https://home.chicagopolice.org/statistics-data/statistical-reports/

# chicago-crime
Chicago PD data analysis on Chicago community areas between 2015-2023

This project is intended to provide a summary overview of various aspects of crime in Chicago neighborhoods. Combining several years of public data provided by the Chicago Police and CMAP, this code showcases several summary views and plots of violent crime and demographic variables across neighborhood and year to give a high-level overview of trends and potential exacerbators of crime. The intention is to deliver an understanding of the issues faced predominantly by West and South side neighborhoods with disproportionately high crime rates. 

I attempt to diagnose underlying causes of violent crime trends by investigating factors such as unemployment and their effect on violent crime rates, if any. Various statistical methods are used, such as pooled OLS, fixed effects, and first differences. Heterogeneity in the models as well as skewness in the underlying data remain a challenge, and further work is necessary to determine omitted variables. 

The Chicago_crime_raw_2015-2023 contains the R code that contains the data manipulation, cleaning, analysis, plotting, and modeling tasks accomplished thus far. the R_workspace provides the actual objects created by the raw code.

Raw data available at CMAP and Chicago PD websites:

CMAP: https://datahub.cmap.illinois.gov/search?categories=%252Fcategories%252Feconomy&q=Community%20Data%20Snapshots

CPD: https://home.chicagopolice.org/statistics-data/statistical-reports/
