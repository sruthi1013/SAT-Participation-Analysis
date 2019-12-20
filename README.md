# Project 1: SAT & ACT Analysis

## Problem Statement

SAT participation rates have been declining over the years as more colleges are opting out of the requirement that standardized test scores be part of a student's application, and as more states are making are making them optional.

## Executive Summary

This proposal analyzes the nation-wide SAT and ACT data from the past two years, in order to suggest one state with a lower participation rate and provide recommendations for how the College Board might increase participation amongst graduating seniors in that state.

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [More Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

## Description of the Data

| Feature             	| Type   	| Dataset  	| Description              	|
|---------------------	|--------	|----------	|--------------------------	|
| state               	| object 	| n/a      	| US State                 	|
| participation_act17 	| float  	| ACT 2017 	| Participation Percentage 	|
| english_act17       	| float  	| ACT 2017 	| Average English Score    	|
| math_act17          	| float  	| ACT 2017 	| Average Math Score       	|
| reading_act17       	| float  	| ACT 2017 	| Average Reading Score    	|
| science_act17       	| float  	| ACT 2017 	| Average Science Score    	|
| composite_act17     	| float  	| ACT 2017 	| Average Composite Score  	|
| participation_sat17 	| float  	| SAT 2017 	| Participation Percentage 	|
| reading_sat17       	| int    	| SAT 2017 	| Average Reading Score    	|
| math_sat17          	| int    	| SAT 2017 	| Average Math Score       	|
| total_sat17         	| int    	| SAT 2017 	| Average Total Score      	|
| participation_act18 	| float  	| ACT 2018 	| Participation Percentage 	|
| composite_act18     	| float  	| ACT 2018 	| Average Composite Score  	|
| participation_sat18 	| float  	| SAT 2018 	| Participation Percentage 	|
| reading_sat18       	| float  	| SAT 2018 	| Average Reading Score    	|
| math_sat18          	| float  	| SAT 2018 	| Average Math Score       	|
| total_sat18         	| float  	| SAT 2018 	| Average Total Score      	|

## CONCLUSIONS
- SAT and ACT participation rates across all the US states are complements of each other, since most students take any one test, but not both in high school.
- States which have made either test compulsary have very high participation rates in that test, and very low participation in the other test.
- A few states which made both tests optional, or any one test mandatory have participation rates depending on the location. In other states, it depends on the students' preferences.
- Higher participation means less total score, because it's probably mandatory, and everyone takes the test, whether they want to or not, and whether they have prepared for it or not.
- Lower participation means more total score, because it's optional, and only people who are interested and have prepared for the test take it.
- Alaska and Iowa both have less than 80% participation in both tests together, which means more than 20% of the high school students in each of those states don't take any test.
- Since Iowa is in the Midwest, and ACTs are more popular in the Midwest, Alaska is a good choice to try and increase SAT participation.
- Both SAT and ACT were made optional in Alaska in 2016. This resulted in a drop in the ACT participation(65% in 2017 to 33% in 2018). 

## RECOMMENDATIONS
- Students can be motivated to take the SATs if they're confident that they'll do will in the tests. This can be done by providing free test prep material/courses.
- Waiving the test fee initially.
- Offering the exam during regular school hours.
- Only 45.7% of Alaska high school students attend college compared to the national average of 63.3%. Promoting a culture which encourages students to pursue education after high school would increase the SAT patricipation rates.

