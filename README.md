# COVID19-Recreation-Health
Survey data from an online panel of U.S. adults from February 2021 Qualtrics regarding their outdoor recreation behavior, mental health status, and mental health risk and protective factors during COVID-19.

**Dataset Citation**

Shen, X. & Parkinson, P. (2021) Outdoor recreation and mental health during the COVID-19 pandemic [Data set]. Oregon State University. https://doi.org/10.7267/doid01DOI

**Abstract**

This dataset contains survey responses was from a panel of U.S. adults proportionally representative of the population in age, gender, and race (n = 503). The data is comprised of participants responses to questions through the online survey platform Qualtrics regarding their outdoor recreation behavior (e.g., frequency, most frequent activity, change in activity during COVID-19), mental health status (i.e., mental well-being, depression, perceived stress), and mental health risk and protective factors during COVID-19. The participants were recruited between February 3 and February 15, 2021 from an online crowd-sourcing platform, Prolific. This dataset offers valuable insights into the role of outdoor recreation in managing stressors during one of the deadliest phases of the COVID-19 pandemic in the U.S. 

**Creator and Contact Information**

Name: Xiangyou Shen
Institution: Oregon State University
College, School or Department: College of Forestry, Department of Forest Ecosystems and Society
Address:212 Richardson
Email: Sharon.shen@oregonstate.edu
ORCID: https://orcid.org/0000-0001-9820-3866
Role: Conceptualization, data curation, data collection, funding acquisition, methodology, project administration, supervision

Name: Colby Parkinson
Institution: Oregon State university
College, School or Department:
Email: cbp5535@psu.edu
ORCID: https://orcid.org/0000-0001-8897-8844
Role: Conceptualization, Data collection

**Funding Source**

Oregon State University Hallie E. Ford Center for Healthy Children and Families

**Related Publications**

Publication under review:
Outdoor recreation’s association with mental health and well-being during the COVID-19 pandemic
Author: Colby Parkinson, Xiangyou Shen, Megan MacDonald, Samuel W. Logan, Lydia Gorrell, Kreg Lindberg

**Research Context**

This dataset was collected as part of a broader study, Play2Cope, which aimed to understand leisure and recreation patterns of individuals and their families during the COVID-19 pandemic. This dataset was used to describe outdoor recreation behavior during the COVID-19 pandemic among various demographic groups and to examine the effect of outdoor recreation on mental health outcomes during the pandemic controlling for risk and protective factors and demographic attributes. The timing of this study was unique, taking place when cases and deaths from COVID-19 were their highest yet in the U.S. but soon after officials had federally approved vaccines to reduce the spread of the virus. 

The study was approved by the International Review Board of the at Oregon State University (IRB-2020-0927)

**Data Collection Source**

Prolific. Version February 2021. London, UK, First Released 2014. Available online: https://www.prolific.co (accessed on 2 December 2021).

**Collection Date**

2021-02-03 to 2021-02-15

**Description of Methods**

The data were collected cross-sectionally via the survey platform Qualtrics. Participation was voluntary, with all participants providing consent before answering questions. Participant recruitment and confirmation of eligibility were conducted via the crowd-souring platform Prolific. The full survey took on average less than 15 minutes to complete. 

**Methods for Pre-Processing**

All included items are provided in their raw form with extraneous and identifiable information removed from the original dataset. Pre-processed data, specifically coded open-ended responses to survey questions, composite items, and factor weights were computed and provided for all relevant items with descriptive information for those items provided within the dataset. 

**Quality Assurance Procedures**

The data does not include any responses from participants who took unreasonably short times to complete the survey (i.e., fewer than three minutes) or expressed patterns (e.g., straight-lining) in their response to questions.

**Filename**

OR_Health_PLOS_Data

**Filetype**

.sav

**Recommended Instruments**

The software used to pre-process the data and the best software to use to access the data is IBM SPSS Statistics Version 29.0.2.0. If you would like to access the data using an open-source software, the authors recommend using either Python or R with data analytics packages that support .sav filetypes. 

