# 872_Final
# NTL-LTER Lake Datasets


## Summary
This is the course final project prepared for the Environmental Data Analytics class (ENV 872) at Duke University, Spring 2019.

Phytoplankton growth depends on the availability of carbon dioxide, sunlight, and nutrients. This project uses data from studies on several lakes in the North Temperate Lakes District in Wisconsin, USA as part of the Long Term Ecological Research station established by the National Science Foundation. The purpose of this project is to find out the relationship between phytoplankton abundance (biovolume) and nutrients (nitrogen and phosphorus) using regression analysis. There are 2 datasets used in this project, which are the nutrients dataset and phytoplankton dataset of the lakes.

## Database Information
Data were collected from the North Temperate Lakes Long Term Ecological Research website at https://lter.limnology.wisc.edu/about/overview

Nutrients data were retrieved from course raw data folder. Phytoplankton data was retrieved from the NTL-LTER data website (https://lter.limnology.wisc.edu/data).

From the data homepage, I searched the key word 'cascade phytoplankton' and downloaded the following dataset:

* Cascade Project at North Temperate Lakes LTER Core Data Phytoplankton 1984 - 2015

csv files were saved as `NTL-LTER_Lake_Nutrients_Raw.csv`,  and `NTL-LTER_Lake_Phytoplankton_Raw.csv` in the 'raw' data folder. 

Phytoplankton dataset was accessed on 2019-03-11.

## Data Content Information
From the NTL-LTER site: 
### Nutrients
Physical and chemical variables are measured at one central station near the deepest point of each lake. In most cases these measurements are made in the morning (0800 to 0900). Vertical profiles are taken at varied depth intervals. Chemical measurements are sometimes made in a pooled mixed layer sample (PML); sometimes in the epilimnion, metalimnion, and hypolimnion; and sometimes in vertical profiles. In the latter case, depths for sampling usually correspond to the surface plus depths of 50percent, 25percent, 10percent, 5percent and 1percent of surface irradiance. The 1991-1999 chemistry data was obtained from the Lachat auto-analyzer. Like the process data, there are up to seven samples per sampling date due to Van Dorn collections across a depth interval according to percent irradiance. Voichick and LeBouton (1994) describe the autoanalyzer procedures in detail. Nutrient samples were sent to the Cary Institute of Ecosystem Studies for analysis beginning in 2000. The Kjeldahl method for measuring nitrogen is not used at IES, and so measurements reported from 2000 onwards are Total Nitrogen.

Methods for 1984-1990 were described by Carpenter and Kitchell (1993) and methods for 1991-1997 were described by Carpenter et al. (2001).

Carpenter, S.R. and J.F. Kitchell (eds.). 1993. The Trophic Cascade in Lakes. Cambridge University Press, Cambridge, England.

Carpenter, S.R., J.J. Cole, J.R. Hodgson, J.F. Kitchell, M.L. Pace,D. Bade, K.L. Cottingham, T.E. Essington, J.N. Houser and D.E. Schindler. 2001. Trophic cascades, nutrients and lake productivity: whole-lake experiments. Ecological Monographs 71: 163-186.

### Phytoplankton
Data on epilimnetic phytoplankton from 1984-2015, determined by light microscopy from pooled Van Dorn samples at 100 percent, 50 percent, and 25 percent of surface irradiance. St. Amand (1990) and Cottingham (1996) describe the counting protocols in detail. Samples after 1995 were counted by Phycotech Inc. (http://www.phycotech.com). Sampling Frequency: varies; Number of sites: 5

Samples counted prior to 1996 were assigned one taxon name with all taxonomic information. This taxon name was split into distinct columns of genus, species and description for archival as best possible. Samples from 2013-2015 were sent to Phycotech inc. (http://www.phycotech.com/) to be counted.

For details see:
Cottingham, K.L. 1996. Phytoplankton responses to whole-lake manipulations of nutrients and food webs. Ph.D. thesis, University of Wisconsin-Madison.

Cottingham, K.L., and S.E. Knight. 1995. Effects of grazer size on the response of mesotrophic lakes to experimental enrichment. Water Science and Technology 32(4): 157-163.

Cottingham, K.L. and S.R. Carpenter. 1998. Population, community and ecosystem variates as ecological indicators: phytoplankton response to whole-lake enrichment. Ecological Applications 8: 508-530.

Elser, J.J. and S.R. Carpenter. 1988. Predation driven dynamics of zooplankton and phytoplankton communities in a whole lake experiment. Oecologia 76: 148 154.

St. Amand, A. 1990. Mechanisms Controlling Metalimnetic Communities and the Importance of Metalimnetic Phytoplankton to Whole Lake Primary Productivity. Ph.D. Thesis, University of Notre Dame, Notre Dame, Indiana.

Notes:
Notes: All data prior to 2013 were taken from a prior version of this dataset. There appear to be inconsistencies in concentration, mean volumes and biovolumes, ant total volumes and biovolumes for data before and after 1991. Users should be aware that these inconsistencies may make some comparisons across the entire data set inappropriate.


## Naming conventions and file formats
Files are named according to the following naming convention: `databasename_datatype_details_stage.format`, where: 

**databasename** refers to the database from where the data originated

**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data 

**stage**refers to the stage in data management pipelines (e.g., raw, cleaned, or processed)

**format** is a non-proprietary file format (e.g., .csv, .txt)


## Additional Information and Support
For more information, please contact **Siying Chen** (siying.chen@duke.edu)