# Run the functions 

Download the two files, in the *Sample_data* of this repo.

Open R studio.

Click on Session → Set Working Directory → Choose Directory

And then select the directory where you downloaded the files - metadata11.txt and microbiome11.csv

Load the library.

```r
library(mbX)
```

Run newer version of ezclean.

```r
ezclean("microbiome11.csv", "metadata11.txt", "g")
```
You will have the output into a dedicated directory in your working directory.

Run newer version of ezviz.

```r
ezviz("microbiome11.csv", "metadata11.txt", "g", "BMIClass", top_taxa = 10, flip = "True")
```

You will have the outputs into a dedicated directory in your working directory.

Run the brand new ezstat function.

```r
ezstat("microbiome11.csv", "metadata11.txt", "g", "BMIClass")
```
You will have the outputs into a dedicated directory in your working directory.
