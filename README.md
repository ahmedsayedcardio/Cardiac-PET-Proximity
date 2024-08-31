# Cardiac-PET-Proximity
This is a deposit of the code used to map proximity to cardiac PET centers across the United States.

Please note that, for this project, you will need an active internet connection because some data is downloaded during the R session.

Additionally, the following files need to be downloaded manually as they will be imported during the analysis:
-  To access data for PET services (use codes 78431 and 78492 to filter to the necessary data; name the file: "Medicare PET Data.xlsx"): https://data.cms.gov/provider-summary-by-type-of-service/medicare-physician-other-practitioners/medicare-physician-other-practitioners-by-provider-and-service/data
-  To access data for census tract shape files (file named "tlgdb_2021_a_us_substategeo.gdb"): https://www2.census.gov/geo/tiger/TGRGDB21/
-  To download major metropolitan areas (file named "tl_2021_us_cbsa.shp"; Store contents in a directory subfolder called: "RU Data"): https://catalog.data.gov/dataset/tiger-line-shapefile-2021-nation-u-s-core-based-statistical-areas
-  US Decennial census (2020) data (store excel file as "US Census Tract 2020 Data.xlsx"): https://data.census.gov/all?d=DEC+Demographic+and+Housing+Characteristics
