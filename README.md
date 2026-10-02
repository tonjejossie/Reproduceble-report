# A simple analysis of iris data

This repository was created for homework in version control
and collaborative scientific coding.

## Aim

The report explores how petal length varies between three
iris species: setosa, versicolor, and virginica.

## Data and analysis

The analysis uses the built-in iris dataset in R, containing
150 flowers, with 50 observations per species.

The report includes:
- Background and a research question
- A boxplot of petal length by species
- A table with sample sizes, means, and standard deviations
- A reference to R, formatted using APA style

## Files

- `report.qmd`: report text and R code
- `resources/references.bib`: bibliography
- `resources/apa.csl`: citation style
- `.gitignore`: excludes generated output and temporary files
- `.Rproj` file: opens the project in RStudio

## Requirements

The project requires R, Quarto, and the R packages knitr
and rmarkdown. RStudio is recommended.

If needed, install the packages from the R console:

```r
install.packages(c("knitr", "rmarkdown"))
```

## How to reproduce the report

1. Clone or download this repository.
2. Open the .Rproj file in RStudio.
3. Open report.qmd.
4. Click Render to generate report.html.

Alternatively, run this command in a terminal from the
project folder:

```bash
quarto render report.qmd
```

The data are included in R, so no separate data download
is required. All analysis code is included in report.qmd.

## Version control and collaboration

Changes are saved in small commits with descriptive messages.
The report is rendered and checked before committing changes
to the analysis.

Generated HTML output is excluded from version control.
Suggestions and improvements are welcome through pull requests.