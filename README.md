# snag-wlf

**READ ME**

**This repository contains the datasets and code for evaluating the use of lidar to discern snag characteristics important for wildlife: Can we remotely classify snags into structural groups based on treetop intactness & DBH?**

GENERAL INFORMATION

1. Title of Dataset: 
“Data for: Evaluating the use of lidar to discern snag characteristics important for wildlife.” <In preparation for Remote Sensing, 2021>

2. Corresponding Author Information		
	Name: Jessica M. Stitt
	Institution: University of Idaho
	Address: Department of Fish and Wildlife Sciences, 875 Perimeter Drive MS 1136, 
			Moscow, ID, USA, 83844
	Email: jstitt@uidaho.edu

3. Date of data collection: 	
Lidar data acquisition: 2016-10-12; Field data collection: 2017-06-01 through 2017-10-31

4. Geographic location of data collection: 
Idaho Panhandle National Forest, Idaho, USA

5. Information about funding sources that supported the collection of the data: 
This research was funded in part by the NSF Idaho EPSCoR Program and the NASA Idaho Space Grant Consortium, and by a NASA Carbon Monitoring Systems (CMS) Program Award (NNH15AZ06I).

SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: None

2. Links to publications that cite or use the data: 
	Stitt, J.M.; Hudak, A.T.; Silva, C.A.; Vierling, L.A.; Vierling, K.T. (In prep). 
		Evaluating the use of lidar to discern snag characteristics important for 
		wildlife. Remote Sensing.

3. Links to other publicly accessible locations of the data: 
	https://github.com/jessmstitt/snag-wlf

4. Links/relationships to ancillary data sets: NA

5. Was data derived from another source? No

6. Recommended citation for this dataset: 
	Stitt, J.M.; Hudak, A.T.; Silva, C.A.; Vierling, L.A.; Vierling, K.T. (In prep). 
		Data for: Evaluating the use of lidar to discern snag characteristics 				important for wildlife. Remote Sensing.

DATA & FILE OVERVIEW

1. File List: 

**1.1.  snag-wlf_README.xlsx 
		A spreadsheet (.xlsx) describing all columns in each of the four (4) .csv files included with this project.
		
**1.2.  snag-wlf_REFplots_ipnf2017.csv
		A spreadsheet (.csv) with information on the 25m-radius survey plots that served as the basis of field data collection.
		
**1.3.  snag-wlf_REFsnags_ipnf2017.csv
		A spreadsheet (.csv) with information on the individual snags within survey plots, including spatial coordinates, structural features, and additional wildlife-relevant features.
		
**1.4.  snag-wlf_REFplots_topo-r25m.csv
		A spreadsheet (.csv) including lidar-derived topographic metrics for each survey plot, averaged across the full 0.2ha plot, including elevation, slope, and transformed aspect (trasp).
		
**1.5.  snag-wlf_REFsnags-d05m_chars-Mx-clean.csv 
		A spreadsheet (.csv) including all individual snags included in this study (n = 198). Information for each snag includes field-derived characteristics, as well as lidar-derived metrics (including standard, structural, and topographic). Lidar metrics were calculated from a 2.5m radius circle around snag central coordinates.
		
**1.6.  snag-wlf_rf-mod.rmd
		R markdown (.rmd) file containing all R scripts & packages used for analyses for this project, including lidar pre-processing, lidar metric calculations, and Random Forest (RF) modeling.

2. Relationship between files, if important: 
File 1.1. describes the headers used in the columns of File 1.2 – 1.5; File 1.6 uses File 1.2 and 1.3 as the basis to derive the metrics found in Files 1.4 and 1.5.

3. Additional related data collected that was not included in the current data package: 
Airborne lidar data acquisitions were flown for the USFS RMRS, and additional information on these datasets can be found within the associated publication linked to this dataset, as well as within: 
	Fekety, P. A., Falkowski, M. J., Hudak, A. T., Jain, T. B., & Evans, J. S. (2018). 
		Transferability of lidar-derived basal area and stem density models within a 
		northern Idaho ecoregion. Canadian Journal of Remote Sensing, 44(2), 
		131-143. https://doi.org/10.1080/07038992.2018.1461557

4. Are there multiple versions of the dataset? No


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
All methods used for collecting and generating data can be found in the associated publication linked to this dataset.

2. Methods for processing the data: 
Methods for processing the data can be found in the R Markdown of File 1.6 and are described in the associated publication linked to this dataset.

3. Instrument- or software-specific information needed to interpret the data: 
Data analyses were performed using the software R (v.4.0.3); all necessary packages and code to perform analyses can be found in the R Markdown of File 1.6.

4. People involved with sample collection, processing, analysis and/or submission: 
Conceptualization, all authors: L.V., K.V., A.H., C.S., and J.S.; methodology, all authors; software, J.S. and C.S.; validation, all authors; formal analysis, J.S.; investigation—lidar data and field-work, J.S. and A.H.; investigation—statistical analyses, J.S. with input from all authors; resources, A.H., L.V., and K.V.; data curation, J.S. and A.H.; writing—original draft preparation, J.S. and K.V.; writing—review and editing, all authors; visualization, J.S. and K.V.; supervision, K.V.; funding acquisition, L.V., A.H., and J.S.
