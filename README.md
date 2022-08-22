# UFOs
## Overview of Project
This project attempts to filter a list of ufo sightings based on various criteria, such as location- specific up to a given city- date, and ufo shape. 
It presents this information in a webpage, providing an easy tool for seasoned enthusiasts and new converts to ufology to use without needing any knowledge of coding or specialized software like python installed on their system.
## Results
Using this page is simple.
A user is presented with filter criteria to the left of the page, shown below.  
![](https://github.com/ChrisJAnderson/UFOs/blob/main/static/images/FilterSearch.png)  
Updating these filter criteria will update the table to the right, shown below, to include sightings that match the criteria given, filtering out extraneous information.
If, for instance, a user is only interested in sightings in california, they can update the state field to ca.  
![](https://github.com/ChrisJAnderson/UFOs/blob/main/static/images/SightingsTable.png)
## Summary
A huge drawback to using this site is the complexity of the filtering. Having so many values on which to filter is useful for someone who knows what they're looking for, but overwhelming for the casual browser. Additionally, leaving five fields open for user input gives too many ways for user error to mess up a search. I can't tell you the number of times I've misentered a datetime value in an online form- this site asks users to enter a specific datetime, an abbreviation for state, an abbreviation for country, and a specific shape. Shape is the biggest of these issues. Entering "saucer" for instance, will not produce "circle" sightings. There's a distinction between "light" and "fireball", and a distinction between "formation" and "other" that seems entirely arbitrary. My first recommendation to improve the webpage is to retool the filters- replace the open fields of state and country with dropdown lists, and possibly reconsider having a shape filter at all(although as it is an optional filter, it doesn't actually impair the data brought up, it's just confusing, and in my opinion the field is badly categorized for a search parameter). My second recommendation regards the readability of the filter window- first, the text should be recolored to black instead of white (as white on white isn't readable), and second, there should be an attempt to align the search fields, which currently are not in line with  each other, resulting in a messy, unpolished look.
