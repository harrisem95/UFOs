# UFOs

## Project Overview
Dana was tasked with building an interactive web page that filters the data in the table on the page based on multiple user inputs. The project allowed us to create filters that searched for multiple criteria at the same time. 


## Results
In the inital lesson, we built an interactive webpage using a story board. We used css elements to style this page to look nice to the end user. We used the jumbotron function to create a stylistic heading to the page and used an image as the background of this section. We then included paragraphs and titles to describe the reasons behind exploring this data. We pulled the data from our data.js file and put it into a table. We then created filters to filter the table to include only the information that we are specifically searching for. For the challenge, we updated the filters so that the end user can search for multiple criteria at the same time. Instead of having a button click function, we had the app.js file listen for any changes in the filters and update the table accordingly. For instance, in the image below, I entered the criteria, "1/1/2010" into the "Enter Date" box, "ca" in the "Enter State" box, "us" in the "Enter Country" box, and "light" into the "Enter Shape" box. As you can see, the table automatically updated the include the appropriate data. 
  
![Filtered Table](/Resources/Filtered_Table.png)  <br />

See below for the unfiltered table. 
![Unfiltered Table](/Resources/Unfiltered_Table.png)



## Challenge Summary
We were successful at creating a  table that allowed the end user to search for multiple criteria at the same time. One drawback of this webpage is the amount of data available. There is not a significant amount of data and therefore, sometimes filtering the table will only give us one result. I would recommend increasing the amount of data available. A reccomendation for further development would be  to create a filter for the duration. It would be helpful to create a filter that didn't select exactly the duration we were looking for, but also all larger values. For instance, if we wanted to filter for all UFO sightings that were 10 minutes or longer. A second recommendation would be to include images and pictures. This would make the data that much more easy to undersstand. Reading about the shape of the sighting is hard to picture, therefore any images that were applicable to this sighting would be very helpful to include in the table. 
  
