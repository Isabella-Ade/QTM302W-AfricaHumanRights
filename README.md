# Human Rights in Continental vs. Island African Nations
This project is a final assignment for QTM302W: Technical Writing at Emory University. 

#### -- Project Status: Completed

## Project Intro/Objective
The purpose of this project is to explore notable findings when conducting exploratory data analysis on [CIRI Human Rights](http://www.humanrightsdata.com/) data. Across academic studies and cultural contexts, distinct regional trends emerge in how human rights are upheld around the globe. Countries that are considered ‘developed or first-world’ have better human rights scores than those in the Global South or considered ‘underdeveloped or third-world.' However, this pattern is disrupted when it comes to the smaller island nations on the African continent. These small island-states often perform substantially better than continental countries in matters of human rights and democracy. 

This phenonmena led to project objectives: the examination of how human rights protections differ between mainland African nations and African island nations and the exploration of variable predictors within island nations. It serves this field of human rights and democracy studies to uncover whether geographic, cultural, or religious factors may affect these scores, and whether there might be better groupings than geography to study human rights on the African continent. This research enters the conversation in regional human rights by examining the distinct performance of African island nations, a rarely explored subset that challenges prevailing geographic assumptions. An understanding of how island nations in Africa defy the common trend can be an insight into democracy and human rights applied to other continental regions, expanding the research and cultural knowledge on how countries achieve and maintain human rights for their citizens.  

### Methods Used
* Descriptive Analysis
* Data Visualization
* Regression Analysis

### Technologies
* R

## Project Description
* Data:
  - The human rights data draws from the [Cingranelli–Richards (CIRI) Human Rights Dataset](http://www.humanrightsdata.com/) (Version 2014.04.14), which includes annual data for 202 countries from 1994–2014. The dataset measures state respect for human rights based on analyses of the U.S. Department of State Country Reports on Human Rights Practices and Amnesty International documentation. While this dataset includes various indicators, this project focuses on the indicators physical integrity index, women's economic rights, and women's poitical rights.
  - The area, population, and GDP data come from [Africapolis](https://africapolis.org/en/about) which is a database created in the collabortion of the [Sahel and West Africa Club](https://www.oecd.org/en/about/directorates/sahel-and-west-africa-club.html) and the [e-Geopolois World Population Database](https://e-geopolis.org/en/home/).  
* The quantitative analysis draws on CIRI human rights indicators to track trends over time for the selected nations. To evaluate the role of  “smallness,", islands are ranked by population in each decade, with additional considerations to GDP and land area to capture characteristics that may shape human rights outcomes. Performance trends of these island nations are then compared against those of mainland African states as well as data analysis of the potential correlation between population and GDP with the observed human rights scores.
* Research Question: What potential influencing factors within the island nations are the best predictors of WECON, WOPOL, and PHYSINT scores?
* Hypothesis: We expect a correlation between island nations’ economic status with women’s economic scores, and a correlation between population size with women’s political rights scores.

## Needs of this project & Next Steps

* As of 12/09/2025, project status is **COMPLETED**
* More robust data for African nations and further analyzation of indicators within island nations and across the continent. Case studies focusing on certain island nations or comparing an island to a continental country. 

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](data) within this repo.    
3. Data processing/transformation scripts are being kept [here](processing_files). This includes the exploratory data analysis and the resulting methods/regression analysis. 

## Featured Notebooks/Analysis/Deliverables
* [EDA Code Notebook](processing_files/QTM302W_CodeNotebook.Rmd)
* [Methods Notebook](processing_files/QTM_Methods)
* [Final Presentation Slide Deck](https://www.canva.com/design/DAG4m_r5J6A/Q6H31-i1aBazY3jZXD_MVg/view?utm_content=DAG4m_r5J6A&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h6afd4a0708)

## Repository Structure 
```
.

├── data/

  │ ├── CIRI_data/

  │ └── africapolis_data/

├── processing_files/

  │ ├── QTM302W_CodeNotebook.Rmd

  │ └── QTM_Methods.Rmd

├── renv

├── .gitattributes

├── .gitignore

├── QTM302W-Group_Project.Rproj

├── README.md

└── renv.lock

```

## Contributing Project Members

|Name     |  Email  | 
|---------|-----------------|
|[Isabella Adeola](https://github.com/[Isabella-Ade])| isabella.adeola@emory.edu   |
|[Christina Dai](https://github.com/[chris-tinad])| christina.dai2@emory.edu   |
|[Hank Standaert](https://github.com/[hankstandaert]) |     hank.standaert@emory.edu    |

## Contact
* Feel free to contact any of the project members with any questions or if you are interested in contributing!
