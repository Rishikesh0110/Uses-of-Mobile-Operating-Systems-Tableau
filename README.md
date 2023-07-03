
# Mobile OS Usage
Worldwide mobile operating system market share usage data from 2008-2014. We are going to analyse percent of users by diffrent operating systems
## About the Data
Worldwide mobile operating system market share usage data from 2008-2014. Data: https://public.tableau.com/app/sample-data/mobile_os_usage.csv

## Tools used
- Used version Tableau 2022.4

## Questions 
1. Top mobile oprating systems which performing well?
2. Uses valume of operatoing systems has increases by year or not.
3. Total count of uses?

## Methods and steps To create this dshboard
1. We need to undestood the data first, here in data we have diffrent mobile operating systems which is used by peoples in timespan 2008-2014 ,and we have date and percent of uses for each os.
2. To check % of uses need to drop in rows and change format of date to dd/mm/yy . Than percent of user also drop in rows and convert it countineous data to descrete data ,than select measure as count. After all these processes drop percent of uses ias label and guide its calculated field to % of total.
3. To create a dognut chart for top ten mobile operating systems by users need to drag mobile operating systems and drop as color and convert chart as pie. Than drag percentage of total in rows and select measure as percentile & again onetime more drag percentage of total in rows as measure percentile than select as dual axis to merge both circles ,than dop the size of second circle and drag title and drop as lebel.
4. To create a bar diagrame for visualizaion of diffrent operating systems with their percent of uses need to drag mobile operating syatems and drop as column and percentage of uses in rows and change measure to sum and same in lebel to see markings ,it will give us a visualization to see clear insights.
5. To see the uses volume of every operating sustems as year wise we took help of line diagrame ,which will show the diffrent trends need to drang the modified date in formate dd/mm/yy and drop in columns than drag percentage of used and drop in rows and change measure to sum than drag mobile operating systems and drop in color and percentage of uses in lebel and measure as sum ,these all steps will provide us diffrent trend line to see insights.
6. To see total count of uses by operating syatems need to drag mobie operating systems  and drop as rows and sum of percentage of total as column ,it will give us a text table with each os nameand uses.

## Conclusion
So, we can conclude after viasualizing the dashboards that which OS is performing well so we can see IOS has highnumber of users followed by Android. And user volums increases year by year
