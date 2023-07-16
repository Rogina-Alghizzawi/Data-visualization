1.	Introduction: 
i.	introduction
Covid-19 started in December 2019 in Wuhan China, and since then the number of cases started to increase as well as the number of deaths. As a result, the world started a global pandemic and no one was allowed to leave their houses until the scientists find out a cure for this virus. A year after the virus started scientists were able to make a vaccine that helps people decrease their chances of having the virus and if they were already diagnosed with covid-19 their chances of getting diagnosed again will also decrease and it will make the diagnosed people have less hurting symptoms. So people started getting their first and their second shot in order to go back to their jobs, further more people with moderately to severely compromised immune systems were encouraged to take an additional dose to improve their immunocompromised response to their initial vaccine series. Also some people whose protection against the virus has decreased over time took a second booster after the completed their vaccination series. 
ii.	Project scope and targeted audience:
This project is about the vaccination process in the USA since the beginning of Covid-19 until June 2022. The project was made to study the changes in the vaccination process starting from December 2021 when people started taking their first shot of vaccine and the changes in the number of vaccines given to different age groups (5 years old- 12 years old, 12 years old- 18 years old, 18 years old- 65 years old, older than 65 years old), the distribution of the vaccines in each state in the US among different types of vaccines(Moderna, Janssen, Pfizer, Unk_Manuf) for the different ae groups mentioned above.
The second part of the project focuses on the number of vaccines administrated by the state itself not including the vaccines administrated by other health facilities, taking into consideration the type of the vaccine and the age group that will take this vaccine. Since there were 2 elementary shots for the vaccines the number of people who completed their 2 shots was stated in the dataset as (series complete yes) having in mind the type of vaccine and the age group. Although people were obligated to take the 2 shots and the majority of people had good immune system some of them especially the people in these age groups (12 years old- 18 years old, 18 years old- 50 years old, 50 years old- 65 years old and older than 65 years old) who have moderately to severely compromised immune systems, were asked to take an additional dose which is intended to improve immunocompromised people’s response to their initial vaccine series.at the end people who have completed their vaccine series, and protection against the virus has decreased over time were asked to take a second booster. All of these information was listed in the dataset that we are worked on. 
The aim of the project was to know If the elections had an impact on the number of vaccinations being distributed in each state. We were aiming to find out if the states that voted for Jo Biden tended to have more vaccinations than the states that voted for Donald Trump. Because the presidential elections were at the begging of the global pandemic we chose this topic to be the plot in the story that we will be telling and what caught our attention was the fact that some citizens posted some tweets about this topic and they were wondering about that same issue that we discussed in our project.
The targeted audience will be our professor and our colleagues in this course (Data Exploration & Visualization) and we are willing for their full attention in order to convince them with the story we will be telling.
 
