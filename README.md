## Project 1: Analysis of Statewide SAT and ACT Participation Rates and Aggregate Scores


### Problem Statement

This project will examine trends in the participation rates and aggregate scores of the US Scholastic Aptitude Test (SAT) and American College Testing (ACT) tests in 2017 and 2018. As participation rates vary greatly by state, this project seeks to look for patterns and suggest to the College Board a suitable state in which to invest resources to improve SAT participation rates. 


### Executive Summary

The SAT is a standardized test in the US and is made up of Evidence-Based Reading and Writing and Math components, each with a maximum score of 800, which is added up to give a total score with a maximum of 1600. The ACT is a standardized test in the US and is made up of English, Math, Reading and Science components, scored from 1 to 36. A composite score is taken from the average score of all four components.

It is compulsory for students in some states to sit for the SAT or ACT as a criteria for graduation, while taking either test is voluntary in others. Both SAT and ACT are accepted by US universities as an indication of the student's academic ability.

Patterns in the data showed that participation in ACT or SAT was negatively correlated, with high participation for one tests usually meaning low participation in another. This is especially true for states with mandatory testing for one of the tests. Test scores in one test was also negatively correlated with the other. Interestingly, the data also showed that participation rates and test scores were negatively correlated, with high participation usually resulting in lower test scores, and vice-versa. It was also observed that East and West Coast states generally preferred the SAT while Midwest states generally preferred the ACT.

After examining the data, I conclude that efforts to increase SAT participation should be focused on Oregon. This is because Oregon does not have mandatory testing for ACT, and the College Board's efforts should be focused on states without compulsory ACT testing, since it is less likely that students would take both ACT and SAT as one test is enough for university admission. Oregon also has low participation rates for both ACT and SAT in 2017 and 2018. The population taking the ACT or SAT has also been split evenly, which means that the SAT is consistently perceived by half of Oregon's test-taking population as a better option. The College Board could focus its efforts on persuading the other half to choose SAT instead of ACT.

Recommendations for the College Board to boost participation rates in Oregon are: reducing the cost of the SAT, increase marketing on the benefits of taking the SAT, and increasing the availability of SAT prep materials in schools.


### Contents
- 2017 Data Import & Cleaning 
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations


### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|Names of US States| 
|act_2018_participation_pct|int|ACT|Members of the graduating class who had taken the ACT as a percentage of the total number of high school graduates in 2017| 
|act_2017_english|float|ACT|Mean score for the English component of the ACT in 2017| 
|act_2017_math|float|ACT|Mean score for the Math component of the ACT in 2017| 
|act_2017_reading|float|ACT|Mean score for the Reading component of the ACT in 2017| 
|act_2017_science|float|ACT|Mean score for the Science component of the ACT in 2017| 
|act_2017_composite|float|ACT|Mean composite score for the ACT, which takes the average of the English, Math, Reading and Science scores in 2017| 
|sat_2017_participation_pct|int|SAT|Members of the graduating class who had taken the SAT test as a percentage of the total number of high school graduates in 2017| 
|sat_2017_evidence_based_reading_and_writing|int|SAT|Mean score for the Evidence-Based Reading and Writing component of the SAT in 2017| 
|sat_2017_math|int|SAT|Mean score for the Math component of the SAT in 2017| 
|sat_2017_total|int|SAT|Mean total score for the SAT in 2017| 
|act_2018_participation_pct|int|ACT|Members of the graduating class who had taken the ACT as a percentage of the total number of high school graduates in 2018| 
|act_2018_english|float|ACT|Mean score for the English component of the ACT in 2018| 
|act_2018_math|float|ACT|Mean score for the Math component of the ACT in 2018| 
|act_2018_reading|float|ACT|Mean score for the Reading component of the ACT in 2018| 
|act_2018_science|float|ACT|Mean score for the Science component of the ACT in 2018| 
|act_2018_composite|float|ACT|Mean composite score for the ACT, which takes the average of the English, Math, Reading and Science scores in 2018| 
|sat_2018_participation_pct|int|SAT|Members of the graduating class who had taken the SAT test as a percentage of the total number of high school graduates in 2018| 
|sat_2018_evidence_based_reading_and_writing|int|SAT|Mean score for the Evidence-Based Reading and Writing component of the SAT in 2018| 
|sat_2018_math|int|SAT|Mean score for the Math component of the SAT in 2018| 
|sat_2018_total|int|SAT|Mean total score for the SAT in 2018| 


### Conclusions and Recommendations

### Key takeaways
- High participation rates in one test usually result in low participation rates for the other. This is because students typically take only one test which is adequate to fulfill university entry requirements 
- Participation rates are negatively correlated with test scores, i.e., states with high participation in a test would usually have a low mean score, and vice-versa. 
    - Tests with low participation rates have high mean total/composite scores. Students taking the non-compulsory/"less popular" test would likely be a minority group of academically-inclined students seeking to increase their chances of getting into a good university by taking both ACT and SAT. <sup>[[1]](https://www.nytimes.com/2013/08/04/education/edlife/more-students-are-taking-both-the-act-and-sat.html)</sup>
- SAT is more popular with West and East coast states, while Midwest states have a preference for ACT. 

### Efforts to increase SAT participation should be focused on Oregon
- Oregon does not have mandatory testing for ACT. 
    - Efforts should be focused on states without compulsory ACT testing, since it is less likely that students would take both ACT and SAT since one test is enough for university admission. As such, participation rates in SAT would be difficult to raise for these states
- It currently has low participation rates for both ACT (40% in 2017 and 42% in 2018) and SAT (43% in 2017 and 48% in 2018). 
    - The split between students taking the ACT or SAT has been very even between 2017 and 2018, which means that SAT is consistently perceived by half of Oregon's test-taking population as the better option. The College Board could focus its efforts on persuading the other half to choose SAT instead of ACT. 

### Recommendations
- Reduce cost of SAT to make it more competitive as SAT and ACT are currently similarly priced <sup>[[2]](https://blog.prepscholar.com/sat-cost-act-cost-and-how-to-save-money)</sup>. The College Board could also make the condition for fee waivers more lenient to allow to more underprivileged students to take the SAT. 
- Increase marketing on benefits of SAT compared to ACT to convince states/schools to conduct more SAT tests. One such benefit could be the introduction of an "Adversity Index", designed to place students' SAT scores in the context of their socioeconomic advantages/disadvantages <sup> [[3]](https://www.insidehighered.com/admissions/article/2019/05/20/college-board-will-add-adversity-score-everyone-taking-sat)</sup>
- Make practice material more readily available by working with schools to provide comprehensive prep material at a reduced cost 

If successful, these recommendations could be applied to other states with similar participation rates with Oregon and has no mandatory testing for ACT. Based on the 2017/2018 data, these states are Alaska, California, Iowa, Kansas and West Virginia. 



