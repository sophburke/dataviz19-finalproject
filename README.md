# Data Visualization Project

## Data

The data I propose to visualize for my project is the [HarvardX-MITx Person-Course Dataset AY2013](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/26147/OCLJIV&version=10.0) . It contains de-identified data from the first year of MITx and HarvardX courses on the edX platform.

## Prototypes

I’ve created a proof of concept visualization of this data. It's a bar chart and it shows viewing by course and engagement levels

[![image](https://user-images.githubusercontent.com/12277937/65547506-992a2b00-dee7-11e9-907b-fe51255146ff.jpg)](https://beta.vizhub.com/sophburke/1f10a1a7bdd64f98a399fc6b11a05bf9)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How do the viewing amounts vary according to course?
 * Is there any correlation between engagement levels and viewing amounts?
 * Where were the viewers from for each course?
 * Is there a relationship between the number of viewing events and discussion forum postings?

## Schedule of Deliverables

Following is a task breakdown and time-table.

 * Create a world map featuring marks to indicate the presence of viewership in those countries. (Estimated delivery, October 10)
    * Create map. (1 day) 
    * Position marks according to the locations where videos were watched. (1 day) 
    * Size marks according to the number of views in that country - using a javascript function to sum up the total number of views per       country. (7 days)
    * Enable interaction through a drop down menu so user can select views by class and institution. (3 days)

* Create a bar chart with a menu to explore the categorical data such as course, gender, level of education, year of birth, institution and engagement according to their relationship to continuous attributes such as number of video plays. (Estimated delivery, October 22)
    * Create bar chart. (3 days)
    * Add color legend. (3 days) 
    * Add drop down menu. (3 days)
  

[![image](https://user-images.githubusercontent.com/12277937/65548960-8107db00-deea-11e9-9a9c-c2057e4c307c.jpg)](https://beta.vizhub.com/sophburke/b70514faa8584a4b98e965e546bc4af8)

## Open Questions

I don't know how to map the viewing data onto the location data on top of a map.
