#ResearchMethodsL7 — Teaching Scripts & Templates
This repository contains all the R scripts we work through in class during the Research Methods for Health & Performance MSc component.

Materials are organised by the same teaching modules we follow during the course.
You’ll also find an interesting-figures/ section with reusable, generic scripts ready to adapt to your own data.
Goal: help you use RStudio confidently for your coursework and, especially, for your dissertation.
Getting started
Download/clone the repo and open ResearchMethodsL7.Rproj in RStudio.
Install needed packages (only once):
install.packages(c(
  "tidyverse","readr","ggplot2","rstatix","effectsize",
  "broom","patchwork","knitr","rmarkdown"
))
)
Each script begins with a small Setup section (packages, paths, and set.seed()); edit the paths to point to your data.
Repository structure
Module-01_* /, Module-02_* /, …
Scripts mirroring the teaching modules (e.g., normality checks, correlations, linear models, effect sizes, etc.).
interesting-figures/
Ready-to-adapt templates (e.g., distribution plots & Q–Q, correlation heatmaps, effect-size plots, APA-ready ggplot theme, model diagnostics, power sketches).
outputs/figures/ and outputs/tables/ (created by scripts as needed).
Please do not commit raw or confidential data to this repository.
How to use the scripts
Replace the example dataset (usually called df) with your own and run the script top to bottom.
Most plotting scripts save figures to outputs/figures/ with informative filenames.
Where relevant, you’ll see comments indicating what to edit (column names, factors, labels).
Figures & reporting
For assessed work, ensure figures meet APA 7th expectations (titles, captions, legible axes, file resolution). Helpful guidance: https://apastyle.apa.org/style-grammar-guidelines/tables-figures/figures.
Questions & support
Bring queries to workshops or open an Issue on this repository—include a minimal reproducible example if possible.
Licence
Unless stated otherwise, materials are released under the MIT License for educational use.
