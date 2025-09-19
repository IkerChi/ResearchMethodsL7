# Research Methods L7 — Teaching Scripts & Templates (University of Chichester)

This repository contains all the **R scripts used in class** during the *Research Methods for Health & Performance* MSc component.  
Materials are **organised by the same teaching modules** we follow during the course.  
You’ll also find an **`interesting-figures/`** section with **reusable, generic scripts** ready to adapt to **your own data**.

> **Goal:** help you use **RStudio** confidently for coursework and especially for your **dissertation**.

---

## What’s inside

- `Module-01_* /`, `Module-02_* /`, …  
  Scripts mirroring the **teaching modules** (e.g., normality checks, correlations, linear models, effect sizes).
- `interesting-figures/`  
  Ready-to-adapt templates such as:
  - Distribution plots & **Q–Q** checks
  - Correlation heatmaps
  - Regression diagnostics
  - Effect-size plots (Cohen’s *d*, Hedges’ *g*)
  - An **APA-ready ggplot theme**
- `outputs/figures/` and `outputs/tables/` (created by scripts as needed)

> Please **do not commit raw or confidential data** to this repository.

---

## Getting started

1. **Clone or download** the repo and open `ResearchMethodsL7.Rproj` in RStudio.
2. **Install packages** (one-off):
   ```r
   install.packages(c(
     "tidyverse","rstatix","effectsize","broom",
     "patchwork","readr","ggplot2","knitr","rmarkdown"
   ))
3. **Each script begins with a small Setup block (packages, paths, set.seed()).** 
 - Edit file paths to point to your data.
 - Run the script top → bottom.
 

Each script begins with a small Setup section (packages, paths, and set.seed()); edit the paths to point to your data.
Repository structure
Module-01_* /, Module-02_* /, …
Scripts mirroring the teaching modules (e.g., normality checks, correlations, linear models, effect sizes, etc.).
interesting-figures/
Ready-to-adapt templates (e.g., distribution plots & Q–Q, correlation heatmaps, effect-size plots, APA-ready ggplot theme, model diagnostics, power sketches).
outputs/figures/ and outputs/tables/ (created by scripts as needed).
Please do not commit raw or confidential data to this repository.

## How to use the scripts
Replace the example dataset (usually called df) with your own and run the script top to bottom.
Most plotting scripts save figures to outputs/figures/ with informative filenames.
Where relevant, you’ll see comments indicating what to edit (column names, factors, labels).

## Figures & reporting

For assessed work, ensure figures meet APA 7th expectations (titles, captions, legible axes, file resolution). Helpful guidance: https://apastyle.apa.org/style-grammar-guidelines/tables-figures/figures.


## Questions & support

Bring queries to workshops or open an Issue on this repository—include a minimal reproducible example if possible.


## Licence

Unless stated otherwise, materials are released under the MIT License for educational use.