**File Information**

1. Number of variables: 71

2. Number of cases/rows: 503

3. Missing data codes:
        Code/symbol: .

**Variable View Information**

1. Name: ID
Category: Identification
Item/Description (Label): Unique identification for subjects
Response options (Values): NA


2. Name: Age
Category: Demographic
Item/Description (Label): What is your year of birth?
Response options (Values): Increments of single years 
Min: 18 (2003) 
Max: 100 (1921)

3. Name: Age_R2
Category: Demographic
Item/Description (Label): Age by 2018 Census categories
Response options (Values): 1: 18-24
2: 25-34
3: 35-44
4: 45-54
5: 55-59
6: 60-64
7: 65-74
8: 75+

4. Name: Caregiver
Category: Demographic
Item/Description (Label): Parenting/caregiver recoded into 0 & 1
Response options (Values): 0: Not caregiver
1: Caregiver

5. Name: FmlInc
Category: Demographic
Item/Description (Label): 2020 Household income before taxes.
Response options (Values): 1: Less than $10,000
2: $10,000 to $19,999
3: $20,000 to $29,999
4: $30,000 to $39,999
5: $40,000 to $49,999
6: $50,000 to $59,999
7: $60,000 to $69,999
8: $7,000 to $79,999
9: $80,000 to $89,999
10: $90,000 to $99,999
11: $100,000 to 149,999
12: $150,000 or more

6. Name: FmlInc_R
Category: Demographic
Item/Description (Label): Short version of income
Response options (Values): {.00, <29,999}...

7. Name: Unemployed
Category: Demographic
Item/Description (Label): Dummy for unemployed or furloughed from WorkSt_R
Response options (Values): 0: No
1: Yes

8. Name: gender
Category: Demographic
Item/Description (Label): Gender identity
Response options (Values): 1: Male
2: Female
3: Trans*
4: Non-binary
5: Prefer not to disclose

9. Name: Sex
Category: Demographic
Item/Description (Label): Gender recoded into M & F
Response options (Values): 0: Female
1: Male

10. Name: Race
Category: Demographic
Item/Description (Label): Race
Response options (Values): 1: White
2: Asian
3: Black or African American
4: Natie Hawaiian or Other Pacific Islander
5: American Indian or Alaska Native
7: Other (please specify)

11. Name: Race_7_TEXT
Category: Demographic
Item/Description (Label): Race- Other
Response options (Values): Open-ended reposonse to question about race

12. Name: Race_R
Category: Demographic
Item/Description (Label): Race w?/ NH or PI and AI or AN in to Indigenous or Pacific Islander (Pre-processed from race for dummy variables)
Response options (Values): 0: White
1: Asian
2: Black or African American
3: Indigenous or Pacific Islander
4: Other

13. Name: Race_ANOVA
Category: Demographic
Item/Description (Label): PI and indigenous as missing (Pre-processed from Race_R to include only large categories)
Response options (Values): 0: White
1: Asian
2: Black or African American

14. Name: asian
Category: Demographic
Item/Description (Label): Dummy for asian from Race_R
Response options (Values): 0: No
1: Yes

15. Name: black
Category: Demographic
Item/Description (Label): Dummy for black or African American from Race_R
Response options (Values): 0: No
1: Yes

16. Name: indigenous
Category: Demographic
Item/Description (Label): Dummy for indigenous or Pacific Islander from Race_R
Response options (Values): 0: No
1: Yes

17. Name: other
Category: Demographic
Item/Description (Label): Dummy for other from Race_R
Response options (Values): 0: No
1: Yes

18. Name: SbjF
Category: Demographic
Item/Description (Label): How do you feel about your financial situation?
Response options (Values): 1: I'm behind on my bills
2: I'm barely making ends meet
3: I'm just getting by
4: I'm doing alright
5: I'm living comfortably

19. Name: white
Category: Demographic
Item/Description (Label): Dummy for white from Race_R
Response options (Values): 0: No
1: Yes

