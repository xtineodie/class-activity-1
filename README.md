# Class Activity 1
## Data Manipulation

In this repository you will find data describing Swirl activity from the class so far this semester. Please connect RStudio to this repository.

### Instructions
  
1. Open a new R Markdown file, please write and run all your commands from within the R Markdown document  
2. Delete the contents of the Markdown file and insert a new code block
3. Load the libraries  `tidyr` and `dplyr`
4. Create a data frame from the `swirl-data.csv` file called `DF1`

The variables are:

`course_name` - the name of the R course the student attempted  
`lesson_name` - the lesson name  
`question_number` - the question number attempted
`correct` - whether the question was answered correctly  
`attempt` - how many times the student attempted the question  
`skipped` - whether the student skipped the question  
`datetime` - the date and time the student attempted the question  
`hash` - anonomyzed student ID  

5a. Create a new data frame that only includes the variables `hash`, `skipped` and `datetime` called `DF2a` 

5b. Create a data frame that is just the first 10 rows of `DF2a` called `DF2`

6. On a scrap piece of paper draw what you think `DF2` would look like in wide format

7. Convert `DF2` from long format to wide format  

8. Create a new data frame from `DF1` called `DF3` that only includes the variables `hash` and `correct`

9. Convert the `correct` variable so that `TRUE` is coded as the **number** `1` and `FALSE` is coded as `0`  

10. Create a new data frame that called `DF4` that provides a mean score for each student

11. **Extra credit** Convert the `datetime` variable into month-day-year format and create a new data frame (`DF5`) that shows the average correct for each day

