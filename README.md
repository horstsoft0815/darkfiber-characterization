# darkfiber-characterization

This repository belongs to the project: Dark-Fiber Characterization for Entanglement Polarized QKD.
It contains various investigations and analyses of measurement data from a polarimeter. A total of two data sets were analyzed:
1. Nordhausen - Sundhausen (29/11/24 - 03/12/24)
2. Erfurt - Sundhausen (20/02/25 - 27/02/25)

These were processed and evaluated using the same methods.
Each data set has its own directory, which has the following functionality and structure:

directory-structure:
 - nordhausen_sundhausen: all files and results for dataset from 29/11/24 to 03/12/24 (Nordhausen to Sundhausen)
   - pdf: generated pdf-files for each jupyter-notebook
   - img: special images from notebooks and additonal images
   - jupyter-notebook-files
 - erfurt_sundhausen: all files and results for dataset from 20/02/25 to 27/02/25 (Erfurt to Sundhausen)
   - pdf: generated pdf-files for each jupyter-notebook
   - img: special images from notebooks and additonal images
   - jupyter-notebook-files

file-description:
- overview.ipynb: overview in measured values, errors, nulls, sizes and first impression
- daily.ipynb: check selected measured values in daily courses/trends (dependency on time)
- weather.ipynb: loading interpolated weather data und check for connection to measured data
- detailed_ellipticity.ipynb: detailed evaluation for ellipticity data
- open-meteo_nordhausen.csv: saved weather data

