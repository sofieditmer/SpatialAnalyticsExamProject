# Space Matters: Investigating Geographic Variability of Voting Patterns in English Parliamentary Constituencies Using Spatial Statistics

### Project Description <br>
￼This repository contains the contents of the final exam project in the Spatial Analytics course at Aarhus University conducted in the spring of 2021, as well as all resources and materials needed in order to recreate the contents of the project. <br>
The aim of this project was to conduct a spatial analysis of the 2019 UK election. This spatial analysis includes assessing the degree of spatial autocorrelation among English constituencies, adressing the Modifiable Areal Unit Problem (MAUP) and creating geographically weighted regression models (GWR) that take spatial location of constituencies into account when performing regression analysis of the election data.

### Content and Repository Structure <br>
The repository follows the overall structure presented below. If one wishes to reproduce the contents of this repository everything needed to do so is provided. The necessary data is provided in the data folder. Three scripts are provided in the ```src```  folder both as rmarkdown-files as well as knitted HTML versions: <br>

- ```Preprocessing.html```: This script prepares the data for spatial analysis of the UK general election in 2019. The preprocessing includes several data wrangling steps that prepare the election, demographic, and spatial data for further analysis. The preprocessed data is saved as a shapefile to the data folder. Hence, this script contains the data manipulations needed to get the required dataframe for spatial analysis of spatial features of the general election in 2019 in the United Kingdom. <br>
- ```Spatial_Autocorrelation_Analysis.html```:  This script contains a spatial analysis of the UK election spatial data. The spatial analysis includes the creation of basic visualizations that are used as stepping stones for creating cartograms, performing spatial autocorrelation tests, and addressing the Modifiable Areal Unit Problem (MAUP). <br>
- ```Spatial_Regression_Analysis.html```: This script contains the code for performing a global regression analysis as well as a geographically weighted regression (GWR) analysis.

| Folder | Description|
|--------|:-----------|
| ```data``` | A folder containing the data needed to perform the analyses.
| ```src``` | A folder containing knitted scripts in a html-format as well as the raw scripts in Rmarkdown format. 
| ```LICENSE``` | A file declaring the license type of the repository.

### Usage and Technicalities <br>
To reproduce the results of this project, the user is advised to clone the repository. This is done by executing the following from the command line: 

```
$ git clone https://github.com/sofieditmer/SpatialAnalyticsExamProject.git SpatialAnalysis_UK_Election
```

Once the repository has been cloned, the user is able to run the scripts provided in the ```src```folder. The ```Preprocessing```script has to be executed to produce the preprocessed data that are required to run the other two scripts. <br>

Since the CSV-file containing the postcodes of the constituencies is too large to store on GitHub, the data has been compressed to a zip-file which the user will have to unzip through the command line before being able to use it. To unzip the data the user is asked to execute the following from the command line:

```
cd SpatialAnalysis_UK_Election/data

unzip open_postcode_geo.csv.zip
```

### License <br>
This project is licensed under the MIT License - see the [LICENSE](https://github.com/sofieditmer/SpatialAnalyticsExamProject/blob/main/LICENSE) file for details.

### Contact Details <br>
If you have any questions feel free to contact us on: <br> 
[201805308@post.au.dk](201805308@post.au.dk) OR [201806701@post.au.dk](201806701@post.au.dk)

