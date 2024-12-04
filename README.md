# Redlining Environmental Justice

A geospatial analysis project focused on exploring the undersampling of biodiversity in redlined neighborhoods.

## Description

This project uses environmental justice, inequality, and biodiversity data to explore how historical redlining has hurt those communities and impacted the sampling of biodiversity in those areas. Redlining is the practice of grading neighborhoods and impacting home ownership in those areas. Neighborhoods graded as "bad" are typically those that hold a high proportion of minorities. These practices have shown to negatively affect the neighborhoods' health and economy. Studies have shown that these areas do not communicate in community science as much, hence the undersampling of biodiversity in these areas.

## Getting Started

### Dependencies

Ensure you have the following prerequisites installed:

R (version 4.0 or later)   

R packages: tmap, sf, dplyr, ggplot2, kableExtra

Quarto for rendering reports

Operating System: macOS, Linux, or Windows 10+

### Installing

Clone the repository from GitHub Classrooms:

https://github.com/efairbanks000/redlining-environmental-justice.git

Your repository structure should look like this:

```
redlining-environmental-justice
│   README.md 
│   analysis.qmd 
│   .gitignore 
│
└───data  
    └───ejscreen  
    │       EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
    │
    └───gbif-birds-LA  
    │       gbif-birds-LA.shp
    │
    └───mapping-inequality  
            mapping-inequality-los-angeles.json
```


## Authors

Eric Fairbanks

efairbanks@ucsb.edu

## Acknowledgments

I want to thank Ruth Oliver, Ale Vidal Meza, and my EDS 223 peers who helped with data accessibility, inspiration, and troubleshooting issues.
