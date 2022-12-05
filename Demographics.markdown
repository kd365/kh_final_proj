---
layout: page
title: Demographic Analysis
permalink: /Demographics/

---

## Safe Playgrounds in Washington DC

### All DC Playgrounds:

**Map 1:**
<style>.embed-container {position: relative; padding-bottom: 75%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="400" height="300" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="All DC Playgrounds" src="//mygmu.maps.arcgis.com/apps/Embed/index.html?webmap=5ad339686a504fb4aba6766b2acdd340&extent=-77.2314,38.8083,-76.8122,38.9961&zoom=true&previewImage=false&scale=true&search=true&searchextent=true&legend=true&disable_scroll=true&theme=light"></iframe></div>

In order to conduct geographic analysis on playground data within the borders of Washington DC, location data was obtained via two routes. First, OpenData DC provided the vast majority of data points through the Parks and Recreation Areas map layer provided by the Department of Parks and Recreation (DPR). This dataset was filtered by the attribute which denotes whether or not a given facility includes a playground. Added to this data were the parks that were returned from a Google API search for playgrounds within Washington DC. One limitation of this dataset which will be addressed in future research is the possibility of overlapping datapoints between these two datasets that were unresolved during their merge.

### Playgrounds to Population Demographics:

#### Age of Residents

**Map 2:**
<style>.embed-container {position: relative; padding-bottom: 75%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="400" height="300" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="Pop under 18 vs Playground Location" src="//mygmu.maps.arcgis.com/apps/Embed/index.html?webmap=42321458082242efa2c7643f75c326eb&extent=-77.236,38.81,-76.8168,38.9978&zoom=true&previewImage=false&scale=true&legend=true&disable_scroll=true&theme=light"></iframe></div>

**Map 3:**
<style>.embed-container {position: relative; padding-bottom: 75%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="400" height="300" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="Percent Pop under 18 vs Playground Location" src="//mygmu.maps.arcgis.com/apps/Embed/index.html?webmap=e7ae0cb6fb3a478f9e7ab4a65c41e825&extent=-77.236,38.81,-76.8168,38.9978&zoom=true&previewImage=false&scale=true&legend=true&disable_scroll=true&theme=light"></iframe></div>

A comparison of park locations (with density overlay) against a heatmap of a given area's population under the age of 18 reveals some interesting trends. 
Both Maps 2 and 3 show that those under the age of 18 seem to be clustered around the edges of Washington DC, which makes sense when one considers that there is typically more housing around the edges of the city in the suburbs. 

When compared to the location of playgrounds, though, there is some disparity. If one considers the most likely users for playgrounds to be those under the age of 18, it is interesting that the most dense locations of playgrounds are in areas where there is a lower ratio of the population under the age of 18 (Map 4). Map 3 seems to do a bit better when taking a look at the cluster in the center of the city- a few tracts with higher numbers of children under 18 coincide with the dense area of playgrounds, but several tracts in the same area have a very low number of residents in the appropriate age range.

This begs the question why these parks were created in these areas, and indicates a possible need for playgrounds in areas with a higher percentage or numbers of children. This could inform a city planner on which areas are suffering from a lack of play spaces. 

#### Economic Status of Residents

**Map 4:**
<style>.embed-container {position: relative; padding-bottom: 75%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="400" height="300" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="Mean Household Income vs Playground Density" src="//mygmu.maps.arcgis.com/apps/Embed/index.html?webmap=b1228d84574340989ea2f6ebcbe6e1b9&extent=-77.2733,38.81,-76.8541,38.9978&zoom=true&previewImage=false&scale=true&legend=true&disable_scroll=true&theme=light"></iframe></div>

This shows....blah
