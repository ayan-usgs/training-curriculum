---
author: Lindsay R. Carr
date: 9998-01-01
slug: Additional
title: Additional Topics in R
image: 
menu:
  main:
    parent: Introduction to R Course
    weight: 2
---
Spatial Analyses
----------------

-   Jeff Hollister at EPA has a great demo for recreating GIS workflows in R: <http://jwhollister.com/rgis_lightning_demo/>
-   `ggmap` is a great package that uses lat/long data as the inputs, follows similar syntax to `ggplot2`: <https://journal.r-project.org/archive/2013-1/kahle-wickham.pdf>
-   You can make interactive maps that are saved as HTML files using `leafletr`: <https://rstudio.github.io/leaflet/>
-   Another RStudio intro to leaflet: <http://blog.rstudio.org/2015/06/24/leaflet-interactive-web-maps-with-r/>

Date Handling
-------------

Dates can be in a few different formats: character, numeric, POSIXlt, and POSIXct \* Blog post about character and numeric formats: <http://www.r-bloggers.com/date-formats-in-r/> \* Article about the Date class and POSIX classes (also has lots of useful examples): <http://biostat.mc.vanderbilt.edu/wiki/pub/Main/ColeBeck/datestimes.pdf> \* Useful R package: `lubridate`, <https://cran.r-project.org/web/packages/lubridate/lubridate.pdf> \* Article describing date classes, the R packages `chron` and `lubridate`, and small intro to plotting with dates: <http://www.noamross.net/blog/2014/2/10/using-times-and-dates-in-r---presentation-code.html>

Matrices
--------

-   Matrices vs data frames: <http://civilstat.com/2012/04/matrix-vs-data-frame-in-r/>
-   Quick intro to creating matrices: <http://www.r-tutor.com/r-introduction/matrix>

Trend Decomposition
-------------------

-   STL: `?stl` in the `stats` package, which is always loaded with base R, and <http://www.wekaleamstudios.co.uk/posts/seasonal-trend-decomposition-in-r/>
-   openair package (Kendall-Mann, Seil-Then): <http://www.openair-project.org/>, <https://cran.r-project.org/web/packages/openair/index.html>

Handling/Exporting Output
-------------------------

-   For tabular data, format it as a data frame. Then use the `write.csv` or `write.table` functions to export it
-   For exporting plots, there is a button in the plots tab in RStudio called “Export”. For in-line exporting of plots, you can save it in many formats using these functions: `jpeg()`, `png()`, `pdf()`, `svg()`, `postscript()`

ggplot2
-------

-   Mailing list, documentation, info on books, and installation info: <http://ggplot2.org/>
-   Cheatsheet for `ggplot2`: <https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf>
-   Slide show introduction: <https://opr.princeton.edu/workshops/Downloads/2015Jan_ggplot2Koffman.pdf>

Rmarkdown
---------

Creating dynamic PDFs, word documents, or HTMLs. A place to have code and text all in one document. \* Basic introduction to what R Markdown really is and how to apply it: <http://rmarkdown.rstudio.com/> \* USGS uses R Markdown (NWIS Reporting Application - release date sometime in 2016)!! \* Cheatsheet for R Markdown: <https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf>

Other
-----

-   Cheatsheet for `dplyr` and `tidyr` (cleaning up data frames): <https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf>
-   Shiny!
-   Overall summary: <http://shiny.rstudio.com/>
-   Cheatsheet <https://www.rstudio.com/wp-content/uploads/2015/02/shiny-cheatsheet.pdf>
-   Example: exploreEGRET <https://waterdatascience.shinyapps.io/exploreEGRET/>
-   Version control w/ Git and GitHub: <http://happygitwithr.com/index.html>
