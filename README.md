# Wings-under-Canopies
### Exploring the relationship between tree cover and bird sightings in Bengaluru

## Project Overview

This undergraduate GIS project explores the relationship between changes in tree cover and recorded sightings of Coppersmith Barbets (*Psilopogon haemacephalus*) between 2018 and 2023.

The Coppersmith Barbet was selected because of its dependence on trees for nesting, foraging and roosting.

## Study Areas

- Hesaraghatta
- Avalahalli State Forest
- GKVK Campus

## Tools and Skills

- QGIS
- R Programming
- Remote sensing
- Spatial data analysis
- Raster and vector processing
- Data cleaning and visualisation
- Ecological interpretation

## Methodology

1. Obtained Coppersmith Barbet occurrence records from eBird through GBIF.
2. Filtered and processed bird occurrence data for the selected study areas.
3. Created study area boundaries in QGIS.
4. Imported and classified bird occurrence points by year.
5. Extracted and clipped tree cover layers to the study area boundaries.
6. Created comparative maps for 2018 and 2023.
7. Analysed temporal trends in bird sightings using R.

## Spatial Analysis

### Hesaraghatta

| 2018 | 2023 |
| --- | --- |
| ![2018](maps/hesaraghatta-2018.png) | ![2023](maps/hesaraghatta-2023.png) |

### Avalahalli State Forest

| 2018 | 2023 |
| --- | --- |
| ![2018](maps/avalahalli-2018.png) | ![2023](maps/avalahalli-2023.png) |

### GKVK Campus

| 2018 | 2023 |
| --- | --- |
| ![2018](maps/gkvk-2018.png) | ![2023](maps/gkvk-2023.png) |

## Preliminary Findings

- The original analysis identified changes in tree cover and recorded bird sightings across the three study areas.
- GKVK Campus showed a decline in reported sightings between 2018 and 2023.
- Avalahalli State Forest showed an increase in reported sightings alongside an apparent increase in tree cover.
- Hesaraghatta exhibited fluctuations in tree cover and bird sightings.

## Limitations

Citizen science records are influenced by observation effort, reporting bias and potential misidentification.

Recorded sightings should not be interpreted as direct estimates of bird population. The analysis is exploratory and does not establish causation between tree cover change and bird sightings.

The original QGIS project and R scripts are no longer available. This repository contains the retained report and exported maps, and the original analysis has not been independently reproduced.

## Data Sources

- OpenStreetMap
- eBird via GBIF
- State of India's Birds
- NASA MODIS


## Project Report

[Read the full project report][wings under canopies.pdf](https://github.com/user-attachments/files/35432990/wings.under.canopies.pdf)

## Academic Context

Azim Premji University  
May 2025
