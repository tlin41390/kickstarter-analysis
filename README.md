# An analysis of Kickstarter Campaigns

## Overview of Project
### Purpose
    the purpose of the project is to bolster knowledged about handling large data sets as well as extracting specific data from
    different sections of the data set in order to represent different areas of interest. There are two seperate fileds that I 
    will be measuring and they are the launch dates of each kickstarter and the goals set for each kick starter.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Dates
    In order to organize the outcomes of theater projects based on the launch date of 
    the file, I created a pivot table and a pivot chart to represents the outcomes. 
    The rows are labled based on the dates of each project and the columns are labeled with the outcomes. 
    The chart depicts which months are where the projects are more likely to be successful. The Y- axis 
    represents the number that is successful, and the x axis represents the months. The data tells what 
    part of the month will be successful fail or be canceled.
    
   ![Outcomes Based on Launch Dates](https://github.com/tlin41390/kickstarter-analysis/blob/main/resources/Theatre%20Outcome%20by%20Launch%20Date.png)
### Analysis of Outcomes Based on Goals
    To analyze the outcomes based on the goals of each theatre project I created a 
    descriptive statistics of each different goal rangeand their success rates compared 
    to the percentage failed. The rows represent the different goal range, and the column
    will represents the number of projects that are successful, failed, and cancelled. Finally 
    there is the percentage of success, fail, and cancelled. The graph represents the precentage of success, fail
    and cancelled depending on the range of goal.
    
   ![Outcomes Based on Goals](https://github.com/tlin41390/kickstarter-analysis/blob/main/resources/Outcomes_Based_On_Goals.png)
### Challenges and Difficulties Encountered
    There were seperate different challenges and difficulties I encountered when working 
    with the data. When putting  together the pivot chart I initially did not know that 
    the dates were alread pregrouped by  years so I did not know that the data was already organised. 
    In addition, I had to format the graph so that the graph will show the relevant data. As for the outcomes 
    based on goals; the challenges I faced when constructing the data set was that I initially forgot to filter out 
    the plays so it took a while for me to figure out why I was handling with a larger data set, where in reality, the
    data set will be much lower because we are supposed to be working for the plays data set only.

## Results
   - What are two conclusions you can draw about the Outcomes based on Launch Date?
   
        The two conclusions I can draw about the outcomes based on the launch date is that there are more successful kickstarter
        plays then failed and canceled. There is a spike of successful plays during the April/May period, and there is a spike of failed
        movies on the September-November range. Moreover, it seems that most kickstarters launch in the beginning of the year over the end
        of the year.
        
   - What can you conclude about the Outcomes based on Goals?
   
        I can conclude in the outcomes based on goals that generally, outcomes usually succeed if the goal is not too high. Generally, there
        are less kickstarter plays as the goals increase in price.
        
   - What are some limitations of this dataset?
   
        There are a few limitations to the datset, such as how the projects are funded, and other variables that may cause the kickstarter to
        fail. For example sometimes the kickstarter may be in a site that not alot of people will use to fund the project based on geography.
        We also do not know the general thoughts of each plays as the reason why the play failed could because there may be low opinion about 
        the overview of the project. Another limitation to the datset is that it does not look at demographic, as the data measures only the 
        goal and if it succeeded or not, so the data is fairly vague.
        
   - What are some other possible tables and/or graphs that we could create?
   
       Other tables that we can create is a table that represents the amount pledged based on the range as well. That way, we can compare how
       much the goal was excdeeded or how short the pledge was from the goal. 
