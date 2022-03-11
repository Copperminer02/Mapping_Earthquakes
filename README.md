# Mapping_Earthquakes

## Overview

This repository contains a series of steps to add layer, lines, refernece geoJSON sites and information, and overall map construction using Leaflet and JAVA Script.  The challenge assignment can be found in:

  1. **Earthquake_Challenge**
    a.  **index.html** - html code that controls styling and access to style sheets, as well as script connectivity to Leaflet, D3, and the Java Script code to gather and process the data from USGS and Leaflet.
      * **css/style.css** - controls styling for map size and legend,
      * **js/challenge_logic.js** - javascript app that makes api calls to USGS eartquake data,  git hub techtonic plate boundaries, and leaflet layer styles.
  
 ## Result
 
 The resulting index.html when ran will display a map of the world with daily earthquake data (colored and sized by magnitude), major earthquakes over the last week (colored and sized by magnitude), and the techtonc plate boundary.  Each of these data layers is selectable in the upper right hand corner.  All three layers will be visible when the indec.html is ran.  Along side the data layers, there are 3 different map styles which can be turned on or off (one at a time) in the right hand corner as well.  The default map underlayer is a world street map.  The user can choose from either a satelite view or a dark theme as well as the stree view.  The toggle box can be seen in the image below.
 
 ![image](https://user-images.githubusercontent.com/91850824/157780459-03108720-1f27-4779-88bd-5d7ee016e508.png)

Each circle (representing earthqauke locations and magnitude) can be clicked on to pup up the magnitude and exact location reported.

![image](https://user-images.githubusercontent.com/91850824/157780679-2fc806b5-b5e2-414e-8f2f-0a36a1190a6b.png)
