# Kickstarter_Analysis
Perform analysis to determine best course of action for a Kickstarter project

#Kickstarter Analysis

## Project Overview

The project's purpose is to assist our client (Lousie) in determining her next move. She is interested in determining how her program fared with the other Kickstarter program similar to hers. The data analysis will review the campaigns according to launch date and funding goals. Providing the instructions to extract the data, transform the data into a "start point" for the project, and then load the data to a location that precludes potential data fratricide that destroys the original data set. The project has three deliverables. 1) Outcomes by date launched, 2) outcomes based on goals, and 3) project documentation.

## Analysis and Challenges 

Data collection and cleansing provided the foundation data source "starterBook.xlsx ."The data analysis began by renaming the file "kickstarter_Challeng.xlsx" to protect the data source from any deviation while conducting his research. Since the project required the UNIX data conversion of columns I and J into readable dates columns, S and T were added to the workbook. Next, to meet the client requirements, the command "YEAR()" was applied to column S. The categorization of years- is outlined in the initial job requirement. The command copied just the year from the date converted to human text. Once the Kickstarter data is set, the next step is to derive a pivot table easily. The extraction, transformation, and load present the pivot table and chart analysis. The analysis inserted column "P" (in hindsight should have added the column to the end of the worksheet) for the year each project was created. The pivot table was built in the worksheet "Theater Outcomes by Launch Date ."The challenge became apparent once the pivot table and pivot chart were created and did not match the predicted solution provided. The analysis framework was understood, but the lack of familiarity with Excel introduced the challenge of completing and presenting the correct answer to the client.

The second project requirement focused on analyzing the Goals to outcome correlation. This section required an additional worksheet to align project outcomes into twelve (12) bins ranging from less than $1000 as the lower bracket to the upper bracket of more than $50,000. The bins were then filled across the columns of project outcome "Successful, Failed, and Canceled ."The challenge, much like the first requirement, was not understanding the requirement but the user's familiarity with the commands. Getting the solution to match the book answer was challenging. The one lesson learned was the placement of the "<=" or ">=" to capture all of the data points. The "=" sign is critical. If not for using previous knowledge and a pivot table to build a solution check, the challenge would have derailed the outcome.

## Results

Direct outcomes of the project are illuminated in the attached graphics. The conclusion from the first requirement is that the success rates climb out of a valley in March and increase beginning in April, peak in May and slowly decline over the Summer months with a slight bump in October to the lowest launch over the NOV-JAN holiday season. Most failed projects happen in OCT, with the lowest in NOV. However, the rate is relatively consistent across the year, hovering below 60 and 35 failings. The actual cancellation of projects is more optimistic as there are less than ten cancellations every month, with the most in January. A definite trend of cancelations could be determined if the data set captures subsequent years.

The second requirement presents that the most successful projects had set goals in the $100 to $4999 bin, with 343 projects achieving their goals (33% success across the entire population, 73% within the bin). The less than $1000 (188, 18% of the total and 75% of total >= $1000) was also determined as a successful range. The least successful was the $45,000 to $49,000 bin with 100% failure. (1 initiated and one failed). Of the whole population, there are no cancellations. The second zone of success is in the band, from $35,000 to $44,999, with 67% within the bins. Any initiation of projects must be made aware of the equal opportunity to fail within that zone, too, with a 33% failure rate consistent with the $35K to $45K band.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106720990/177204721-d5788ed6-1411-4a93-b730-bbf8b6c30234.png)

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106720990/177204725-5ac2a07a-7d1c-4dc4-a385-fde5e9932834.png)

## Closing

The assessment of the data shows several opportunities to begin a Kickstarter project. The information clearly illustrates the temporal space to start work and the amount of capital that denotes success over failure. The careful analysis could provide a more detailed brief that could inform the client of a specific time and budget to begin the project. If it is possible to analyze over multiple years to solidify the trends seen above, that will increase the certainty of success.



  

