# BHL-Thesis

## BACKGROUND

These data files accompany my doctoral thesis, "Virtual Bio-Diverse Relationships and Digital Knowledges: Latin America in and through the Biodiversity Heritage Library" as a partial requirement for my Ph.D. in Hispanic Studies at McGill University. These files include metadata extracted from the database and catalogue of the *Biodiversity Heritage Library* (BHL). Several of these files are also available through [BHL's GitHub repository](https://github.com/gbhl/bhl-us-data-sets/tree/master/Metadata-LatinAmerica) as I produced them as part of an internship research project in the summer of 2021. This internship was funded by McGill University and supervised by BHL Program Director, Martin Kalfatovic. I further describe this project in a two-part blog series with BHL. See [Part 1](https://blog.biodiversitylibrary.org/2021/11/understanding-bhl-through-metadata-patterns-of-bio-diverse-knowledge-production.html) and [Part 2](https://blog.biodiversitylibrary.org/2021/11/geopolitics-of-metadata-knowing-panama-through-biodiversity-heritage-library.html).
The part of my dissertation concerning these files constitutes an analysis of metadata patterns in materials about Latin America in BHL's collection to identify shortcomings in the equitable representation of materials about Latin America, to recognize and counteract biases in the presence and importance of sites of knowledge production in the Global South versus the Global North, and to inform decolonizing strategies and policy. 
Data employed in this project were downloaded from [BHL's data website](https://www.biodiversitylibrary.org/data) as of July 1st, 2021, except for the file Bertholletia excelsa.csv (see SUBSETS DESCRIPTION). 

## FILE FORMAT

Each data file is a comma-separated values file (.csv) containing metadata categories for materials in BHL's collection that include one or more subjects related to Latin America in their subject lists. See the following sections in this file for information about the data found in each file.
Each row in a data file contains between two and thirteen columns. The first row in each file contains the column names. See the following sections in this file for information about the data found in each column. 

## FILE DESCRIPTION

All acronyms for subset names are indicated in parentheses in the next section of this file. 

1. SUB Lists.csv - csv file containing listed subjects per TitleID for all records (146806) that were part of BHL's collection as of July 1st, 2021.

2. Data files - csv files belonging to one of the following groups:
	+ Metadata subsets - csv files including full metadata details for the selected materials. The names of these files follow one of these three patterns:
	
		+ Subset acronym.csv
		+ Subset acronym - Unique.csv
		+ Species name.csv
		
		When the second pattern is used, only unique title IDs for the selected subject are included, i.e. works in volumes, issues, and/or numbers appear as a single record under their shared title ID. When the third pattern is used, the metadata included are the result of an online search by scientific name (included in the file's name) on BHL's catalogue. 

	+ Subject lists - csv files including only listed subjects per TitleID for the selected materials. The names of these files follow this pattern:
		
		+ Subset acronym - SL.csv
		
	+ Word frequencies - csv files including only the most frequent words in each subject list for the selected materials. The names of these files follow this pattern:
		
		+ Subset acronym - WF.csv

## SUBSETS DESCRIPTION

+ Greater Regions (GR) subset - Incorporates all BHL records* (4465) that include at least one of the following subjects: Latin America, Central America, South America, West Indies. 
+ Latin American Countries (LAC) subset - Incorporates all BHL records (6801) that include the name of at least one Latin American country (except Mexico): Argentina, Belize, Bolivia, Brazil,  British Guiana, Chile, Colombia, Costa Rica/Costa-Rica, Ecuador, El Salvador, French Guiana, Guatemala, Guiana/Guyana, Honduras, Nicaragua, Panama, Paraguay, Peru, Surinam/e, Uruguay, Venezuela.
+ Mexico (MEX) subset - Incorporates all BHL records (2995) that include at least one of the following subjects: Mexico; Mexico, North; Mexico, Northern.
+ Indigenous Peoples – General (IP-G) subset - Incorporates all BHL records (1052) that include at least one of the following subjects: Indians of Central America, Indians of Mexico, Indians of South America, Indians of the West Indies, Aztecs, Incas. 
+ Indigenous Peoples – Specific (IP-S) subset - Incorporates all BHL records (135) that include at least one of the following subjects: Carib Indians, Choco Indians, Cuna Indians, Diaquita Indians, Goajiro Indians, Huichol Indians, Kickapoo Indians, Mapuche Indians, Mayas, Mayoruna Indians, Mojo Indians, Shipibo-Conibo Indians, Taino Indians, Tairona Indians, Tarahumara Indians, Yahgan Indians.
+ West Indies (WI) - Contains all unique IDs (228) that include the subject West Indies. 
+ Central-Latin-South America (CLS) - Contains all unique IDs (710) that include at least one of the following subjects: Central America, Latin America, South America. 
+ Central American Countries (CAC) - Contains all unique IDs (485) that include the name of at least one Central American country: Belize, Guatemala, Honduras, Nicaragua, Costa Rica, Panama, El Salvador.
+ South American Countries (except Brazil) (SAC)- Contains all unique IDs (1221) that include the name of at least one South American country (except Brazil): Argentina, Bolivia, Colombia, Chile, Ecuador, Guyana, (French) Guiana, Paraguay, Peru, Surinam/Suriname, Uruguay, Venezuela.
+ Brazil (BR) - Contains all unique IDs (543) that include the subject Brazil.
+ Mexico (MEX SUB) - Contains all unique IDs (917) that include the subject Mexico.
+ Panama (PAN) - Contains all unique IDs (185) that include the subject Panama.
+ Bertholletia excelsa - Incorporates subject lists of all records (680) in BHL as of January 2022 that contain the scientific name *Bertholletia excelsa*. These records were obtained through a scientific name search on [BHL's website] (https://www.biodiversitylibrary.org/).
+ Indians of - ALL (I-ALL) - Incorporates subject lists of all records (417) in BHL that contain a subject beginning with the frase *Indians of* in their subject lists.
+ Indians of Mexico/Indians of Mexico-Central-South America/Indians of the West Indies (IP-G2) - Incorporates all records (158)in BHL that contain one of the following subjects in their subject lists: *Indians of Mexico, Indians of Central America, Indians of South America, Indians of the West Indies*.
+ Indigenous (IND) - Incorporates subject lists of all records (17) in BHL that contain the term *Indigenous* as part of at least one subject referring to Indigenous peoples in their subject lists.

*All data in numbers as of July 1st, 2021 except when otherwise indicated. 

## COLUMN DEFINITIONS

+ TitleID - Identifier of each included material as determined by BHL. 
+ Title - Full title of each included material.
+ Author - Full name of the author(s) and years of birth and death (when appropriate).
+ Holding Institution - Name of the institution that contributes the material to BHL.
+ Year - Year of publication of each included material.
+ StartYear - Year of first volume/issue publication of each included material (for volumes and periodicals).
+ EndYear - Year of final volume/issue publication of each included material (for volumes and periodicals).
+ Full Publication Details - Known publication details exactly as they appear in each included material and/or in BHL's database. 
+ Place of Publication - Place of publication of each included material extracted and cleaned from the "Full Publication Details" column. 
+ Latitude - Latitude coordinate for the place of publication of each included material, as appears in the "Place of Publication" column. 
+ Longitude - Longitude coordinate for the place of publication of each included material, as appears in the "Place of Publication" column.
+ Language - Language code for each included material. 
+ Includes Subject - Subject that appears in each included material for it to be selected as part of a specific subset. 
+ Location of Indigenous group - Geographical location (countries) of the Indigenous group(s) included as subject.
+ TitleURL - BHL URL for each included material. 
+ Listed subjects - Complete list of subjects for each included material as they appear in BHL's database.
+ Words - Most frequent words in a subject list subset, from most frequent to least frequent. 
+ POS - Part of speech of each word in a subject list subset.
+ Frequency - Frequency counts for each word in a subject list subset. 
+ Volume* - Volume or issue of the work where the scientific name is mentioned. 
+ Page* - Specific page in the volume or issue of the work where the scientific name is mentioned. 

*For Bertholletia excelsa.csv only

## IMPORTANT NOTE ON THE PAN SUBSET

Two data files for unique IDs in the PAN subset are included. Data in the second file (PAN - Unique - No missing fields.csv) have been cleaned to reduce the number of missing fields in these records. 