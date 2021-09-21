# Ford GoBike System Data
## by (Tasnime Aboelyazid)


## Dataset

> this project is divided into 2 main parts:
1) perform an exploratory data analysis on this dataset Ford GoBike System Data using python and data visualization, this part begin by cleaning the data and understand its structure then perform some visualizations from simple relationship to multivariate ones .
2) begin the explanatory data analysis by using the relationship and information taken by the previous part and start to display it in a way that audience can understand and get the idea with the help of some visualizations and some documentation to make it easy .

> Ford GoBike System dataset contains 183412 data with 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip), including some null values
> for cleaning and better analysis purpose we change some data type and added some columns for more relationship like :start_hour, start_week, member_age and duration _minute



## Summary of Findings

> After completing the analysis we get several information and relationship about this dataset :
1) The trip distribution over day hours peaks around two timeframes, 8am-9am and 17pm-18pm, during typical rush hours. also while observing the trip distribution over days, we see that the majority of rides happened on work days (Mon-Fri)
2) Subscribers use the system heavily on work days i.e. Monday through Friday whereas customers ride a lot on weekends. Many trips concentrated around 8-9am and 17-18pm on work days for subscribers when used for work commute, yet customers tend to use more in the late afternoon around 17pm Monday to Friday.
3)the male users are usimg more rides while comparing with female and other with long durations , other types of customers are taking long rides while they are older (50 - 60)
4) the start_station_name and ens_station_name didn't help for getting more information or relationship
5) when the age between 20 to 45, the trip duration is higher than the older ages.


## Key Insights for Presentation

> 1) Trip Duration distribution : it is one of the main focus while exploring this dataset , the majority of the trips were between 5 to 15 minutes range.
2) Age Distribution : younger riders are more often using the app and making more rides then the  older riders ,and most riders were around 25 to 40 years old.
