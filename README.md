# GRID - Global Repository of Infectious Disease Data (GRID)
## QAQC and Summary Statistics

## Status: Preliminary DRAFT
### - Internal DART Use Only: Please do not circulate or quote -

## Dataset Coverage
- All GRID data

## Data source
- Origin: sickistats2 on GDrive

## Prepared by
- Preston and Murray (@ EcoHealth Alliance NYC)

## Caveats
- These results are intended to guide QAQC of the GRID database for modeling 
- **Data entry and validation efforts are ongoing**
- The summ report is automated and **formatting may vary**.

## Intended Recipients:
- **EHA DART:** Nico Preston, Carla Tilchin, Alexa Frank, Zach Gold
- **EHA:** Kris Murray

## Steps
- Launch iPython Notebook
    ipython notebook --pylab inline
- Open grid_summ.ipynb

### to update data
- Open and run code in grid_load.ipynb
- This generates a new data file (coreEIDs.csv)

## Outputs
Main figures can be seen here
http://goo.gl/QvIJC2

## Files
todo.md - contains pending todo items
grid_load.ipynb - iPython Notebook with data ingester for GDrive api
grid_summ.ipyng - iPython Notebook with summary stats

