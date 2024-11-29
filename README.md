# Benchmark

## Overview

This repository contains code for conducting benchmark timing on a server. It is designed to facilitate performance evaluation of database operations.

## Getting Started

### Prerequisites

-   **R** and **RStudio** are required to run the code.
-   Ensure that you have access to the database and necessary credentials to connect.

### Setup Instructions

1.  **Download the Repository**\
    Download this repository:
    -   Either download as a ZIP file using `Code -> Download ZIP`, then unzip.
    -   Or, use GitHub Desktop to clone the repository.
2.  **Open the R Project**
    -   Navigate to the `Benchmark` folder and open the project file `Benchmark.Rproj` in RStudio.
    -   You should see the project name in the top-right corner of your RStudio session.
3.  **Run the Analysis Code**
    -   Open the `CodeToRun.R` file. This is the main script you’ll use.
    -   Follow the instructions within the file to add your database-specific information.
    -   Run the code as directed. This will generate a `Results` folder containing the outputs, including a ZIP file with the results for sharing.
4.  **Visualize Results in Shiny**
    -   Navigate to the `shiny` folder and open the project file `shiny.Rproj` in RStudio.
    -   You should see the project name in the top-right corner of your RStudio session.
    -   Copy the generated result files (in .csv format) into the `Data` folder located within the `shiny` folder.
    -   Open the `global.R` script in the `shiny` folder.
    -   Click the *Run App* button in RStudio to launch the local Shiny app for interactive exploration of the results.

The overall results of the benchmark, run by all the data partners involved, will be published in the following Shiny app: <https://dpa-pde-oxford.shinyapps.io/benchmark-hdruk/>
