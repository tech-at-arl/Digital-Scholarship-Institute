## **Exercise 2 - Review and normalize data (20 - 30 minutes)**

Any data visualization requires clean, normalized data. Let's review the **Landmarks** dataset to see which data points need cleaning or normalization. Find a partner and work together.

1. Navigate to the Boston Landmarks Commission **Landmarks** dataset. Addresses can be georeferenced and points plotted. With some data cleanup to normalize the dates we can also create a temporal map (time lapse) of when landmarks were designated. The landmarks can then be plotted as points and represented as icons (statues).

2. Download the Boston Landmarks Commission **Landmarks** CSV file and open it in Google Sheets.

3. We will go over data normalization, specifically looking at temporal and spatial data.

*1. Clean up the "date_desig" column so that the dates appear in this format: YYYY-MM-DD. If no date is provided, use 0000-00-00.

*2. Highlight the column

*    1. In Google Sheets menu select Format → Number → More Formats → More Date and Time Formats

*    2. Select the YYYY-MM-DD option and apply to your column

*3. We will also geocode the address data.

1. Add Geocode by Awesome Table as an Add-on to your Google Sheets.

2. Select "Start Geocoding"

*1. Identify the "Address" and "Neighborhood" as the two columns to be geocoded.

*2. This will create a new column labeled "Full Address" and also a "Latitude" and "Longitude" column.

3. Finish geocoding and download the spreadsheet as a CSV file.

4. Upload into Carto as a layer to your existing map.

*    1. Open the tableview in Carto and change data type for "date_desig" column to "date" otherwise Carto will read this as a string and not process it as temporal data.

*1. Style the points and identify landmarks with an icon.

*    1. Open CartoCSS and increase the marker-width to adjust the icon size.

*2. Add pop-up info window with details about the landmark.

*3. Create a widget.
