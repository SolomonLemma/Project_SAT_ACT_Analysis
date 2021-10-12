# Project: SAT and ACT Analysis

### Problem Statement

The data used in this project containing the test scores and participation rates for the two standardization tests, SAT & ACT, conducted in the US for the universities and colleges admission requirements. The datasets provided in the year 2017 contains the following values in the csv files formats:

    SAT 2017: State, Participation Rate, Math & Evidence-Based Reading and Writing, and Total scores.
    ACT 2017: State, Participation Rate, Math, Science, Reading, English, and Composite scores.

This project used SAT and ACT dataset to examine the participation rate of the states in the year 2017. The data cleaning methods were applied to prepare the data for further analysis investigate. In addition, the study estimates the statistical description of the data with the correlation of each test participation for preferred test scores. The project aimed to address the overall statistical distribution of the SAT over ACT in the same year with different states for imporuving participation rates.


##  Outline of the Summary

- Error data cleaned it appeared in composit and participation of scores 
- State with lowest participation rates
  - 2017 ACT : **Maine** (8%)
  - 2017 SAT : **North Dakota**, **Mississippi **, **Iowa** (2%)	

- States with highest participation rates
  - 2017 ACT :  **Alabama**, **North Carolina**, **Montana**, **Colorado**, **Oklahoma**... (100%)
  - 2017 SAT : **District of Columbia**, **Michigan**, **Connecticut**, **Delaware**        (100%)
 	
- State with highest mean total/composite scores
  - 2017 ACT :  **New Hampshire** (25.5)
  - 2017 SAT :  **District of Columbia** (950)
  
- State with lowest mean total/composite scores
  - 2017 ACT : **Nevada** (17.8)
  - 2017 SAT : **Minnesota** (1295)
  
- Heatmaps, histograms, boxplots and  scatterplots were applied to visualize the results in depth.
- Strong negative relationship between test participation and average test score is found. States with lower participation rates likely to see higher average scores than a state with higher participation rates on that same test
- The distribution for ACT participation rates skewed to the left whereas for SAT participation rates skewed to the right for both years. ACT participation is higher than SAT.

### Contents:
- [Background](#Background)
- [2017 Data Import & Cleaning of ACT and SAT](#2017-Data-Import-&-Cleaning-of-ACT-and-SAT)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-Data)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)


## Conclusions and Recommendations
There is interest in the academic institution to use SAT or ACT test as reference standard for the admission (1). However, states have different preferred requirement either SAT or CAT participation for college admission (1-2). The results confirmed each tests has independent of each other’s to estimate the participation of the student for the college or university admissions. The analysis showed more states (17) have 100% participation rate of ACT as compared with states for SAT (4 states). This indicates ACT has more preferred than SAT. Further, there were four states had above 50% participation in SAT and ACT. From these results it may be better to use both tests as tools to all states instead one. 

## Reference 
1)	https://blog.prepscholar.com/act-vs-sat 
2)	Coyle, T. R., Purcell, J. M., Snyder, A. C., & Richmond, M. C. (2014). Ability tilt on the SAT and ACT predicts specific abilities and college majors. Intelligence, 46, 18-24.
3)	VanderPlas, J. (2016). Python data science handbook: Essential tools for working with data. " O'Reilly Media, Inc." (used throughtout the analysis.)
---
