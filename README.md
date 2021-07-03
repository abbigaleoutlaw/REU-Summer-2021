# Analysis of Hispanic Voters in Florida through Subgroup Identification

This project is part of an undergraduate research experience with Embry-Riddle Aeronautical University. I am specifically working with the Florida Democratic Party to determine if sub-group identity of Hispanic voters influences their party affiliation and to analyze or predict other trends that might impact party affiliation or voter activity. 

## Introduction

The Florida Democratic Party is an affiliate of the United States Democratic Party in Florida. The Florida Democratic Party helps with the advertising of democratic party candidates. They also help with creating and funding advertisements with specific purposes, such as to target a specific voter market or to promote down-ballot democratic candidates. The Florida Democratic Party has tasked us with looking into factors that influence Hispanic voter's political party affiliation, such as their subgroup identity and social factors.

From 2016 to 2018, Hispanic Democratic performance went down statewide. Underperformance was isolated in South Florida, meaning this is where the Democratic Party received less votes than anticipated based on results from previous elections. Besides the South Florida region, Hispanic Democratic performance improved from 2016 to 2018. Decrease in Hispanic Democratic performance statewide is important because 26.4 percent of Florida's population is Hispanic. This means that a little more than a quarter of Florida's population is Hispanic, which allows them to heavily influence the vote. The Hispanic population is also one of the fastest growing minority populations in the United States, which means over time, they will continually have more influence on political elections. Another reason studying and predicting subgroups of Hispanic voters is important is the different social factors faced by different Hispanic subgroups when integrating into American culture that could influence their party affiliation. There is also research on how different Hispanic subgroups vote differently based on conditions "back home," meaning the country they or their ancestors emigrated from.

## Scope of the Project 

The goal is to predict subgroups of Hispanic voters, determine the influence one's subgroup has on their party affiliation, identify trends in social factors that influence a voter's party affiliation, and analyze or predict the impact of the different social factors on Hispanic voters in Florida. The project also looks at Hispanic voters' activity in previous elections to determine voting frequency patterns based on party affiliation.

## Data Description

In order to begin the project, we were given Voter History and Voter Registration zip files. These files contain data for all counties in Florida based on zip code. I chose one county, Nassau County, to look more in-depth at. I created Excel files with Nassau County data only in order to condense the amount of data within the files. From the Excel files, I analyzed the data to create graphics to describe the population in Nassau County. 

#### Voter Registration Zip File 

The Voter Registration Zip file contains all the registered voters in Florida, but I specifically looked at the information of registered voters in Nassau County. For each voter, the file contained their county code, voter ID number, name (first, middle, last, second last, and suffix), residence address, zip code, mailing address, gender, race, birthday, registration date, party affiliation, precinct, voter status, phone area code, phone number, email address, etc. 

#### REU Data File 

The REU Data file contains all of the information on the registered voters in Nassau County from the Voter Registration Zip File. I narrowed the voter information down to what was important in helping predict sub-group identity and trends in party affiliation or voter activity. For each voter, I kept county code, voter ID number, name(s), zip code, gender, race, birthday, registration date, party affiliation, voter status, and phone area code. With this information, I was able to create numerous graphics and tables to describe the total population and registered voter population of Nassau County. The REU Data file also contains data from proximityone.com about the distribution of sub-group identities for each zip code in Nassau County. The proximityone.com data contains the number of Hispanics in each sub-group in each zip code of Nassau County, the percentage of Hispanics each sub-group represents by zip code, and the total population of each zip code in Nassau County.

Nassau County consists of six zip codes: 32009, 32011, 32034, 32046, 32097, and 32234. The total population of Nassau County is 79,819 with a Hispanic population of 2,517.

