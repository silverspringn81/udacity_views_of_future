Visualizations of U.S. adults' views of technology and the future
===

##Description
Udacity Data Analyst Nanodegree P6

##Author
Shinichiro Tanaka

##Summary

- Three visualizations are provided to show the main findings derived from a 2014 survey by the Pew Research Center and Smithsonian magazine, which asked 490 U.S. adults about their predictions on a range of potential technological developments and their views on the resulting future.

- We can see from the first bar chart, showing % of U.S. adults who feel technological changes will lead to a mostly better or worse future, that the majority (~58%) are positive about long-term changes. 

- We can see from the second stacked bar chart, showing the relationship between household income of the respondents with their views on technological changes, that higher-income Americans have more positive views on the future.

- We can see from the third bar-plus-line chart, showing the distribution of respondents' predictions on five specific technologies in the next 50 years and % within each prediction group who feel technological changes will lead to a mostly better future, that there are no clear correlations between the predictions and the positive views on the future.


##Design

- Initial design plan:
As a first step I decided to show (1) the distribution of 50-year predictions on five technologies, (2) the distribution of views on the future which long-term technological changes will bring about, and (3) the distribution of views on the future within each household income group. It was straightforward to use a bar chart for the three visualizations since all of them are to compare distributions among different categorical variables. I added buttons to chart (1) so that we can switch technologies on a single chart. A stacked bar chart was used for (3) to show relative frequencies of different views on the future within each income group. 

- Updated design plan::
After collecting feedback on my first visualization I noticed that (i) I needed to clarify the main story of the visualization, (ii) I should show relationships between 50-year predictions on the five technologies and views on the long-term future, and (iii) I should show the sample size and income distribution of the respondents.  So I modified my visualization as follows in the updated version:

1. I changed the order of the three charts to clarify the main story: (a) the majority are positive about long-term changes (b) higher-income people are more positive about the future (c) there is no clear correlation between the 50-year predictions and the views on the long-term future. This story might indicate that all U.S. adults are more or less feeling that some kinds of technologies are developing so rapidly that they will realize in the next 50 years, while it is mostly higher-income people who have positive views on the long-term future perhaps because richer people benefit more from advanced technologies than poor people.

2. I added line graphs to the bar charts for 50-year predictions in order to show % of people within each prediction group who have positive views on the future.

3. I included the sample size in the page summary and added another bar chart to the stacked bar chart to show income distribution of the respondents. 

In the submission, I have included "exploreData.html" where I explored the original dataset with R and considered the design plans. 


##Feedback

I have collected feedback from three persons.

Feedback #1:

1.What do you notice in the visualization?
- you have clearly defined without seeing the graph what we should
expect from the visualizations from the title, and each subheadings.
2.What questions do you have about the data?
- why did you choose this dataset?
3.What relationships do you notice?
- that people are positive about long-term changes, and people with
higher income are happy.
4.What do you think is the main takeaway from this visualization?
5.Is there something you don’t understand in the graphic?
- what is the main story? is it about technology and future? Is it
because we have better technology that we have a better future?
or because we have more income that we feel better about ourselves?

Feedback #2:

1.What do you notice in the visualization?
- You can show how the 50-year predictions on the five technologies change by household income.  
2.What questions do you have about the data?
- What is the sample size for the three charts?
3.What relationships do you notice?
- There should be some correlations between 50-year predictions and the views on the long-term future. Can you show that those who have positive views on the future are also predicting that the specific technologies will happen in the next 50 years? 
4.What do you think is the main takeaway from this visualization?
5.Is there something you don’t understand in the graphic?
- You should show how the sample sizes differ in each chart explicitly. 

Feedback #3:

1.What do you notice in the visualization?
- Although the research by Michael Osborne predicts 47% of current jobs will be replaced by technologies in the next two decades, people have mostly positive views on the future across all income groups.
2.What questions do you have about the data?
3.What relationships do you notice?
- People tend to predict that a technology will happen with a high possibility when they are able to imagine it. (It is still hard to imagine how the technology will be like to control the weather...)  
4.What do you think is the main takeaway from this visualization?
- Vast investment in science and technology by U.S. government are supported by people's positive views on the technological development.  
5.Is there something you don’t understand in the graphic?
- You should include income distribution of the respondents. May be biased to higher-income? 


##Resources

1. Overall:
https://github.com/mbostock/d3/wiki/Gallery
2. Add buttons:
http://www.nikhil-nathwani.com/blog/posts/radio/radio.html
3. Wrapping text:
http://bl.ocks.org/mbostock/7555321
