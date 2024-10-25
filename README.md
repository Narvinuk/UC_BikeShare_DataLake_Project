# UC_BikeShare_DataLake_Project
BikeShare Data Lake Project
<H3>Divvy is a bike sharing program in Chicago, Illinois USA that allows riders to purchase a pass at a kiosk or use a mobile application to unlock a bike at stations around the city and use the bike for a specified amount of time. The bikes can be returned to the same station or to another station. The City of Chicago makes the anonymized bike trip data publicly available for projects like this where we can analyze the data.

Since the data from Divvy are anonymous, we have generated fake rider and account profiles along with fake payment data to go along with the data from Divvy. The dataset looks like this:</H3>

<H3> Data Sources: </H3>
<H5> Payments.csv  riders.csv  stations.csv      trips.csv</H5>
<img src="https://github.com/Narvinuk/UC_BikeShare_DataLake_Project/blob/main/dm1.PNG">

 <H5> Data Model :</H5>
 <img src="https://github.com/Narvinuk/UC_BikeShare_DataLake_Project/blob/main/dm4.PNG">

<p> This data model design is in star schema model which consist a fact table (trip_fact) with related dimension table dim_rider,dim_paymet and dim_station with calculated measuure like trip
duration and member_age
<H3>DataStore</H3>
<img src="https://github.com/Narvinuk/UC_BikeShare_DataLake_Project/blob/main/dm2.PNG">

</p>
