# UFOs - The Truth is out There! 

# Overview of the Project

We were requested by our client to assist in a project making a searchable webpage of UFO sightings. The data was stored as a JavaScript array.  The data needed to be in table format and our client wants to be able to filter based on certain criteria. The table was created using JavaScript and HTML/CSS and Bootstrap were used to make the website more appealing. 

# Results

The data of the UFO sightings has been added to a webpage and are stored in table format.  Below you will see an image of the webpage; 
<img width="1356" alt="UFO_Main_Page" src="https://user-images.githubusercontent.com/98054953/167484473-dbc43527-cbac-489b-8591-072d3d78acfa.png">

The webpage is ready for users to determine view the data that has been collected around the UFO sightings. 
The Filter Search fields on the left hand side of the page can be used to find specific sitings. 
For example, for all the events in the state of Arizona, type "ar" in the "Enter State" search field and press enter.  The results are shown below: 

<img width="1348" alt="UFO_Filter_State" src="https://user-images.githubusercontent.com/98054953/167485653-27e1871d-8e91-48d5-8473-fa9a439510e3.png">

After a search has been complete, you can restart the page by clicking on "UFO Sightings" in the upper left hand corner.  This will remove the filters and return the data to the original table. 

<img width="924" alt="UFO_Sightings_Reset_Button" src="https://user-images.githubusercontent.com/98054953/167485902-46a78f36-f311-47eb-a8c0-9e72075eb6a6.png">

The Filter Search can also be performed by the shape of the event.  For example, all events with the shape "triangle' are shown below:

<img width="1360" alt="UFO_Filter_shape" src="https://user-images.githubusercontent.com/98054953/167485919-b5d08d86-65a3-40a1-ace8-d07cea4e9c91.png">

# Summary

The webpage performs the filtering of the dataset and allows users to interact with the data. One drawback of this new design is that the search has to match perfectly to the data as entered.  Therefore a couple of recommendations are included for further development of the webpage: 

1. Allow partial matching of the search strings rather than exact matches. 
2. Format the City, State and Country data to follow normal conventions.  They are all currently lower case.  City and State are usually capitalized so the standard user may inadvertently enter the values as capitalized and will not find a match.  The country data is also in lower case and should be revised to uppercase if an exact match is required. 
3. The date search is restricted to one day at a time.  It may be prefered to have a date range that can be searched if the user is looking for patterns over several dates. 



