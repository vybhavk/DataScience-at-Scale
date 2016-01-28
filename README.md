# DataScience-at-Scale

I have used the San Francsico data set to do Data Visualization by using the tableau. Below are the output files which explains about the data and its graph

My intention is to visualize how the Number of records are there with respective to Time,Category,Location,on day of week.

<b>TIME VS NUMBER OF RECORDS<br></b>

This shows the Visualization between Time ,Number of records:
<br> [Time Vs Number of Records.pdf](https://github.com/vybhavk/DataScience-at-Scale/files/102715/Time.Vs.Number.of.Records.pdf)</br>
We can see that in evenging from 5- 6 pm the Crime rate is high while in early morning 4 am the Crime rate is low when compared to other part of the day.

<b>DAY VS NUMBER OF RECORDS</b></br>

Lets check the Crime rate as per the day of week with respective to each district.
<br>[Day Vs No of records.pdf](https://github.com/vybhavk/DataScience-at-Scale/files/102722/Day.Vs.No.of.records.pdf)</br>
We can see clearly in the visualization that Sunday has highest crime incidents in almost all the district. Especially we can see that Southern district has registered the highest crime records.
From this visualization,we can clearly identify the total number of records as per each district with respective to day of week.

<b>WEEKDAY VS WEEKEND</b> <br>
On going in depth we can see how the crime rate on weekends and weekends.
<br>[Weekend vs Weekday.pdf](https://github.com/vybhavk/DataScience-at-Scale/files/102716/Weekend.vs.Weekday.pdf)<br>
We can see that weekday has more crime rate than on weekend.


<b>CATAGORY vs NUMBER OF RECORDS</b>
In order give priority of resolution on which catagory should focus more, lets visualize the day as per catagory
<br>[Category Vs NumberOfRecords.pdf](https://github.com/vybhavk/DataScience-at-Scale/files/102717/Category.Vs.NumberOfRecords.pdf)<br>
We can see that Theft/Larceny has 1988 incidents on overall.But there is one confusion that how they are with respective to each  district??

<b>CATAGORY VS LOCATION</b> 
Lets visualize the Crime records with respective each district, each catagory 
<br>[Category Vs location vs NoOfRecords.pdf](https://github.com/vybhavk/DataScience-at-Scale/files/102719/Category.Vs.location.vs.NoOfRecords.pdf)<br>
This visualization is bit colorful than the past one and Theft/Larceny has recorded more mainly in southern district.In the same way the Bribery,Burglary,Extortion,Loitering has less incidents
So we can say that Southern district has more crime incidents especailly theft.

<b>TIME VS RESOLUTION</b><br>
Lets check the rate resolution of the crime reports a bit particularly on catagories ARREST,CITED,NONE with respective to the time the incident happened.
<br>[Time Vs Resolution.pdf](https://github.com/vybhavk/DataScience-at-Scale/files/102714/Time.Vs.Resolution.pdf) <br>

<b>Steps followed in Tableau for Data visualization.</br>
1)Drag what ever the rows we need to represent in graph to the Row field.
2)Drag the fields to the Column field.
3) we can create filter by using some columns.

Ex:
1) Drag "Number of Records" from measures to rows.
2) Drag "Hour(time)" from dimensions to columns. By default, this will be aggregated to Hour.
3) we can create filter by using some columns like catagory or district column.
</br><img src=".jpg" alt="Mountain View" style="width:304px;height:228px;">

Optional: Right click anywhere in the visualization and go to "Trend Lines" and click "Show Trend Lines."To view the statistical model, right click again, go to "Trend Lines" and click "Describe Trend Model."
