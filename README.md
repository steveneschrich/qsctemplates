# qsctemplates

This is a package for storing RMarkdown templates that are suitable for use in the
PHSU-MCC Partnership (https://www.phsu-moffitt.org/). In particular, the Quantitative Sciences Core, or QSC (https://www.phsu-moffitt.org/qsc) uses this for analysis reports.

## Installing
To install this package, use
```
devtools::install_github("steveneschrich/qsctemplates")
```
Note there may be a few dependencies to install in addition, but that should happen automatically. 

## Using qsctemplates
It is very easy to use QSC templates in RStudio. Navigate to `File -> New File -> RMarkdown`
and scroll through to find the relevant template. That will open a template markdown that
you can then work from.

Note, if you use R by itself you can always perform the following:
```
dsreportr::new_markdown("qsctemplates::qsc_pdf")
```
That will create a new `Untitled.Rmd` in the current directory with the template.
