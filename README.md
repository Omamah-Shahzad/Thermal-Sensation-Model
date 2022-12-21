# Thermal-Sensation-Model
For this project I am applying machine learning models (both regression and classification) to the dataset which contains information about various individuals, their clothing, and its properties along with other atmospheric elements such as temperature, pressure humidity etc. The users also provided feedback on if they feel cold or not. The feedback (through AMV and PMV) which is based on the following mapping:
The following table shows the mapping of sensations:

 | Value | Thermal Sensation | 
 | ------|:-----------------:| 
 | +3    | hot               | 
 | +2    | warm              |  
 | +1    | slightly warm     |   
 |  0    | neutral           | 
 | -1    | slightly cool     |  
 | -2    | cool              |   
 | -3    | cold              | 

The dataset is given in an excel file named CollectedData.xlsx, see sheet 2 of excel file. The dimension names (column headers) are not mentioned in the given file. The table below describes the columns which will be of interest.

 |Column number	| Feature Name | Feature Description              |
 | -------------|:------------:| :-------------------------------:|
 | 3	          | Age	         | Age                              |
 | 22	          | Clo	         | Clothing insulation              |
 | 19	          | Met	         | Met Rate                         |
 | 26	          | Dewpt	       | Dewpt                            |
 | 27	          | PlaneRadTemp | plane radiant temperature        |
 | 37	          | Ta	         | Average air temperature          |
 | 38	          | Tmrt	       | Average mean radiant temperature |
 | 40	          | Vel	         | Air Velocity                     |
 | 42	          | AirTurb	     | Air Turbulance                   |
 | 43	          | Pa	         | Vapor Pressure                   |
 | 44	          | Rh	         | Humidity                         |
 | 74	          | TaOutdoor	   | Outdoor Air Temperature          |
 | 77	          | RhOutdoor	   | Outdoor Humidity                 |
 | 8	          | AMV	         | Classification response variable |
 | 49	          | PMV	         | Regression response variable     |
