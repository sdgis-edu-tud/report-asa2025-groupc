---
editor_options: 
  markdown: 
    wrap: 72
---

# Report group C for the Applied Spatial Analytics 2025 course (BK TU Delft)

This is a repository of group C report produced in the Applied Spatial
Analytics 2025 course at TU Delft. The goal was to use Multi Criteria
Decision Analysis and Typology construction (k-means clustering) to
analyse potentials of urban stream restoration of the river Teplica in
Senica, Slovakia.

### Authors and contact information

Viola Ebermannová (MSc track Urbanism, BK TU Delft) –
v.ebermannova\@student.tudelft.nl, <https://github.com/violae>

Hongyue Kang (MSc track Urbanism, BK TU Delft) – hongyuekang\@tudelft.nl

Kelly Schoonderwoerd (MSc Geomatics, BK TU Delft) –
K.R.Schoonderwoerd\@student.tudelft.nl)

### Directory structure

directory folder: **report-asa2025-groupc**. (In list, folders are
listed in bold and files are listed in italics.)

-   **data**

    -   *analysisgeometry_aggregated_allattributes.gpkg* – file used in
        report for typology construction - K-means clustering

    -   *MCDA.gpkg* – geopackage layer with weighted and normalised
        criteria and MCDA analysis results.

-   **img** – various images used throughout the report, named based on
    location in report

-   **pdf** – various pdfs used throughout the report, named based on
    location in report (99\_ = appendix)

-   **report_files** – files from typology construction by k-means
    clustering algorithm written in R within the report .qmd file

-   *CITATION* – recommended citation

-   *LICENSE* – license file

-   *README.md*

-   *report.qmd* – THE MAIN REPORT QMD FILE

-   *ReproducibilityChecklist.md* – a reproducibility checklist for the
    purposes of reproducibility self assessment

-   files and folder for proper working of the directory

    -   .**github -\>** *.keep*

    -   .*gitignore*

    -   .*Rhistory*

    -   *.asa2025-report.Rproj* – RStudio project file

    -   *report.html*

### Software and hardware needed

This project was processed using laptops with following software and
tools:

-   [QGIS](https://qgis.org/) – spatial analysis and data visualisation

-   [PST plugin for
    QGIS](https://smog.chalmers.se/projects/pst-plugin-for-qgis/) –
    space syntax analysis

-   [Google Earth Engine](https://earthengine.google.com/) – NDVI and
    Land Surface Temperature analyses, using scripts inside of the
    engine

-   [RStudio desktop](https://posit.co/download/rstudio-desktop/) –
    editing report, clustering algorithms written in
    [R](https://www.r-project.org/)

-   [Quarto](https://quarto.org/)– the report is a Quarto markdown file

### Data availability

Data is available in the **data** folder.

### Feedback

In the **Pull requests** section of your repository, you will find a
**Feedback** pull request. We will use this pull request to provide
feedback on your report throughout the quarter. You can also use this
pull request to ask questions about the feedback.

### Asking for help

If you have questions about the assignment, please ask them in
[Discussions](https://github.com/sdgis-edu-tud/asa2025/discussions).
