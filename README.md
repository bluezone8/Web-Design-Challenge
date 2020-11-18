# LATITUDE Data Visualization Web Site
____
### PURPOSE
The purpose of this repository is to maintain files related to the Latitude Visualizations Web Site
_____
### ANALYTICAL TOOL CHOICE AND RATIONALE
The primary tools used for theis project include HTML, CSS, and Bootstrap.  While the basic structure wasa, of course, created in HTML, Bootstrap was chosen as the styling mechanism to provide prebuilt CSS classes that were ideal for the type of site that was desired.  The Bootstrap classes were particularly useful for the navigation portion of the site.  Additional CSS was also used to provide additional styling that Bootstrap was not used for or to make minor changes to the Bootstrap clasees used to better suit the site.  
In addition to the web site tools, the Pandas Python library was used within Jupyter Notebooks to convert the cities data csv to a dataframe and ,ultimately, to an html table displayed in the Data page of the site.  
______
### APROACH
The core of the approach to this type of effort is determining the specific layouts that would best facilitate deriving the maximum valuse from the visualizations.  In other words, what presentation styles will aid the user in best understanding the data presented in the charts etc.  for this project, it was decided to provide the user with access to the key visualizations from one location and be able to access them from other areas easily.  In addition, the data used was included as a table for viewing.  
____
### INCLUDED ITEMS
1.  Home Page of the web site which provides access to all of the four key visualizations  as well as  a summary of the project (index.html)
2.  Comparison Page of the web site which allows the user to see all of the key visualizations together simultaneously (comparison.html)
3.  The Data page of the web site which provides access to the cities data table used for the project (data.html)
4.  visualizations folder which contains the pages for the four key visualzaions as well as a brief textual analysis for each of them. included pages:(clodiness.html, humidity.html, temp.html, and wind.html) 
5.  Resources folder which contains the orginal csv file of the data used. (cities.csv)
6.  assets folder which contains the two sub folders of css which contain the css style sheet files (styles.css, bootstrap,min.css) and images which contains the images of the visualizations included. (Fig1.png, Fig2.png, Fig3.png, Fig4.png) 
7.  Converted html of cities csv data table file (cities.html) 
8.  Jupyter Notebook containing the Python/ Pandas code used to convert the cities csv data file to an html table.(table_convert.ipynb)