![Total Population by Zip](https://user-images.githubusercontent.com/86391094/124338997-f2bd9000-db78-11eb-8a1d-2b840050e786.png)

As seen in the figure above, zip code 32009 has a total population of 3,325. In zip code 32011, there is a total population of 13,854. The total population of zip code 32034 is 31,008. Zip code 32046 has a total population of 9,410. In zip code 32097, there is a total population of 15,616. The total population of zip code 32234 is 6,606.

Within Nassau County, there are 18 sub-groups represented, 19 if "others" is considered as an individual sub-group. In Nassau County, the sub-groups with the least representation are Paraguayan with no representation and Bolivian with only one representative. The distribution of representation among Hispanic sub-groups can be seen in the figure below.

![Sub-Group Percentages in Nassau County](https://user-images.githubusercontent.com/86391094/124339130-1c2aeb80-db7a-11eb-852e-f262f0db8a27.png)

The figure below shows which Hispanic sub-group is represented the most in each zip code of Nassau County. In zip code 32009, Mexican and Puerto Rican sub-groups have the most representation at 33.33 percent. In zip code 32011, the sub-group with the most representation is Mexican at 34.34 percent. In zip code 32034, the sub-group with the most representation is Mexican at 44.28 percent. In zip code 32046, the sub-group with the most representation is Cuban at 32.87 percent. In zip code 32097, the sub-group with the most representation is Puerto Rican at 31.28 percent. Note that zip code 32234 is not in the figure due to the fact that it is recognized to be a part of Duval County. However, in our voter data file, it is considered part of Nassau County. In zip code 32234, the sub-group with the most representation is Mexican at 43.80 percent.

<img src="https://user-images.githubusercontent.com/86391094/124339224-f520e980-db7a-11eb-80bf-dd07862e4b73.png" width="500" height="500" />

Within Nassau County, there are 70,707 registered voters with Hispanics representing 1.996 percent of registered voters. This means that there are 1,411 Hispanics registered to vote in Nassau County.

| Zip Code | Non-Hispanic | Hispanic |
| -------- | ------------ | -------- |
| 32009 | 2472 | 28|
| 32011 | 11458 | 170 |
| 32034 | 31731 | 632 |
| 32046 | 7011 | 53 |
| 32097 | 16568 | 528 |
| 32234 | 56 | 0 |

The table above compares the number of non-Hispanic voters to Hispanic voters in each zip code of Nassau County.

![Total Hispanics vs  Registered Hispanic Voters](https://user-images.githubusercontent.com/86391094/124339596-96a93a80-db7d-11eb-994b-c0b624d26c92.jpg)

The figure above compares the total Hispanic population of Nassau County to the total number of registered Hispanic voters in Nassau County by zip code. Note, in zip code 32097, almost all Hispanics are registered to vote. Also, in zip code 32234, there are no Hispanics registered to vote.

![Party Affiliation Percentages](https://user-images.githubusercontent.com/86391094/124339643-e425a780-db7d-11eb-9996-d06df8595a27.png)

The figure above shows the distribution of voters among different parties. The figure shows the percentage of Non-Hispanic voters in each party affiliation and the percentage of Hispanic voters in each party affiliation. The percentages are based on total non-Hispanic voters and total Hispanic voters, not the total number of registered voters. NPA means no party affiliation, REP represents the Republican Party of Florida, DEM represents the Democratic Party of Florida, and others includes the Libertarian Party of Florida, the Green Party of Florida, the Independent Party of Florida, the Constitution Party of Florida, the Ecology Party of Florida, the Reform Party of Florida, and the Party for Socialism and Liberation-Florida.

#### Age and Gender with Party Affiliation File

The Age and Gender with Party Affiliation file contains the same data as the REU data file. I used each voter's birthday to calculate their age. From their age, I was able to describe the age distribution of all registered voters in Nassau County and the age distribution of registered Hispanic voters in Nassau County. 

![Age Distribution of All Voters](https://user-images.githubusercontent.com/86391094/124340322-5a2c0d80-db82-11eb-9c83-ed82c73f1c14.png)

The figure above shows the age distribution of all registered voters in Nassau County by generation. Amongst all voters, the generation with most representation is GEN X, which is people ages 41-56. The generation with least representation is WWII, which is people ages 94-99.

![Age Distribution of Hispanic Voters](https://user-images.githubusercontent.com/86391094/124340327-67e19300-db82-11eb-880f-a8c623cdc00b.png)

The figure above shows the age distribution of Hispanic voters in Nassau County by generation. When comparing all voters to Hispanic voters, majority of Hispanic voters are millennials (ages 25-40) and majority of all voters are GEN X (41-56). Also, note that there is only one Hispanic voter in the WWII generation in Nassau County.

## Implementation

One goal is to identify trends amongst Hispanic voters that will help us predict their party affiliation and vote. In order to do this, known factors, such as age and location, that create trends amongst non-Hispanic voters must be researched and applied to Hispanic voters within Nassau County. Once trends have been found amongst Hispanic voters in Nassau County, the trends can be used to predict Hispanic voters' party affiliation and vote in a larger region of Florida, or even all of Florida.

To start, I looked into age being a trend amongst Hispanic voters like it is with non-Hispanic voters. To look into whether this was a trend, I used my Age and Gender Party Affiliation file. From this file, I was able to create a graph that showed the party affiliation distribution by generation. The figure below showing the distribution does not show a useful trend of generation having an impact on party affiliation because No Party Affiliation is favored among younger generations.

![Party Affiliation by Age of Hispanic Voters](https://user-images.githubusercontent.com/86391094/124340371-bb53e100-db82-11eb-85b1-ef52761af2ad.png)

Another goal is to predict Hispanic voters sub-groups because there are studies that suggest Hispanic voters vote differently based on their sub-group identity. To predict sub-group identities, I used an Excel file (NASSAU COUNTY-HISPANIC File), created Dr. Berezovski to combine all of our data sets. The file is able to predict a Hispanic voter's sub-group identity based on zip code and last name and on zip code, last name(s), first name, and middle name. When predicting a Hispanic voter's sub-group based on zip code, last name(s), first name, and middle name, there were 67 false negatives, which is 4.75 percent of all registered Hispanic voters in Nassau County. When predicting a Hispanic voter's sub-group based on zip code and last name only, 452 Hispanic voters were not identified as Hispanic, meaning 32.01 percent of all registered Hispanic voters were falsely identified. Looking at the percent of false negatives is one way to measure the accuracy of the prediction method.

The last goal is to look at how active Hispanic voters are and find trends amongst their activity that could explain why the Democratic Party of Florida is experiencing underperformance. To examine voter activity of Hispanic Voters in Nassau County, I used the original Voter History Zip file. The Voter History Zip file recorded every time a voter voted based on their ID number. To calculate how active each Hispanic voter was I used the "countif" function in excel to count the number of times each Hispanic voter had voted. From the data obtained, I was able to create two figures: one compares active and passive voters by generation and the other compares active and passive voters by party affiliation. 

![Voter Activity based on Generation](https://user-images.githubusercontent.com/86391094/124341532-01ad3e00-db8b-11eb-8a39-db1259d3c2cd.png)

The figure above compares active and passive voters based on generation. It makes sense that the percent of active voters increases with age due to the fact that older voters have had more opportunities to vote. 

The figure below compares active and passive voters based on party affiliation. Hispanics with Republican Party Affiliation are slightly more active than Hispanics associated with the Democratic Party, No Party Affiliation, or affiliation with another party. By slightly more active, I mean there is about three percent more Hispanics associated with the Republican Party that have voted at least one time. 

![Voter Activity based on Party Affiliation](https://user-images.githubusercontent.com/86391094/124341534-05d95b80-db8b-11eb-9300-6034a3c37442.png)

The chart below compares the number of Hispanics within each party affiliation and the total number of times Hispanics within each party affiliation have voted. 

| | DEM | NPA | REP | Other(s) |
| # of voters | 411 | 504 | 478 | 18 |
| # of times voted | 1146 | 767 | 2086 | 14 |

When examining voter activity of Hispanic voters in Nassau County, I found that Hispanic voters with Republican Party Affiliation were significantly more active than Hispanic voters with no party affiliation or Democratic Party affiliation. I also looked at age and voter activity to find that voters ages 67 to 75 (Boomers I generation) tended to be the most active.

![Active vs  Passive Voters based on Generation and Party Affiliation](https://user-images.githubusercontent.com/86391094/124341540-0eca2d00-db8b-11eb-9555-117b58acdfbc.png)



## Conclusion

I also looked at the Hispanic voters' activity in Nassau County. I found that Hispanic voters associated with the Republican Party of Florida voted more frequently than Hispanic voters associated with the Democaratic Party of Florida and Hispanic voters with no party affiliation. I am going to see if there is a pattern with age amongst voters based on party affiliation and voting frequency. I am also going to see if there is a trend amongst different subgroups based on party affiliation and voting frequency. I want to also look at other counties in Florida to see if the trend of Republican Hispanics being more active holds true. 

