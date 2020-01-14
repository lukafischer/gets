# gets
The R Package *gets* provides General-to-Specific (GETS) modelling of the mean and variance of a regression, and Indicator Saturation (ISAT) methods for detecting and testing for structural breaks in the mean. Facilities for *user-specified* GETS and ISAT methods are also provided

# Installation
The following R command installs the stable version from CRAN:

    install.packages('gets', dependencies = TRUE)

To install the development version available here at Github, first download the tarball (i.e. the file named gets_x.xx.tar.gz). Next, run:

    system("R CMD INSTALL --build gets")

Alternatively, you can try installing directly from GitHub with the following code (remember to change x.xx):

    install.packages(
      "https://github.com/gsucarrat/gets/raw/master/gets_x.xx.tar.gz",
      repos = NULL, type = "source"
    )
    
# Resources
* An introduction (PDF): [https://doi.org/10.18637/jss.v086.i03](https://doi.org/10.18637/jss.v086.i03)
* User-specified GETS and ISAT (PDF): [https://mpra.ub.uni-muenchen.de/96148/](https://mpra.ub.uni-muenchen.de/96148/)
* Webpage: [http://www.sucarrat.net/R/gets](http://www.sucarrat.net/R/gets)
* CRAN webpage: [https://CRAN.R-project.org/package=gets]( https://CRAN.R-project.org/package=gets)
* [https://felixpretis.climateeconometrics.org/software/](https://felixpretis.climateeconometrics.org/software/)

# License
This package is free and open source software, licensed under GPL (>= 2)
