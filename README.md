# NOAA Fisheries Memo to Record

This is a template for a NOAA Fisheries Memo to Record in Quarto. 

## Installation (Simple Method)

To install, the package first install the `noaafisherieswcr` package from GitHub:

```r  
remotes::install_github("rfortherestofus/noaafisherieswcr")
```

From there, you can run the following code in the console to create a new Memo to Record Quarto file:

```r
library(noaafisherieswcr)
create_new_memo_to_record()
```

This will create a new Quarto file that you can use as a starting place for your memo. You can edit or add any content you want to this Quarto file before rendering it, which will create a Word document that you can then edit as you see fit. 