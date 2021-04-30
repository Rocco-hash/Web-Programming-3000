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

========================================
    VISUALIZATION 2: DAVID VINCI
========================================
Visualization 2: In my folder, there is a files folder that contains "d22a6e9c4b47d398faffbefad669e5b807a0c8bc3eaf4d28edfd52330fa48ac1"
which is the name of the files SHA256 hash for my csv data.

The file named "75faaaca1f1a4f415145b9db520349a3a0b93a53c1071346a30e6824586a7c251f45367d9262ed148b7a2b5c2694aa7703f3ac88051abc65066fd0074fdf9c9e" contains all of the data
that creates the map of the USA.
The file named "438813e85a5cfb28@205.js" is the javascript file containing the data, color, scale, and map.
The file named "a33468b95d0b15b0@703" also handles color but seems like it is the intensity of the color. It also handles the scale and legend.
The file named "index.html" imports different files."index.js" exports from "438813e85a5cfb28@205.js", im not really sure what that accomplishes.
"inspector.css" formats the main page.
"package.json" looks like it just shows what all of the files in the original file does.
Im not 100% sure what "runtime.js" does but i think that may be the reason why i cant just simply change the file names to something more readable.
I think it might be checking is see if the file type is what they want etc.
