# California School Districts Successful Transition to New Mathematics Framework

### Problem Statement
The Board of Education for the state of California would like to allocate resources to districts in need pertaining to student success in math. The project aims to identify the California school districts with the lowest student performances in mathematics by using ACT and SAT data. Those school districts will be looked at further to determine what resources or funds would be beneficial in order to increase student success in mathematics.

### Datasets & Data Dictionary

* ACT 2019 score report for California. This report highlights the school, district, and county averages for each ACT section: English, Mathematics, Reading, and Science. The averages, as well as the composite scores, are on a scale of 1 - 36. ([`act_2019_ca.csv`](./data/act_2019_ca.csv): 2019 ACT Scores in California by School)
* SAT 2019 score report for California. This report highlights the school, district, and county numbers over benchmark. Instead of providing average, the state provides the number of students who have surpassed the benchmark values. For this project's purposes, the 12th grade math numbers will be used as only 12th grade math numbers are available for the ACT data and this will keep the datat consistent. The benchmark for 12th grade math is 530. Therefore, the numbers listed are the number of students who have surpassed the benchmark. ([`sat_2019_ca.csv`](./data/sat_2019_ca.csv): 2019 SAT Scores in California by School)

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**dname**|*object*|sat_act_2019_ca_d|The names of all of the districts with SAT and ACT data in California for the year 2019.| 
|**num_schools_in_district_sat**|*integer*|sat_act_2019_ca_d|The number of schools in the district with SAT data.| 
|**enroll12_mean_sat**|*float*|sat_act_2019_ca_d|The average enrollment of students in 12th grade for the schools in the respective district for the SAT.|
|**pctmathbenchmark12_mean_sat**|*float*|sat_act_2019_ca_d|The average percentage of students surpassing the math SAT benchmark score of 530 for the respective district.|
|**num_schools_in_district_act**|*float*|sat_act_2019_ca_d|The number of schools in the district with ACT data.|
|**enroll12_mean_act**|*float*|sat_act_2019_ca_d|The average enrollment of students in 12th grade for the schools in the respective district for the ACT.|
|**avgscrmath_mean_act**|*float*|sat_act_2019_ca_d|The average math score on the ACT for the respective district. Scores range from 1-36.| 

### Brief Analysis 

This study found that approximately 17 school districts across California scored in the bottom 10% of the SAT and ACT compared to the overall California standardized test scores. While the 2019 SAT data did not provide exact SAT Math scores, the mean percentage of students surpassing a benchmark score of 530, for 12th grade students only, for each of the school districts was provided. Using this variable, the school districts were sorted and analyze. The 2019 ACT data provided the actual average ACT Math scores for the school districts.  Through analysis, it was deteremind there were not immediate outlier school districts.  The bottom 10% list for each SAT and ACT were compared and those school districts appearing in both lists are being recommended for extra funds for the mathematics department. 



### Conclusions & Recommendations
As California moves to a new mathematics framework where students will be 'de-tracked' and placed in one level per mathematics classes, this will increase the diversity in math classrooms. Using the 2019 SAT and ACT results for California school districts, the specific school districts that have scored in the bottom 10% will be identified to provide extra resources. In order to adequately compare, only 12th grade test takers were analyzed. While the data provided for 2019 does not give explicit SAT Math scores, we were able to identify the average percentage of students who surpassed the California benchmark SAT Math score of 530 for each school district. The ACT data did provide an average math score. 

Data was analyzed to identify the school districts in the bottom 10% for each of SAT Math Benchmark Percenages for 12th graders and ACT Average Math Score for 12th graders. The final list of recommended school districts include those that appeared in both the bottom SAT and bottom ACT list. 

It is our recommendation the the following school districts are looked at further to determine what resources or funds would be beneficial in order to in order to successfully implement the new California Mathematics Framework: Centinela Valley Union High, Compton Unified, Cutler-Orosi Joint Unified, Delhi Unified, Farmersville Unified, Firebaugh-Las Deltas Unified, Golden Plains Unified, Gonzales Unified, Gustine Unified, Inglewood Unified, Le Grand Union High, Lynwood Unified, Mendota Unified, Reef-Sunset Unified, SBE - Academia Avance Charter, San Joaquin County Office of Education, Soledad Unified, and South Monterey County Joint Union High.

