# UFOs


## **Overview**
The purpose of this analysis was develop a website that depicts a web-based dashboard that displays UFO sighting data in a dynamic table. The dynamic tbale is created utilizing JavaScript and HTML, while CSS and Bootstrap were used to modify the aesthetic of the dashboard. The table takes user input to apply filters to the data based on the following categories: date, city, state, country, and shape.


## **Results**

### Welcome to UFO Sightings!!!

![Welcome](https://github.com/OmarQasem94/UFOs/blob/main/static/images/Welcome.PNG)
 
### Unfiltered Table

![Unfiltered](https://github.com/OmarQasem94/UFOs/blob/main/static/images/Unfiltered.PNG)

### How the Table Interacts with User Input:

By specifying a date, city, state, country, or shape the user can filter the UFO sighting data to inspect specific sightings. However, the user input must be in lower case and cannot include a space at the end of the text. Once the user provides the input the filter can be applied by pressing "Enter" or clicking outside the input box. Finally, to cancel the applied filters the user can click on the UFO sighting's in the top left corner of the website.

![Filtered](https://github.com/OmarQasem94/UFOs/blob/main/static/images/Filtered.PNG)


## **Summary**

### Drawbacks to the Website

* The user must know the exact dates, cities, states, countries, or shapes to complete the search successfully.
* The filter are case sensitive and input must be in lower case and some cities include spaces at the end.

### Recommendations

1. Incorporate a trim function to remove any all spaces except those between words.

@. Modify the date filter to take in two date to search within a range rather than specific dates. This is a problem because if the user does not know the exact date the use of the filter is limited.
