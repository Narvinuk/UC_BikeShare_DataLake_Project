# UC_BikeShare_DataLake_Project

<div style="display: grid; place-content: center;">
BikeShare Data Lake Project
</div>
<P> <B>Divvy is a bike sharing program in Chicago, Illinois USA that allows riders to purchase a pass at a kiosk or use a mobile application to unlock a bike at stations around the city and use the bike for a specified amount of time. The bikes can be returned to the same station or to another station. The City of Chicago makes the anonymized bike trip data publicly available for projects like this where we can analyze the data.

Since the data from Divvy are anonymous, we have generated fake rider and account profiles along with fake payment data to go along with the data from Divvy. The dataset looks like this:</B></P>

<H3> Data Sources: </H3>
<H5> Payments.csv  riders.csv  stations.csv      trips.csv</H5>
<img src="https://github.com/Narvinuk/UC_BikeShare_DataLake_Project/blob/main/Src_Files_Sample_Data.PNG">

 <H5> Data Model :</H5>
 <img src="https://github.com/Narvinuk/UC_BikeShare_DataLake_Project/blob/main/Bike_Share_DW_Star_Schema.PNG">

<p> This data model design is in star schema model which consist two fact tables trip_fact   with calculated trip duration and member_age  along with dimension keys for rider_id,station_id and ridetype_id,date_id
and payment_fact with amount measure  with rider_id and date_id dimension keys
<H3>DataStore</H3>
<img src="https://github.com/Narvinuk/UC_BikeShare_DataLake_Project/blob/main/Tables.PNG">
</p>
Sample Dim and Fact data :
<img src="https://github.com/Narvinuk/UC_BikeShare_DataLake_Project/blob/main/Start_Schema_Tables_Sample_Data.PNG">

