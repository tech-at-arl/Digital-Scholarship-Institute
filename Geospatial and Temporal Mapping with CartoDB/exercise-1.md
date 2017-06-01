# **Lesson**

## **Exercise 1 - Create a basic map with points (30 - 40 minutes)**

This first exercise will be demonstrated by the instructor, step by step, and then participants will attempt to visualize this dataset and explore the Carto UI.

1. Login to the Carto dashboard

   * Find "Your datasets" where you will upload new datasets.

   * Find "Your maps" where you will be able to see your published maps.


2. Go to the [City of Boston Open Data](https://data.boston.gov/group/geospatial), find the **Buildings** dataset and download the **CSV file.**


3. In your Carto dashboard go to "Datasets" and click on "New Dataset"

   * Select your file "Buildings.csv" and click on "Connect Dataset" to upload it

   * Click on the dataset in your dashboard and you will be able to view the table

   * Find the Part_Center and Part_Center_1 columns (Q, R)

      * Click on the three vertical dots next to the column header "Part_Center" and select "rename column." Rename it to "Longitude."

      * Click on the three vertical dots next to the column header "Part_Center_1" and select "rename column." Rename it to "Latitude."

   * Click on "Create map" (bottom right corner)


4. You will now see a map view with a sidebar with layers and widgets

   * You should see "positron labels," "buildings,", and "positron – basemap"

   * Your buildings map will not have any points, because it is not georeferenced.


5. Let's georeference your map

   * Click on the **Buildings** layer in the sidebar and then the "georeference" button.

   * In the "Parameters" section – identify the columns that contain latitude and longitude values. Click "apply."


6. Your map now has points!

   * Zoom in to Boston to see the points on your map.

   * You'll notice that your sidebar now has additional menu items

      * Data, Analysis, Style, Pop-up, Legend
     * We will return to these items later.

   * Notice that you can toggle between your data table and map view in the bottom right corner of your map.


7. Questions before moving on?
