# internet-use-mental-health

This is the code repository for the paper "Positive association between Internet use and mental health among adults aged ≥50 years in 23 countries". It contains directories for code and data.

## Directory
### code
- **0_package_installation**: installation essential software packages required for the project.
- **1_data_processing**: R Markdown files (*.Rmd) for data processing.
- **2_analysis**: R Markdown files (*.Rmd) for data analysis and visualization. Specifically, **analysis.Rmd** requires the processed data in the **processed** file.

### data
- **country_level_factors.xlsx**: collected country-level factors.
- **raw**: original data files obtained from the [offical website](data\raw\README.md) of each cohort.
- **processed**: processed data files.

## System requirements
All codes were originally processed using:

- System hardware:
  - R version 4.3.3 (2024-02-29 ucrt)
  - Platform: x86_64-w64-mingw32/x64 (64-bit)
  - Running under: Windows 10 x64 (build 19045)
&nbsp;
- Software:
  
| name_version | name_version | name_version |
|---------|---------|---------|
| broom.mixed_0.2.9.5    | data.table_1.15.4   | doParallel_1.0.17     |
| dplyr_1.1.4            | foreach_1.5.2       | forcats_1.0.0         |
| geepack_1.3.11         | gfoRmula_1.0.4      | ggplot2_3.5.1         |
| ggpubr_0.6.0           | ggsci_3.2.0         | ggtext_0.1.2          |
| glue_1.7.0             | gt_0.11.0           | gtsummary_1.7.2       |
| haven_2.5.4            | iterators_1.0.14    | lme4_1.1-35.5         |
| lmerTest_3.1-3         | lubridate_1.9.3     | marginaleffects_0.21.0|
| Matrix_1.6-5           | metadat_1.2-0       | metafor_4.6-0         |
| mice_3.16.0            | miceadds_3.17-44    | modelsummary_2.1.1    |
| numDeriv_2016.8-1.1    | patchwork_1.2.0     | purrr_1.0.2           |
| readr_2.1.5            | readxl_1.4.3        | sjlabelled_1.2.0      |
| skimr_2.1.5            | stringr_1.5.1       | survival_3.7-0        |
| tibble_3.2.1           | tictoc_1.2.1        | tidyr_1.3.1           |
| tidyverse_2.0.0        |                     |                       |

## License
This project is available under the MIT license.

## Contact
Yan Luo - luo.yan@my.cityu.edu.hk