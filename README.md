# Mission to Mars

## Overview

The purpose of this project is to use web scraping tools to quickly gather data and specifically retrieve information about Mars to display on a flask web application. 


## Summary

The components:

- Splinter to automate the browser and interact with the webpages to scrape the data and images.

- BeautifulSoup to parse HTML to access different HTML conponents and extract certain elements.

- Flask web application with routes to display the data on the homepage and scraping.

- Bootstrap to enhance the components of the HTML and CSS of the index.html file.

- MongoDB to store the data scraped and integrate into webpage by the functions defined in scraping.py file.


The finished web application to display web scraped data for Mission to Mars, using HTML as the layout for the web application and flask routes to connect the scraping functions and MondoDB where the data is stored.

![image](https://github.com/courtneysims/Mission-to_Mars/blob/eb3a7a819d0076a64c17ffa147a6a42d9c73b4ad/Resources/mission_mars_webpage.PNG)


The web application is enhanced with Bootstrap:

- Aligning center the table title, Mars Facts, and making the text bold by applying "strong."
- Styling the Mars Facts table to be striped grey and white for visual display. 
- Styling the "scrape New Data" button to have a longer rectangle box.



![image](https://github.com/courtneysims/Mission-to_Mars/blob/eb3a7a819d0076a64c17ffa147a6a42d9c73b4ad/Resources/bootstrap_text_formatting.PNG)

![image](https://github.com/courtneysims/Mission-to_Mars/blob/6af02b8c79383e20825f8e8b4a8ba98a20007d48/Resources/table_color_format.PNG)

![image](https://github.com/courtneysims/Mission-to_Mars/blob/6af02b8c79383e20825f8e8b4a8ba98a20007d48/Resources/button_shape_format.PNG)