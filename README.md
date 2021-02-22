# PMA_Age_Indication
This repository hosts preprocessing and analysis of manually annotated Premarket approval statements (PMA).

Clean_PMA_Analysis notebook has the code surrounding preprocessing, analyzing, and visualizing the number of devices available across age.
This script produces ageAnnot.csv which is used for analysis. This csv has been provided in the data folder.

Query_PMAs notebook has code that queries the FDAOpen API for device metadata using the PMAs.
This script produces openFDAPMA.csv which is used for analysis in the Clean_PMA_Analysis notebook. This csv has been provided in the data folder.
This csv is used later on in the Clean_PMA_Analysis analysis to characterize the types of devices available.

AgeIndication_Gap notebook has code surrounding the lag time in approval between generic device categories (Product code)
