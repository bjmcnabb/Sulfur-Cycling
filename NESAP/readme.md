Scripts included here generate a summertime DMS climatology for the NE subarctic Pacific, using ensembled random forest regression and artificial neural network algorithms. 

All DMS data can be found in the NOAA PMEL repository (https://saga.pmel.noaa.gov/dms/). For a full list of predictor data used, see "Satellite_Data_Processing_NESAP.ipynb".

PLEASE NOTE: 
The "Taylordiagram.py" script is from the public domain and is NOT my creation - all credit goes to Yannick Copin (https://gist.github.com/ycopin/3342888). However, this version is included for compatability and is modified to do the following:
- includes functionality that enables the user to normalize the standard deviations (and RMSE contours) to the reference data. This also replaces the x-axis label with "Standard deviation (norm.)" when enabled.
- includes functionality that enables a legend and text boxes to be added to the figure.
- changes the correlation tick values/locations.
- changes the reference point to a gold star adn increases it's size.