# Project 2 Documentation
### Project by Emily Horton and Xander Kaylan

## Overview
For project 2, we decided to use Star Wars API (SWAPI: https://swapi.co/) to make a webpage for looking up information about Star Wars characters. Our project allows a user to search for a character by name, or browse through random characters, which can be filtered by the film they appeared in. The intent is to introduce people to Star Wars lore that they may be unfamiliar with, as well as to allow the quick lookup of facts for characters they already knew about.

## Our Process
We typically met each other on Saturday afternoon to work together on the project, while making adjustments and tweaks outside of class. We kept in touch via texting.

To start the project, we created a GitHub repo and started by creating all of the needed files and folders for the project. From there, we worked on writing the basic layout of the page and figuring out how to get and parse information from SWAPI. Our original idea was to incorporate images of the characters that were pulled up, but this functionality turned out to not work with SWAPI, which only has biographical information available- not images. After exploring several possibilities via Google Images and other image-searching APIs, we decided to abandon the idea of adding in pictures and instead focus on getting the basic information for the characters.

To meet the requirements of the project, we used a search bar with a search button, a drop-down menu to filter randomly-selected characters by the film they appeared in, and a button to retrieve random characters from SWAPI.

For the theme of our website, we decided that a starry space background would be perfect for our Star Wars app, and we used colors used in Star Wars material, such as the yellow backgrounds and the blue loading icons. We thought that using flippable panels to display character names and information would help us display information to the user in an engaging way.

## Workload
We both worked on this project equally. Xander did most of the groundwork for the HTML and the CSS. He added the grid layout, formatted a lot, and created the query to make sure it looked good in a 1024 by 768 screen size. He also implemented the jQuery for displaying character data on flippable panels. Emily did a lot of the javascript work for getting the API working, as well as for handling errors. Xander coded the process of pulling the data from SWAPI (both the random and the search) and appending it onto the panels, and Emily did tweaks to the CSS and the HTML for better aesthetic and functional purposes.

## Sources
The background image for our page was taken from: https://pixabay.com/photos/starry-sky-star-galaxies-andromeda-1654074/

We utilized jQuery for the flipping effect of displaying character information.

The SWAPI Documentation can be found here: https://swapi.co/documentation

Our loading graphic was created using loading.io: https://loading.io/

We also referenced Stack Overflow, as well as the Mozilla Developer Network.


## Grade
After considering our project and comparing it to the rubric, we think we would deserve a 90. Our interface is easy-to-use and it is obvious what all of our controls do. The app provides an easy and pleasing way to search for information on Star Wars characters and has a fitting theme. However, we did not make our app mobile-friendly, and the functionality is a little basic. We feel as though those reasons keep us from the "above and beyond" category of grading, but we think our website looks good and works well.
