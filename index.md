---
title       : The NHANES Portal shinyApp  
subtitle    : Retrieving National Health And Nutrition Examination Survey Demographics
author      : Christopher J Endres
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [shiny,interactive] # {mathjax, quiz, interactive, bootstrap}
mode        : selfcontained # {standalone, draft}

---

##  A shinyApp Portal to the NHANES database
### The National Health And Nutrition Examination Survey (NHANES)
* The purpose of the NHANES project is to assess health and nutritional status in the US.
* This unique project combines interviews and physical examinations.
* Data are available to the public and are often used for research.
* Data have been updated continuously since 1999.
* More information is available at the NHANES website <http://www.cdc.gov/nchs/nhanes.htm>

### Functionality of the NHANES shinyApp
* Provides easy access and retrieval of basic NHANES data fields.
* Specifically, it displays a summary of gender, age, ethnicity, and marital status.
* Data are available from 2001-2012, and are reported in 2-year intervals.

---

## Retrieving key NHANES demographics

###### 1: Select desired year
###### 2: Click on 'Show columns'
###### 3: Select desired column
###### 4: Click 'Retrieve demographic data'
###### 5: For clarity, select 'Translate code'
###### 6: Finally, click 'Generate Summary'


### In step 3 the user selects the key demographic to display

* Gender
* Age
* Ethnicity
* Marital Status

Link to the app <https://cjendres1.shinyapps.io/BrowseNHANESdemographics/>

---

## Sample information that is reported

[1] "By default, the NHANES Portal shinyApp reports raw values"

[1] "For example, for the gender demographic for 2007-2008 the first 10 values are:"

Gender 
 [1] 2 2 1 2 1 1 1 1 1 1

[1] "The code (1=Male,2=Female) can be translated at a click of a button to produce :"

 [1] Female Female Male   Female Male   Male   Male   Male   Male   Male  
Levels: Male Female

[1] "The total for each category can be summarized at the click of a button"



|  Gender  |  Total  |
|:--------:|:-------:|
|   Male   |  5096   |
|  Female  |  5053   |

### Test out the app on the next page!

--- #shineserve

<iframe src = 'https://cjendres1.shinyapps.io/BrowseNHANESdemographics/' height = '600px'></iframe>


