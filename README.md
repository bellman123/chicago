# chicago-crime
Chicago PD data analysis on Chicago community areas between 2015-2023

This project is intended to provide a summary overview of various aspects of crime in Chicago neighborhoods. Combining several years of public data provided by the Chicago Police and Chicago Metropolitan Agency for Planning (CMAP), this code showcases several summary views and plots of violent crime and demographic variables across neighborhood and year to give a high-level overview of trends and potential exacerbators of crime. The intention is to deliver an understanding of the issues faced predominantly by West and South side neighborhoods with disproportionately high crime rates. 

I attempt to diagnose underlying causes of violent crime trends by investigating factors such as unemployment and their effect on violent crime rates, if any. Various statistical methods are used, such as pooled OLS, fixed effects, and first differences. Heterogeneity in the models as well as skewness in the underlying data remain a challenge, and further work is necessary to determine omitted variables. 

The Chicago_crime_raw_2015-2023 contains the R code that contains the data manipulation, cleaning, analysis, plotting, and modeling tasks accomplished thus far. the R_workspace provides the actual objects created by the raw code.

Raw data available at CMAP and Chicago PD websites:

CMAP: https://datahub.cmap.illinois.gov/search?categories=%252Fcategories%252Feconomy&q=Community%20Data%20Snapshots

CPD: https://home.chicagopolice.org/statistics-data/statistical-reports/
