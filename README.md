RmdTemplates
============

R package containing templates for authoring manuscripts for various journals. 
For now the package only contains templates for all journals from PLoS, the 
Public Library of Science (all PLoS journals share the same basic template). 
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

The template should now be accessible via "File > New File > R Markdown... > 
From Template"