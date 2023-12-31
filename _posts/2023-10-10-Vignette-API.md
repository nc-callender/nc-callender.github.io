# Project 2- Vignette Assignment

# Project

The assignment was to select an API (application programming interface), build functions to pull different types of data from the API, and then do some exploratory data analysis.  I chose to pull data from the Center for Disease Control and Prevention relating to Vaccination Coverage among Adolescents.  

While making this selection, I limited myself to choices that do not require a key, since the end product is required to be made public.  I selected the dataset because I thought it would be interesting to look at vaccination coverage among adolescents.  As children become older, well-child doctor visits may morph into sports physicals and immunizations may not be as closely monitored.  Additionally, there is variation between states as far as which vaccines are required for school, which could lead to some interesting variations.  

Datawise, it was most interesting to see how vaccination coverage for hepatitis A varied in states without vaccination requirements for secondary school.  The data allowed for examination with regard to insurance coverage, ethnicity, poverty level, and urbanicity.  The finding that the vaccination rates were lower in the uninsured was not surprising.  However, I was a bit surprised about the fact that lower vaccination coverage was observed in rural areas.  

As a kid, no-one in our community had well-child visits; but one day each summer, the health department set up a vaccination clinic in a local church and all the kids got their shots at the same time.  I find myself picturing events like this and wondering: 

- if they still happen, and   
- if so, do they give all the recommended vaccines  
- or just the ones required for public school attendance  


# Programming

For this assignment, I found particular challenges in doing the check input coding.  Several of my functions involved filtering for a state of interest, or vaccine of interest.  If nothing was entered for an option, then I wanted to return all states or all vaccines.  So, the input could be null or an item in a list.  It took a while to learn that those two things could not be checked in a single if statement; it had to check for null and then only if it was not null" check to see if it was in a list.  

In making tables, it was a process to learn how to give things labels so that contingency tables did not look amateurish.  I never did get the “summary” table to a point I was happy.

In making graphs, I made lots of new types of graphs.  Several were challenging.  I found making the map hard but was not surprised by it.  I was surprised at how hard it was to make a scatter plot with the dots-connected (overlaid line plot); I am used to that being very easy (yay Excel! And Quattro and Kaleidagraph!).   I was also surprised by how much harder it is to make a single box plot compared to making a series of box plots.

With regard to learning about overall approach, I would do a deeper investigation of the data before starting to write functions.  I did use unique on all the columns to get possible values.  But I was not thorough enough to realize some values were only based on entries in other columns.  I tried to make tables only to find out they were empty.  

# Links
[Rendered Github](https://github.com/nc-callender/ST558-Project2#readme)

[Repository](https://github.com/nc-callender/ST558-Project2)
