# EDS 220 - Assignment 4, Task 2

## Purpose
The purpose of this project is to visualize the impact of wildfires and fire scars using false color imagery. The project focuses specifically on the Thomas Fire in Ventura and Santa Barbara counties which took place in 2017. Through this project we can gain a deeper understanding of how false color imagery, remote sensing, and data visualization can assist in environmental monitoring. The final output of this project is a false color image of the Thomas Fire.

## Repository Setup
This repository contains two notebooks. The notebooks `hwk4-task2-false-color-CARDELLE.ipynb` and `hwk2-task4-fire-perimeter-CARDELLE.ipynb` have exercises for selecting fire perimeters and creating true and false color images.

The `data` folder is included in the `.gitignore`.

## Data Access

The fire perimeter data was obtained from https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436.
The landsat data is from https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2 and was accessed through the server at `/courses/EDS220/data/hwk4_landsat_data landsat8-2018-01-26-sb-simplified.nc`. This data was pre-processed to remove data outside land and coarsen the spatial resolution.

## Acknowledgments
This repository contains materials for the fourth assignment for the course [EDS 220 - Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/). This course is part of the [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science).

