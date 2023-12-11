# SpatialDB

## Project Overview

This project involves the creation of a spatial drawing, specifically a cityscape, along with the implementation of various spatial database operations. The tasks encompass spatial drawing creation, layer division, metadata insertion, code implementation for drawing shapes, spatial indexing, visualization, spatial queries, and result analysis.

### Project Tasks

1. **Create Your own Spatial Drawing**
   - Generate a spatial drawing, such as a farm scene, with a focus on a city in France.
   - Include a student ID number visibly located in the upper right corner of the image.

2. **Divide Layers and Create Tables**
   - Divide the drawing into at least 5 layers.
   - Create tables corresponding to each layer, incorporating a minimum of 4 objects with 3-4 different shapes in each layer.

3. **Insert Spatial Metadata**
   - Insert spatial metadata to define the spatial space for subsequent work.

4. **Code Drawing Shapes and Insert Data**
   - Implement the necessary code to represent drawing shapes.
   - Insert both spatial and descriptive data into the respective tables.

5. **Create Spatial Indexes**
   - Establish spatial indexes for efficient retrieval and analysis.

6. **Visualize Drawing**
   - Utilize SQL Developer or another appropriate software to visualize the spatial drawing.

7. **Spatial Queries and Visualization**
   - Create a minimum of 3 spatial queries.
   - Visualize the results of each query.

8. **Conclusions**
   - Summarize the findings and experiences gained throughout the project.

## Project Workflow

To execute the project scripts successfully, follow the order below:

1. **script_table.sql**: Creates necessary tables for the project.
2. **script_metadata.sql**: Inserts spatial metadata defining the spatial space.
3. **script_values.sql**: Inserts geometrical values and descriptive data into tables.
4. **script_spatial_indexes.sql**: Establishes spatial indexes for efficient retrieval.
5. **script_queries.sql**: Defines and executes spatial queries.

I conducted this project using Oracle SQL Developer version 19.2.1. However, for enhanced spatial visualizations, I highly recommend installing Oracle SQL Developer version 23 or later, as it provides access to GeoRaptor. GeoRaptor is a valuable tool for visualizing spatial data and can significantly enhance the experience of working with geographic information in your project.

I began by conceptualizing my city, creating a farm scene reflective of a location in France. Using draw.io, I developed a class diagram to model the necessary classes for the project. Once the conceptual groundwork was laid, I implemented tables and sequences in line with the drawn layers. Spatial metadata was added to establish a workable spatial space. Geometrical values were inserted into the tables, involving calculations such as slope coefficient, dilation, and rotation to organize the city logically.

Visualization of the results provided insights into the created city. Informational data was incorporated, and queries were crafted to answer complex questions. Despite challenges with the "map view," which occasionally led to performance issues in SQL Developer, the project was rewarding. The ability to create a city and visualize databases in a coordinate system showcased the practicality of spatial data, particularly for those dealing with GIS data.

## Conclusions

Working with a "map view" can pose challenges, particularly with performance issues when handling numerous objects. However, the freedom to create a custom city and visualize databases spatially proved to be an engaging and valuable experience. The project highlighted the significance of spatial data beyond visualization, demonstrating its utility in diverse fields, especially for professionals dealing with GIS data.

