# Bikesharing

## Overview of Project
### Purpose of Project
In this project, I demonstrated my proficiency with various JavaScript and HTML features including: using console.log() to debug code, d3.select(), arrow functions, forEach() with JavaScript objects, filters with d3.select(), if-else statements, list-group-item class, label, and input tags to add filtered data to an index.html file, and script tags to an index.html file. 

### Background of Project
Dana, a journalist, has a JavaScript datafile about UFO sightings that she wants to organize and display. I built a table using data stored in a JavaScript array. Then, I created filters that it will react to user input, and placed the table into an HTML file for easy viewing. Users will be able to search the data by date, city, state, country, and shape of the UFO sightings. 


---
## Results

There are at least seven visualizations for the NYC Citibike analysis (7 pt)
There is a description of the results for each visualization (7 pt)


The “Filter Search” allows users to search for UFO sightings by date, city, state, country, or shape. The search can be done using any combination of filters. For example, a user could search by just the state of Oregon, just triangle shaped UFOs, or by a combination of the state of Oregon and triangle shaped UFOs.  

### FORMATING 
* Date is entered as MO/DA/YEAR
* State and Country are entered using their two letter abbreviations 

### HOW TO SEARCH 
ADD FILTER 
* Choose any filter  
* Type your criteria 
* Hit Enter [table will adjust] 
* OPTIONAL: repeat for remaining filters


REMOVE FILTER 
* Choose filter you want to remove
* Delete text
* Hit Enter [table will adjust]

    

### EXAMPLE
**Example 1: You want to search for sightings in the state of Oregon**
ADD FILTER 
* Choose any filter = "I want to search by the *state* of Oregon."  
* Type your criteria = The abbreviation for Oregon, "or", is typed under "Enter a State". 
* Hit Enter = The table will look like the image below. 
![filter_or](static/images/filter_or.png)

**Example 2: You want to adjust your search so the table displays sightings in the state of Oregon that were in the shape of a triangle**
ADD ANOTHER FILTER 
* Choose any filter = "I want to add triangle to the *shape* filter."  
* Type your criteria = Type "triangle" under "Enter a Shape". 
* Hit Enter = The table will look like the image below. 
![filter_or_triangle](static/images/filter_or_triangle.png)
 
**Example 3: You want to adjust your search so the table displays sightings that were in the shape of a triangle**
REMOVE FILTER 
* Choose filter you want to remove = "I want to remove the *state* of Oregon."  
* Delete text = Delete "or" typed under "Enter a State". 
* Hit Enter = The table will look like the image below. 
![filter_triangle ](static/images/filter_triangle.png)

---
## Summary
There is a high-level summary of the results and two additional visualizations are suggested for future analysis (5 pt)

The placeholder, a short hint that describes the expected value, is a useful visual affect for the user. However, it can be unclear what the table is displaying when the placeholders for unused filters remain after the initial filter is applied. My recommendations below, outline how to make the table easier to interact with and read. 



[link to dashboard](LINK GOES HERE)
[link to dashboard](LINK GOES HERE "link to dashboard")
