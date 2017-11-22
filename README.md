# Purpose
The purpose of this project is to assess the technical abilities, and UI architecture understanding
 of front end developer candidates; specifically, regarding React Apps.

# Requirements / Elements of the UI

***Important: Refer yourself to the WIREFRAMES.PDF document to get a better understanding of the site's layout.***

The app must provide the following elements.

## Top navigation bar
The top navigation bar drives what the side-menu (and main content area will show)
In the mockup, we can see that the navigation bar has 4 items; Home, Products, Company, and Blog.

- Clicking on a navigation bar item should bring its specific side-menu; 
- Clicking on a navigation bar item should also display the main content related to its first (default) item.

## Side menu 
The side menu presents:
  - A list of the sub sections of the currently selected item in the top navigation bar
  - An optional, and per section, widget; located at the bottom of the submenu.
    - Note that some sections have no widget.
  - Also note that some sections (i.e.: blog) have no sidebar.

### Widget  
The widget area will be used to display additional information in relation to the currently selected section in the top navigation bar.

The widget could be anything from a graph, to a google map embed; however, for this exercise, we only need you to provide two mock widgets composed of a div with a title of "Widget Home", and "Widget Company"

Only the *products* and *company* section have a widget.

## Main content

The main content is the central element of the mockup; it is used to display arbitrary content.

For this exercise simply have a title that describes the content along with some filler text will be sufficient.

## Notification / Alert Bubble

The final element is a notification / alert bubble that hovers on top of the content at the bottom right corner of the screen.

 - The alert is triggered via the *Alert* button located at the right of the top navigation bar.
 - When triggered, the alert is displayed for 5s then disappears.

# Data Structure of the site

***The site content should be driven programmatically by the `data.json` file.***
Note that we will test your code with another data.json file respecting the same data structure.

# Important Notes
  - ***Refer yourself to the WIREFRAMES.PDF document to get a better understanding of the site's layout.***
  - ***The site content should be driven programmatically by the `data. Son` file.***
    - Note that we will test your code with another data.json file respecting the same data structure.
  - we recommend using create-react-app or some other starter
  - recommend redux, but not necessary
  - npm modules and frameworks are ok
  - server-side rendering is not important
  - bundling is not important
  - tests: good!
  - styling is not important, except insofar as to convey important information (e.g., selection)

Points awarded for:
  - clean and well encapsulated code
  - control reuse
  - extensibility
  - clean and idiomatic react/redux



