# AI-Augmented Analytics for Data Visualization: Module 4: Data Preparation

Prompts are on the course page.

## Installation

1. Download and unzip this project, or clone this repository.
2. Install R and Quarto. Open the `.Rproj` file in RStudio, or open the folder in Positron.
3. Run `source("setup.R")` once in the R console.
4. Use the module guide prompt to complete `scripts/01_data-prep.R` and `notebooks/01_data-prep-review.qmd`.
5. Run `source("scripts/01_data-prep.R")` from the project folder to prepare the data.
6. Render the review with `quarto render notebooks/01_data-prep-review.qmd` from the project folder.

## Contents

- `scripts/01_data-prep.R`: data inspection, preparation, and export.
- `notebooks/01_data-prep-review.qmd`: review of the prepared sample, exclusion counts, and exploratory plot.
- `inputs/raw/nhanes_2021_2023_analysis.csv` and its codebook in `inputs/raw/codebooks/`.
- `inputs/final/`: generated sample and exclusion counts. Git ignores this directory.
- `setup.R`: required R packages.
- `_quarto.yml`: notebook rendering settings.
