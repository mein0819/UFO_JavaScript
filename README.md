# UFO Sightings

## Project Overview

This project uses Javascript ES6+ to build a dynamic website that filters UFO sighting data from a Javascript data array file. The site allows the user to filter data based on the date, city, country, and UFO shape of the sighting, showing results based on just a single filter or multiple filters at the same time, allowing for fine-tuned results. 

## Resources

- Data Sources: data.js
- Software: Visual Studio Code 1.67, Javascript ES6+, Bootstrap 3.3.7

## Results

### The Main Site

![main page](https://github.com/mein0819/UFO_JavaScript/blob/main/readMeImages/mainpage_Full.png)

### Input Boxes for Filters and Results Section

![filters](https://github.com/mein0819/UFO_JavaScript/blob/main/readMeImages/filterMain.png)

Entering in filter criteria will filter and show results by pressing the enter key, tabbing to the next input box or using the mouse to click into another input box. There is no button that triggers the search. Also, the more input boxes that are used to filter, the more fine-tuned the search will be.
Here only the date and city have been entered:

![filter2](https://github.com/mein0819/UFO_JavaScript/blob/main/readMeImages/filter2.png)

Here the search has been further refined by entering a shape filter:

![filter3](https://github.com/mein0819/UFO_JavaScript/blob/main/readMeImages/filter3.png)

To start a new search or clear the filters, the user has to click on the page title above the jumbotron section:

![reset](https://github.com/mein0819/UFO_JavaScript/blob/main/readMeImages/reset.png)

## Summary

While this site works as intended, it's intuitiveness is limited. For instance, the current design for text input is case sensitive. All input can only be entered in the exact way it's shown in the placeholder text, so the date format has to be exactly the same, and all text has to be lowercase. If the input is not entered correctly, no results are shown. This image shows an example of using proper casing to enter in the city: 

![cityCap](https://github.com/mein0819/UFO_JavaScript/blob/main/readMeImages/cityCap.png)

Because the city, 'Benton', begins with a capital letter, no results will be shown on the right. There are further limitations, such as not having a search and reset button near the filters. Further development can be made to provide these functions, which will help make the site more intuitive. Adding the capability to search by a range of dates rather than a single date would also be a useful function, in addition to allowing a wider range of text input to be accepted. 

