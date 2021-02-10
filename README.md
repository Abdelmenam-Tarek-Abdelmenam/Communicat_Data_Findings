# Communicat_Data_Findings
udacity nanodegree project on data visulization 
## i used fordgobike-tripdata data you can easiky downlod it from here(https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


**you can find all concolusion in Ford_Bike_Analysis_Report.pdf** please read it first 

Welcome in Communicate Data Findings project
By Abdelmenam Tarek Abdelmenam
data set overview
FordGoBike System Data Investigation
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area

gatheing :-
- I downlod the data from this [link](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)
- i didn't downlod it programatily becuse it has abig size 28 MB and it will take time.
- I uploded the csv file to the nootbook here 

cleaning :- 
i did some cleaning as drop some column greate some and change data types .
Delete unneeded column 'end_time' , 'start_station_id' ,'end_station_id' ,'bike_share_for_all_trip’ I will not use them 
Convert data type 
invalid birth of year
There is some birth of year smaller than 1934 which mean the customer is older than 85
make new columns  


insights :
-I LOOK at age , Speed , duration and distance distribution and get some results
Comment :- 
-> age has right skewed distribution with mean of 34 and minimum age of 18 and maximum age of 81 
the most common customer age is 31 
with the increase of age the number of customer decrease and that makes sense because the health
Also the small age has a little number of trips   
-> duration has a common values from 0 to 25 min after that it has a right skewed distribution , and it has some outliers 
-> Speed has a normal distribution with a mean 10.8 km/hr and a max speed 36 km/hrs 
distance has a mean of 1.7 km ,the maximum is 69 km , and it has some outliers 

-Study number of trips in different times as Different hour of the day…etc
-> There is some days of the month that  that have many number if trips as 28 , 30 and other days with small number of trips as 9
-> There is some hours that have many number if trips which are 8 ,17 and I think this make sense because it’s time for work
-> Thursday has the high number of trip in the week and Saturday has the least number of trips .
In my opinion this related to the weekend  

-User classification counting “gender and type”
->type :-Subscriber type is the most common type more than the customer type 
-> Gender :- Men love riding bike more than women so that’s normal that the number of men’s trips mor than number of women 

-Most common start and end station names

-Relation between customer type and trip duration and his speed
->Customer travel in a small average compare to the subscriber and the normal also it has a wide range of speed rather than the customer  

-Relation between customer gender and trip duration and his speed 
->Its clear that male has a bigger speed and longer trips than the female 

-find the relation between speed , duration and age
->The duration decrease also with the increase of age as older people can’t ride for long times 
->The speed decrease with the increase of age and that a normal observation because it is a negative relation between the age and riding bike speed 

-relation between gender and user type
->- there is a relation between gender and type as all gender has many subscriber more than customer 

-Relation between day and hour 
->there is some active hour for every day 

-Common start to end combination with more than 200 record
->The most common combination is from 19th Street BART Station to  Grand Ave at Perkins St  

-relation between distance and other parameter 
->In general the trip distance decrease with the increase of age but it’s clear that subscribers has big distance than the customer and also male has a bigger distance than females  
 
 
resources :-
i get some help from stackoverflow and kaggle comments
i searched in seaborn , matplotlib documentaion for spme function parameter 
