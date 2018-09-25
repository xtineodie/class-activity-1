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
`hash` - anonymyzed student ID  

5. Create a new data frame that only includes the variables `hash`, `lesson_name` and `attempt` called `DF2`

6. Use the `group_by` function to create a data frame that sums all the attempts for each `hash` by each `lesson_name` called `DF3`

7. On a scrap piece of paper draw what you think `DF3` would look like if all the lesson names were column names

8. Convert `DF3` to this format  

9. Create a new data frame from `DF1` called `DF4` that only includes the variables `hash`, `lesson_name` and `correct`

10. Convert the `correct` variable so that `TRUE` is coded as the **number** `1` and `FALSE` is coded as `0`  

11. Create a new data frame called `DF5` that provides a mean score for each student on each course

12. **Extra credit** Convert the `datetime` variable into month-day-year format and create a new data frame (`DF6`) that shows the average correct for each day

