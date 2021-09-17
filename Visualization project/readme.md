# (Ford Bikes)
## by (Sayed Abdul-Monem)


## Dataset

>> the Dataset is Ford Bikes and it contains information of trips for a time 
 1.duration_sec             | 174952 non-null  float64       
 2.start_time               | 174952 non-null  datetime64    
 3.end_time                 | 174952 non-null  datetime64    
 4.start_station_id         | 174952 non-null  object         
 5.start_station_name       | 174952 non-null  object        
 6.start_station_latitude   | 174952 non-null  float64       
 7.start_station_longitude  | 174952 non-null  float64       
 8.end_station_id           | 174952 non-null  object        
 9.end_station_name         | 174952 non-null  object        
 10.end_station_latitude    | 174952 non-null  float64       
 11.end_station_longitude   | 174952 non-null  float64       
 12.bike_id                 | 174952 non-null  object        
 13.user_type               | 174952 non-null  category      
 14.member_birth_year       | 174952 non-null  float64       
 15.member_gender           | 174952 non-null  object       
 16.bike_share_for_all_trip | 174952 non-null  object  
 17.member_age              | 174952 non-null  float64  

## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.
## Univariate
the number of trips reached a peak value of hour at 8 Am and 17 Pm and more trips in days from monday to friday. 
Also the most bikers trips are male people and the most bikers are subscribers not customers. 
Also the Ages of most bikers lie between 20 years and 40 years.
most of bikers take a short  trip with a period around to 5 minutes to 15 minutes <br>
No transformation is needed except the steps of data wrangling described above 

## Bivariate
first i found that the trip durations for subscribers are more tha for customers.
also i found that  the trips from monday to friday are smaller than the trips in saturday and sunday which gives an indication that the trips are smaller in weekdays than in weekends. 
also i found that the subscribers use the bike for work from monday to friday not like the customers use it in the weekend which may be for fun and the subscribers are older than and longer in the trips from the customers 

## Multivariate 
there no big changes in the duration per hour for the subscribers but there is a big change in duration per hour for the customers as it incearses at 3 AM and 4 AM .
also there no big changes in the duration per day for the subscribers but there is a big change in duration per day for the customers as it increases high in saturday and sunday    

## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
> most of the bikers are subscribers 
> most hour trips starts at 8 AM  and 8 Pm
> most of riders are male 
> the mean duration trips is almost the same for each other during hours of the day except at 8 AM and 8 Pm 
> the mean durration trips is close to each other during days for week except in weekends 
> there no big changes in the duration per hour for the subscribers
> there is a big change in duration per day for the customers as it increases high in saturday and sunday