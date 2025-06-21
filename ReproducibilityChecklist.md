The following checklist can be used to assess the level of reproducibility of our project.

## Documentation

-   [x] Is there a README file that indicates
    -   [x] the purpose of the project,
    -   [x] who to contact with questions,
    -   [x] a map of the directory structure, and
    -   [x] a description of what software and hardware is needed to reproduce your workflow?
-   [x] Are there README files in each folder describing the contents of the folder, how they were acquired/generated?
-   [x] Is there a CITATION file that tells users how to site the project, data, and code?
-   [x] Does the project have a LICENSE file?
-   [x] Is the project's repository publicly available?

## Data

-   [x] Is the data included or linked, with instructions on how to obtain the data?
-   [ ] If data is not included, is this because it is not necessary or generated as part of the project?
-   [ ] Are your raw data (if any) and processed data files separated?
-   [ ] If data is not open:
    -   [ ] Is it accessible via a protocol?
    -   [ ] Is there synthetic data provided so the project can be run?
-   [ ] Is citation information available for the data?
-   [x] Does the data use open formats, such as CSV and TXT?

## Software

-   [ ] Is there a list of dependencies?
-   [ ] Is a container available to run the project?
-   [ ] Are version number of every external application used in the process?
-   [ ] Does your project use only open software?

## Workflow and automation

-   [x] Is the workflow clearly documented (with or without code)?
-   [x] Is your workflow scripted, i.e., using code?
-   [x] Is your code well documented?
-   [x] Is your code modular, i.e., does it use functions?
-   [ ] Are unit tests available for the code?
-   [ ] Does your repository make use of continuous integration tools to insure internal reproduciblity?

## Organization

-   [x] Are all data, code, results, and documentation housed within a monophyletic folder structure?
-   [ ] Is your project folder structured to separate your data, code, documentation, and results?
-   [x] Can the project be run from the project's root folder?
-   [x] Is the project under version control?
-   [x] Do files use a consistent naming scheme that indicates what they contain?

## Publication

-   [x] Are papers and reports from the project generated using literate programming tools so that results are not hard-coded?
-   [x] Does the project have a persistent identifier?

[The template of this list](https://github.com/Rbanism/repro-r-workshop/blob/main/documents/checklist.md) was created by [Claudiu Forgaci (cforgaci)](https://github.com/cforgaci), and inspired by the more extensive [Checklist Questions to stimulate thought about a Project's Reproducibility](https://github.com/datacarpentry/rr-intro/blob/gh-pages/checklist.md) which the RBanism team recommends you consider for making your work reproducible.
