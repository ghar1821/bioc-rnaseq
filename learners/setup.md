---
title: Setup
---

Ensure that you have the most recent versions of R and RStudio installed on your computer. 
For detailed instructions on how to do this, you can refer to the section "If you already have R and RStudio installed" 
in the [Introduction to R](https://carpentries-incubator.github.io/bioc-intro/#r-and-rstudio)
episode of the [Introduction to data analysis with R and Bioconductor](https://carpentries-incubator.github.io/bioc-intro) lesson.

Additionally, you will also need to install the following packages that will be used throughout the lesson. 

```r
install.packages("BiocManager")
BiocManager::install(c("tidyverse", "SummarizedExperiment",
                       "ExploreModelMatrix", "org.Mm.eg.db",
                       "DESeq2", "vsn", "ComplexHeatmap",
                       "RColorBrewer", "hexbin", "cowplot",
                       "clusterProfiler", "enrichplot", "kableExtra"))
```

*If you are attending a workshop, please complete all of the above before the workshop. Should you need help, an instructor will be available 30 minutes before the workshop commences to assist.*







