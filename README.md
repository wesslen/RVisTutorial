### Set up

1.  Download the materials in this repository using the "Download Zip" button.

2.  Ensure you have R and R Studio installed on your machine. Open R Studio and run the following command to ensure you have all of the R libraries:

```{r}
packages <- c("flexdashboard","readr","dplyr","lubridate","htmlwidgets","htmltools","KernSmooth","sp","devtools",
              "xts","dygraphs","reshape2","visNetwork","igraph","leaflet")

lapply(packages, install.packages(packages), character.only = TRUE)

devtools::install_github("hrbrmstr/streamgraph")
```
