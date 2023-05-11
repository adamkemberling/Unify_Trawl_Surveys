# Unify Trawl Surveys

## About

This repository documents the data engineering steps for unifying the major State, Federal and International fisheries-independent trawl survey programs of the Northwest Atlantic. Creating a unified data product for multi-species species distribution modeling of the shelf habitat of this region.

### Organization

Project documentaion is organized by original data sources of which there are five:
 1. NOAA Northeast Trawl Survey
 2. DFO Trawl Survey
 3. Maine / New Hampshire Inshore Trawl Survey
 4. Massachusetts Inshore Trawl Survey

Each data source has been given a directory detailing how the data source was acquired with details about the survey program. These folders contain the R code used for any reshaping or transformation steps.

### Survey Data Unification Workflow

Following any initial reshaping steps, the five data sources are then combined into a single unified data resource. Details on this process have been outlined in the `survey_integration` directory, with workflow order detailed using the {targets} package.


#### Partners
 * Northeast Fisheries Science Center (US)
 * Department of Fisheries and Oceans (Canada)
 * Maine Department of Marine Resources (US)
 * New Hampshire Fish and Wildlife (US)
 * Massachusetts Division of Marine Fisheries (US)

####  Funding

Funding for this project will be detailed shortly.
