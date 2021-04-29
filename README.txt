README.TXT

==============================
STRUCTURE OF THIS FILE
==============================

This files describes the major sections of the site, including the data visualizations created by each member of the group.

Subheadings describe each file for the major sections.


====================
    MAIN PAGE
====================
The index page for the site contains links to all visualizations.

main.html - The main HTML page contains a table with a description of each member's data visualization, and links to their page.
main.css - The CSS stylesheet defines the styles used on the main page.

========================================
    VISUALIZATION 1: MALACHI COAN
========================================

    Visualization: Chloropleth Map of the world
    Data: Population Density data from the United Nations

Visualization1/index.html - This page loads the D3.js files and my javascript and style sheet. It contains an SVG element where the SVG map will be drawn, form inputs to select a year, and a container where information for each country will be written by a mouseover function.
Visualization1/map.js - Javascript code to load and parse the data, draw the SVG map, color each country based on its population density, and create a mouseover effect to show each country's data.
Visualization1/styles.css - Contains styles for the HTML elements on the index page.
Visualization1/WPP2019_POP_F06_POPULATION_DENSITY.csv - Contains population density for the countries of the world from 1955 to 2020. Downloaded from the United Nations website, converted to CSV.

