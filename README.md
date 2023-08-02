# Useful R Packages

Many useful R functions come in packages, free libraries of code written by R's active user community. To install an R package, open an R session and type the following command at the command line:

```R
install.packages("<the package's name>")
```

R will download the package from CRAN, so you'll need to be connected to the internet. Once you have a package installed, you can make its contents available to use in your current R session by running:

```R
library("<the package's name>")
```

There are thousands of helpful R packages for you to use, but navigating them all can be a challenge. To help you out, we've compiled this guide to some of the best. We've used each of these and found them to be outstanding – we've even written some of them. But you don't have to take our word for it; these packages are also some of the top most downloaded R packages.

## To Load Data

- **DBI**: The standard for communication between R and relational database management systems. Packages that connect R to databases depend on the DBI package.
- **odbc**: Use any ODBC driver with the odbc package to connect R to your database. Note: RStudio professional products come with professional drivers for some of the most popular databases.
- **RMySQL**, **RPostgresSQL**, **RSQLite**: If you'd like to read in data from a database, these packages are a good place to start. Choose the package that fits your type of database.
- **XLConnect**, **xlsx**: These packages help you read and write Microsoft Excel files from R. You can also just export your spreadsheets from Excel as .csv's.
- **foreign**: Provides functions that help you load data files from other programs into R, including SAS and SPSS data sets.
- **haven**: Enables R to read and write data from SAS, SPSS, and Stata. R can also handle plain text files – no package required. Just use the functions read.csv, read.table, and read.fwf. If you have even more exotic data, consult the CRAN guide to data import and export. For more information about using R with databases, see [db.rstudio.com](https://db.rstudio.com).

## To Manipulate Data

- **tidyverse**: An opinionated collection of R packages designed for data science that share an underlying design philosophy, grammar, and data structures. This collection includes all the packages in this section, plus many more for data import, tidying, and visualization listed here.
- **dplyr**: Essential shortcuts for subsetting, summarizing, rearranging, and joining together datasets. dplyr is our go-to package for fast data manipulation.
- **tidyr**: Tools for changing the layout of your datasets. Use the gather and spread functions to convert your data into the tidy format, the layout R likes best.
- **stringr**: Easy-to-learn tools for regular expressions and character strings.
- **lubridate**: Tools that make working with dates and times easier.

## To Visualize Data

- **ggplot2**: R's famous package for making beautiful graphics. ggplot2 lets you use the grammar of graphics to build layered, customizable plots.
- **ggvis**: Interactive, web-based graphics built with the grammar of graphics.
- **rgl**: Interactive 3D visualizations with R.
- **htmlwidgets**: A fast way to build interactive (JavaScript-based) visualizations with R. Packages that implement htmlwidgets include:
  - leaflet (maps)
  - dygraphs (time series)
  - DT (tables)
  - diagrammeR (diagrams)
  - network3D (network graphs)
  - threeJS (3D scatterplots and globes).
- **googleVis**: Lets you use Google Chart tools to visualize data in R. Google Chart tools used to be called Gapminder, the graphing software Hans Rosling made famous in his TED talk.

## To Model Data

- **tidymodels**: A collection of packages for modeling and machine learning using tidyverse principles. This collection includes rsample, parsnip, recipes, broom, and many other general and specialized packages listed here.
- **car**: car's Anova function is popular for making type II and type III Anova tables.
- **mgcv**: Generalized Additive Models.
- **lme4/nlme**: Linear and Non-linear mixed effects models.
- **randomForest**: Random forest methods from machine learning.
- **multcomp**: Tools for multiple comparison testing.
- **vcd**: Visualization tools and tests for categorical data.
- **glmnet**: Lasso and elastic-net regression methods with cross-validation.
- **survival**: Tools for survival analysis.
- **caret**: Tools for training regression and classification models.

## To Report Results

- **shiny**: Easily make interactive web apps with R. A perfect way to explore data and share findings with non-programmers.
- **R Markdown**: The perfect workflow for reproducible reporting. Write R code in your markdown reports. When you run render, R Markdown will replace the code with its results and then export your report as an HTML, PDF, or MS Word document, or an HTML or PDF slideshow. The result? Automated reporting. R Markdown is integrated straight into RStudio.
- **xtable**: The xtable function takes an R object (like a data frame) and returns the LaTeX or HTML code you need to paste a pretty version of the object into your documents. Copy and paste, or pair up with R Markdown.

## For Spatial Data

- **sp**, **maptools**: Tools for loading and using spatial data, including shapefiles.
- **maps**: Easy-to-use map polygons for plots.
- **ggmap**: Download street maps straight from Google maps and use them as a background in your ggplots.

## For Time Series and Financial Data

- **zoo**: Provides the most popular format for saving time series objects in R.
- **xts**: Very flexible tools for manipulating time series datasets.
- **quantmod**: Tools for downloading financial data, plotting common charts, and doing technical analysis.

## To Write High-Performance R Code

- **Rcpp**: Write R functions that call C++ code for lightning-fast speed.
- **data.table**: An alternative way to organize datasets for very, very fast operations. Useful for big data.
- **parallel**: Use parallel processing in R to speed up your code or to crunch large datasets.

## To Work with the Web

- **XML**: Read and create XML documents with R.
- **jsonlite**: Read and create JSON data tables with R.
- **httr**: A set of useful tools for working with HTTP connections.

## To Write Your Own R Packages

- **devtools**: An essential suite of tools for turning your code into an R package.
- **testthat**: testthat provides an easy way to write unit tests for your code projects.
- **roxygen2**: A quick way to document your R packages. roxygen2 turns inline code comments into documentation pages and builds a package namespace. You can also read about the entire package development process online in Hadley Wickham's R Packages book.

---

Feel free to use and modify this README.md to
