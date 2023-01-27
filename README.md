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
    ![Here](https://github.com/meduardoscervantes/InstrinsicTechnicalExam/blob/main/resources/img/top_20_school.png "Top Schools with 8th Graders")


2. Create the [address.ipynb](https://github.com/meduardoscervantes/InstrinsicTechnicalExam/blob/main/address.ipynb) file for coding.
3. Read in the CSV file in python using Pandas
4. Using [Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview), 