20. Name: WorkSt
Category: Demographic
Item/Description (Label): current work status?
Response options (Values): 1: Working from home
2: Working outside home - high-risk position
3: Working outside home - non-high-risk position
4: Furloughed
5: Unemployed
6: Prefer not to disclose 

21. Name: WorkSt_R
Category: Demographic
Item/Description (Label): Work status with furloughed and unemployed recoded and combined (pre-processed from WorkSt)
Response options (Values): 0: Working from home
1: Working outside home - high-risk position
2: Working outside home - non-high-risk position
3: Furloughed or unemployed

22. Name: Workst_R2
Category: Demographic
Item/Description (Label): Simplified work status
Response options (Values): 0: Working from home
1: Working outside home
2: Unemployed or Furloughed 

23. Name: From_Home
Category: Demographic
Item/Description (Label): Dummy for working from WorkSt_R
Response options (Values): 0: No
1: Yes

24. Name: From_Work
Category: Demographic
Item/Description (Label): Dummy for working outside home
Response options (Values): 0: No
1: Yes

25. Name: High_Risk
Category: Demographic
Item/Description (Label): Dummy for working outside home - high risk positions from WorkSt_R
Response options (Values): 0: No
1: Yes

26. Name: Low_Risk
Category: Demographic
Item/Description (Label): Dummy for working outside home - non-high-risk positions from WorkSt_R
Response options (Values): 0: No
1: Yes

27. Name: Dprs_1
Category: Mental Health Status
Item/Description (Label): Feeling down, depressed, or hopeless (value 0-3 needs to be 1-4 for calculation of composite variable)
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

28. Name: Dprs_2
Category: Mental Health Status
Item/Description (Label): Feeling down, depressed, or hopeless (value 0-3 needs to be 1-4 for calculation of composite variable)
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

