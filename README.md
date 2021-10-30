# Crash Dummies - Car Crash Report Analysis

## Team Members: Shreya Udeshi, Ra Ish Andrews, Ellis Purwanto

## Background

**Source of Data:** https://www.nhtsa.gov/file-downloads?p=nhtsa/downloads/CRSS/

![Crash Dummies](/images/1.gif)

* The U.S. Department of Transportation, National Highway Traffic Safety Administration issued a car crash report

* Accidents in 2018 appear to relate to three variables: location, time, and driver demographic

* We will evaluate a variety of subcategories within the data set during our research, including Region (in terms of localities), Date (in terms of time), and Age and Gender (in reference to person’s demographic)

## Objectives

**Understand Data**

**Discover Patterns**

**Establish Relationships Between Data Elements**

## Data Elements

**Location Data Frame:** Manner_of_Collision, REGION, URBANICITY

**Person Data Frame:** AGE_IM,  SEX_IM, INJSEV_IM

**Time Data Frame:** CASENUM, NUM_INJ, URBANICITY, MONTH, WKDY_IM, HOUR_IM

### Location Data Frame

**Urbanicity v/s Number of Car Crashes**

* Urban areas contain a population of 250,000 or greater

* There are more accidents in Urban Areas than Rural drastically

![Urbanicity](/images/urbanicity.png)

**Region v/s Number of Car Crashes**

* Northeast (PA, NJ, NY, NH, VT, RI, MA, ME, CT) 

* Midwest (OH, IN, IL, MI, WI, MN, ND, SD, NE, IA, MO, KS) 

* South (MD, DE, DC, WV, VA, KY, TN, NC, SC, GA, FL, AL, MS, LA, AR, OK, TX)

* West (MT, ID, WA, OR, CA, NV, NM, AZ, UT, CO, WY, AK, HI)

* Ther are more accidents in the *South* region than any other region

![Region](/images/region.png)

**Region v/s Urbanicity (Number of Crashes)**

![Urbanicity](/images/region_urbanicity.png)

**Manner of Collision Vs Number of Accidents**

* "Manner of Collision" describes the orientation of two motor vehicles in-transport when they are involved in the “First Harmful Event” of a collision crash

![Manner of Collision Vs Number of Accidents](/images/manner_coll.png)

**Manner of Collision Vs Number of Accidents by Region**

Out of the top 15- Most accidents happen Front-to-Rear in the South 

![Manner of Collision Vs Number of Accidents by Region](/images/manner_coll_region.png)

#### Analysis

* Most accidents in the data set are occurring in the south from Front to Rear accidents.
* This could be caused to congestion on highways in highly populated areas.
* Also, studies show that the south tends to be more behind in infrastructure and development  than other areas of the US

[Location Analysis](/Ra_Crash_Dummy_Analysis/Final_Accident_Analysis2018.ipynb)

### Persons Data Frame

![Persons Data Frame](/images/male_female.png)

#### Analysis

* As shown in the visualizations, it can be inferred that Males tend to drive more recklessly than Females.
* Fatal Injuries tend to occur in Male Senior Drivers than any other Age Group.
* Male adults aged 50 and up tend to have much more total accidents than both the <18 and 19-29 age groups combined.
* Surprisingly, the <18 age group has significantly less accidents than every other age group, which could be caused by teens delaying getting a driver license or a stricter rules imposed by local authorities.
* Although many accidents occur each year, over half of them, regardless of gender or age, result in No Injury.

[Person Analysis](/AutoInsuranceClaims.ipynb)

### Time Data Frame

**Monthly Car Crashes**  

![Monthly Car Crahes](/images/monthly.png)

#### Analysis

* The higher number of holiday accidents is due to a multitude of factors that occur throughout the holiday season.
* Overall, there is more traffic on the roads. People are more distracted and are stress driving
* Fatigued Driving, Drunk Driving
* Unfamiliarity to the roads
* Lastly, as it starts to get cooler it also starts to get darker sooner

**Daily Car Crashes**

![Daily Car Crahes](/images/daily.png)

#### Analysis

* As we can see from the bar graph, car crashes on weekdays are practically identical, however there are more car crashes on Friday and Saturday since people are all coming home for the weekend.
* According to a study, more people are consuming alcohol on the weekends, and more people are also feeling relaxed after the work week. This leads to more drunk driving crashes, as well as auto accident injuries resulting from speeding and other forms of reckless driving.

**Hourly Car Crashes**

![Hourly Car Crahes](/images/hourly.png)

#### Analysis

* Believe it or not, most auto accident injuries and fatalities happen during rush hour on most days of the week
* A number of these collisions result from people returning home after office hours, aggressive driving and tailgating 

**Monthly Car Crashes by Urbanicity**

![Monthly Car Crahes by Urbanicity](/images/monthly_urbanicity.png)

**Daily Car Crashes by Urbanicity**

![Daily Car Crahes by Urbanicity](/images/daily_urbanicity.png)

**Hourly Car Crashes by Urbanicity**

![Hourly Car Crahes by Urbanicity](/images/hourly_urbanicity.png)

#### Analysis

* The accompanying figures clearly show that most car accidents occur in urban settings. In comparison to rural areas, urban areas have 30-40% more crashes.
- Car accidents in cities are caused by several common factors:
* Tailgating, dangerous driving (including speeding and incorrect lane changes), and road rage are all caused by large traffic volumes on multi-lane highways
* One-way streets and a limited number of U-turns
* Potholes can cause drivers to lose control of their vehicles or damage the tires on their automobiles.
* It is exceedingly dangerous for drivers to run red lights.

[Time Analysis](/Crash_TimeAnalysis/main.ipynb)

### Final Presentation

[Presentation](/Crash_Dummies.pptx)



