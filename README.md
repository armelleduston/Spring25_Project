# Spring25_Project

A spatial analysis of air quality and lung cancer data

## Data 
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HMOEJO

**Abstract provided on harvard dataverse**

Data comes from two different sources. Population-based lung cancer incidence rates for the 
period 2010-2014 (most updated data) were abstracted from National Cancer Institute state cancer 
profiles (Schwartz et al. 1996).This national county-level database of cancer data is collected 
by state public health surveillance systems. The domain specific county level environmental 
quality index (EQI) data for the period 2000-2005 were abstracted from United States 
Environmental Protection Agency (USEPA) profile. Complete descriptions of the datasets used in 
the EQI are provided in Lobdell’s paper (Lobdell 2011). Data were merged based on the Federal 
Information Processing Standards (FIPS) code. Out of 3144 counties in United States this study 
has available information for 2602 counties: Data was not available for four states namely 
Kansas, Michigan, Minnesota and Nevada due to state legislation and regulations which prohibit 
the release of county-level data to outside entities, county whose lung cancer mortality 
information is missing were omitted from the data set, the Union county, Florida is an outlier 
in terms of mortality information which was deleted from the data set, in the process of local 
control analysis this study experiences two (cluster 28 and 29) non-informative clusters 
(non-informative cluster is one for which either treatment or control group information is 
missing). For analysis, non-informative clusters information was deleted from the data set. 
Three types of variables are used in this study: (i) lung cancer mortality as an outcome 
variable (ii) binary treatment indicator is the PM2.5 high (greater than 10.59 mg/m3) vs. 
low (less than 10.59 mg/m3) (iii) three potential X confounder for clustering namely land EQI, 
sociodemographic EQI and built EQI. For each index, higher values correspond to poorer 
environmental quality (Jagai et al. 2017). As PM2.5 is one of the indicators for measuring 
air EQI, that is why we do not consider the air EQI to avoid confounding effects. (2020-01-31)