2.	Problem definition:
i.	Problem definition: 
As covid-19 started spreading and the global pandemic started taking place in all countries in the world the US was one of the countries that had a pandemic until scientists find a cure for this virus. After the vaccine was found people started taking their first shots then the second shot and they became fully vaccinated. During the process of providing the states with the enough amount of vaccinations for all citizens the president elections were about to start and all the predicted coming residents started making campaigns to encourage people to vote for them. After a while the results came out and Biden was selected to be the next president of the USA. Everything was going good until some people started noticing that the states that voted for Biden are having better ratio of vaccines to the total number of citizens in each state. People started posting on tweeter that it is unfair to give vaccinations to chosen states and the vaccinations should not be related to politics and that every state should be given the same ratio of vaccinations to the total number of people in every state. (https://twitter.com/HarpWizard/status/1518228413663916033?s=20&t=7aADdAt33j04-wMISWdmbg)
(https://twitter.com/sam_d_1995/status/1412463419601604610?s=20)

Also taking into consideration the audience we wanted to involve in our project we made a survey that involves the same data that was collected in the dataset to see if our small population will give us the same result as the dataset will show.
https://docs.google.com/forms/d/e/1FAIpQLSegv0xN8FvpxcMDPqn47QpkbysbLw1x3Fykn09lfIovqclrbw/viewform?usp=sf_link

ii.	EDA objectives:
While going through the Exploratory Data Analysis steps we were able to find out the outliers in the dataset, we were able to understand how the data is distributed among the columns and how that helped us figure out how to visualize the data and come out with useful insights to understand the problem we defined above.

iii.	Deliverables
The result we came out from our exploration of the data is that the elections did really effected the distribution of the vaccinations in the US states and that the states which voted for Biden had noticeably larger amount of vaccinations than the ones voted for Trump.


	Column name	Description	Type
1.		Date	Date data are reported on CDC COVID Data Tracker	Date time 
2.		MMWR_Week	The week of the epidemiologic year as defined by the Morbidity and Mortality Weekly Report	Integer 
3.		Location	Jurisdiction (State)
	Object 
4.		Distributed	Total number of delivered doses	Object 
5.		Distributed_Janssen	Total number of J&J/Janssen doses delivered	Object
6.		Distributed_Moderna	Total number of Moderna doses delivered	Object
7.		Distributed_Pfizer	Total number of Pfizer-BioNTech doses delivered	Object
8.		Distributed_Unk_Manuf	Total number of doses delivered from other manufacturers	Object 
9.		Dist_Per_100K	Delivered doses per 100,000 census population
	Object
10.		Distributed_Per_100k_5Plus	Total number of doses delivered per 100,000 people ages 5+
	Object
11.		Distributed_Per_100k_12Plus	Total number of doses delivered per 100,000 people ages 12+	Object
12.		Distributed_Per_100k_18Plus	Total number of doses delivered per 100,000 people ages 18+	Object
13.		Distributed_Per_100k_65Plus	Total number of doses delivered per 100,000 people ages 65+	Object
14.		Administered	Total number of administered doses based on the jurisdiction (state) where administered	Object
15.		Administered_5Plus	Total number of doses administered to people ages 5+ based on the jurisdiction where administered	Object
16.		Administered_12Plus	Total number of doses administered to people ages 12+ based on the jurisdiction where administered	Object
17.		Administered_18Plus	Total number of doses administered to people ages 18+ based on the jurisdiction where administered	Object
18.		Administered_65Plus	Total number of doses administered to people ages 65+ based on the jurisdiction where administered	Object
19.		Administered_Janssen	Total number of J&J/Janssen doses administered	Object
20.		Administered_Moderna	Total number of Moderna doses administered
	Object
21.		Administered_Pfizer	Total number of Pfizer-BioNTech doses administered
	Object
22.		Administered_Unk_Manuf	Total number of administered doses from other manufacturers	Object
23.		Admin_Per_100K	Total number of doses administered per 100,000 census population based on the jurisdiction where recipient lives	Object
24.		Admin_Per_100k_5Plus	Total number of doses administered per 100,000 people ages 5+	Object
25.		Admin_Per_100k_12Plus	Total number of doses administered per 100,000 people ages 12+
	Object
26.		Admin_Per_100k_18Plus	Total number of doses administered per 100,000 people ages 18+	Object
27.		Admin_Per_100k_65Plus	Total number of doses administered per 100,000 people ages 65+	Object 
28.		Recip_Administered	Total number of doses administered based on the jurisdiction where recipient lives	Object
29.		Administered_Dose1_Recip	Total number of people with at least one dose based on the jurisdiction where recipient lives	float64
30.		Administered_Dose1_Pop_Pct	Percent of population with at least one dose based on the jurisdiction where recipient lives	Object
31.		Administered_Dose1_Recip_5Plus	Total number of people ages 5+ with at least one dose based on the jurisdiction where recipient lives	float64
32.		Administered_Dose1_Recip_5PlusPop_Pct	Percent of population ages 5+ with at least one dose based on the jurisdiction where recipient lives	Object
33.		Administered_Dose1_Recip_12Plus	Total number of people ages 12+ with at least one dose based on the jurisdiction where recipient lives	float64
34.		Administered_Dose1_Recip_12PlusPop_Pct	Percent of population ages 12+ with at least one dose based on the jurisdiction where recipient lives	Object
35.		Administered_Dose1_Recip_18Plus	Total number of people ages 18+ with at least one dose based on the jurisdiction where recipient lives	float64
36.		Administered_Dose1_Recip_18PlusPop_Pct	Percent of population ages 18+ with at least one dose based on the jurisdiction where recipient lives
	Object
37.		Administered_Dose1_Recip_65Plus	Total number of people ages 65+ with at least one dose based on the jurisdiction where recipient lives	float64
38.		Administered_Dose1_Recip_65PlusPop_Pct	Percent of population ages 65+ with at least one dose based on the jurisdiction where recipient lives	Object
39.		Series_Complete_Yes	Total number of people who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient lives	float64
40.		Series_Complete_Pop_Pct	Percent of people who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient lives	Object
41.		Series_Complete_5Plus	Total number of people ages 5+ who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient 
lives	Object
42.		Series_Complete_5PlusPop_Pct	Percent of people ages 5+ who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient lives	float64
43.		Series_Complete_12Plus	Total number of people ages 12+ who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient lives	Object
44.		Series_Complete_12PlusPop_Pct	Percent of people ages 12+ who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient lives	float64
45.		Series_Complete_18Plus	Total number of people ages 18+ who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient lives	Object
46.		Series_Complete_18PlusPop_Pct	Percent of people 18+ who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient lives	float64
47.		Series_Complete_65Plus	Total number of people ages 65+ who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient lives	Object
48.		Series_Complete_65PlusPop_Pct	Percent of people ages 65+ who are fully vaccinated (have second dose of a two-dose vaccine or one dose of a single-dose vaccine) based on the jurisdiction where recipient lives	float64
49.		Series_Complete_Janssen	Total number of people who are fully vaccinated (completed primary series) with the J&J/Janssen vaccine based on the jurisdiction where recipient lives	Object
50.		Series_Complete_Moderna	Total number of people who are fully vaccinated (completed primary series) with the Moderna vaccine based on the jurisdiction where recipient lives	Object
51.		Series_Complete_Pfizer	Total number of people who are fully vaccinated (completed primary series) with the Pfizer vaccine based on the jurisdiction where recipient lives	Object
52.		Series_Complete_Unk_Manuf	Total number of people who are fully vaccinated (completed primary series) with two doses from an unknown two-dose vaccine manufacturer based on the jurisdiction where recipient lives	Object
53.		Series_Complete_Janssen_5Plus	Total number of people ages 5+ who are fully vaccinated (completed primary series) with the J&J/Janssen vaccine based on the jurisdiction where recipient lives	Object
54.		Series_Complete_Moderna_5Plus	Total number of people ages 5+ who are fully vaccinated (completed primary series) with the Moderna vaccine based on the jurisdiction where recipient lives	Object
55.		Series_Complete_Pfizer_5Plus	Total number of people ages 5+ who are fully vaccinated (completed primary series) with the Pfizer vaccine based on the jurisdiction where recipient lives	Object
56.		Series_Complete_Unk_Manuf_5Plus	Total number of people ages 5+ who are fully vaccinated (completed primary series) with two doses from an uknown two-dose vaccine manufacturer based on the jurisdiction where recipient lives	Object
57.		Series_Complete_Janssen_12Plus	Total number of people ages 12+ who are fully vaccinated (completed primary series) with the J&J/Janssen vaccine based on the jurisdiction where recipient lives	Object
58.		Series_Complete_Moderna_12Plus	Total number of people ages 12+ who are fully vaccinated (completed primary series) with the Moderna vaccine based on the jurisdiction where recipient lives	Object
59.		Series_Complete_Pfizer_12Plus	Total number of people ages 12+ who are fully vaccinated (completed primary series) with the Pfizer vaccine based on the jurisdiction where recipient lives	Object
60.		Series_Complete_Unk_Manuf_12Plus	Total number of people ages 12+ who are fully vaccinated (completed primary series) with two doses from an unknown two-dose vaccine manufacturer based on the jurisdiction where recipient lives	Object
61.		Series_Complete_Janssen_18Plus	Total number of people ages 18+ who are fully vaccinated (completed primary series) with the J&J/Janssen vaccine based on the jurisdiction where recipient lives	Object
62.		Series_Complete_Moderna_18Plus	Total number of people ages 18+ who are fully vaccinated (completed primary series) with the Moderna vaccine based on the jurisdiction where recipient lives	Object
63.		Series_Complete_Pfizer_18Plus	Total number of people ages 18+ who are fully vaccinated (completed primary series) with the Pfizer vaccine based on the jurisdiction where recipient lives	Object
64.		Series_Complete_Unk_Manuf_18Plus	Total number of people ages 18+ who are fully vaccinated (completed primary series) with two doses from an unknown two-dose vaccine manufacturer based on the jurisdiction where recipient lives	Object
65.		Series_Complete_Janssen_65Plus	Total number of people ages 65+ who are fully vaccinated (completed primary series) with the J&J/Janssen vaccine based on the jurisdiction where recipient lives	Object
66.		Series_Complete_Moderna_65Plus	Total number of people ages 65+ who are fully vaccinated (completed primary series) with the Moderna vaccine based on the jurisdiction where recipient lives	Object
67.		Series_Complete_Pfizer_65Plus	Total number of people ages 65+ who are fully vaccinated (completed primary series) with the Pfizer vaccine based on the jurisdiction where recipient lives	Object
68.		Series_Complete_Unk_Manuf_65Plus	Total number of people ages 65+ who are fully vaccinated (completed primary series) with two doses from an unknown two-dose vaccine manufacturer based on the jurisdiction where recipient lives	Object
69.		Additional_Doses	Total number of people who are fully vaccinated and have received a first booster (or additional) dose based on the jurisdiction where recipient lives	Object
70.		Additional_Doses_Vax_Pct	Percent of people who are fully vaccinated and have received a first booster (or additional) dose based on the jurisdiction where recipient lives	float64
71.		Additional_Doses_12Plus	Total number of people ages 12+ who are fully vaccinated and have received a first booster (or additional) dose based on the jurisdiction where recipient lives	Object
72.		Additional_Doses_12Plus_Vax_Pct	Percent of people ages 12+ who are fully vaccinated and have received a first booster (or additional) dose based on the jurisdiction where recipient lives	float64
73.		Additional_Doses_18Plus	Total number of people ages 18+ who are fully vaccinated and have received a first booster (or additional) dose based on the jurisdiction where recipient lives	Object
74.		Additional_Doses_18Plus_Vax_Pct	Percent of people ages 18+ who are fully vaccinated and have received a first booster (or additional) dose based on the jurisdiction where recipient lives	float64
75.		Additional_Doses_50Plus	Total number of people ages 50+ who are fully vaccinated and have received a first booster (or additional) dose based on the jurisdiction where recipient lives	Object
76.		Additional_Doses_50Plus_Vax_Pct	Percent of people ages 50+ who are fully vaccinated and have received a first booster (or additiuonal) dose based on the jurisdiction where recipient lives	float64
77.		Additional_Doses_65Plus    	Total number of people ages 65+ who are fully vaccinated and have received a first booster (or additional) dose based on the jurisdiction where recipient lives	Object
78.		Additional_Doses_65Plus_Vax_Pct	Percent of people ages 65+ who are fully vaccinated and have received a first booster (or additional) dose based on the jurisdiction where recipient lives	float64
79.		Colmns name 	Description	type
80.		Additional_Doses_Moderna	Total number of fully vaccinated people who have received a first Moderna booster (or additional) dose	Object
81.		Additional_Doses_Pfizer	Total number of fully vaccinated people who have received a first Pfizer booster (or additional) dose	Object
82.		Additional_Doses_Janssen	Total number of fully vaccinated people who have received a first J&J/Janssen booster (or additional) dose	Object
83.		Additional_Doses_Unk_Manuf	Total number of fully vaccinated people who have received a first booster (or additional) dose from another manufacturer	Object
84.		Second_Booster	Total number of people who have received a second booster dose in the US	Object
85.		Second_Booster_50Plus	Total number of people ages 50+ who have received a second booster dose based on the jurisdiction where recipient lives	Object
86.		Second_Booster_50Plus_Vax_Pct	Percentage of people ages 50+ with a first booster dose who received a second booster dose based on the jurisdiction where recipient lives	float64
87.		Second_Booster_65Plus	Total number of people ages 65+ who have received a second booster dose based on the jurisdiction where recipient lives	Object
88.		Second_Booster_65Plus_Vax_Pct	Percentage of people ages 65+ with a first booster dose who received a second booster dose based on the jurisdiction where recipient lives	float64
89.		Second_Booster_Janssen	Total number of people who have received a second booster dose manufactured by J&J/Janssen	object
90.		Second_Booster_Moderna	Total number of people who have received a second booster dose manufactured by Moderna	Object
91.		Second_Booster_Pfizer	Total number of people who have received a second booster dose manufactured by Pfizer-BioNTech	Object
92.		Second_Booster_Unk_Manuf	Total number of people who have received a second booster dose from another manufacturer	Object
