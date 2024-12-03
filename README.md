# expandrank

this repository houses the most recent version of the **expandrank** command for expanding and ranking observations in Stata.  

you can install the **expandrank** from SSC:

    ssc install expandrank

or from GitHub:

    net install expandrank, from("https://raw.githubusercontent.com/jankabatek/expandrank/master/ado/") replace

## How to use expandrank
    . sysuse auto, clear  
    . expandrank 20
    . browse

New: expandrank now supports expanding by variable values

    . sysuse cancer, clear 
    . expandrank studytime
    . browse 
