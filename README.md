# GY7702-Assignment-2
CW2: Data Science Project - Assignment 2

## Introduction <a name="introduction"></a>
This is a repository for the [**GY7702 R for Data Science**](https://le.ac.uk/modules/2020/gy7702) assignment at the University of Leicester. 

Option B was selected from the assignment and the code, output and analysis are presented in GY7702_Assignment_2.Rmd.

This assignment entails developing skills in exploratory data analysis and geodemographic classification. With the data focused in the 2011 Output Area Classification for the assigned LAD and the main document was created in RMarkdown.  

## Table of contents 
* [General info](#introduction)
* [Prerequisites](#prerequisites)
* [Datasets](#datasets)
* [References](#references)

## Prerequisites <a name="prerequisites"></a>
The dependencies for the assignment are:
* [tidyverse](https://www.tidyverse.org/)
* [magrittr](https://magrittr.tidyverse.org/)
* [lubridate](https://lubridate.tidyverse.org//)
* [knitr](https://yihui.org/knitr/)
* [ggplot2](https://ggplot2.tidyverse.org/)
* [psych](https://cran.r-project.org/web/packages/psych/index.html)
* [GGally](https://ggobi.github.io/ggally/)
* [fmsb](https://rdrr.io/cran/fmsb/man/radarchart.html)

## Main Datasets <a name="datasets"></a>

* 2011_OAC_Raw_kVariables.csv: a dataset containing the 60 final variables used by [**Gale et al (2016)**](http://josis.net/index.php/josis/article/view/232/150) to create the 2011 Output Area Classification (2011OAC, see also [**Chris Gale’s GitHub pages**](http://geogale.github.io/2011OAC/));
* 2011_OAC_Raw_kVariables_Lookup.csv: a table containing all the information (metadata) about the 60 variables included in 2011_OAC_Raw_kVariables.csv;
* OA11_LSOA11_MSOA11_LAD11_EW_LUv2.csv: a dataset indicating for each census Output Area (OA), the Lower-Super Output Area (LSOA), Middle-Super Output Area (MSOA) and Local Authority District (LAD) that contain it (see also [**UK Census geography**](https://www.ons.gov.uk/methodology/geography/ukgeographies/censusgeography))
* covid_cases_total_MSOA_20201123.csv: a dataset listing the total number of covid-19 cases for each MSOA in England (see also [**Coronavirus (COVID-19) in the UK website**](https://coronavirus.data.gov.uk/))

## References <a name="references"></a>

This assignment would like to acknowledge that this document includes teaching materials from Dr Stefano De Sabbata for the module [GY7702 R for Data Science](https://le.ac.uk/modules/2020/gy7702). And the associated teaching materials can be found [here](https://sdesabbata.github.io/granolarr/)

R for Data Science by Garrett Grolemund and Hadley Wickham, O’Reilly Media, 2016. [See online book](https://r4ds.had.co.nz/) 

This repository / document contains public sector information licensed under the [Open Government Licence v3.0](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/): 2011_OAC_Raw_kVariables.csv, 2011_OAC_Raw_kVariables_Lookup.csv, OA11_LSOA11_MSOA11_LAD11_EW_LUv2.csv and covid_cases_total_MSOA_20201123.csv. See also [**Gale et al (2016)**](http://josis.net/index.php/josis/article/view/232/150), [**Chris Gale’s GitHub pages**](http://geogale.github.io/2011OAC/), [**UK Census geography**](https://www.ons.gov.uk/methodology/geography/ukgeographies/censusgeography), [**Coronavirus (COVID-19) in the UK website**](https://coronavirus.data.gov.uk/) and [**Office for National Statistics**](https://geoportal.statistics.gov.uk/).

