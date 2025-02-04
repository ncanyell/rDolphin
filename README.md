# rDolphin

10/09/2018: New version 0.2.0: Update to optimize performance and logical structure of the program.

Thanks to Paul Driscoll, Naomi Rankin and Rico Rueedi for their valuable comments.

## Please run these commands in the R console to install the package:

1. `source("https://bioconductor.org/biocLite.R"); biocLite("impute"); biocLite("MassSpecWavelet")` #installation of packages that cannot be installed from Github
2. `install.packages("devtools")`    #installation of package necessary to install rDolphin from Github
3. `devtools::install_github("danielcanueto/rDolphin")`           #installs rDolphin
4. `library(rDolphin)`          #loads rDolphin

If, at some moment, the installation fails, probably the reason is a missing dependency. Please read on the console for "there is no package called" messages, install the package required with `install.packages` and run `devtools::install_github("danielcanueto/rDolphin")` again.


## Introduction to the package:

A vignette is available for the use of functions through the R console (we recommend the use of RStudio or a similar program):

https://github.com/danielcanueto/rDolphin/blob/master/vignettes/rDolphin_introduction.Rmd

A vignette is available for the replication of different Metabolights studies of human urine, blood and faecal extract:

https://github.com/danielcanueto/rDolphin/blob/master/vignettes/MTBLS_profiling_replication.Rmd

Available ROI profiles of fecal extract, blood and urine are available on the "extdata" folder inside the package folder.

------

An (still not updated to last changes) introductory tutorial for the use of rDolphin inside the GUI is available on this link: https://docs.google.com/document/d/12OJHLgs4dbboBQJHUP0YExfIeZQV8l7n4HQmkWZBWwo/edit

For a quick look to the capabilities of the Shiny GUI, examples of sessions of profiling of MTBLS1 (urine), MTBLS237 (faecal extract) and MTBLS374 (blood) Metabolights data sets are available on the next links:

MTBLS1: https://www.dropbox.com/s/k483tfn59e66mkb/MTBLS1_GUI_session.RData?dl=0

MTBLS237: https://www.dropbox.com/s/08kjxpd08vo9tq9/MTBLS237_GUI_session.RData?dl=0

MTBLS374: https://www.dropbox.com/s/nj59fheh903vzpu/MTBLS374_GUI_session.RData?dl=0

To load e.g. the MTBLS1 profiling session, run “rDolphin_GUI()” to open the GUI and click on the "Resume a saved session" button on the left panel. 


## Tab Images of MTBLS1 session:

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331880/df9f75e2-28e4-11e7-8e85-ae117f279d17.png)

![alt text](https://cloud.githubusercontent.com/assets/21126465/25332294/25baf29e-28e6-11e7-8fa5-feeeecfb6493.png)

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331878/df9d5ca8-28e4-11e7-99d4-9bd89e3d8174.png)

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331882/dfa16046-28e4-11e7-87b0-d10e6a7f71e8.png)

![alt text](https://cloud.githubusercontent.com/assets/21126465/25331881/dfa12748-28e4-11e7-9932-d120a31cef72.png)




