# InstrinsicTechnicalExam by Manuel Cervantes

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
---
    ![](https://github.com/meduardoscervantes/InstrinsicTechnicalExam/blob/main/resources/img/top_20_school.png "Top Schools with 8th Graders")

    Rank 1: HERNANDEZ
    Rank 2: RICHARDSON
    Rank 3: NORTHWEST
    Rank 4: SAWYER
    Rank 5: HEALY
    Rank 6: HANSON PARK
    Rank 7: LINDBLOM HS
    Rank 8: MOUNT GREENWOOD
    Rank 9: KENWOOD HS
    Rank 10: INTRINSIC HS
    Rank 11: LYON
    Rank 12: GARY
    Rank 13: STEVENSON
    Rank 14: ARMSTRONG G
    Rank 15: SHIELDS MIDDLE
    Rank 16: EBERHART
    Rank 17: NIGHTINGALE
    Rank 18: LOCKE J
    Rank 19: CICS - LONGWOOD
    Rank 20: EDWARDS
---
4. Convert the information into a map to try and see if the location of the schools may have an impace.
5. Created the [address.ipynb](https://github.com/meduardoscervantes/InstrinsicTechnicalExam/blob/main/address.ipynb) file for coding.
6. Read in the CSV file in python using Pandas
7. Using [Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview), the schools could be plotted on to a map to show the distance from central Chicago.