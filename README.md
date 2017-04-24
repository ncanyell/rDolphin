# rDolphin

## Please run these commands in the R console to install the package:

1. `install.packages(c("devtools","knitr","rmarkdown","rprojroot","evaluate","yaml","htmltools","shiny","spam","maps","gtable","scales","dendextend","base64enc","dplyr","purrr","tidyr","viridisLite","seriation","randomForest","itertools","TSP","fit.models","rrcov","RJSONIO","DEoptimR"))`               (installation of packages necessary in next steps, as well as installation of all dependencies from packages called by rDolphin not adequately installed by install_github) 
2. `devtools::install_github("ThomasSiegmund/D3TableFilter")`             (installs D3TableFilter) 
3. `source("https://bioconductor.org/biocLite.R"); biocLite("MassSpecWavelet")`            (installs MassSpecWavelet) 
4. `devtools::install_github("danielcanueto/rDolphin", build_vignettes = TRUE)`           (installs rDolphin)
5. `library(rDolphin)`          (loads rDolphin)

If, at some moment, the installation fails, probably the reason is a missing dependency. Please read on the console for "there is no package called" messages, install the package required with `install.packages` and run `devtools::install_github("danielcanueto/rDolphin", build_vignettes = TRUE)` again.


## Introduction to the package:

For a quick look to the capabilitites of the package, examples of sessions of profiling of MTBLS1 and MTBLS242 Metabolights data sets are available on the next links:

MTBLS1: https://www.dropbox.com/s/8onmpp9hsngtgjc/MTBLS1_example.RData?dl=0

MTBLS242: https://www.dropbox.com/s/zlk2vo0e0iu1z0f/MTBLS242_example.RData?dl=0

To load e.g. the MTBLS242 profiling session, run “Dolphin_GUI()” to open the GUI and click on the "Reanudate a saved session" button on the left panel. 


A vignette is available for the use of functions outside the GUI and can be run with this command `browseVignettes("rDolphin")`. An introductory tutorial for the use of rDolphin inside the GUI is available on this link: https://docs.google.com/document/d/12OJHLgs4dbboBQJHUP0YExfIeZQV8l7n4HQmkWZBWwo/edit

## Tab Images of MTBLS1 session:

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331880/df9f75e2-28e4-11e7-8e85-ae117f279d17.png)

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331884/dfa2235a-28e4-11e7-8874-7c60968d392b.png)

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331878/df9d5ca8-28e4-11e7-99d4-9bd89e3d8174.png)

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331882/dfa16046-28e4-11e7-87b0-d10e6a7f71e8.png)

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331883/dfa1f56a-28e4-11e7-923f-792896f612d5.png)

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331881/dfa12748-28e4-11e7-9932-d120a31cef72.png)




