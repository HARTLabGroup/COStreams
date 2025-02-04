## Description of the project

This repository contains all code for *Calculating Euclidan and along-river distance between sites*.

## Organization of the project

The project has the following structure:

-   .gitignore

-   Code: All code written for this project

    -   
    -   WordTemplate.docx: A Microsoft Word document used to a style template for generating AspenHabitatModelling.docx

    -   references.bib: A BibTeX file containing all information for all references used in the project

-   Data: All data used in this project

    -   

-   ecology.csl : A [Citation Style Language](https://citationstyles.org/) file used to format references following the formatting style provided by the journal *Ecology*

-   License.md


-   README.md

-   Results: A folder containing all outputs

    -   sites-euclidean.csv: a csv file containing the linear distance between all sites

    -   sites-river.csv: a csv file containing the distance along the river network between all sites

## Description of Analyses and Data

### Code

All analyses are can be run from the script COStreamDist.Rmd. This script uses relative paths with the .rproj file and the "here" package in R to reference each of the datasets and use them in analyses. To repeat our analyses, this project must be open in R Studio software prior to opening the .rmd document.

### Input data

All input data are either stored in this repository or publicly available online. The main script is structured to download data from the internet, however we acknowledge that broken URLs are a common issue. Users should take note that the code is structured to download data only once. Thus care should be taken when users are interested in replacing input datasets with updated versions. The best approach is to delete the entire directory where the data is stored.

## License

This project is licensed under the MIT License - see the Lincese file for details
