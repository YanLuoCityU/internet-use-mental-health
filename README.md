# internet-use-mental-health

This is the code repository for the paper "The beneficial impact of Internet use on the mental well-being among adults aged ≥50 years in 23 countries". It contains directories for code, data, and results.

## Directory
### code
- **0_package_installation**: installation essential software packages required for the project.
- **1_data_processing**: R Markdown files (*.Rmd) for data processing.
- **2_analysis**: R Markdown files (*.Rmd) for data analysis and visualization. Specifically, **analysis.Rmd** requires the processed data in the **processed** file, and **analysis_demo.Rmd** uses the demo dataset **demo_data.RData**.

### data
- **country_level_factors.xlsx**: collected country-level factors.
- **raw**: original data files obtained from the offical website of each cohort.
- **processed**: processed data files.
- **demo**: a demo dataset in R Data format (demo_data.RData), which serves as an example for the project.

### results
- **Figure (demo)**: figures generated using the demo dataset.
- **Table (demo)**: tables generated using the demo dataset.

## System requirements
All codes were originally processed using:

- System hardware:
  - R version 4.1.1 (2021-08-10)
  - Platform: x86_64-w64-mingw32/x64 (64-bit)
  - Running under: Windows 10 x64 (build 19044)
&nbsp;
- Software:
  
| name_version | name_version | name_version |
|---------|---------|---------|
| doParallel_1.0.17 | iterators_1.0.14 | foreach_1.5.2 |
| tictoc_1.2 | sjlabelled_1.2.0 | haven_2.5.4 |
| metafor_4.4-0 | numDeriv_2016.8-1.1 | metadat_1.2-0 |
| lmerTest_3.1-3 | lme4_1.1-35.1 | Matrix_1.6-5 |
| glue_1.6.2 | patchwork_1.2.0 | ggtext_0.1.2 | ggpubr_0.6.0 |
| forestploter_1.1.1 | gtsummary_1.7.2 | mice_3.16.0 | skimr_2.1.5 |
| readxl_1.4.3 | lubridate_1.9.3 | forcats_1.0.0 | stringr_1.5.1 |
| dplyr_1.1.2 | purrr_1.0.1 | readr_2.1.5 | tidyr_1.3.0 |
| tibble_3.2.1 | ggplot2_3.4.4 | tidyverse_2.0.0 |

## How to run
You can run the <code>./code/2_analysis/analysis_demo.Rmd</code> using the demo data to achieve all statistical analyses and data visualization in the project.

## License
This project is available under the MIT license.

## Contact
Yan Luo - luo.yan@my.cityu.edu.hk