## Rutgers Student Instructional Rating Survey (SIRS) Analysis
This project was started due to a combination of wanting to play with various python libraries and curiosity as to the results of the countless surveys that I took as a student.
The data was acquired using another python application (sirs_scraper in github) and most of the data processing was done outside this project.

Initially, the data consisted of 1,742,798 rows (responses), with each question in each course survey getting its own row. The rows contain a count of ratings on a Likert scale of 1-5, with 1 being the 'worst' and 5 being the 'best'. A total of 202 questions were collected, however, we will only be focusing on the standard 'university' questions as they are consistent across almost all courses.
A list of the questions used will be available in the apendix (bottom of page).  

Final usable dataset is 1,703,467 rows by 23 columns with data from Spring 2001 to Spring 2016.

First, we did some exploratory data analysis, then we attempted to predict the course overall rating using machine learning (linear regression). A model
using data up and including Spring 2016.  
Few months later, Fall 2016 data was released (and scraped). We ran the data through our model and found that it had similar accuracy and ability to predict ratings.
