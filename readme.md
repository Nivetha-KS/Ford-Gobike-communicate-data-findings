# Ford GoBike System - Effects of Ride Frequent & Ride Duration
## by Nivetha KS


## Dataset

The dataset use in this investigation consists of Ford GoBike sharing system covering the greater San Francisco Bay area in the year 2017(June-December).Refer [Bay_Wheels_wikipedia](https://en.wikipedia.org/wiki/Bay_Wheels). It consists of various ride characteristics and riders characteristics.

Investigation focused on below features from the cleaned dataset(453159 bike ride entries and 15 features):

- Trip Duration (seconds)
- Start Day
- Start Month
- Start Hour
- User Type (“Subscriber” = Member or “Customer” = Casual)
- Member Age
- Member Gender


## Summary of Findings

In the exploration, I found that there are many ride time and rider characteristics influencing the ride frequency and ride duration.

#### Ride Frequency:
- **Peak times**(day: weekdays, month: Oct-Dec, hour: 8-9AM, 4-6PM)
- **Subscribed Male** riders are commuting more during **weekdays**(Tuesday & Wednesday: ~56k, Thursday: ~53k) whereas Other gender casual customers are commuting the least eternally.
- **Subscribed Male** riders are commuting more during **October** month(~65k).
- **Subscribed Male** riders are commuting more during the peak hours **8-9 AM** upto(~ 37k) and **4-6 PM** upto(~ 38k).
- Most of riders age lies between 29 - 42 age range which indicates riders age infulences the ride frequency. Older age riders commuting less.
- **San Francisco Caltrain (Townsend St at 4th St)** is the most commuted start station as well as the end station

#### Ride Duration
- **Peak times**(day: weekends - month: Jul-Aug, hour: 3AM)
- Overall subscribed Female riders and casual Other gender riders are taking more ride duration who rides the most during ride duration with respect to ride duration.
- Surprisingly all age group riders has uniformly distributed ride durations which means older riders are riding fast as well as the younger riders ranges approximately below 20k seconds
- **Foothill Blvd at Fruitvale Ave** and **Palm St at Willow St** are the long trip duration start stations as well as end stations.

## Key Insights for Presentation

For the presentation, I focus on the the effects of Ride Frequent and Ride Duration influenced by ride time characteristics(Day, Month, Year) and Rider characteristics(Gender, User Type, Age).

I start by introducing the relationship between Ride Frequency and Ride Duration. Then, I continue by plotting relationship between individual rider characteristics(Age, User Type, Gender) and time characteristics (Day, Month, Hour) based on both Ride Frequency and Ride Duration using count, bar and scatterplots.

At last, I have plotted the Relationship between time characteristics and Riders characteristics(Gender, User Type) by ride Frequency and Ride Duration using Heatmap and FacetGrid.

