RmdTemplates
============

R package containing templates for authoring manuscripts for various journals
using the [rmarkdown language (v2)](http://rmarkdown.rstudio.com/) developed by 
the good people from [RStudio](http://www.rstudio.org/). 

For the moment the package only contains templates for all journals from [PLoS, 
the Public Library of Science](http://www.plos.org/) (as far as I can tell all 
PLoS journals share the same basic template). 

More journals will come as I write articles for them, or as contributors offer 
their own templates :-)

---

To install the package, run the following line in the R console: 

```R
if (!require("devtools")) {
  install.packages("devtools")
}
devtools::install_github("morpionz/RmdTemplates")
``` 

The template should now be accessible in [RStudio](http://www.rstudio.org/) via 
"File > New File > R Markdown... > 
From Template"