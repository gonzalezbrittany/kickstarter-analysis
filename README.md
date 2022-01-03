Data Exploration of Campaign Strategies 

(l) Overview of Project
	Do different variables impact the outcome of campaigns? If so, what variables seem to impact campaign outcomes the most? After looking into numerous variables and collecting data, the campaign for the play Fever shows to have been successful in a short period of time. The purpose of this analysis is to dig deeper into how funding goals and launch dates impact the outcomes of theater campaigns with a focus on plays. 

(ll) Analysis	
Analysis of Outcomes Based on Launch date

For this analysis, we will be focusing on the parent category Theater. To find how launch date played an impact on outcomes, the campaign outcomes variable will show which campaigns were successful, failed or canceled. The launch date variable for each category is broken down by month to provide a clearer understanding of how campaign outcomes are impacted throughout the year. A count of successful, failed, and cancelled campaigns was collected and plotted on the line chart.


Analysis of Outcomes Based on Goals
Before the start of a campaign, various funding goals were set ranging from $1.00 to $100,000,000.00. For this analysis, dollar-amount ranges were created. The funding goal for each play campaign was grouped into these new ranges. A count of successful, failed, and canceled campaigns for each funding goal range was calculated. The count was then transformed into the percentage of successful, failed and canceled for the range based on the total number of play campaigns. The percentages of outcomes based on range are plotted on a line chart.

(lll) Challenges and Difficulties Encountered

	When first looking at the launched_at and deadline variables, it is not clear as to what these categories are meant to represent. The variable headers indicate this may be a date but the only way to confirm is by using a timestamp converter. After being made aware of resources available, a timestamp converter (https://www.epochconverter.com/)  was used to verify that these two variables are in fact dates. A formula was then implemented in the dataset to convert the timestamp to a format that can be used for analytical purposes. For this dataset, we convert these into a month/day/year format. 

(llll) Results

	Outcomes based on launched date Analysis
  
   After analyzing the outcomes based on launched date, what is clear is that there are more successful campaigns vs failed campaigns around May. As it gets closer to the end of the year, the number of successful campaigns decreases while the number of failed campaigns does not fluctuate greatly. This helps conclude that there is a relationship between a May launch date and successful theater campaigns. The number of canceled campaigns does not fluctuate throughout the year, therefore, we do not have evidence of a relationship between launch date and canceled campaigns.
   
	Outcomes based on goals analysis 
  
	After analyzing campaign outcomes based on goals, there is evidence that suggests funding goals that are below $1,500.00 have a better chance of being successful than funding goals that are above $1,500.00. There does seem to be some overlap between successful campaigns and failed campaigns between $35,000.00 to $55,000.00 funding goals. The percentage of having a successful campaign in this range is higher than failed. This may be due to a higher number of backers counts for those campaign or other variables that may have impacted the funding range for these unique campaigns. Overall, there is a higher percentage of having a successful campaign for funding goals that are under $1,500.00.
  
	Dataset Limitations
  
	There are some limitations to the dataset. A limitation is we do not have data on how much each backer contributed for each campaign. Did one campaign have a single backer that made a substantially large contribution compared to the others that caused the campaign to succeed instead of fail? Another limitation of the dataset is that the data only applies to campaigns that were run by Louise. Because of this, the results would not be applicable to a larger population.
  
	Other possible data visualization graphs
  
	A possible graph that may give more insight into the outcome of a campaign is the length of the campaign versus just the start date. Is there a correlation between the length of the campaign and the campaigns outcome? It would also be interesting to see how other non-theater campaigns played out when it came to funding goals and outcomes. Are there other campaign strategies that are just as successful as theater?