29. Name: Depression
Category: Mental Health Status
Item/Description (Label): Average of 2 depressive symptom items in Physical Health Questionnaire (MEAN((Dprs_1+1),(Dprs_2+1)). Pre-processed from DPRS_X variables.
Response options (Values): Min: 0 
Max: 6

30. Name: EWB1
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I have felt cheerful and in good spirits
Response options (Values): 0: At no time
1: Some of the time
2: Less than half of the time
3: More than half of the time
4: Most of all the time
5: All of the time

31. Name: EWB2
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I have felt calm and relaxed
Response options (Values): 0: At no time
1: Some of the time
2: Less than half of the time
3: More than half of the time
4: Most of all the time
5: All of the time

32. Name: EWB3
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I have felt active and vigorous
Response options (Values): 0: At no time
1: Some of the time
2: Less than half of the time
3: More than half of the time
4: Most of all the time
5: All of the time

33. Name: EWB4
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I woke up feeling fresh and rested
Response options (Values): 0: At no time
1: Some of the time
2: Less than half of the time
3: More than half of the time
4: Most of all the time
5: All of the time

34. Name: EWB5
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - My daily life has been filled with things that interest me
Response options (Values): 0: At no time
1: Some of the time
2: Less than half of the time
3: More than half of the time
4: Most of all the time
5: All of the time

35. Name: EmoWell
Category: Mental Health Status
Item/Description (Label): Sum of 5 items in WHO-5 Well-being Index. Pre-processed from EWBX variables.
Response options (Values): Min: 0
Max: 25

36. Name: Stress_1
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I found it hard to wind down
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

37. Name: Stress_2
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I tended to over-react to situations
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

38. Name: Stress_3
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I felt that I was using a lot of nervous energy
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

39. Name: Stress_4
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I found myself getting agitated
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

40. Name: Stress_5
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I found it difficult to relax
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

41. Name: Stress_6
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I was intolerant of anything that kept me from getting on with what I was doing
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

42. Name: Stress_7
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I felt that I was rather touchy
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

43. Name: Stress
Category: Mental Health Status
Item/Description (Label): Sum of 7 stress items in DASS-21. Pre-processed from Stress_X variables. 
Response options (Values): Min: 0
Max: 21

44. Name: FavOR
Category: Outdoor Recreation Behavior
Item/Description (Label): What is your most frequent outdoor recreation activity during COVID-19?
Response options (Values): Open-ended response

45. Name: FavOR_Rec
Category: Outdoor Recreation Behavior
Item/Description (Label): What is your most frequent outdoor recreation activity during COVID-19? (Pre-processed from FavOR to add numeric values)
Response options (Values): Open-ended response

46. Name: FavOR_CatR
Category: Outdoor Recreation Behavior
Item/Description (Label): Favorite outdoor activity categorized (Pre-processed from FavOR_Rec taking open-ended responses and placing them into categories manually by researcher)
Response options (Values): 1: Walking
2: Exploring Places
3: Motorized Recreation
4: Running or Jogging
5: Bicycling
6: Water-Based Sports
7: Field or Court Sports
8: Skiing, hockey, and board sports
9: Other specialized activities
10: Relaxing activities
11: Gardening or Yard Work
12: Other - home
13: Other - Adventure
14: Hiking

47. Name: FavOR_Broad
Category: Outdoor Recreation Behavior
Item/Description (Label): Favorite outdoor activity by activity type (Pre-processed from FavOR_CatR to broader categories)
Response options (Values): 1: Nature Activities
2: Near Home Activities

48. Name: ORChng
Category: Outdoor Recreation Behavior
Item/Description (Label): Compared with how frequent you recreated outdoors before COVID-19, how is your current level of outdoor activity:
Response options (Values): 1: Much less now than before COVID-19
2: Slightly less now than before COVID-19
3: About the same
4: Slightly more now than before COVID-19
5: Much more now than before COVID-19

49. Name: ORChngCat
Category: Outdoor Recreation Behavior
Item/Description (Label): Categorical OR Change (pre-processed from ORChng so slightly less and slightly more are maintain)
Response options (Values): 0: Maintain
1: Less
2: More

50. Name: Same_OR
Category: Outdoor Recreation Behavior
Item/Description (Label): Same/Maintain OR Level Dummy
Response options (Values): 0: No
1: Yes

51. Name: Less_OR
Category: Outdoor Recreation Behavior
Item/Description (Label): Less OR Dummy
Response options (Values): 0: No
1: Yes

52. Name: More_OR
Category: Outdoor Recreation Behavior
Item/Description (Label): More OR Dummy
Response options (Values): 0: No
1: Yes

53. Name: ORFreq
Category: Outdoor Recreation Behavior
Item/Description (Label): Over the past month, how often did you recreate outdoors?
Response options (Values): 1: Less than once a week
2: Once a week
3: 2-3 times a week
4: 4-5 times a week
5: Almost every day

54. Name: COV_OutlNorml
Category: Risk/Protective Factor
Item/Description (Label): I am optimistic that life will return to normal soon
Response options (Values): 1: Strongly Disagree
2: Disagree Moderately
3: Disagree Slightly
4: Agree Slightly
5: Agree Moderately
6: Agree Strongly

55. Name: COV_OutlVccn
Category: Risk/Protective Factor
Item/Description (Label): Situations are improving with the development of vaccines
Response options (Values): 1: Strongly Disagree
2: Disagree Moderately
3: Disagree Slightly
4: Agree Slightly
5: Agree Moderately
6: Agree Strongly

56. Name: COVID_Precaution
Category: Risk/Protective Factor
Item/Description (Label): I take active precautionary measures to lower the risk of infection
Response options (Values): 1: Strongly Disagree
2: Disagree Moderately
3: Disagree Slightly
4: Agree Slightly
5: Agree Moderately
6: Agree Strongly

57. Name: COVID_RiskGeneral
Category: Risk/Protective Factor
Item/Description (Label): There is a high likelihood of acquiring COVID-19 in general
Response options (Values): 1: Strongly Disagree
2: Disagree Moderately
3: Disagree Slightly
4: Agree Slightly
5: Agree Moderately
6: Agree Strongly

58. Name: COVPM_Anxiety
Category: Risk/Protective Factor
Item/Description (Label): COVID-19 preventative measures cause anxiety in me
Response options (Values): 1: Strongly Disagree
2: Disagree Moderately
3: Disagree Slightly
4: Agree Slightly
5: Agree Moderately
6: Agree Strongly

59. Name: COVPM_Cnstr
Category: Risk/Protective Factor
Item/Description (Label): COVID-19 preventative measures are constraining
Response options (Values): 1: Strongly Disagree
2: Disagree Moderately
3: Disagree Slightly
4: Agree Slightly
5: Agree Moderately
6: Agree Strongly

60. Name: COVPM_LowerRisk
Category: Risk/Protective Factor
Item/Description (Label): COVID-19 preventative measures help lower the risk of infection
Response options (Values): 1: Strongly Disagree
2: Disagree Moderately
3: Disagree Slightly
4: Agree Slightly
5: Agree Moderately
6: Agree Strongly

61. Name: COVPM_PrvFulLife
Category: Risk/Protective Factor
Item/Description (Label): COVID-19 preventative measures make it hard to live a full life
Response options (Values): 1: Strongly Disagree
2: Disagree Moderately
3: Disagree Slightly
4: Agree Slightly
5: Agree Moderately
6: Agree Strongly

62. Name: COVPM_Safer
Category: Risk/Protective Factor
Item/Description (Label): COVID-19 preventative measures help make our environment safer
Response options (Values): 1: Strongly Disagree
2: Disagree Moderately
3: Disagree Slightly
4: Agree Slightly
5: Agree Moderately
6: Agree Strongly

63. Name: Neg_RM
Category: Risk/Protective Factor
Item/Description (Label): Negative perception of restrictive measures  (calcualted as average). Pre-process of  COVPM_Anxiety, COVPM_PrvFullLife and COVPM_Cnstr.
Response options (Values): Min: 1
Max: 6

64. Name: Pos_RM
Category: Risk/Protective Factor
Item/Description (Label): Positive perception of restrictive measures (calcualted as average). Pre-process of  COVPM_LowerRisk and COVPM_Safer.
Response options (Values): Min: 1
Max: 6

65. Name: Infct
Category: Risk/Protective Factor
Item/Description (Label): Have you been confirmed (via a positive test) or suspected (based on symptoms) that you had COVID-19?
Response options (Values): 0: No, I have not been confirmed or suspected
1: Yes, I have been confirmed via a positive test
2: Yes, I have been suspected based on my symptoms
3: Prefer not to disclose

66. Name: Infct_R
Category: Risk/Protective Factor
Item/Description (Label): Infct w/ prefer not to disclose marked as missing; suspected/confirmed combined (Pre-processed from infct)
Response options (Values): 0: No
1: Yes, confirmed or suspected

67. Name: Lonely_2
Category: Risk/Protective Factor
Item/Description (Label): Over the past two weeks - I felt isolated
Response options (Values): 0: Not at all
1: Some of the timex
2: A considerable amount of time
3: Most of the time

68. Name: Isolated
Category: Mental Health Status
Item/Description (Label): Over the past two weeks - I felt isolated (pre-processed from Lonely_2
Response options (Values): 1: Not at all
2: Some of the timex
3: A considerable amount of time
4: Most of the time

69. Name: Pre_extn
Category: Risk/Protective Factor
Item/Description (Label): Do you have chronic disease(s) or pre-existing medical/psychiatric illness?
Response options (Values): 0: No 
1: Yes

70. Name: AbsRes_Dep
Category: Regression Calculation
Item/Description (Label): Absolute value of residuals from OLS regression for depression
Response options (Values): NA

71. Name: weight_Dep
Category: Regression Calculation
Item/Description (Label): Computed weight for WLS regression for depression
Response options (Values): NA




