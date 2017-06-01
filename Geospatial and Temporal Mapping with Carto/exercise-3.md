# **Exercise 3** 

## **Create layers and add polygons to your map (40 minutes)**

Working with your partner - we will now look at how to create layers and create polygons. We will discuss the difference between points and polygons, how layers work, what is possible when you have layers, etc.

1. Go to the [Boston Landmarks Commission Historic Districts](https://data.boston.gov/dataset/boston-landmarks-commission-blc-historic-districts)dataset and download the **Shapefile. **Find the **Sea Level Rise** Plus 5 Feet dataset and download the **Shapefile**. You will also use the cleaned Boston Landmarks Commission **Landmarks** dataset.

2.  In your Carto map view, click on "Add" in the sidebar to add these datasets to your existing map.
     * Click on "Connect Dataset" and browse for your file
     * Do not unzip the zip file and select "Add layer"

3. You'll be taken back to your map view once you add the layer and will see polygons appear on your map.

4. Repeat step II for the next two datasets.

5. You will now see the points and polygons on your map. You will also see the four layers (A, B, C, D) in your sidebar.

6. Explore the different layers
   * Find the eye icon and turn off the layers that you are not currently working with.
   * Reposition the order of the layer cards in the sidebar to see the appearance change.

7. Style your layers
   * Start with **Historic Districts**
   * Click on the **Historic Districts** layer to go into the style menu
   * Click on "fill" and select "by value" to color code the polygons by "place_name"
     * Polygons will be color coded by neighborhood
     * Explore stroke and blending for additional style options 
     * For example: Blending with multiply will make the polygon transparent and allow building points to show through the layer.
       * Select "labels" to add labels for each "place_name" and can style additional features.
       * Note: If map already contains labels for neighborhoods/districts/towns then the label will be duplicative.
   * Repeat styling for each layer
      * Decide whether you want to color code specific values or have one color for the entire layer.
      * For **Building** and **Landmarks** points – you can also use icons, such as a house.
      * **Note**: You can turn off other layers to view only the one you are styling. If you prefer using CSS, you can use the CSS editor in Carto.
    * Review styling and go back to your layers if you want to change the appearance.

8.  Add an info window using the "Pop-up" option
     * Select data to display
    * You can also edit this in the HTML editor

9.  Change your basemap
     * In your layers sidebar, click on the "basemap" card and choose a source and style to modify the basemap.
     * You can also pull in a basemap from an external source (WMS, mapbox, tiles, etc.)

10. Edit Map options, metadata, and name
    * Click the options icon under the pencil in the left blue sidebar
      * Select the map options that will be available when map is published
      * Can include the options to turn on/off specific map layers
    * Click on the three vertical dots next to the map name
      * Edit the metadata (rename map, add description, and tags)
      * Export your map as a .carto file

11. Rename your layers and widgets so they make sense to someone viewing your map online.
