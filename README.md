# New Methods for Old Questions: Predicting Historical Urban Renewal Areas in the United States

This repo contains the code and data inputs/outputs for an experimental method used to predict 1940s Census tracts that received urban renewal in the article "New Methods for Old Questions: Predicting Historical Urban Renewal Areas in the United States"

Author: [Wenfei Xu](urbandataresearchlab.com)


## Citation
If you would like to use the data and/or code from this repo, please use the following citation: 
```

@article{doi:10.1177/23998083241260778,
author = {Wenfei Xu},
title ={New methods for old questions: Predicting historical urban renewal areas in the United States},

journal = {Environment and Planning B: Urban Analytics and City Science},
volume = {0},
number = {0},
pages = {23998083241260778},
year = {0},
doi = {10.1177/23998083241260778},
URL = { 
        https://doi.org/10.1177/23998083241260778
},
eprint = { 
        htts://doi.org/10.1177/23998083241260778
}
,
    abstract = { Mid-20th century urban renewal in the United States was transformational for the physical urban fabric and socioeconomic trajectories of neighborhoods and its displaced residents. However, there is little research that systematically investigates its impacts due to incomplete national data. This article uses a multiple-model machine learning method to discover 204 new Census tracts that were likely sites of federal urban renewal, highway construction related demolition, and other urban renewal projects between 1949 and 1970. It also aims to understand the factors motivating the decision to “renew” certain neighborhoods. I find that race, housing age, and homeownership are all determinants of renewal. Moreover, by stratifying the analysis along neighborhoods perceived to be more or less risky, I also find that race and housing age are two distinct channels that influence renewal. }
}

```

## Data
The repo contains the following datasets: 
- `CPI_U_RS.csv`: Consumer price index used to adjust home values for inflation. 
- `non_spatial_data.csv`: Urban Renewal projects data details each urban renewal project, size, and city. From the Digital Scholarship Lab.  
- `ur_projects_cleaned.zip`: Shapefile of cleaned Urban Renewal Project boundaries. From the Digital Scholarship Lab and cleaned. 
- `ur_tracts.geojson`: 1940s Census tracts with indicating which tracts had urban renewal according to methods used in the paper. 

## Requirements
These notebooks can be run using the [Geographic Data Science environment](https://github.com/darribas/gds_env). 
