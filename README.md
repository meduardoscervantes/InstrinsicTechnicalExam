# Instrinsic Technical Exam by Manuel Cervantes

## Thought Process
1. Get the source data from the Official [Chicago Public Schools](https://www.cps.edu/about/district-data/demographics/) Website.
2. Open the Excel sheets to understand what is in the data.
3. Carefully consider the task: `The recruitment team has requested your help with data analysis. They are getting ready to recruit students to fill the 9th grade seats at the Downtown campus. They want to create a list of schools to target.`
4. Decide that based on the information from the 2022-2023 Demographics Spreadsheet, look into the number of 8th grade students who are ready to move on to the 9th grade.
5. Create the list of schools to target. 

## Execution
1. Convert the 2022-2023 Demographics Spreadsheet into a CSV file for python.
2. Create the [8th_graders.ipynb](https://github.com/meduardoscervantes/InstrinsicTechnicalExam/blob/main/8th_graders.ipynb) file for coding.
3. Looking at the Eight Graders enrollment column, organize the schools based on the number of 8th grade enrolled students.
    ![](https://github.com/meduardoscervantes/InstrinsicTechnicalExam/blob/main/resources/img/top_20_school.png "Top Schools with 8th Graders")
4. Convert the information into a map to try and see if the location of the schools may have an impact.
5. Created the [address.ipynb](https://github.com/meduardoscervantes/InstrinsicTechnicalExam/blob/main/address.ipynb) file for coding.
6. Using [Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview), the schools could be plotted on to a map to show the distance from central Chicago by getting their coordinates.
7. Displayed the top 20 schools
    ![](https://github.com/meduardoscervantes/InstrinsicTechnicalExam/blob/main/resources/img/top_20_map.png "Top 20 Schools with the most 8th Graders")
8. Recognized that some schools were either too far North and South from downtown
    ![](https://github.com/meduardoscervantes/InstrinsicTechnicalExam/blob/main/resources/img/possible_outliers.png "Possible Outlier Schools from Google Data")

## Conclusion
With the short amount of time to work on this, we can confidently give the recruitment team a list of schools to reach out to based on the number of actively enrolled 8th grade students.

### Considerations
- I would have liked to get more data from the schools that were not found from [Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview) to get a more accurate map.
- Further analyze internal information. If there is data from students that enrolled with Intrisic that came from other schools, try and see what that information shows to form a stronger relationship with those secondary schools.
- Create clusters of schools that are more likely to join based on their distance from the Downtown school. Students that attend school close to the Downtown campus would not have to make as much of a change to attend the school. 