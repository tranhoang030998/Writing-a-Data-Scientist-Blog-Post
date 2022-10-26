# Writing-a-Data-Scientist-Blog-Post

## Prerequisites

The code is saved in ```.ipynb``` file and can be run with any tool that support this file format. These are libraries that is used in this project:

- pandas
- numpy
- matplotlib
- seaborn
- warnings

### This project aims to answer these questions:

- What are percentage of User Type and Member Gender?
- Is there any relationship between duration second and user type?
- Is there any relationship between duration second, week day and user type?
- What is top 10 Start and End Station have most rider?

### Results
For the code, please check the notebook ```Udacity_BlogPost.ipynb```.

The findings of this project already published follow the link:

https://medium.com/@tranhoang030998/ford-gobike-system-in-san-francisco-c7bd35a4511f

### Data:
This project use data from 201902-fordgobike-tripdata.csv that I already uploaded

## Dataset

- The data including information of 183.412 ford gobike trips in San Francisco area with 16 variables (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). But some datas has wrong so it need to be clean them.

## Summary of Findings

- I found that there are relationships between age, gender, day of week, and hour to the duration of trips. The number of riders is distributed more in San Francisco and less in Oakland and Berkeley. The reason why rider in San Francisco crowded is it's a travelling city so it have a lot of traveler visited and they rent the bike to go around the city and the beach easier. Besides that, People usually spend more time on a biking trips on the weekend because they seem to have to go to work on the weekday or traveller usually visited at weekend.

## Key Insights for Presentation

- I focus on just the location, user types, gender, and age. I started by showing the start location and pick top 10 start location has most riders and recommend them to improve more and more their services. Next one I show the percentage of bike rides for all user types subcriber and customer, it's show the subcriber users are 89.2% and that mean the customer users are 10.8%. Then I plot the distributed of trip duration by days and user type and also trip duration by gender and user type.
