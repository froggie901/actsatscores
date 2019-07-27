# Analysis of ACT/SAT Scores by Region and State 

A Project to Investigate Differences in ACT/SAT Scores Across the US

# Executive Statement

In 2016, the College Board released a new format for the SAT. We know from internal data that the participation rate varies across different regions in the US. The midwest region has lowest participation rate across the county, yet the average overall score is much higher that national average (1). As a case study for this report we examine the state of Missouri.

## Project Layout, Python Libraries,  and Data Dictionary 

This section contains the foldering, libaries, and the data dictionary that was used for this project. 

### Libraries


### Layout 

-| README.md
-| Data
	- act_2017.csv (Raw Data, ACT 2017) 
	- sat_2017.csv (Raw Data, SAT 2017)
-| Jupyter Notebook
	- actsat_edanotebook.ipynb (Exploratory Data Analysis)

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**State**|*string*|sat_2017_df| U.S. States| 
|**Participation**|*string*|sat_2017_df| Rates of Participation, Percentage|
|**Evidence-Based Reading and Writing**|*integer*|sat_2017_df| Raw Score (200-800)|
|**Math**|*integer*|sat_2017_df| Raw Score (200-800)|
|**Total**|*integer*|sat_2017_df| Raw Score (400-1600)|
|**State**|*string*|act_2017_df| U.S. States|
|**Participation**|*string*|act_2017_df| Rates of Participation, Percentage|
|**English**|*integer*|act_2017_df| Raw Score (1-36)|
|**Math**|*integer*|act_2017_df| Raw Score (1-36)|
|**Reading**|*integer*|act_2017_df| Raw Score (1-36)|
|**Science**|*integer*|act_2017_df| Raw Score (1-36)|
|**Composite**|*integer*|act_2017_df|Average Score (1-36)|
|**State**|*string*|sat_2018_df| U.S. States|
|**Participation**|*string*|sat_2018_df| Rates of Participation, Percentage|
|**Evidence-Based Reading and Writing**|*integer*|sat_2018_df| Raw Score (200-800)|
|**Math**|*integer*|sat_2018_df| Raw Score (200-800)|
|**Total**|*integer*|sat_2018_df| Raw Score (400-1600)|
|**State**|*string*|act_2018_df| U.S. States|
|**Participation**|*string*|act_2018_df| Rates of Participation, Percentage|
|**Composite**|*integer*|act_2018_df|Average Score (1-36)|





## Sources 

(1) https://economix.blogs.nytimes.com/2009/08/28/why-the-midwest-rules-on-the-sat/
