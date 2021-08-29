**PROJECT OVERVIEW**

This analysis was prepared to identify trends and relationships in the data from several crowdfunding campaigns for theatre-related projects and  specifically, plays. The project outcomes were examined against the campaign launch dates, and individual funding goals. The data is presented visually, with the ultimate goal of drawing actionable insights for future campaigns.

#**ANALYSIS AND CHALLENGES**

##* Analysis*

The data used was drawn from a larger dataset of crowdfunding projects, which can be found [here](https://github.com/farwaali08/kickstarter-analysis/blob/662918993b2c2f31c305ea1fd6d03418b9aa185f/KICKSTARTER%20ANALYSIS.xlsx). As the focus of this analysis is theatre-related projects and plays, the raw data was organized to include the desired parameters, such as the parent and sub-categories of the campaigns.

First, the 'Theatre' related projects were analyzed based on the campaign launch date. This includes data for plays, as well as musicals and spaces. This relationship is illustrated in the line chart below.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/89050277/131239437-ef1cc580-9446-410e-9243-1a464b80fb39.png)
This information can be used to address questions such as the overall response to theatre-based projects, whether seasonal trends exist, and their influence, if any, on the project outcome.

Kickstarters pertaining to plays specifically, were examined next, however this analysis compared the project outcomes to the individual funding goals. The funding goals were divided into 12 dollar-ranges, and cross-referenced with the project outcomes for each goal category. The success rates were calculated, and plotted per the chart below:
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89050277/131239440-3b906741-3b4b-408b-a47b-30abad319ef2.png)
This is intended to draw insights into what funding goals are generally more achievable.

##*Challenges*

The analysis for Outcomes Based on Goals is heavily reliant on functions and formatting, which can be subject to manual or user errors. Some possible challenges could include incorrect use of the COUNTIFS formula, which essentially would prevent the analysis from moving forward. Another example is in calculating the percentages for the success rate. This, again, can be subject to manual errors, as the formulae may not be copied or carried over correctly. Incorrect calculations would result in an incorrect graph, which would certainly be challenging to explain.

#**RESULTS**

##*Conclusions, Limitations, and Suggestions*

###“Theatre Outcomes by Launch Date”

The data suggests that overall, campaigns for theatre-based projects are generally more successful than not. The “Theatre Outcomes by Launch Date” analysis indicates that 61% of the projects were successful, however, this includes all 3 categories (plays, musicals, and spaces,). To gain better insight on how plays fare, the data should be filtered to include the “plays” sub-category.

Interestingly, both the successful and failed campaigns on “Theatre Outcomes by Launch Date” analysis seems to follow similar seasonal trends, with peaks (some relative) in February, May, and October. The trend lines follow a very similar shape, with the biggest difference being the magnitude. Approximately 50% of all campaigns were launched between April and August, and these are also the months with the highest number of successful campaigns. It’s unclear whether the high number is simply because there are more campaigns overall. This analysis only considers the number of campaigns, which is limiting in the information that it provides. A more effective way to present this data would be to calculate the success rate of all campaigns (as a ratio or percentage,) as this provides better context. For example, when examining the successful campaigns in January and February, it appears (at least visually,) that there is a large difference between the two, however there is a fairly similar success rate, at 58% and 63%, respectively. A success rate would better determine if any seasonal trends exist, and if they should be explored further.

###“Outcomes Based on Goals”

This analysis provides insight on how funding goals impact the outcome of a campaign, and the data is expressed as a percentage. The failed and successful campaign rates seem to have an inverse relationship. Smaller campaigns have a higher success rate up to the $19,999 threshold, where the success/failure ratio is the same. Anything higher than this range is generally unsuccessful, save for the $35,000 to $39,999 category. Further analysis should be done to determine whether this is an outlier. It may also be worthwhile to decrease the number of dollar-ranges after the $19,999 range. In total, from the $20,000 to greater than $50,000 ranges, there are 62 projects in total, with an overall success rate of 34%. This suggests that the successful campaigns in the $35,000 to $39,999 range may not be anomalies after all.

The number of projects is also an important consideration here, and should be added to the analysis. A pie chart illustrating the number of successful campaigns would also help provide context to the analysis.

Ultimately, further analysis is required before any action can be taken.
