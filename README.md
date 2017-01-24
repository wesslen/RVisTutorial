### Set up

1.  Download the materials in this repository using the "Clone or download" button and click the "Download ZIP" link. Unzip the file locally.

2.  Ensure you have R and R Studio installed on your machine. Open R Studio and run the following command to ensure you have all of the R libraries:

```{r}
packages <- c("flexdashboard", "readr", "dplyr", "lubridate", "htmlwidgets", "htmltools",
              "KernSmooth", "sp", "devtools", "xts", "dygraphs", "reshape2", "visNetwork",
              "igraph", "leaflet", "plotly", "highcharter")

lapply(packages, install.packages(packages), character.only = TRUE)

devtools::install_github("hrbrmstr/streamgraph")
```

Before we get into the visualizations, we'll start with two introductory tutorials to R from Brooke Anderson's [R Programming for Research](https://github.com/geanders/RProgrammingForResearch) materials: [tutorial 1](https://github.com/geanders/RProgrammingForResearch/raw/master/slides/CourseNotes_Week1.pdf) and [tutorial 2](https://github.com/geanders/RProgrammingForResearch/raw/master/slides/CourseNotes_Week2.pdf). 

For users looking for a great resource on learning R as a whole, I strongly recommend Brooke Anderson's course GitHub repository.

### Visualization Demos

*   [Spatial (Leaflet) Demo](https://rpubs.com/ryanwesslen/241940)

*   [Time Series Demo](https://rpubs.com/ryanwesslen/242027)

*   Network Demo (TBD)

### Links for Tools

*   [RMarkdown](http://rmarkdown.rstudio.com/)

*   [HTMLWidgets](http://www.htmlwidgets.org/)

*   [Flexdashboard](http://rmarkdown.rstudio.com/flexdashboard/)

*   [Shiny](https://shiny.rstudio.com/)

### Links for Publishing

*   [RPubs](https://rpubs.com/)

*   [Shinyapps.io](https://www.shinyapps.io/)

### Great R References

*   [Winston Chang's Cookbook for R](http://www.cookbook-r.com/)

*   [Dean Attali's Shiny Demos](http://deanattali.com/shiny/)

*   [Dean Attali's Shiny Tutorial](http://deanattali.com/blog/building-shiny-apps-tutorial/)
