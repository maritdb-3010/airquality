# Airquality around Amsterdam
This files explains how the data retrieved from https://www.luchtmeetnet.nl/ is changed.

## Steps towards cleaned data
1. On https://www.luchtmeetnet.nl/, and under 'Reports' the data is retrieved. NO2 is chosen as component in a mean year hour report. The range is set between 2015-2020.
2. The data is opened in Excel.
3. For each year, a seperate tab is created, and each NO2 value with the corresponding year is added to these tabs.
4. The tables with the data, are cleaned by creating a heading for each colomn. **NOTE:** Each colomn starts with a letters and not with numbers. 
Additionally, everything that doesn't fit in the rectangular array is removed.

## Units of measurements
The retrieved values of NO2 are in microgram/m3
