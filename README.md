# bellabeat_wellness

## What are some trends in smart device usage that could apply to Bellabeat customers to help influence Bellabeat's marketing strategy.


#### **1. Business task** 
Determine trends in smart device usage that could apply to Bellabeat customers to help influence Bellabeat's marketing strategy.

● **What is the problem you are trying to solve?** 
Analyze smart device data to determine trends to gain insight into how consumers use non-Bellabeat smart devices.

● **How can your insights drive business decisions?** 
These insights can be used to make data-driven business strategies for growth opportunities.


#### **2. Description of all data sources used** 
The data being used has been made available by Möbius under CC0: Public Domain data license agreement: <https://creativecommons.org/publicdomain/zero/1.0/>. The time frame being analyzed is April 12, 2016 through May 12, 2016.

**● Where is the data stored and located?** 
Data is broken up into 18 CSV files. All CSV files are on local PC and broken into daily, hourly and minute categories. Data is located on local Desktop that was obtained as .csv files from <https://www.kaggle.com/datasets/arashnic/fitbit>.
The following datasets will be used for analysis:
● sleepDay_merged
● weightLogInfo_merged
● dailyActivity_merged

**● How is the data organized?** 
The data is organized into long format.

**● Are there issues with bias or credibility in this data?** 
The original data source can be confirmed, but it is missing some values which may be key to answering the question being asked by business. The data is not current and may no longer represent current trends.

**Reliability :** Dataset is reported to be collected from 30 individuals whose age and gender is not revealed. 30 individuals is also not a large enough data sample to rule out bias or provide decent fitness population representation. There are also values missing information such as calories or steps.
**Originality :** Data was collected using third party platform Amazon Mechanical Turk.
**Comprehensive :** The data contains daily, hourly and minute data on categories such as steps, calories, intensities and sleep.
**Current :** Data is 7 years old and may no longer represent current patterns and trends.
**Cited :** Original source is from directly from owner that collected data.

**● How are you addressing licensing, privacy, security, and accessibility?** 
The data being used has been made available by Möbius under CC0: Public Domain data license agreement: <https://creativecommons.org/publicdomain/zero/1.0/> 

**● How did you verify the data's integrity?** 
Due to the small dataset, I used Excel to review data provided.

**● How does it help you answer your question?** 
It helps clarify the amount of data and also what data values may be missing.

**● Are there any problems with the data?** 
Data values are missing from steps, calories, distance, etc. that will further limit it's accuracy.


#### **3. Documentation of any cleaning or manipulation of data** 
**● What tools are you choosing and why?** 
Due to the small dataset I am using Excel 2016 to clean and manipulate data. From the 18 CSV files provided there were 3 datasets that provided unique daily information:
● dailyActivity_merged contains 33 unique ID's 
● weightLogInfo_merged contains 8 unique ID's 
● sleepDay_merged contains 24 unique ID's 

After reviewing weightLogInfo, due to it only having 8 unique ID's I have chosen to omit it from analysis as there is not enough data to capture unbiased trends that may be occurring.

**● Have you ensured your data’s integrity?** 
Data integrity was reviewed for accuracy, completeness, consistency, and validity. Issues with data values have been documented.

**● What steps have you taken to ensure that your data is clean?** 
**1.** In Excel 2016 I used Find and Replace to replace all blank numeric values with NA.
**2.** Created column called Weekday and used =WEEKDAY() to obtain the numeric equivalent of Sunday through Saturday. I then copied and pasted the column as values only to remove formula and used find and replace to change numeric values to the the individual days of the week (1=Sunday, 2=Monday, 3=Tuesday, 4=Wednesday, 5=Thursday, 6=Friday, 7=Saturday).
**3.** I confirmed all values with no data had 0 indicated and were not left blank.
**4.** The CSV file Data sleepDay_merged was copied and pasted into dailyActivity_merged CSV file. All blank numerica values were replaced with 0.
**5.** File was saved as 041216_051216_wellness_clean.xls

**● How can you verify that your data is clean and ready to analyze?** 
Due to the small dataset, verification is able to be visually done by reviewing it in Excel 2016. Additionally using filter options in Excel also will confirm no missing or unusual data values.

**● Have you documented your cleaning process so you can review and share those results?** 
The cleaning and analysis process has been documented in R Markdown.


#### **4. Summary of analysis** 
**● How should you organize your data to perform analysis on it?** 
Data is combined and organized into columns.

**● Has your data been properly formatted?** 
Data has been properly formatted to match datatype being used.

**● What surprises did you discover in the data?** 
More data values than expected were missing and that all 33 participants did not provided consistent data.

**● What trends or relationships did you find in the data?** 
Over the 30 day period analyzed the trend that was found is that the bulk of walking was done on the weekdays and the weekends appears to have had less activity. Another trend found that late afternoon (6-7 PM) was the most popular time to engage in activities.

**● How will these insights help answer your business questions?**
The business questions being asked are how could the trends found apply to Bellbeat customers and how to influence Bellabeat marketing strategy. While the insights found can lift the veil on how customers are using competitor products, an analysis of Bellabeat customers will still need to be done, to compare how non-Bellabeat customer and Bellabeat customers use their wellness products. From a marketing perspective the Bellabeat app, Leaf and Time products can be used to track activity, sleep and stress with the Bellabeat app providing some extra tracking services such as menstrual cycle and mindfulness habits.


#### **5. Supporting visualizations and key findings** 
**● Were you able to answer the business questions** 
I was able to identify trends that can be used towards marketing strategies.

**● What story does your data tell?** 
The 30 day data story shows that customers are doing the highest proportion of activities during the work week and saving the weekends to rest. The data also shows that the later afternoon was the most active time for activities and that April was a more active month than May.

**● How do your findings relate to your original question?** 
The findings identify some trends with smart device usage that can be used for Bellabeat's marketing strategy.

**● Who is your audience? What is the best way to communicate with them?** 
The main audience is the marketing team and executive team.

**● Can data visualization help you share your findings?** 
Data Visualization is able to paint a picture that clearly identifies any trends or relationships that may be happening.\

**● Is your presentation accessible to your audience?** 
Presentation is in a Tableau dashboard and story format, in addition to HTML.


The most popular time for smart device users to get active were on the late afternoon workdays between 6:00 PM and 7:00 PM followed by the lunch time period of 12 PM through 2 PM. Data also reinforced that the more active a user was the more calories they burned which also resulted in their sleep hours to become consistent and steady.


#### **6. Top three recommendations** 
Recommendations for marketing strategy:
1. Activities and challenges that Bellabeat and new customers can complete using the Bellabeat app, Leaf or Time during peak active times.
2. Market Bellabeat app, Leaf or Time towards working individuals who would be interested in also tracking their stress levels.
3. Use of alerts and alarms to get users moving during sedentary periods.
4. Reminders for users to go to sleep to maintain appropriate daily sleep needs.
\
