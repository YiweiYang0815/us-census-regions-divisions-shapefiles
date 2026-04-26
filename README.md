# U.S. Census Regions and Divisions Shapefiles

This repository provides GIS-ready shapefiles and crosswalk tables for the four U.S. Census regions and nine Census divisions defined by the U.S. Census Bureau.

The goal of this repository is to fill a gap: while the U.S. Census Bureau defines the Northeast, Midwest, South, and West regions, as well as the nine Census divisions, convenient ready-to-use shapefiles for these groupings are not always easy to find.

## Contents

This repository includes:

- A crosswalk table linking U.S. states to their Census region and Census division
- A shapefile for the four U.S. Census regions:
  - Northeast
  - Midwest
  - South
  - West
- A shapefile for the nine U.S. Census divisions
  - New England
  - Middle Atlantic
  - East North Central
  - West North Central
  - South Atlantic
  - East South Central
  - West South Central
  - Mountain
  - Pacific

**The generated crosswalk table and shapefiles for U.S. Census regions and divisions can be found in the `outputs` folder.**

## Source

Region and division definitions are based on the U.S. Census Bureau reference map:

U.S. Census Bureau. *Census Regions and Divisions of the United States*.  
https://www2.census.gov/geo/pdfs/maps-data/maps/reference/us_regdiv.pdf

The U.S. state boundary shapefile was downloaded from the U.S. Census Bureau TIGER/Line Shapefiles 2025 state-level dataset:

U.S. Census Bureau. *TIGER/Line Shapefiles: 2025 State Boundaries*.  
https://www2.census.gov/geo/tiger/TIGER2025/STATE/

A copy of the downloaded state shapefile is also included in the `data` folder of this repository.

## Environment Setup

Before running the notebook, create and activate a Python virtual environment.

## Intended Use

These files are intended for researchers, students, analysts, and GIS users who need convenient spatial boundaries for U.S. Census regions and divisions.
