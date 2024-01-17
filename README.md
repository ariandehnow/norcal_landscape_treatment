# norcal_landscape_treatment_sample

## Data_Cleaning
This is a sample of the code I wrote to compile geospatial data on landscape treatment activites across Northern California. It imports data from the RawData folder, then cleans, concatenates, and organizes it before eliminating redundancies. The final output is a neatly structured geospatial database of treatments from different sources that is exported as a shapefile and csv to the JoinedDataExports folder.


## Data_Analysis
This code sample analyzes the dataset created in the previous step. It imports the most recent csv from the JoinedDataExports folder and then aggregates the acreages of different categories of treatment activity by county and watershed group to create an overview table. The overview table is then exported to the OverviewExports folder as a csv. 