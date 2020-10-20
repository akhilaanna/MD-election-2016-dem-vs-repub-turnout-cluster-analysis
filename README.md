# MD-election-2016-dem-vs-repub-turnout-cluster-analysis

## Background Information 

With the 2020 presidential election around the corner, it is interesting to take a look at results from 2016. According to the New York Times, 2016's Democratic candidate Hillary Clinton took the win for the state of Maryland with 60.3% of votes choosing her to be president. Though Maryland, as well as many other states, demonstrated its support for Clinton, other states' results coupled with the electoral college system led to Republican candidate Donald Trump's victory for the 2016-2020 term. As with any election, a further analysis into Maryland's results can help researchers better understand trends about voters. In this data analysis, each of Maryland's counties are analyzed for total number of voters and voter turnout for each main political party: the Democrats and the Republicans. This doesn't necessarily provide a reasoning for why Maryland voted for Clinton or why Trump won overall in 2016, but rather takes a more specific look into the state and analyzes how each county votes. 

2016 Results Information from: https://www.nytimes.com/elections/2016/results/maryland

## Business Question

How were the number of Democratic and Republican voters and their respective voting turnout rates distributed throughout the state for the 2016 presidential election, both statistically and geographically? 

## Data Question 

To answer this multi-pronged question, we can ask multiple separate data questions: 
1) How many Democratic and Republican voters were there in each county, and how does each county's counts compare to the average value for the entire state? 
2) What was the voting turnout rate for each county, and how did each of the rates compare to the average value for the entire state? 
3) What are three anchor points that can illustrate the potential clusters of the voting data from questions 1 and 2? 

## Data Analysis 

I conducted a cluster analysis using data from the Maryland State Board of Elections website for 2016's general presidential election: https://elections.maryland.gov/elections/2016/index.html

Data questions 1 and 2 were answered by organizing the dataset and evaluating the z-scores for each of the county's results for the following four variables: Democrat turnout (turnout_dem), Democrat number of voters (voters_dem), Republican turnout (turnout_rep), and Republican number of voters (voters_rep). 

After determining random preset anchors, I used Excel Solver to calculate what the actual anchors are that accurately represent different clusters among the data. 

**Summary of the Solver output:** 


**Meaning of above summary:** 



**Geographic representation:** 



**Meaning of above geographic representation:** 


## Business Answer 

The number of voters and voting turnout data for the two parties were distributed into three groups:
*Group 1* - fewer Dem. and Rep. voters than avg, higher Dem. and Rep. turnout than avg
*Group 2* - fewer Dem. and Rep. voters than avg, lower Dem. and Rep. turnout than avg
*Group 3* - more Dem. voters than avg with less than avg turnout; fewer Rep. voters than avg, and significantly less than avg turnout 

In essence, the voting data is distributed into 3 separate groups, each of which demonstrate different voting behaviors. When put visually on a map, the three groups do not seem to strongly be organized by geography.  

## Use of Findings 

Campaign managers for the Democratic and Republican candidates can use this information to identify where they need to put more work into promoting their respective parties. At this critical point in the 2020 election, campaigners are focusing on states that have a critical impact on who will win, but for the 2024 election, campaigners can use this analysis to properly advertise in the correct locations. For example, Anchors/Groups 2 and 3 had low turnouts for both Democratic and Republican voters, meaning that campaign managers for both parties could focus their attention on counties corresponding to those anchors in order to get more people to cast their ballots and contribute to the election. This could entail organizing more rallies, putting up more billboards and lawn signs, and generally placing more of an investment into those areas. 
