# (Ford GoBike Data Exploration)
## by (Nahla Nabil)


## Ford GoBike Dataset

* Ford goBike dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area during Febraury 2019. It consists of info about trips taken by service's members, their types, their age, their gender, stations of starting and ending trips, duration of trips etc. There are 174,952 trips in the dataset with 21 features. Out of 21 specifications 13 are numerical, 2 are datetime & 6 are object type. I calculated some features such as: member_age, duration_min, distance_km between start & end area.

* I'm most interested in figuring out features that affect using the bike-sharing system the most: day of week, the average trip time, type of users, age, gender


## Summary of Findings

* For **member_age**, it is normally distributed. We noticed that values started to increase from almost 18 years to almost 30 years then suddenly decreased. We also noticed there's a high peak around 25 to 35 years.
* For **users_type** Subscribers or Customers:
-   Large segment of users were **Subscribers** with 90.86%
-   Regular **Customers** were about 9.14% of overall users
* For **users_gender**, they are divded into Males, Females or Others:
-   Large segment of users are **Males** with 74.61%
-   **Females** who used this system were about 23.36%
-   Not-defined gender **Others** were about 2.03% of overall users
* According to **start days**, it's obvious that this system is used more during weekdays than weekends.
* For **duration_min**, it is normally distributed. We noticed that values started to increase from 1 minute to almost 8 minutes, then suddenly decreased. There's a high peak around 6 to 10 minutes.
* For **dictance_km**, it is normally distributed. We noticed that values started to increase from 1 km to almost 90 km then suddenly decreased. There's a high peak around 85 to 95 km.
* Overall, we can say that users who are using this system the most, are in their **30s**, their type is **subscribers**, mostly are **males** ,using it during **weekdays** not weekends
* There's a **positive correlation** between **Distance (km)** & **Duration (min)** , which make sense that long distances trips take more time.
* Most rides' duration were ~= 8 minutes for each.
* According to **users type**, Subscribers are always larger than Customers for all 3 gender types.
* Most **Subscribers** are Males = 114874 **male-subscriber**, followed by 35140 **female-Subscriber**, then the least number of Subscribers are 3001 **other-subscriber**.
* For **Customers**, Most of them are Males = 10468 **male-customer**, then 4093 **female-customer** & the least are 412 **other-customer**
* Number of rides for both **Male-Customers** & **Male-Subscribers** increases during weekdays but are less during weekends.
* Number of rides for **Female-Subscribers** also increases during weekdayse but decreases during weekends.
* **Female-Subscribers** are less than **Males**, with large difference.
* **Female-Customers** just increases in **Thursday**, while decreases & almost still the same the whole week.
* **Others-Subscribers** increases during weekdays & decreases during weekends.
* **Others-Customers** increases in **Thursdays, Wednesdays & Fridays**, but decreases and still the same for **Tuesdays, Mondays, Sundays & Saturdays**.
* For **Subscribers**: Most rides are of distance **~50 km**, which are taken by users of age ~25:30, then ~27:33
* Followed by rides of distance **~100 km**, which are taken by users of age ~27:33, then ~25:30
* For **Customers**: Most rides are of distance **~100 km**, which are taken by users of age ~27:33
* Followed by rides of distance **~50:150 km**, which are taken by users of age ~25:33
* For Long distance number of old users -of age more than 30s- are less than others who take small distances.

## Key Insights for Presentation

* For Peresentation, I focused on Member gender, User type, Start day, Duration & distance and their relations with each others.
* I found that:
-   User type Subscribers are more than Customers
-   Most members ages are between 27:33 years
-   Most registered ride duration in the system are almost 10 minutes
-   Rides during weekdays are more than weekends
-   There is positive correlation between duration & distance
-   Males are more than Females & the useres signed with gender others are the least
