# Personal Website

## Author
Louise Oh 

## Deployed Website
[View my website here](https://louiseoh18.github.io/biostat777-intro-louise-oh/)

## Technical Details

This website was built using **Quarto**, an open-source scientific and technical publishing system.

* **Editing:** Built locally in RStudio.
* **Analysis:** The `Example Analysis` page was rendered from a `.qmd` file, executing R code chunks.
* **R Packages Used:**
    * `tidyverse` 
        * `dplyr`, `tidyr` for data wrangling 
        * `ggplot2` for data visualization
    * `knitr`, `DT` for data tables
    * `NHANES` for dataset
* **Deployment:** This site is deployed using [GitHub Pages](https://pages.github.com/). The `_quarto.yml` file is configured to output the rendered HTML to the `/docs` folder, which is set as the publishing source in the repository settings.